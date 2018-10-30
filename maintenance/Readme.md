# Maintenance
For now, the only maintenance task I had to do were :
- axes greasing
- cleaning the hotend

## Axe greasing
The process is straight forward, the hotend will move on all axes, all you have to do is to put some grease (dry WD40 for instance) on the bearings.

## Hotend cleaning
The hotend will raise, position to to center of X and start heating.

Wait for the hotend to reach its max temp then brush the noozle with a metallic brush (caution, it's hot).

Depending on you previous filament you should adapt the gcode - lines 5 and 10 - (`M104 S205` meaning 205°)

note : these gcodes are originally provided by Dagoma.
