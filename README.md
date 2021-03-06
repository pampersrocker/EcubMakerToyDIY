# EcubMakerToyDIY
Settings for the EcubMakerToyDIY (tested on Cura 4.4.1)

The settings and profiles found in this repository are extracted from the generated gcode files of the EcubWare cura clone. They have been fixed and modified to operate more efficiently. Use at your own risk.

Things to keep in mind:

* Ensure Fan Speed is set to 100% at all times as there is only a single fan for cooling and part cooling, so if the fan is turned off, the printer head will no longer be sufficiently cooled. The default settings of cura disable the fan for the initial layer, which can lead to heat problems when printing a large initial layer.
* Dual FDM printing is currently extremely slow and broken as a filament change takes about a minute and will cause oozing when returning from the sidebay.
