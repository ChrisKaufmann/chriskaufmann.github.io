---
title: "Startup gcode"
date: 2020-12-21 21:11
sidebar:
  nav: "3d"
permalink: /3d-printing/gcode/
---

My current startup gcode. This does three main things:
1. Starts heating the nozzle and bed right away
 * ```
M104 S{print_temperature}     ; start heating hotend
M140 S{print_bed_temperature} ; start heating bed
```
2. Moves to zero, then up 15mm
 * ```
G28 X0 Y0 Z0  ;move X/Y/Z to min endstops
G1 Z15.0 F6000 ;move the platform down 15mm
```
3. Wipes the nozzle *in front of the bed*, then moves to start printing
 * ```
G0 Z0.15 ; Drop to bed
G92 E0 ; zero the extruded length
G1 X40 E10 F500 ; Extrude 10mm of filament in a 4cm line
G92 E0 ; zero the extruded length
G1 E-1 F500 ; Retract a little
G1 X80 F4000 ; Quickly wipe away from the filament line
```

I like this because I don't have to wait extra minutes for the bed to heat, then the extruder to heat up, they do it at the same time.  

*and* more importantly for my purposes, drops the primed line of extruded material in front of the bed.


```
M104 S{print_temperature}     ; start heating hotend
M140 S{print_bed_temperature} ; start heating bed
G21        ;metric values
G90        ;absolute positioning
M82        ;set extruder to absolute mode
M107       ;start with the fan off

; wipe nozzle
G28 X0 Y0 Z0  ;move X/Y/Z to min endstops
G1 Z15.0 F6000 ;move the platform down 15mm
G1 F6000
G29 ; initiate z-probing

;Wait for temp
M190 S{print_bed_temperature} ; wait for bed to get to temp
M109 S{print_temperature}     ; wait for hotend to get to temp

G0 Z0.15 ; Drop to bed
G92 E0 ; zero the extruded length
G1 X40 E10 F500 ; Extrude 10mm of filament in a 4cm line
G92 E0 ; zero the extruded length
G1 E-1 F500 ; Retract a little
G1 X80 F4000 ; Quickly wipe away from the filament line
G1 Z0.3 ; Raise and begin printing.
;Put printing message on LCD screen
M117 Printing...
```
