# Drip
## Overview

Raindrop can be used to design both point source drip and inline drip grids
### Point Source Drip
Point source drip is made up of emitters are used to deliver water directly to each plants root system. Single outlet or multi-outlet emitters deliver a specified  demand to each plant. Drip demands are measured in gallons per hour (GPH) or liters per hour (LPH).  In raindrop, each type of plant is assigned a drip demand.

In Raindrop,  point source drip demands are totaled up and assigned to a drip remote control valve. Hydraulics are not calculated.

There are **XX** ways to assign drip demands to a remote control valve.

If you are working with non-Raindrop plants in an an xref, you need to assign drip demands to each plant. Open the file containing plant objects and use 'Assign demands to plants' from the drip tab. You will be prompted to select plants to assign demands to. It is useful to assign demands via category (grasses get 1 GPH, shrubs 6 GPH, deciduous trees get 16 GPH etc.) You can use the command 'FS' to easily select all blocks by layer or name.  Raindrop will insert a DripDemandBlock on each selected plant. The layer for these will typically be *3284-DripFlows*. Once all plants have a drip demand associated with them, we need to get those demands back into your irrigation drawing. From the planting drawing, use FS again to select all DripDemandBlocks, use *Ctrl+Shift+C* to copy them with a base point. Use 0,0 as a base point. Switch back to your irrigation drawing, use *Ctrl+V* to paste the demand blocks into your irrigation drawing, use the same base point as the previous step.

## Poly Drip Pipe
Running the "Draw Poly Drip" command will prompt the user to start drawing a spline, a polyline that curves based on fixed points as defined by the user. Placing one will preview the path the line will take, and the curves of the previous segments are adjusted based on the placement of the next several points. It's recommended to leave the curves as obvious possible due to the nature of the monochromatic final print.

Selecting an existing poly drip spline will show the designated anchor points and allow for the individual adjustment of same.

## Drip Flows
Running "Assign Drip Demands to Plants" will prompt a selection from the user to assign a value to. Applying said value to blocks and adding a number to each instance of the block for visual aid and use with one of our other commands.

## Drip Boundaries
Running this command and selecting one or multiple closed polylines surrounding Drip Flow blocks will allow the user to easily add several Drip Flows to a single Drip Remote Control Valve (DRCV). 

## Plant Demands to Drip Valve
Allows the user to manually or precisely select which Drip Flow blocks to associate with an existing DRCV, this will also automatically create a zone designator with a flow value calculated with any existing drip flow blocks associated with it.