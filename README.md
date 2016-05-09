# 4xidraw
Repository of my [4xidraw](https://www.youmagine.com/designs/4xidraw) clone. The original version of the project works with GRBL firmware and an arduino with CNC shield. However, I want to use a RAMPS with Marlin firmware.

## Marlin
I modified the config.h file to use the firmware with a coreXY printer. It's also configured the speed of each axis.

## [laser-gcode-exporter-inkscape-plugin](https://github.com/misan/laser-gcode-exporter-inkscape-plugin)
Inkscape's plugin to generate a gcode from a vectorial image. I added a modification on plugin to be able to use a servo with the marlin firmware

## Pieces
I modified servoholder.step and PenCarriege.step to can use 3mm road instead of 4mm.
