---
title: "Calculating Steps"
date: 2020-12-12 14:50:00
sidebar:
  nav: "3d"
permalink: /3d-printing/esteps/
---
1. Get current g-steps - enter `M503` and note current e-steps <input type="number" id="current" onkeyup="esteps()">

2. Extrude 100mm filament: `G1 F100 E100`

3. Measure actual extruded <input type="number" id="actual" onkeyup="esteps()">

4. Calculate new (<b id="100">100</b>/<b id="actual_function"></b>) * (<b id="current_function"></b>) = <b id="new_steps"></b>

5. Enter new:<b id='new_display'></b>


Formula:
```
(expected/actual) * (current e-steps)
```
<script>
function esteps(){
	var current = document.getElementById('current').value;
	var actual  = document.getElementById('actual').value;
	var new_steps= (current/actual*100).toFixed(2);
    $("#actual_function").html(actual);
    $("#current_function").html(current);
    $("#new_steps").html(new_steps);
    $("#new_display").html("M92 E"+new_steps);
}
</script>
