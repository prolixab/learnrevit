---
layout: page
title: Module 2
permalink: /modules/module02/
---

Building Envelope

This module builds upon the concepts introduced in Module 01 on Building
Elements to provide a deeper understanding of building element tectonics
for creating these elements so you can apply them to your own projects.

Steps to take

[Exercise 1 Modeling Wall Types, Structures, and Design Features](#Exercise1A)

[Exercise 2 Adding Doors, Windows, and Wall Openings](#Exercise1B)

[Exercise 3 Creating Roof Shapes](#Exercise1C)

[]{#Exercise1A .anchor}Exercise 1 --- Modeling Wall Types, Structures,
and Design Features

In this exercise, you will learn about the principles of change
management by substituting generic walls for more detailed wall
assemblies. In addition, you will develop an understanding for how wall
types are created and defined.

Objectives:

-   Edit a wall's constraints and instance properties.

-   Define a wall's structure and adjust the material wrapping settings.

-   Add design features to a wall, such as sweeps and reveals.

-   Use and modify stacked wall types.

-   Edit wall boundaries to create custom shapes.

## Change exterior wall types through substitution in-place

1.  Navigate to the folder containing the downloaded resources for
    Module 1.

Module02_Resources

2.  Open Revit file: Module02Ex01_Modelling wall types_structures_design
    features_Imperial_Start.rvt

3.  Open the Ground Floor plan view.

4.  Select all exterior walls of Generic -- 8" (0.2m).

    a.  Hover over an exterior wall.

    ![Image 2](media\image2.png)

    b.  Right click in the canvas window and select Select All
        > Instances\>Visible in View.

    ![Image 3](media\image3.png)

    c.  Select Exterior -- Brick wall type.

    ![Image 4](media\image4.png)

5.  Open {3D} 3D View. Confirm exterior walls are brick.

    ![Image 5 ](media\image5.png)

## Create a new interior wall type

1.  Open the Ground Floor plan view.

1.  On the Architecture tab, click Wall.

    ![](media\image6.png){width="1.88in" height="0.95in"}

2.  In Properties Palette, select Generic 8\" (.20 m) wall type.

    a.  Click Edit Type.

    ![Image 7](media\image7.png)

    b.  Click Duplicate.

    ![Image 8](media\image8.png)

    c.  Rename to: Wood Panel Wall.

    ![Image 9](media\image9.png)

    d.  Click OK.

3.  Define the material definition of the wall type.

    a.  Click Edit Structure.

    ![Image 10](media\image10.png)

    b.  Edit Structure \[1\] to:

        Material = Wood -- Stud Layer

        Thickness = **0' 1 5/8" (0.041m)**

    ![Image 11](media\image11.png)

        *Note: Use search window in the Material Browser and type
        material name you are looking for.*

> Structure \[1\] is associated with structural materials supporting a
> wall and has the highest cleanup priority.

c.  Click Insert button two times to add (2) new layers to the wall
    > definition

![Image 12](media\image12.png){width="2.3399365704286965in"
    height="1.0625in"}

![Image 13](media\image13.png){width="2.3402777777777777in"
    height="0.4128477690288714in"}

6.  Edit Layer 2:

    a.  Select Layer 2 row

    b.  Click Up button once

    c.  Click Function = Finish 1 \[4\]

> Note: Function determines a material layers behavior in the model
> environment for cleanup at wall intersections with other wall types.
> Material functions of the same kind will cleanup.
>
> Finish 1 \[4\] is associated with exterior materials and is a lower
> priority than structural materials.

d.  Change Material =

    Wood - Horizontal Panel

![Image 14](media\image14.png)

> Note: Use search window in the Material Browser and type material name
> you are looking for.

e.  Change Thickness = **0' 1/2" (0.012m)**

![Image 15](media\image15.png)


7.  Edit Layer 3:

    a.  Select Layer 3 row

    b.  Click Down button twice

    c.  Click Function = Finish 2 \[5\]

> Note: Finish 2 \[5\] is associated with interior materials and is a
> lower priority than structural materials.

d.  Change Material =

    Wood - Horizontal Panel

e.  Change Thickness = **0' 1/2" (0.012m)**

![Image 16](media\image16.png)


8.  Click OK button twice to exit both dialog boxes

9.  Click Modify to end the wall placement command

Change interior wall types through substitution in-place

1.  Select all interior walls of

    Interior - 3 1/8\" Partition (1-hr) (0.79m).

    a.  Hover over an interior wall.

        ![](media\image17.png){width="2.3958333333333335in"
        height="1.7013156167979002in"}

    b.  Right click in the canvas window and select Select All
        > Instances\>Visible in View.

    c.  Select Wood Panel Wall wall type.

```{=html}
<!-- -->
```
10. Open Ground Floor plan view.

11. Select labeled exterior walls to receive Wood Panel Wall type.

    ![](media\image18.png){width="2.3958333333333335in"
    height="1.7013156167979002in"}

12. In Properties palette, change wall type to: Wood Panel Wall type.

13. Open {3D} 3D View. Confirm interior walls and selected exterior
    walls have wood paneling.

    ![](media\image19.png){width="2.7291666666666665in"
    height="1.5513156167979003in"}

14. Save the Revit file as: Module02Ex01_Modelling wall
    types_structures_design features_Imperial_Finished.rvt

    This concludes Exercise 1.

[]{#Exercise1B .anchor}Exercise 2 --- Adding Doors, Windows, and Wall
Openings

In this exercise, you will add doors and window openings using the array
command to the same house used in the previous exercise using Autodesk
Revit.

Objectives:

-   Place windows and doors and change their location using temporary
    dimensions.

-   Use arrays to quickly place groups of regularly spaced windows.

-   Use the Group and Associate array option.

-   Edit door and window instance properties.

-   Create new window and door types.

-   Create wall openings.

Place and array exterior doors

1.  Navigate to the folder containing the downloaded resources for
    Module 2.

Module02_Resources

15. Open Revit file:

    Module02Ex02_Adding doors windows openings_Imperial_Start.rvt

16. Open the Floor -- Living Area plan view.

17. On the View Control toolbar, set the visual style to Wireframe.

    ![](media\image20.png){width="2.013888888888889in"
    height="1.17250656167979in"}

18. On the Architecture tab, click Door.

    ![](media\image21.png){width="1.88in" height="0.95in"}

19. In Properties Palette, select Double-Glass 48" x 108" door type.

    ![](media\image22.png){width="1.4434481627296587in"
    height="1.9305555555555556in"}

20. Place Double-Glass 48" x 108"door type at location shown below.

    ![](media\image23.png){width="2.6944444444444446in"
    height="1.5315791776027996in"}

    a.  Hover cursor over Revit wall and use CAD underlay as a reference
        > guide for handing and swing direction

    b.  Left click to place door

    c.  Hit ESC key twice to end the door placement command.

21. Array the previous door to create the remaining two doors along that
    wall.

    a.  Select the double door just placed in plan view.

    b.  Click the Array tool in the Modify panel.

        ![](media\image24.png){width="1.66in" height="0.79in"}

    c.  Set the Array number = 3.

        ![](media\image25.png){width="2.3637226596675416in"
        height="1.6666666666666667in"}

> Note: This sets the total number of instances to be arrayed including
> the first door.

d.  Set the array distance and direction graphically on-screen. Pick the
    > two points shown below.

    ![](media\image26.png){width="2.4722222222222223in"
    height="1.4052635608048993in"}

> Note: Use the same reference point for point 2.

e.  Hit the Enter key to accept the array.

f.  Click ESC key twice to end the array command.

```{=html}
<!-- -->
```
22. Open {3D} 3D view and confirm doors are inserted correctly as shown
    below.

    ![](media\image27.png){width="2.675540244969379in"
    height="1.5208333333333333in"}

Place and array exterior windows

1.  On the Architecture tab, click Window.

    ![](media\image28.png){width="1.88in" height="0.95in"}

```{=html}
<!-- -->
```
23. In Properties Palette, select Casement Dbl with Trim 48" x 72"
    window type.

24. Place Casement Dbl with Trim 48" x 72"window type at location shown
    below.

    ![](media\image29.png){width="2.6805555555555554in"
    height="1.5236843832020996in"}

    a.  Hover cursor over Revit wall and use CAD underlay as a reference
        > guide for handing and swing direction.

> ![](media\image30.png){width="1.7911515748031497in"
> height="1.4880336832895888in"}
>
> Plan view enlarged
>
> ![](media\image31.png){width="1.7824070428696412in"
> height="1.5277777777777777in"}
>
> Section view

b.  Left click to place window.

c.  Hit ESC key twice to end the window placement command.

```{=html}
<!-- -->
```
25. Array the previous window to create the remaining two windows along
    that wall.

    a.  Select the casement window just placed in plan view.

    b.  Click the Array tool in the Modify panel.

        ![](media\image24.png){width="1.66in" height="0.79in"}

    c.  Set the Array number = 3.

    d.  Set the array distance and direction graphically on-screen. Pick
        > the two points shown below.

        ![](media\image32.png){width="2.1868558617672793in"
        height="1.2430555555555556in"}

> Note: Use the same reference point for point 2.

e.  Hit the Enter key to accept the array.

f.  Click ESC key twice to end the array command.

```{=html}
<!-- -->
```
26. Open {3D} 3D view and confirm windows are inserted correctly as
    shown below.

    ![](media\image33.png){width="2.675540244969379in"
    height="1.5208333333333333in"}

27. Save the Revit file as: Module02Ex02_Adding doors windows
    openings_Imperial_Finished.rvt

    This concludes Exercise 2.

[]{#Exercise1C .anchor}Exercise 3 --- Creating Roof Shapes

In this exercise, you will create two hip roofs and join them for the
house used in the previous exercise using Autodesk Revit.

Objectives:

-   Create roofs by specifying their footprint and adjusting their
    properties.

-   Modify a roof footprint and slope-defining edges to fine-tune the
    shape and create various roof shapes and forms.

-   Create a custom roof form by extruding a roof surface from a
    sketched profile.

Create a hip roof over the main living area

1.  Navigate to the folder containing the downloaded resources for
    Module 2.

Module02_Resources

28. Open Revit file: Module02Ex03_Creating roof
    shapes_Imperial_Start.rvt

29. Open the Roof-Living & Bedrooms plan view. Focusing on roof 1.

    ![](media\image34.png){width="2.6851859142607175in"
    height="2.2222222222222223in"}

30. On the Architecture tab, click Roof by Footprint.

    ![](media\image35.png){width="2.77in" height="0.84in"}

31. In Properties Palette, select Basic Roof Generic - 12" roof type and
    set Base Offset from Level = **0'-0" (0m)**.

32. In Modify \| Create Roof Footprint tab, confirm Boundary Line and
    Line mode is selected.

    ![](media\image36.png){width="1.97in" height="0.96in"}

    a.  Mark Defines slope check box.

        ![](media\image37.png){width="1.38in" height="1.12in"}

33. Create a closed boundary as indicated by the (3) sketch lines shown
    in red for roof form 1.

    ![](media\image34.png){width="2.6851859142607175in"
    height="2.2222222222222223in"}

    a.  Click Modify command to end sketching.

        *Note: Linework must be contiguous.*

34. Set the roof pitch for the sloped linework.

    a.  Window select all of the sketch linework for the roof sketch.

        ![](media\image38.png){width="1.7152777777777777in"
        height="1.625in"}

    b.  In Properties palette, set pitch to **3" (0.0762m)**.

        ![](media\image39.png){width="1.8611111111111112in"
        height="1.782557961504812in"}

35. Click Finish Edit Mode to create the 3D roof element.

    ![](media\image40.png){width="1.96in" height="0.96in"}

    *Note: If you receive error messages, confirm that none of the
    linework overlaps itself. Then try Finish Edit mode again.*

    a.  Attach highlighted walls to roof? Click Yes.

        ![C:\\Users\\herridj\\AppData\\Local\\Temp\\SNAGHTML1bc7b6f.PNG](media\image41.png){width="2.5277777777777777in"
        height="1.04128280839895in"}

36. Roof progress shown below.

    ![](media\image42.png){width="2.6875in"
    height="1.5276312335958004in"}

Create a hip roof over the bedroom area

1.  Open the Roof-Living & Bedrooms plan view. Focusing on roof 2.

    ![](media\image34.png){width="2.6851859142607175in"
    height="2.2222222222222223in"}

```{=html}
<!-- -->
```
37. On the Architecture tab, click Roof by Footprint.

    ![](media\image35.png){width="2.77in" height="0.84in"}

38. In Properties Palette, select Basic Roof Generic - 12" roof type and
    set Base Offset from Level = **0'-0" (0m)**.

39. In Modify \| Create Roof Footprint tab, confirm Boundary Line and
    Line mode is selected.

    ![](media\image36.png){width="1.97in" height="0.96in"}

    a.  Mark Defines slope check box.

        ![](media\image37.png){width="1.38in" height="1.12in"}

40. Create the (3) sketch lines shown below in blue for roof form 2.

    ![](media\image34.png){width="2.6851859142607175in"
    height="2.2222222222222223in"}

    a.  Hit ESC key once to pause sketching continuously.

    b.  Unmark Defines slope check box.

        ![](media\image43.png){width="1.44in" height="1.14in"}

    ```{=html}
    <!-- -->
    ```
    a.  Create (1) sketch line shown below in green for roof form 2 to
        > create a closed boundary.

        ![](media\image34.png){width="2.4444444444444446in"
        height="2.022987751531059in"}

41. Set the roof pitch for the sloped linework.

    a.  Select the (3) sketch lines below.

        ![](media\image44.png){width="2.4027777777777777in"
        height="1.3657895888013998in"}

    b.  In Properties palette, set pitch to **3" (0.0762m)**.

        ![](media\image39.png){width="1.8611111111111112in"
        height="1.782557961504812in"}

42. Click Finish Edit Mode to create the 3D roof element.

    ![](media\image40.png){width="1.96in" height="0.96in"}

    *Note: If you receive error messages, confirm that none of the
    linework overlaps itself. Then try Finish Edit mode again.*

    a.  Attach highlighted walls to roof? Click Yes.

        ![C:\\Users\\herridj\\AppData\\Local\\Temp\\SNAGHTML1bc7b6f.PNG](media\image41.png){width="2.5277777777777777in"
        height="1.04128280839895in"}

43. Roof progress shown below.

    ![](media\image45.png){width="2.7291666666666665in"
    height="1.5513156167979003in"}

Join the two hip roofs together

1.  Open the {3D} 3D View. Orbit the view to the following orientation
    shown below where we can see the gable end of the bedroom roof
    created in the previous step.

    ![](media\image46.png){width="2.7291666666666665in"
    height="1.5513156167979003in"}

```{=html}
<!-- -->
```
44. Select the bedroom roof, the one with the gable end facing you
    on-screen.

45. On the Modify \| Roofs tab, Geometry panel, click the Join / Unjoin
    Roof tool.

    ![](media\image47.png){width="1.15in" height="0.97in"}

    a.  Select the top edge of the bedroom roof as indicated by Mark 1
        > below.

        ![](media\image48.png){width="2.173611111111111in"
        height="1.2355260279965004in"}

    b.  Then, pick the face of the main living room roof to project to
        > as indicated by Mark 1 below.

        ![](media\image49.png){width="2.173611111111111in"
        height="1.2355271216097987in"}

46. Roof progress as shown below.

    ![](media\image50.png){width="2.7222222222222223in"
    height="1.5473687664041995in"}

47. Cleanup the interior walls projecting through the bedroom roof.

    a.  Select the interior walls.

    b.  Click Attach / Top Base command.

    c.  Select bedroom roof.

48. Roof completed as shown below.

    ![](media\image51.png){width="2.6805555555555554in"
    height="1.5236843832020996in"}

    This concludes Exercise 3.
