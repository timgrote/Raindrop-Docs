# Pipes
## Overview
Pipes are represented with polylines. Each polyline can have only one size of pipe. Mainline pipes are constantly under pressure. Lateral pipes are only pressurized when the remote control valve controlling them are open. There are different types of lateral pipes available for sprinklers, PE Drip, Tree Drip, and Shrub Drip. PE Drip piping is represented the drawing with a curved spline. Users can specify the default (minimum) size and class of each type of lateral in the Pipes tab of the settings form.

Mainline pipes are shown in modelspace by thick red lines, and don't use pipe hops. Valves will snap to Mainline pipes when placed near and rotated accordingly.


![](/images/Settings-Pipes.png)


## Working with Pipes
<img style="float:right;margin-left: 30px; " src="../images/Pipes.png">
Use the *Pipe* tab of the Irrigation Palette to work with pipes.


## Paint Laterals
Running the Paint Laterals [needs a space on the button] command will change the cursor to a circle that will snap a lateral pipe to any heads or Remote Control Valves that it touches. The flow of any sprinklers painted on the current instance will be added to the sum next to the cursor.

Clicking while the command is active will designate a joint in the pipe, which can be used to add turns or angles to the pipe without needing a sprinkler to join to.

"Paint laterals" will not calculate the flows of existing pipe, even if connected, it's recommended to use the Total Flows command [maybe move total flows here or copy it] instead.

After the command is started, and a point is made (either to an existing sprinkler or designating a point by clicking) pressing V will alter the next input to be a Remote Control Valve, clicking at this point will insert the valve at the cursor, snapping to center on a Mainline pipe if present, rotating to be parallel.

## Mainline [should be shown above paint laterals by virtue of it's used first?]
Prompts the user to designate a start point for mainline, clicking will designate another point, but the mainline will not register correctly if connected back to itself in the same instance of the command.

## Show Label
Once a zone is sized, any pipes that are larger than the default (minimum) size will be called out with labels at the start and end of their run. Show Label is useful in cases where match lines are present or another instance of sizing text is needed.