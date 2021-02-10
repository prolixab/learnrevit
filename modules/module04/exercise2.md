---
layout: page
title: Interiors and Circulation - Exercise 2
permalink: /modules/module04/exercise2
---

[Learn Revit](/learnrevit/) > [Module 4](/learnrevit/modules/module04/) > Exercise 2

## Exercise 2 --- Modeling Custom Stairs

** In this exercise, you will use various methods to customize stairs via
Type Properties and Instance Properties. **

Objectives:

-   Edit the sketch to change the stair boundary and shape of the
    risers.

-   Change stair and rail types.

-   Modify the steepness of a stair by adjusting the settings in the
    Properties

    palette.

-   Create and edit a spiral stair.

### Create a steeper stair type for the Studio space

1.  Navigate to the folder containing the downloaded resources for
    Module 4.

Module04_Resources

10. Open Revit file:

    Module04Ex02_Modeling Custom Stairs_Imperial_Start.rvt

11. Open First Floor plan view.

    a.  Starting stair layout.

        ![](media\image19.png)
    b.  Finished stair layout.

![](media\image20.png)

12. Create a new stair type.

    a.  Select and delete the existing stair.

    b.  In the Architectural tab, Circulation panel, click Stair by Sketch method.

    c.  In Properties palette, select stair type: Residential -- Open Riser.

        ![](media\image21.png)

    d.  Click Edit Type.

    e.  Click Duplicate.

    f.  Rename new stair type as:

        Residential -- Open Riser - Steep.

    g.  Set stair properties as follows:

        Min Tread Depth = **9" (0.22m)**

        Max Riser Height = **9" (0.22m)**

        ![](media\image22.png)

    h.  Click OK to accept values and exit dialog boxes.

13. Create a new stair in the Studio room.

    a.  Set the base of the stair across from the column and dragging
        > the cursor downwards towards the opening and setting the upper
        > level of the stairs just beyond the bounding box.

        ![](media\image23.png){

    b.  Move the upper level edge of the stair to align with the top
        > edge of the wall opening.

        ![](media\image24.png)

### Create a spiral stair for the Residence space

1.  In the First Floor plan view, pan downwards until you see the dashed
    boundary with red lines where the spiral stair will be placed.

> ![](media\image25.png)

14. Create a new stair type.

    a.  Select and delete the existing stair.

    b.  On the Architectural tab, Circulation panel, click Stair by
        > Sketch method.

    c.  In Properties palette, select stair type: Residential -- Open
        > Riser.

        ![](media\image21.png)

    d.  Click Edit Type.

    e.  Click Duplicate.

    f.  Rename new stair type as:

        Residential -- Open Riser - Spiral.

    g.  Set stair properties as follows:

        Min Tread Depth = **11" (0.27m)**

        Max Riser Height = **10" (0.25m)**

        ![](media\image26.png)

    h.  Click OK to accept values and exit dialog box.

15. Create spiral stair.

    a.  Click Center End Arc mode.

        ![](media\image27.png)

    b.  Place center point at red X origin point.

        ![](media\image28.png)

    c.  Set Run radius = **2'-0" (0.60m)**.

    d.  Left click to set the upper level of the stair.

        ![](media\image29.png)

        *Note: You will receive a warning message that the stair cannot
        be completed because it would revolve more than 360 degrees. We
        will address this next.*

    e.  In Properties palette, set Actual Tread Depth = **10" (0.25m)**.

        ![](media\image30.png)

    f.  Erase the existing spiral stair sketch.

    g.  Resketch stair sketch.

        ![](media\image31.png)

        *Note: Confirm that 0 risers are remaining.*

  
    a.  Click Finish Edit Mode to create the 3D stair.

        ![](media\image8.png)

    b.  Progress stair shown below.

        ![](media\image32.png)

16. Spiral stair fit and finish.

    a.  Flip the stair direction, select the stair and click the Flip
        > grip highlighted in the red circle.

        ![](media\image33.png)

    b.  Rotate the stair so the upper level is horizontal. Select stair
        > and Click the Rotate tool in the Modify panel.

        ![](media\image34.png)

17. Change stair handrail type to:

    Handrail -- Pipe.

18. Add a center pole for spiral stair.

    a.  On the Architectural tab, Build panel, click Column:
        > Architectural tool from the pulldown menu.

        ![](media\image35.png)

    b.  In Properties palette, select:

        Round Column -- 8" diameter and set Height constraint to Roof.

        ![](media\image36.png)

    c.  Locate column center at center of spiral stair.

19. Open First Floor -- Spiral Stair 3D view.

    ![](media\image37.png)

20. Save the Revit file as: Module04Ex02_Modeling Custom
    Stairs_Imperial_Finished.rvt

    This concludes Exercise 2.

