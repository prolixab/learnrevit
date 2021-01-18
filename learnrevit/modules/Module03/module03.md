![](media\image1.png){width="3.7995417760279966in"
height="1.9331003937007873in"}Introduction to BIM

Module 03 Curtain Systems

In this module, you will explore techniques for working with curtain
walls and the elements that

define a complete curtain system---panels, grids, and mullions.

You will be able to:

-   Specify the layout and spacing of the curtain wall elements for new
    curtain wall systems and how to modify existing ones.

-   Explore the design options available for customizing grid patterns,
    panel materials, and panel types.

Steps to take

[Exercise 1 Creating Curtain Walls](#Exercise1A)

[Exercise 2 Adjusting Grid Lines](#Exercise1B)

[Exercise 3 Choosing and Creating Curtain Panel Types](#Exercise1C)

[Exercise 4 Placing Doors in Curtain Walls](#Exercise1D)

Exercise requirements

To use Autodesk Revit you will need an Autodesk ID. As a Student or
Educator, you can obtain an Autodesk ID for free at
[www.autodesk.com/education](http://www.autodesk.com/education) .

-   Download the Autodesk Revit software for free at
    [www.autodesk.com/education](http://www.autodesk.com/education) and
    install it.

[]{#Exercise1A .anchor}Exercise 1 --- Modeling Wall Types, Structures,
and Design Features

In this exercise, you will learn to substitute a curtain wall for an
opaque wall and define its grid line layout through parametric rules.

Objectives:

-   Create new curtain walls.

-   Change the type of an existing wall to a curtain wall.

-   Adjust the placement and orientation of curtain walls.

-   Define curtain wall type properties to automatically place curtain
    grids and

    mullions.

Create a new curtain wall type and define its properties

1.  Navigate to the folder containing the downloaded resources for
    Module 1.

Module03_Resources

2.  Open Revit file: Module03Ex01_Creating curtain
    walls_Imperial_Start.rvt

3.  Open the First Floor plan view.

4.  Create a new curtain wall type.

    a.  Select the exterior wall indicated by Mark 1 below.

        ![](media\image2.png){width="2.316389982502187in"
        height="1.5138888888888888in"}

    b.  In Properties Palette, select:

Curtain Wall 2 wall type.

![](media\image3.png){width="1.8309175415573054in"
height="2.6319444444444446in"}

*Note: Curtain Wall 2 creates a singular plate of glass to the extents
of the wall area with no 3D geometry automatically created for
mullions.*

c.  In Properties palette, click Edit Type.

d.  In Type Properties dialog box, click Duplicate.

e.  Rename curtain wall to:

> Residence NorthWall

a.  Click OK.

```{=html}
<!-- -->
```
5.  Define curtain grid properties of new curtain wall.

    a.  Set type properties for vertical and horizontal grids to Fixed
        > Number.

        ![C:\\Users\\herridj\\AppData\\Local\\Temp\\SNAGHTMLcba518.PNG](media\image4.png){width="2.3898140857392827in"
        height="2.4722222222222223in"}

        *Note: We will specify actual quantity of grids in the Instance
        properties.*

    b.  Click OK to continue.

    c.  In Properties palette, set grid properties as follows:

        ![](media\image5.png){width="1.7954932195975504in"
        height="2.2777777777777777in"}

    d.  Click Apply to continue.

    e.  Click Modify to end the command.

6.  Open North-Residence elevation view.

7.  Curtain wall should look like the finished one below.

    ![](media\image6.png){width="1.7777777777777777in"
    height="1.9492377515310586in"}

8.  Save the Revit file as: Module03Ex01_Creating curtain
    walls_Imperial_Finished.rvt

    This concludes Exercise 1.

[]{#Exercise1B .anchor}Exercise 2 --- Adjusting Grid Lines

In this exercise, you will explore designing a creative curtain grid
layout for the same house used in the previous exercise using Autodesk
Revit.

Objectives:

-   Add new grids to existing curtain walls.

-   Edit existing curtain grid lines and segments.

-   Add mullions to curtain grid lines.

-   Pin and unpin curtain system elements to prevent or allow changes to
    the layout.

Modify North side residence curtain wall design

1.  Navigate to the folder containing the downloaded resources for
    Module 3.

Module03_Resources

9.  Open Revit file:

    Module03Ex02_Adjusting grid lines_Imperial_Start.rvt

10. Open North-Residence elevation view.

    a.  Starting curtain grid layout.

        ![](media\image6.png){width="1.7777777777777777in"
        height="1.9492377515310586in"}

    b.  Finished curtain grid layout.

![](media\image7.png){width="1.7291666666666667in"
height="1.9223293963254593in"}

11. Deleting grid segments.

    a.  Select grid line to be modified indicated by Mark 1 below.

        ![](media\image8.png){width="1.9934426946631671in"
        height="1.3958333333333333in"}

        *Note: You may need to use the TAB key to cycle to the nested
        grid line element.*

    b.  Click the Add / Remove Segments command.

        ![](media\image9.png){width="1.72in" height="1.0in"}

    c.  Click the grid segment indicated by the red X to remove it.

        ![](media\image8.png){width="1.9934426946631671in"
        height="1.3958333333333333in"}

    d.  Click Modify command to end the command.

    e.  Confirm your result below.

        ![](media\image10.png){width="1.5560793963254593in"
        height="1.4513888888888888in"}

12. Adding grid segments entire length.

    a.  On the Architecture tab, Build panel, Click the Curtain Grid
        > command.

        ![](media\image11.png){width="2.4063648293963253in"
        height="0.7792847769028871in"}

    b.  Click the All Segments command.

        ![](media\image12.png){width="1.8in" height="0.8in"}

    c.  Snap a grid line at Mark 1 shown below. Hover over the bottom of
        > the curtain wall and find the midpoint snap for that panel and
        > left click with mouse to insert grid line.

        ![](media\image13.png){width="1.4279188538932635in"
        height="1.4722222222222223in"}

13. Adding grid segments for one segment.

    a.  Click the Curtain Grid command.

    b.  Click the One Segment command.

        ![](media\image14.png){width="1.8in" height="0.8in"}

    c.  Snap a grid line at Mark 1 shown below. Hover over the bottom of
        > the curtain wall and find the midpoint snap for that panel and
        > left click with mouse to insert grid line.

        ![](media\image15.png){width="1.5508464566929134in"
        height="1.5763888888888888in"}

14. Continue the grid layout process using the previous techniques until
    your elevation looks like the one below.

    ![](media\image7.png){width="1.7291666666666667in"
    height="1.9223293963254593in"}

15. Add 3D mullions to curtain grid lines

    a.  On the Architecture tab, Build panel, Click the Mullion command.

        ![](media\image16.png){width="2.3472222222222223in"
        height="0.7613757655293089in"}

    b.  On the Placement panel, Click the All Grid Lines command.

> ![](media\image17.png){width="1.03in" height="0.8in"}

c.  Place your cursor over any grid line on that curtain wall and left
    > click with mouse to apply 3D mullions to the entire curtain wall.

> ![](media\image18.png){width="1.58211176727909in"
> height="1.7480107174103237in"}

16. Finished result shown below.

> ![](media\image19.png){width="1.7971642607174103in"
> height="1.839750656167979in"}

17. Save the Revit file as: Module03Ex02_Adjusting grid
    lines_Imperial_Finished.rvt

    This concludes Exercise 2.

[]{#Exercise1C .anchor}Exercise 3 --- Creating curtain panel types

In this exercise, you will create a curtain panel type and layout for
the house used in the previous exercise using Autodesk Revit.

Objectives:

-   Select individual curtain wall panels.

-   Change curtain wall panels to different types.

-   Select multiple curtain wall panels to be modified at once.

-   Create new curtain panel types and specifying their properties.

Assign curtain panels to specific locations on a curtain wall by
substitution in-place

1.  Navigate to the folder containing the downloaded resources for
    Module 3.

Module03_Resources

18. Open Revit file: Module03Ex03_Creating curtain panel
    types_Imperial_Start.rvt

19. Open the North-Residence elevation view.

    a.  Starting curtain panel layout.

        ![](media\image20.png){width="1.5833333333333333in"
        height="1.5405402449693788in"}

    b.  Finished curtain panel layout.

![](media\image21.png){width="1.5825557742782153in" height="1.6875in"}

20. Apply Solid -- White curtain panel to upper left curtain panel
    indicated by Mark 1 below. Make a selection set of curtain panel
    using any of the techniques below.

    ![](media\image22.png){width="1.4406616360454942in"
    height="1.5361964129483814in"}

    a.  Tab selection technique:

        i.  Hover over mullion edge adjacent to panel 1.

        ii. Hit the Tab key (3) times to cycle through elements and
            > acquire a tool tip that reads curtain panel.

            ![](media\image23.png){width="1.816550743657043in"
            height="1.7916666666666667in"}

        iii. Left click to accept selection set.

    b.  Window and Filter selection set technique:

        i.  Create either a crossing window selection set window through
            > panel 1 from the roof down into panel 1 or create a normal
            > selection window around panel 1.

        ii. Click Filter from Selection panel.

            ![](media\image24.png){width="0.92in" height="0.79in"}

        iii. Isolate Curtain Panels category. Click Check None, then
             > mark Curtain Panels category, and finally Click OK to
             > continue.

             ![C:\\Users\\herridj\\AppData\\Local\\Temp\\SNAGHTML15e1174.PNG](media\image25.png){width="2.12917760279965in"
             height="2.0555555555555554in"}

             *Note: Window selections sets apply all the way through the
             model view and may obtain panels you can't see from that
             view. Experiment with where you create selection set
             windows.*

21. In Properties Palette, select Solid - White curtain panel.

    ![](media\image26.png){width="1.4166666666666667in"
    height="2.407438757655293in"}

22. Click Modify command to end command.

23. Complete the remaining White curtain panel assignments as shown
    below.

    ![](media\image21.png){width="1.6666666666666667in"
    height="1.6521883202099739in"}

Create new curtain panel types, materials, and finish design layout

1.  Make a selection set of curtain panel indicated by Mark 1 below.

    ![](media\image27.png){width="1.6420505249343833in"
    height="1.7509394138232721in"}

```{=html}
<!-- -->
```
24. In Properties Palette, click Edit Type.

25. In Type Properties dialog box, click Duplicate.

26. Rename to: Solid - Gray

27. Click OK to continue.

28. Left click in the value field for Material, then click the Browse
    button.

    ![](media\image28.png){width="2.315679133858268in"
    height="1.0920538057742781in"}

29. In the Material Browser, type: **gray** in the search window and
    select the Gray Panel material.

    ![](media\image29.png){width="2.4424070428696414in"
    height="1.678526902887139in"}

30. Click OK twice to continue.

31. Click Modify to end the command.

32. Progress result shown below.

    ![](media\image30.png){width="1.7699070428696413in"
    height="1.7951017060367453in"}

33. Repeat the previous steps to create a new panel type called: Wood
    Panel -- Dark.

    a.  Assign the material: Wood Panel -- Dark.

    b.  Apply the material to the following curtain panel location shown
        > below.

        ![](media\image31.png){width="1.8783497375328084in"
        height="1.9236111111111112in"}

34. Save the Revit file as: Module03Ex03_Creating curtain panel
    types_Imperial_Finished.rvt

    This concludes Exercise 3.

[]{#Exercise1D .anchor}Exercise 4 --- Placing Doors in Curtain Walls

In this exercise, you will learn about a custom door type specifically
designed for curtain walls for the house used in the previous exercise
using Autodesk Revit.

Objectives:

-   Adjust curtain grid segments to create a panel with the dimensions
    for a desired door opening.

-   Change a curtain wall panel element into a single or double door.

Assign curtain panels to specific locations on a curtain wall by
substitution in-place

1.  Navigate to the folder containing the downloaded resources for
    Module 3.

Module03_Resources

35. Open Revit file: Module03Ex04_Placing door in curtain
    walls_Imperial_Start.rvt

36. Open the South-Studio elevation view.

    a.  Starting curtain panel layout.

        ![](media\image32.png){width="1.7497944006999124in"
        height="1.8125in"}

    b.  Finished curtain panel layout.

![](media\image33.png){width="1.7709306649168854in"
height="1.9027777777777777in"}

37. Modify the curtain grid lines as shown below using the techniques
    learned in Exercise 2 of this module.

    ![](media\image34.png){width="1.7380949256342957in"
    height="1.8125in"}

38. Change width of curtain panel indicated by Mark 1 below to receive a
    door.

    a.  Select curtain grid line to reveal temporary dimensions.

        ![](media\image35.png){width="1.4027777777777777in"
        height="1.4848108048993875in"}

    b.  Set width = **4'-0" (1.21m)**

    c.  Hit the Enter key to accept value.

39. Assign the numbered curtain panels below, curtain panel type: Wood
    -- Dark.

    ![](media\image36.png){width="1.737004593175853in"
    height="1.8293667979002626in"}

40. Assign the highlighted panel in light blue below, curtain panel
    type:

Curtain Wall Single Door - Wood

![](media\image37.png){width="1.8730621172353457in"
height="1.9916896325459317in"}

41. Save the Revit file as: Module03Ex04_Placing door in curtain
    walls_Imperial_Finished.rvt

    This concludes Exercise 4.
