---
layout: page
title: Building Envelope - Exercise 1
permalink: /modules/module02/exercise1
exclude: true
---

[Learn Revit](/learnrevit/) > [Module 2](/learnrevit/modules/module02/) > Exercise 1

## Modeling Wall Types, Structures, and Design Features

###  Change exterior wall types through substitution in-place

2.  **Download the start file [here](Module02Ex01.rvt).**

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

### Create a new interior wall type

1.  Open the Ground Floor plan view.

1.  On the Architecture tab, click Wall.

    ![](media\image6.png)

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

        Thickness = **0.041m**

    ![Image 11](media\image11.png)

        *Note: Use search window in the Material Browser and type
        material name you are looking for.*

> Structure \[1\] is associated with structural materials supporting a
> wall and has the highest cleanup priority.

c.  Click Insert button two times to add (2) new layers to the wall
    > definition

![Image 12](media\image12.png)

![Image 13](media\image13.png)

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

e.  Change Thickness = **0.012m**

![Image 15](media\image15.png)


7.  Edit Layer 3:

    a.  Select Layer 3 row

    b.  Click Down button twice

    c.  Click Function = Finish 2 \[5\]

> Note: Finish 2 \[5\] is associated with interior materials and is a
> lower priority than structural materials.

d.  Change Material =

    Wood - Horizontal Panel

e.  Change Thickness = **0.012m**

![Image 16](media\image16.png)


8.  Click OK button twice to exit both dialog boxes

9.  Click Modify to end the wall placement command

### Change interior wall types through substitution in-place

1.  Select all interior walls of

    Interior - 3 1/8\" Partition (1-hr) (0.79m).

    a.  Hover over an interior wall.

     ![Image17](media\image17.png)

    b.  Right click in the canvas window and select Select All
        > Instances\>Visible in View.

    c.  Select Wood Panel Wall wall type.


10. Open Ground Floor plan view.

11. Select labeled exterior walls to receive Wood Panel Wall type.

    ![Image18](media\image18.png)

12. In Properties palette, change wall type to: Wood Panel Wall type.

13. Open {3D} 3D View. Confirm interior walls and selected exterior
    walls have wood paneling.

    ![Image19](media\image19.png)

14. Save the Revit file as: Module02Ex01_Finished.rvt and hand in.

    This concludes Exercise 1.

