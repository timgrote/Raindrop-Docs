# Clock
## Overview
Default overview of any and all existing valves in the drawing, including any created and referenced only in the legend.

Sorting by controller where applicable, uncontrolled and unnumbered valves will appear in the seperate list on the right side.

Station displays the number of the valve associated with the selected controller. Shows the total flow of any connected sprinklers or drip flow blocks, and area is entire area affected by sprinklers as understood through the Weighted Zone Area command. Plant type can be set by the user to associate a planting depth to be used in the precip table.

## Numbering Zones
Requires user to select a controller, and then starts at the lowest unassigned number (Default 1) and lets the user select valves or designators to be numbered in order.

Using the Renumber Zones command requires the user to select a starting valve, and then offers a prompt asking how much to be renumbered and in which direction, adding one or more to all numbered zones higher than the selection or below. Useful when zones are added or larger zones are broken up into smaller ones.

## Weighted Zone Areas
Prompts the user to select a layer with closed polylines around all areas where sprinklers are present, calculating how much of each area is covered by the maximum radius of sprinklers within the polylines. Any sprinklers that are outside of the polylines cause an error note to be placed the point of offense.

## Export Precip Table
Lets the user select multiple valves or designators to be exported into an .tsv file with associated flow in gallons per minute, area in square feet, and plant type with depth if applicable.