![](media\image1.png){width="3.7995417760279966in"
height="1.9331003937007873in"}Introduction to BIM

Module 07 Rendering Materials

In this module, you explore how to use Autodesk® Revit® software to
adjust the appearance of the building model elements that appear in
their 2D and 3D views.

You will be able to:

-   Assign materials to model elements through object styles, type
    properties, and instance properties.

-   Adjust the render appearance of materials to display realistic
    views.

Steps to take

[Exercise 1 Assigning Materials to a Component](#Exercise1A)

[Exercise 2 Creating New Materials](#Exercise1B)

Exercise requirements

To use Autodesk Revit you will need an Autodesk ID. As a Student or
Educator, you can obtain an Autodesk ID for free at
[www.autodesk.com/education](http://www.autodesk.com/education) .

-   Download the Autodesk Revit software for free at
    [www.autodesk.com/education](http://www.autodesk.com/education) and
    install it.

[]{#Exercise1A .anchor}Exercise 1 --- Assigning Materials to a Component

In this exercise, you will learn how to assign existing rendering
materials to building elements. Rendering materials can be defined as
either a type property or an instance property.

Objectives:

-   Assign materials to model elements by object category.

-   Assign materials by altering an element's type properties.

-   Assign materials by specifying an element's instance properties.

Create a new material for sidewalk and ramp on East side of Residence
and Studio buildings

Sidewalk

1.  Navigate to the folder containing the downloaded resources for
    Module 7.

Module07_Resources

2.  Open Revit file:

    Module07Ex01_Assigning Materials to a Component_Imperial_Start.rvt

3.  Open the Exterior Perspective 3D plan view.

4.  Hover over the exterior sidewalk and note the category and material.

![](media\image2.png){width="2.673611111111111in"
height="1.6030905511811024in"}

5.  Open the First Floor plan view.

6.  Create a new floor style.

    a.  Select the exterior concrete sidewalk**.**

    b.  In Properties palette, Click Edit Type.

    c.  Click Duplicate.

    d.  Rename to: Wood Patio.

    e.  Click OK.

7.  Change structural properties.

    a.  Click Edit... button in Structural field.

    b.  Change properties as follows:

        Mark 1 = Set thickness to **4" (0.10m**).

        Mark 2 = Material to: Wood Deck.

> ![](media\image3.png){width="2.42in" height="1.33in"}

8.  Click OK twice to accept all changes.

Ramp

9.  Select ramp element.

10. In Properties palette, click Edit Type.

11. Apply new floor type to exterior ramp.

> ![](media\image4.png){width="2.13in" height="1.11in"}

12. Finished override results below.

    ![](media\image5.png){width="2.6666666666666665in"
    height="1.5692727471566055in"}

Change materials assigned to console table

1.  Open the First Floor plan view.

```{=html}
<!-- -->
```
13. Zoom into the Living Room area.

14. Match materials used for sectional sofa family.

    a.  Select Sectional Sofa_6482 family**.**

    b.  In Properties palette, Click Edit Type.

    c.  Note which materials are assigned for reference.

        ![](media\image6.png){width="2.37in" height="1.42in"}

    d.  Click Cancel.

15. Assign similar materials to Console Table.

    a.  Select Console Table along East wall.

    b.  In Properties palette, instance properties.

        Table Surface = Laminate -- Ivory, matte

        Table Frame = frame

        Pedestal = frame

![](media\image7.png){width="1.85in" height="2.26in"}

16. Final results shown below.

    ![](media\image8.png){width="2.2599628171478567in"
    height="1.9636570428696414in"}

17. Save the Revit file as: Module07Ex01_Assigning Materials to a
    Component_Imperial_Finished.rvt

    This concludes Exercise 1

[]{#Exercise1B .anchor}Exercise 2 --- Creating New Materials

In this exercise, you will learn how to create new rendering materials
by accessing the Asset Browser material library to import rendering
materials into the current project for use and assign materials to
components.

Objectives:

-   Create new materials by duplicating existing ones and setting the
    shading color

    and surface pattern.

-   Replace the render appearance assigned to materials using options
    available

    in the Autodesk library.

-   Adjust settings to fine-tune or alter a material's render
    appearance.

Create new materials for Eames chair

Chair Frame

1.  Navigate to the folder containing the downloaded resources for
    Module 7.

Module07_Resources

18. Open Revit file:

    Module07Ex02_Creating New Materials_Imperial_Start.rvt

19. Open Living Room Interior 3D plan view.

20. On the Manage tab, Settings panel, click Materials command.

21. Select the frame material from Material Browser.

    a.  Duplicate the material

        ![](media\image9.png){width="1.41in" height="2.38in"}

    b.  Rename copied material to:

        Eames Chair Frame.

    c.  Open Asset Browser.

        ![](media\image10.png){width="1.6418088363954506in"
        height="0.5917180664916886in"}

    d.  Open Asset Browser.

        i.  Search for **teak** (Mark 1)

        ii. Select Wood -- Teak material (Mark 2)

        iii. Double Left click to assign material asset to Eames Chair
             > Frame material name.

             ![C:\\Users\\herridj\\AppData\\Local\\Temp\\SNAGHTML9d1dee.PNG](media\image11.png){width="2.39in"
             height="0.94in"}

    e.  Close Asset Browser.

22. Assign surface pattern to material.

    a.  Select Graphics tab (Mark 1)

    b.  Surface pattern: Select Wood 3 (Mark 2)

        ![C:\\Users\\herridj\\AppData\\Local\\Temp\\SNAGHTML9f7a02.PNG](media\image12.png){width="2.45in"
        height="1.39in"}

23. Click OK to accept material changes.

Chair Leather

1.  On the Manage tab, Settings panel, click Materials command.

```{=html}
<!-- -->
```
24. Select the Eames Chair Frame material from Material Browser.

    a.  Duplicate the material

    b.  Rename copied material to:

        Eames Chair Leather.

    c.  Open Asset Browser.

        i.  Search for **creased black** from the Leather library

        ii. Select Creased - Black materia

        iii. Double Left click to assign material asset to Eames Chair
             > Leather material name.

             ![C:\\Users\\herridj\\AppData\\Local\\Temp\\SNAGHTMLa5c8fc.PNG](media\image13.png){width="2.39in"
             height="0.68in"}

    d.  Close Asset Browser.

25. Click OK to accept material changes.

Chair Metal

1.  On the Manage tab, Settings panel, click Materials command.

```{=html}
<!-- -->
```
26. Select the Eames Chair Frame material from Material Browser.

    a.  Duplicate the material

    b.  Rename copied material to:

        Eames Chair Metal.

    c.  Open Asset Browser.

        i.  Search for **chrome polished** from the Metal library.

        ii. Select Chrome - Polished material.

        iii. Double Left click to assign material asset to Eames Chair
             > Metal material name.

             ![C:\\Users\\herridj\\AppData\\Local\\Temp\\SNAGHTMLaa1da1.PNG](media\image14.png){width="2.31in"
             height="0.79in"}

    d.  Close Asset Browser.

27. Click OK to accept material changes.

Assign new materials to Eames chair

1.  Open Living Room Interior 3D view.

2.  Select Eames Lounge chair.

3.  In Properties palette, instance properties:

    a.  Set Seat Fabric = Eames Chair Leather

    b.  Set Metal Parts = Eames Chair Metal

    c.  Set Wooden Shell = Eames Chair Frame

```{=html}
<!-- -->
```
28. Click Apply to accept material changes.

29. Set visual style to: Realistic.

30. Finished results shown below.

    ![](media\image15.png){width="2.4800656167979in"
    height="1.4097222222222223in"}

31. Save the Revit file as: Module07Ex02_Creating New
    Materials_Imperial_Finished.rvt

    This concludes Exercise 2.
