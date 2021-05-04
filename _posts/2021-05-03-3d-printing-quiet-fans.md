---
title: "Quiet Fans"
date: 2021-05-03 15:17:00
sidebar:
  nav: "3d"
permalink: /3d-printing/quiet-fans/
---

In my ender 3, I use Noctua 4020 fans for hotend and parts, a Noctua 4010 for CPU, and  a Noctua 80mm for the PSU.
Ender 3 has a total of two buck converters.
1: 24->12v goes to a header, powers the PSU, CPU, Hotend fans, and lights.
2: 0-24v -> 0-12v Parts Cooling Fan

In my ender 6, I use Noctua 4020 fans for hotend and parts, the Sunon 6010 for the PSU, and the two 7530 fans for CPU and Raspberry Pi.
Ender 6 has a total of 3 buck converters
1: 24->~8v, goes to a header for CPU, Raspberry Pi, and PSU fans
2: 24v->12v, goes to a header just under the breakout board for hotend and lights, and powers the buck converter for the part cooling fan
3: 12v-> parts cooling fan


| Machine	| Use 			| Brand		| Voltage	| Size	| Price		| Link |
| -------	| ---			| -------	| --------	| ---- 	| -------	| ----|
|Ender 3/6	| Hotend/Part 	| Orion		| 24v 		| 4010	| $11.89	| [Mouser](https://www.mouser.com/ProductDetail/orion-fans/od4010-24mb/?qs=8xdMPHO%2FENm39wmFy6BgQQ%3D%3D&countrycode=US&currencycode=USD) |
|octoprint	| Raspi Fan		| Generic 	| 3-5v		| 30x30 | $7.99		| [Amazon](https://amzn.to/2QJFcBu) |
|Ender 3/6	| Notend/Part	| Noctua	| 12v		| 4020	| $14.95	| [Amazon](https://amzn.to/2PKwClg) [Thingiverse](https://www.thingiverse.com/thing:4460693) |
|Ender 3/6	| Part			| Generic Blower| 24v	| 5015	| 2/$5.99	| [Amazon](https://amzn.to/3xM5TpN) [Thingiverse](https://www.thingiverse.com/thing:3744260) |
|Ender 6	| Base Cooling	| Generic Blower| 12v	| 7530	| $8.38		| [Amazon](https://amzn.to/3ukt2gE) |
|Ender 3	| CPU			| Noctua	| 12v		| 4010	| $13.95	| [Amazon](https://amzn.to/33atSR8) |
|Ender 3	| PSU			| Noctua	| 12v		| 80x80x25| $9.95	| [Amazon](https://amzn.to/2PKxczs) [Thingiverse](https://www.thingiverse.com/thing:3570785) |
|Ender 3	| PSU			| Noctua	| 12v		| 120x120x25 | $19.95|[Amazon](https://amzn.to/3efrNtN) [Thingiverse](https://www.thingiverse.com/thing:3672346) |
|Ender 6	| PSU			| Sunon		| 12v		| 6010	| $6.42		| [Mouser](https://www.mouser.com/ProductDetail/sunon/mf60101v3-1000u-a99/?qs=EU6FO9ffTwekSIQ43CVQVg%3D%3D&countrycode=US&currencycode=USD) |



 Misc
| Name					| Price 	| Link |
| Fan header/splitter	| $7.60		| (Amazon)[https://amzn.to/3aZDKBC] |
| Buck Converter		| 4/$16.99	| (amazon)[https://amzn.to/3efrNtN]|

