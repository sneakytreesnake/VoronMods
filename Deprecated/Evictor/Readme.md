# Evictor
Mod for Voron2.4 that automatically removes prints once they are complete. Currently compatible for 350mm.

# Motivation
I print a fairly substational amount of individual parts from different gcode files. Having to clear the bed manually before starting a new print is work that I'd rather not do, so I started developing a mod to automatically clear prints from the bed once they are complete.

While designing this mod, I wanted to keep the amount of new parts to purchase low, ideally reusing parts that you would typically have lying around. Therefore I designed the parts with no additional stepper motors (often every stepper slot on peoples mainboard is full) and used 2x MGN9 rails the same length as the X extrusion (which will be left over parts from people upgrading from V2.4r1 to V2.4r2).


# Development roadmap
As a rough roadmap, my plan is as follows:
1) Design a mechanism to clear the bed after a print. At this stage, it will only be useful for materials that do not need a heated, enclosed printer.
3) Design a mechanism to open the front doors after a print, and close them again. This will allow printing of ABS.
5) Design a mechanism to automatically wipe down the bed with alcohol - and do so safely!
6) Write a klipper plugin that will allow queuing of multiple gcode files in a row.

There are no release dates for anything - they will be completed when they are ready.

# Installation
It is recommended that the following mods are set up and working before starting this mod:
1) Klicky probe (link) [Essential]
2) Auto Z calibration (link) [Essential]
3) ERCF (link) [Recommended], or filament sensor and large filament spools
5) Bed fans (link), or Nevermore (link) [Recommended to speed up chamber reheating]
