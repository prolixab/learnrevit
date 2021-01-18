![](media\image1.png){width="3.7995417760279966in"
height="1.9331003937007873in"}Introduction to BIM

Module 04 Interiors and Circulation

In this module, you will explore techniques for creating several types
of common circulation elements for multistory buildings, including
stairs, elevators, and ramps.

You will be able to:

-   Create simple examples demonstrating circulation techniques.

-   Edit and customize elements as needed to model more complex
    conditions.

-   Add railings at floor edges and around floor openings.

Steps to take

[Exercise 1 Creating a Stair and Ramp](#Exercise1A)

[Exercise 2 Modeling Custom Stairs](#Exercise1B)

[Exercise 3 Creating a Floor Opening](#Exercise1C)

[Exercise 4 Creating an Elevator](#Exercise1D)

Exercise requirements

To use Autodesk Revit you will need an Autodesk ID. As a Student or
Educator, you can obtain an Autodesk ID for free at
[www.autodesk.com/education](http://www.autodesk.com/education) .

-   Download the Autodesk Revit software for free at
    [www.autodesk.com/education](http://www.autodesk.com/education) and
    install it.

[]{#Exercise1A .anchor}Exercise 1 --- Creating a Stair and Ramp

In this exercise, you will learn to model stairs and ramps using the
same technique of creating run lines (path lines).

Objectives:

-   Create stairs by sketching run lines.

-   Flip a stair direction and move a stair into place.

-   Create stairs with multiple runs and complex layouts (for example,
    L-shaped,

    U-shaped, and curved stairs).

-   Create and modify ramps.

Create a straight run stair

1.  Navigate to the folder containing the downloaded resources for
    Module 4.

Module04_Resources

2.  Open Revit file: Module04Ex01_Creating Stair and
    Ramp_Imperial_Start.rvt

3.  Open the First Floor plan view. The dashed red line boundary is
    where the stair will be placed.

> ![](media\image2.png){width="2.4930555555555554in"
> height="2.863705161854768in"}

4.  On the Architecture tab, Circulation panel, click the pulldown menu
    for Stair tool.

    a.  Select Stair by Sketch

        ![](media\image3.png){width="1.12in" height="1.25in"}

    b.  Confirm that Base Level = First Floor, and Top Level = Second
        > Floor

        ![](media\image4.png){width="1.55in" height="1.97in"}

    c.  Confirm that stair width = **3'-0" (0.91m)**

        ![](media\image5.png){width="1.56in" height="1.31in"}

    d.  Set the base of the stair at Mark 1 by left clicking the mouse
        > and dragging the cursor downward to Mark 2 outside of the
        > bounding box and left click to set the upper end point of the
        > stair.

        ![](media\image6.png){width="1.8367300962379702in"
        height="1.898642825896763in"}

    e.  Sketch linework will appear.

        ![](media\image7.png){width="1.814248687664042in"
        height="1.8680041557305336in"}

    f.  Click Finish Edit Mode to create the 3D stair.

        ![](media\image8.png){width="1.78in" height="0.8in"}

5.  Move the stair into its final position.

    a.  Select the stair element.

    b.  Use the Move tool and set a base point at Mark 1 and the
        > destination point at Mark 2.

        ![](media\image9.png){width="1.7889610673665792in"
        height="1.869514435695538in"}

Create an L-shaped ramp

1.  In the First Floor plan view, pan downwards until you see the dashed
    red line boundary where the ramp will be placed.

> ![](media\image10.png){width="2.0182753718285213in"
> height="1.58413167104112in"}

6.  On the Architecture tab, Circulation panel

    a.  Click the Ramp tool.

        ![](media\image11.png){width="0.71in" height="0.86in"}

    ```{=html}
    <!-- -->
    ```
    a.  Confirm that Base Level = First Floor, Base Offset = **-1'-9"
        > (-0.53m)**, and Top Level = First Floor

        ![](media\image12.png){width="1.55in" height="1.35in"}

    b.  Confirm that the ramp width = **3'-0" (0.91m)**

        ![](media\image13.png){width="1.55in" height="1.22in"}

    c.  Set the base of the ramp at Mark 1 by left clicking the mouse
        > and dragging the cursor downward **15'-0" (4.57m)** to Mark 2
        > and left click, move the cursor to Mark 3 and left click, and
        > then move the cursor to the left and outside of the bounding
        > box and left click to set the upper end point of the stair at
        > Mark 4.

        ![](media\image14.png){width="1.8833333333333333in"
        height="2.0925929571303588in"}

        *Note: We will move the ramp to its final position in a later
        step.*

    d.  Sketch linework will appear.

        ![](media\image15.png){width="2.097729658792651in"
        height="2.233946850393701in"}

        *Note: Confirm that 0" is remaining.*

    e.  Click Finish Edit Mode to create the 3D ramp.

        ![](media\image8.png){width="1.78in" height="0.8in"}

7.  Move the ramp into its final position.

> ![](media\image16.png){width="1.8892268153980751in"
> height="2.1805555555555554in"}

8.  Ramp fit and finish items.

    a.  Open {3D} 3D View.

    b.  Delete the ramp railings

    c.  Select the ramp and set the

        Top Offset = **-3" (-0.1m)** to align with the sidewalk.

    d.  Make ramp solid.

        i.  Select ramp element.

        ii. In Properties palette, click Edit Type.

        iii. Change Shape value = Solid.

> ![](media\image17.png){width="2.4652777777777777in"
> height="0.40598753280839894in"}

iv. Click OK.

v.  Click Modify to end the command.

```{=html}
<!-- -->
```
e.  Final ramp result shown below.

> ![](media\image18.png){width="2.4879461942257217in"
> height="1.7638888888888888in"}

9.  Save the Revit file as: Module04Ex01_Creating Stair and
    Ramp_Imperial_Finished.rvt

    This concludes Exercise 1

[]{#Exercise1B .anchor}Exercise 2 --- Modeling Custom Stairs

In this exercise, you will use various methods to customize stairs via
Type Properties and Instance Properties.

Objectives:

-   Edit the sketch to change the stair boundary and shape of the
    risers.

-   Change stair and rail types.

-   Modify the steepness of a stair by adjusting the settings in the
    Properties

    palette.

-   Create and edit a spiral stair.

Create a steeper stair type for the Studio space

1.  Navigate to the folder containing the downloaded resources for
    Module 4.

Module04_Resources

10. Open Revit file:

    Module04Ex02_Modeling Custom Stairs_Imperial_Start.rvt

11. Open First Floor plan view.

    a.  Starting stair layout.

        ![](media\image19.png){width="1.7222222222222223in"
        height="1.764306649168854in"}

    b.  Finished stair layout.

![](media\image20.png){width="1.7870275590551181in"
height="1.8472222222222223in"}

12. Create a new stair type.

    a.  Select and delete the existing stair.

    b.  In the Architectural tab, Circulation panel, click Stair by
        > Sketch method.

    c.  In Properties palette, select stair type: Residential -- Open
        > Riser.

        ![](media\image21.png){width="1.55in" height="1.96in"}

    d.  Click Edit Type.

    e.  Click Duplicate.

    f.  Rename new stair type as:

        Residential -- Open Riser - Steep.

    g.  Set stair properties as follows:

        Min Tread Depth = **9" (0.22m)**

        Max Riser Height = **9" (0.22m)**

        ![](media\image22.png){width="2.4097222222222223in"
        height="1.3757928696412949in"}

    h.  Click OK to accept values and exit dialog boxes.

13. Create a new stair in the Studio room.

    a.  Set the base of the stair across from the column and dragging
        > the cursor downwards towards the opening and setting the upper
        > level of the stairs just beyond the bounding box.

        ![](media\image23.png){width="1.9366524496937882in"
        height="1.4562718722659667in"}

    b.  Move the upper level edge of the stair to align with the top
        > edge of the wall opening.

        ![](media\image24.png){width="1.9375in"
        height="1.4064271653543308in"}

Create a spiral stair for the Residence space

1.  In the First Floor plan view, pan downwards until you see the dashed
    boundary with red lines where the spiral stair will be placed.

> ![](media\image25.png){width="2.017405949256343in"
> height="1.8041568241469816in"}

14. Create a new stair type.

    a.  Select and delete the existing stair.

    b.  On the Architectural tab, Circulation panel, click Stair by
        > Sketch method.

    c.  In Properties palette, select stair type: Residential -- Open
        > Riser.

        ![](media\image21.png){width="1.55in" height="1.96in"}

    d.  Click Edit Type.

    e.  Click Duplicate.

    f.  Rename new stair type as:

        Residential -- Open Riser - Spiral.

    g.  Set stair properties as follows:

        Min Tread Depth = **11" (0.27m)**

        Max Riser Height = **10" (0.25m)**

        ![](media\image26.png){width="2.534514435695538in"
        height="0.7368285214348207in"}

    h.  Click OK to accept values and exit dialog box.

15. Create spiral stair.

    a.  Click Center End Arc mode.

        ![](media\image27.png){width="1.64in" height="0.74in"}

    b.  Place center point at red X origin point.

        ![](media\image28.png){width="1.8827405949256344in"
        height="1.6064687226596674in"}

    c.  Set Run radius = **2'-0" (0.60m)**.

    d.  Left click to set the upper level of the stair.

        ![](media\image29.png){width="1.7172747156605424in"
        height="1.4527220034995625in"}

        *Note: You will receive a warning message that the stair cannot
        be completed because it would revolve more than 360 degrees. We
        will address this next.*

    e.  In Properties palette, set Actual Tread Depth = **10" (0.25m)**.

        ![](media\image30.png){width="1.55in" height="1.48in"}

    f.  Erase the existing spiral stair sketch.

    g.  Resketch stair sketch.

        ![](media\image31.png){width="1.6036143919510062in"
        height="1.3680555555555556in"}

        *Note: Confirm that 0 risers are remaining.*

    ```{=html}
    <!-- -->
    ```
    a.  Click Finish Edit Mode to create the 3D stair.

        ![](media\image8.png){width="1.78in" height="0.8in"}

    b.  Progress stair shown below.

        ![](media\image32.png){width="1.7713845144356954in"
        height="1.5416666666666667in"}

16. Spiral stair fit and finish.

    a.  Flip the stair direction, select the stair and click the Flip
        > grip highlighted in the red circle.

        ![](media\image33.png){width="1.7289282589676291in"
        height="1.5486111111111112in"}

    b.  Rotate the stair so the upper level is horizontal. Select stair
        > and Click the Rotate tool in the Modify panel.

        ![](media\image34.png){width="1.8930413385826772in"
        height="1.5694444444444444in"}

17. Change stair handrail type to:

    Handrail -- Pipe.

18. Add a center pole for spiral stair.

    a.  On the Architectural tab, Build panel, click Column:
        > Architectural tool from the pulldown menu.

        ![](media\image35.png){width="2.455615704286964in"
        height="0.8011231408573928in"}

    b.  In Properties palette, select:

        Round Column -- 8" diameter and set Height constraint to Roof.

        ![](media\image36.png){width="2.454876421697288in"
        height="0.8125in"}

    c.  Locate column center at center of spiral stair.

19. Open First Floor -- Spiral Stair 3D view.

    ![](media\image37.png){width="1.9375in"
    height="2.0653357392825895in"}

20. Save the Revit file as: Module04Ex02_Modeling Custom
    Stairs_Imperial_Finished.rvt

    This concludes Exercise 2.

[]{#Exercise1C .anchor}Exercise 3 --- Creating a Floor Opening

In this exercise, you will create a floor opening for the spiral stair
created in the previous exercise and add protective railing.

Objectives:

-   Cut an opening to allow stairs to pass through floors.

-   Calculate the head height of stairways.

-   Modify floor openings.

-   Create railings.

-   Modify the physical properties of railings.

Create floor opening

1.  Navigate to the folder containing the downloaded resources for
    Module 4.

Module04_Resources

21. Open Revit file: Module04Ex03_Creating Floor
    Opening_Imperial_Start.rvt

22. Open the Second Floor plan view.

    a.  Starting spiral stair layout.

        ![](media\image38.png){width="1.5130653980752407in"
        height="1.3263888888888888in"}

    b.  Finished spiral stair layout.

        ![](media\image39.png){width="1.5167508748906386in"
        height="1.3125in"}

23. Select the second floor plate.

    a.  Create a crossing-window selection set starting just outside the
        > East wall and dragging inwards into the building.

    b.  Click the Filter tool to isolate the Floors category.

24. Edit floor boundary.

    a.  On Modify \| Floors tab, Mode panel, click Edit Boundary.

        ![](media\image40.png){width="1.86in" height="0.72in"}

    b.  Using the Line tool from the Draw panel, sketch out lines
        > indicated by Mark 1 and Mark 2 below.

        ![](media\image41.png){width="1.6625349956255469in"
        height="1.6493821084864393in"}

    c.  Switch to Center-ends Arc tool and draw an arc with a **3' --
        > 10" (1.16m)** radius starting from the North side and ending
        > at 180 degrees. Refer to picture above.

    d.  Hit ESC key once to end the sketch mode.

    e.  Select the Arc line and drag the endpoint clockwise to the 270
        > degree angle. Use the trim tool to clean up the linework as
        > needed.

        ![](media\image42.png){width="1.6111111111111112in"
        height="1.4312040682414697in"}

    f.  Click the Finish Edit Mode to generate the floor opening.

        ![](media\image43.png){width="1.82in" height="0.74in"}

    g.  If you receive a warning message, click Unjoin elements.

    h.  Finished floor opening result below.

        ![](media\image44.png){width="1.6388888888888888in"
        height="1.4779505686789152in"}

Add railing to floor opening

1.  On the Architectural tab, Circulation panel, from the Railing tool
    pulldown menu, click Sketch Path.

```{=html}
<!-- -->
```
25. Draw linear railing.

    a.  Use the Line tool to sketch the horizontal line from the column
        > to the edge of the wall indicated by Mark 1.

        ![](media\image45.png){width="1.6388888888888888in"
        height="1.5020866141732283in"}

    b.  Click Finish Edit Mode to generate the first railing element.

        ![](media\image46.png){width="1.24in" height="0.8in"}

        *Note: Railing sketches must be contiguous. The circular railing
        will be created separately.*

26. Draw curvilinear railing.

    a.  Use the Center-ends Arc tool to sketch a curvilinear line
        > tracing the floor opening starting at the top of the stairs
        > and dragging the arc clockwise to the 180 degree position.

        ![](media\image47.png){width="1.6319444444444444in"
        height="1.4983978565179352in"}

    b.  Hit ESC key twice, then select the arc line and drag the end
        > point from 180 degrees to 270 degrees.

    c.  Click Finish Edit Mode to generate the first railing element.

        ![](media\image46.png){width="1.24in" height="0.8in"}

    d.  Open Second Floor -- Spiral Stair 3D View to see the finished
        > railing result below.

        ![](media\image48.png){width="2.0453018372703413in"
        height="1.4722222222222223in"}

27. Save the Revit file as: Module04Ex03_Creating Floor
    Opening_Imperial_Finished.rvt

    This concludes Exercise 3.

[]{#Exercise1D .anchor}Exercise 4 --- Creating an Elevator

In this exercise, you will learn to integrate Elevator family components
along with Wall families to create an elevator enclosure.

Objectives:

-   Place an elevator component.

-   Add walls to enclose the elevator.

-   Cut an elevator shaft that spans all levels.

-   Provide openings in the shaft walls to access the elevator at each
    floor.

Place elevator components on first and second floors in the Studio space

1.  Navigate to the folder containing the downloaded resources for
    Module 4.

Module04_Resources

28. Open Revit file: Module04Ex04_Creating an
    Elevator_Imperial_Start.rvt

29. Open the First Floor plan view.

    a.  Starting Elevator layout.

        ![](media\image49.png){width="1.9547222222222222in"
        height="1.4930555555555556in"}

    b.  Finished Elevator layout.

        ![](media\image50.png){width="1.9586143919510062in"
        height="1.4392180664916885in"}

30. Place elevator components.

    a.  On Architectural tab, Build panel, click Component tool.

    b.  In Properties palette, select Electric_Lift 1000 x 880mm.

        ![](media\image51.png){width="1.64in" height="1.66in"}

    c.  Place elevator component at location shown with the edge aligned
        > with the wall face.

        ![](media\image52.png){width="1.929705818022747in"
        height="1.4375in"}

    d.  Select elevator component just placed and use Copy to Clipboard
        > from the Clipboard panel.

    e.  Open Second Floor plan view.

    f.  On the Modify tab, Clipboard panel, select Aligned to Current
        > View from the Paste pulldown menu to place another instance of
        > the elevator.

        ![](media\image53.png){width="1.23in" height="1.61in"}

    g.  Click Modify to end the placement command.

Add elevator enclosure walls

1.  Open the First Floor plan view.

    a.  On the Architecture tab, Build panel, click the Wall tool.

    b.  In the Properties palette, select the Generic Wall -- 6" wall
        > type.

    c.  Set Height constraint = Roof.

    d.  Layout the walls as shown below.

        ![](media\image54.png){width="1.9583333333333333in"
        height="1.4040999562554681in"}

        *Note: This particular design does not require Shaft Openings
        between floors for the elevators. In other cases you would use
        this element type to create openings in floors.*

2.  Open the Second Floor plan view.

    a.  On the Architecture tab, Build panel, click the Wall tool.

    b.  In the Properties palette, select the Generic Wall -- 6" wall
        > type.

    c.  Set Height constraint = Roof.

    d.  Layout the wall as shown below.

        ![](media\image55.png){width="1.9444444444444444in"
        height="1.5603083989501312in"}

Create wall openings for elevators

1.  Open the Second Floor plan view.

```{=html}
<!-- -->
```
a.  On the Architecture tab, Opening panel, click the Wall Opening tool.

b.  Layout the wall opening as shown below.

    ![](media\image56.png){width="0.9722222222222222in"
    height="1.055029527559055in"}

c.  Edit the wall opening element properties.

    I.  Select the wall opening element

    II. Change opening properties in Properties palette as shown. Set
        > Unconnected Height to **7'-0" (2.13m).**

        ![](media\image57.png){width="1.55in" height="1.97in"}

    III. Click Apply to accept.

d.  Open the First Floor plan view.

e.  Repeat the steps again to create a wall opening.

f.  Open Second Floor -- Elevator 3D view to check progress.

    ![](media\image58.png){width="1.9583333333333333in"
    height="1.5363265529308836in"}

Add guardrails

1.  Open the Second Floor plan view.

```{=html}
<!-- -->
```
a.  On the Architectural tab, Circulation panel, from the Railing tool
    > pulldown menu, click Sketch Path.

b.  Layout railings below using:

    Guardrail -- Pipe.

    ![](media\image59.png){width="1.9930063429571303in"
    height="1.2097287839020123in"}

c.  Finished elevator core and railing layout.

    ![](media\image60.png){width="2.3798873578302713in"
    height="1.5347222222222223in"}

```{=html}
<!-- -->
```
31. Save the Revit file as: Module04Ex04_Creating an
    Elevator_Imperial_Finished.rvt

    This concludes Exercise 4.
