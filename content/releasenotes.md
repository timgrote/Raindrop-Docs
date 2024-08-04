# Raindrop Release Notes

Find out what's new and what's fixed.

[🦟 Report bugs here 🚨](https://www.raindropirrigationsoftware.com/feedback/) or 
[ ⬇️ Download Current Version Now⬇️](https://updates.raindropirrigationsoftware.com/Raindrop_Setup.exe){ .md-button .md-button--primary }

---
## Version 1.2.8688.39685
### October 18, 2023

### Features 🌄
- A terrain model can now be built from contours for both existing and proposed contours.
- Sprinklers and valves are inserted at the elevations set by the terrain model
### Improvements 🔝
- Renumbering interface is now built into the clock palette directly.
- Users can now specify a path to the drawing holding default settings, sprinklers and valves
- Lateral sizing now takes elevation into account
- Mainline Analysis shows  hydraulic grade line for nodes and POCs
- Control valves now show a required pressure based on lateral losses and elevation after sizing.
- Pipes now show start and end pressure/elevations in properties.

### Bugfixes 🐛
- Save as default in settings saves sprinkler assemblies as well as other settings.
---
## Version 1.1.8626.19261
### August 18, 2023

### Improvements 👍
- Added application rate and runtimes to runtime schedule
- Runtime schedule can now be exported to Excel format. 
- Plant Type - Required Depth form now matches app style.
- Mainline Analysis console provides more information.


### Bugfixes 🐛🐛
- Quantities files no longer get written twice, asking for overwriting existing files.
- The Mainline Analysis palette doesn't pop up without being asked to. Silly palette. 🤡
- Fixed a crash on some new drawings opening pipe settings.
---
## Version 1.1.8613.39898
### August 1, 2023

### Improvements 🙌
- Various updates and fixes to the mainline analysis form.
- Editing pipes in the properties palette updates the Mainline Analysis form, and vice versa.
- Raindrop plants can now be  assigned boundaries and added to drip remote control valves.
- Header updates for quantities reports.
- Clock Tab now remembers the last selected controller in the drawing.


### Bugfixes 🪲
- Drip Laterals for shrubs, trees and drip supply now show in legend as expected.
- InlineDripGrids, and sprinkler lateral pipe  now show up in quantities report as expected.
- Text Styles now imported from user custom template and main template.
- Zooming to an object from paperspace no longer crashes CAD.
- Controller layer is now thawed when numbering/renumbering valves. Results were confusing when the controller layer was frozen.

---
## Version 1.1.8532.24417
### May 12, 2023

### Improvements 🙌
- Installer updates and improvements.
- Existing sleeves now update their size if the pipe inside them is modified.
- New commands for inserting notes for planting, irrigation and flag notes. Find these on the Misc. Tab.


### Bugfixes 🪲
- Fixed a bug where pipe labels were not always updating when the pipe was modified.
- Changes from the settings form now show in the tool palette immediatly.
- Architectural units
	- Inline drip grids now report their flows/properties properly.
	- Lateral Hydraulics are now calculating correctly.
- Lateral size labels and flow arrows are now working when sizing zones.

--- 
### November 28, 2022

### Improvements 🙌
- Easier to add new plants to the database.
- License status is more clearly stated at the bottom of the 


### Bugfix 🪲
- Polydrip tubing no longer disappears when drawing it.
- Fixed a bug with weighted areas when drawing units are inches.
- Fixed sprinkler radius being wrong during *Layout on Polyline* command when drawing units are inches.
- Fixed a bug where drip valves were showing up twice in the legend.
- Fixed: Swapping sprinklers while show radius was unchecked was showing the radius circle.
- Fixed drip remote control valves showing up twice in legend.
- Fixed incorrect plant properties showing in settings.

- ---
## Version 1.1.8277.32217
### September 1, 2022

### Improvements 🙌
- Easier to add new plants to the database.
- Plants can be deleted from the project now.
- Plant quantities can be exported to text or Excel
- Users can set the text height of plant labels in settings
- Quantities now include the project title and subtitle
- Implemented a color ramp for plant layer colors
- Updates to error reporting
- Users can search for plants in the plant settings.
- Added a sample file for importing  plants

### Bugfix 🪲
- Fixed links showing bad pressures.
