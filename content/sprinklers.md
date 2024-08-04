# Sprinklers
## Overview
<img style="float:right;margin-left: 30px; " src="../images/SprinklerTab.png">
Raindrop uses a block to represent a sprinkler, and a circle to represent the radius of the sprinkler. The angle of throw is not represented. The radius of the sprinkler is meant for design purposes, and not meant to be shown on final construction plans.

A Raindrop project contains a list of *project sprinklers* that the user can choose from during design. The user can add various sprinkler series with the Add Sprinklers dialog. A *series* of sprinkler includes all the nozzles for the chosen model and user selected pressure of sprinkler.

To work with sprinklers in a project, switch to the Sprinklers tab of the irrigation tools palette. If the irrigation tool palette is not visible, run the command *IR_TOOLPALETTE* to show it.

There are filter lists that adjust the list to only show sprinklers from a certain manufacturer or specific series that have already been added to the project.

## Adding sprinklers to a project
Click the *Add* button on the sprinklers tab. Using the given filters select for a sprinkler model and pressure you want to add to the drawing. A list of all available nozzles for the chosen sprinkler will be shown in the *nozzles* list. Clicking the *add* button will add all the series shown in the nozzle list to the project sprinklers list.

## Manually inserting sprinklers into the drawing *(IR_INSSPRINKLER)*
This command can be run by double clicking a sprinkler in the sprinkler tab, or using the *Insert* button. Moving  the cursor into the drawing, a sprinkler is shown with the radius of the sprinkler as well as a 75% reduced radius for user reference. Clicking the cursor will insert the sprinkler at the chosen location. If the rotate box is checked, the user will be prompted to specify a rotation for the sprinkler block. Pressing the Q or A key while the command is active allows the user to change the nozzle's size or angle during the command. This command can also be run via the *Insert* button. Clicking near or on top of an exisiting sprinkler swaps the existing sprinkler for the new one, and attaches any pipe from the old sprinkler to the new one.

## Polyline Layout *(IR_POLYLINELAYOUT)*
Clicking the polyline layout button will allow the user to draw or pick a polyline to place sprinklers along. Sprinklers will be spaced evenly along the polyline at a distance less than the chosen spacing. The command will prompt for a side to offset the sprinklers to, or to leave them centered on the polyline. This command is useful to place sprinklers along an edge of landscaping. Finally, there is an option to draw pipes between all the sprinklers inserted during the command.

## Meandering Layout *(IR_MEANDERLAYOUT)*
Meandering layout promps the user for two polylines, and places the selected sprinkler series along the polyline adjusting the radius and sprinkler series to minimize the overthrow off of the irrigated area. This command is intended to be used with Matched Precipitation Rate (MPR) series of sprinklers. Usually a half sprinkler is chosen. After the command is completed, check the ends of the polylines to see if a quarter circle sprinklers need to be inserted. Some adjustment near the centers of the polylines may also be required. This command is a huge time save for areas between curb lines and meandering sidewalks.

## Swap *(IR_SWAPSPRINKLER)*
Prompts the user for a selection of sprinklers to swap to the selected sprinkler. If the rotate box is checked, the user will be prompted for the rotation of each new sprinkler. Swapping individual sprinklers can also be accomplished by manually inserting a sprinkler on top of an existing one.

## Swap full/part *(IR_SWAPFULLPART)*
Swaps full for part circle sprinklers and vice-versa. Only used on sprinkler series without a pre-defined block.

## Total Flows *(IR_SUMSPRINKLERS)*
Prompts the user to select sprinklers in the drawing, and returns the total flow of the selected sprinklers. Useful for determining how many sprinklers to include in a zone.

## Set Radius *(IR_SETRADIUS)*
Prompts the user for a radius to assign to sprinklers, and the sprinklers to assign the radius to. Draws new radius circles for the selected sprinklers.