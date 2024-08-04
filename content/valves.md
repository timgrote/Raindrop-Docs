# Valves and Zones
## Overview
<img style="float:right;margin-left: 30px; " src="../images/Valves.png">
Raindrop uses blocks to represent different valves. Each type of valve has a unique blockname.  Each valve block also has a description that can be changed by the user. This description will show up in the legend and quantity take offs. Working with valves is done from the Valves tab in the Irrigation Tools Palette. Some of the valve blocks have already been given a suggested description/use. The descriptions are user customizable. More valve blocks will be added as develoment continues.

## Remote Control Valves
Remote control valves have RCV in their name.  RCVs  are inserted like regular valves, and can also be inserted using the *Paint Lateral Pipe* command. Remote control valves are used to control a *zone* of sprinklers.

## Zones
A zone is an area of multiple sprinklers connected to each other by a network of lateral pipe. Each zone network starts with a remote control valve. The *Size Zone* button on the valve tab allows the user to pick one or more remote control valves. The network of lateral pipe attached to each zone will be sized according to the sizing settings in the settings form.

*Related Commands*
SZ- Sizes selected valves


## Points of Connection
Each irrigation project will have at least one point of connection (POC) to a water source. That source might be a potable connection, a pump station at an irrigation pond, or some other source of irrigation water. POCs are represented with a special block. User's can insert a POC block into the drawing with the *Insert POC* button.

## Adding valves to the drawing (IR_INSVALVE)
Valves can be inserted by clicking the *Insert* button, or double clicking on the valve in the list of valves. Valves can be inserted on mainline pipe only. The user will be promted for a point to insert the valve at. If the user picks on or near a mainline, the valve will be inserted on that mainline pipe, and the mainline pipe will break into two sections on either side of the valve. If the *Auto Rotate* button is checked the valve block will align to the mainline it was inserted on.