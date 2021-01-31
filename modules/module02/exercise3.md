---
layout: page
title: Building Envelope - Exercise 3
permalink: /modules/module02/exercise3
exclude: true
---

[Learn Revit](/learnrevit/) > [Module 2](/learnrevit/modules/module02/) > Exercise 3

## Creating Roof Shapes

**In this exercise, you will create two hip roofs and join them for the
house used in the previous exercise using Autodesk Revit.**

Objectives:

-   Create roofs by specifying their footprint and adjusting their
    properties.

-   Modify a roof footprint and slope-defining edges to fine-tune the
    shape and create various roof shapes and forms.

-   Create a custom roof form by extruding a roof surface from a
    sketched profile.

###  Create a hip roof over the main living area

28. **Download the start file [here](Module02Ex03.rvt).**

29. Open the Roof-Living & Bedrooms plan view. Focusing on roof 1.

    ![](media\image34.png)

30. On the Architecture tab, click Roof by Footprint.

    ![](media\image35.png)

31. In Properties Palette, select Basic Roof Generic - 12" roof type and
    set Base Offset from Level = **0'-0" (0m)**.

32. In Modify \| Create Roof Footprint tab, confirm Boundary Line and
    Line mode is selected.

    ![](media\image36.png)

    a.  Mark Defines slope check box.

    ![](media\image37.png)

33. Create a closed boundary as indicated by the 3 sketch lines shown
    in red for roof form 1.

    ![](media\image34.png)

    a.  Click Modify command to end sketching.

        *Note: Linework must be contiguous.*

34. Set the roof pitch for the sloped linework.

    a.  Window select all of the sketch linework for the roof sketch.

    ![](media\image38.png)

    b.  In Properties palette, set pitch to **3" (0.0762m)**.

    ![](media\image39.png)

35. Click Finish Edit Mode to create the 3D roof element.

    ![](media\image40.png)

    *Note: If you receive error messages, confirm that none of the
    linework overlaps itself. Then try Finish Edit mode again.*

    a.  Attach highlighted walls to roof? Click Yes.

    ![](media\image41.png)

36. Roof progress shown below.

    ![](media\image42.png)

### Create a hip roof over the bedroom area

1.  Open the Roof-Living & Bedrooms plan view. Focusing on roof 2.

    ![](media\image34.png)


37. On the Architecture tab, click Roof by Footprint.

    ![](media\image35.png)

38. In Properties Palette, select Basic Roof Generic - 12" roof type and
    set Base Offset from Level = **0'-0" (0m)**.

39. In Modify \| Create Roof Footprint tab, confirm Boundary Line and
    Line mode is selected.

    ![](media\image36.png)

    a.  Mark Defines slope check box.

    ![](media\image37.png)

40. Create the 3 sketch lines shown below in blue for roof form 2.

    ![](media\image34.png)

    a.  Hit ESC key once to pause sketching continuously.

    b.  Unmark Defines slope check box.

    ![](media\image43.png)

  
    a.  Create 1 sketch line shown below in green for roof form 2 to create a closed boundary.

    ![](media\image34.png)

41. Set the roof pitch for the sloped linework.

    a.  Select the 3 sketch lines below.

    ![](media\image44.png)

    b.  In Properties palette, set pitch to **3" (0.0762m)**.

    ![](media\image39.png)

42. Click Finish Edit Mode to create the 3D roof element.

    ![](media\image40.png)

    *Note: If you receive error messages, confirm that none of the
    linework overlaps itself. Then try Finish Edit mode again.*

    a.  Attach highlighted walls to roof? Click Yes.

    ![](media\image41.png)

43. Roof progress shown below.

    ![](media\image45.png)

### Join the two hip roofs together

1.  Open the {3D} 3D View. Orbit the view to the following orientation
    shown below where we can see the gable end of the bedroom roof
    created in the previous step.

    ![](media\image46.png)


44. Select the bedroom roof, the one with the gable end facing you
    on-screen.

45. On the Modify \| Roofs tab, Geometry panel, click the Join / Unjoin
    Roof tool.

    ![](media\image47.png)

    a.  Select the top edge of the bedroom roof as indicated by Mark 1 below.

    ![](media\image48.png)

    b.  Then, pick the face of the main living room roof to project to as indicated by Mark 1 below.

    ![](media\image49.png)

46. Roof progress as shown below.

    ![](media\image50.png)

47. Cleanup the interior walls projecting through the bedroom roof.

    a.  Select the interior walls.

    b.  Click Attach / Top Base command.

    c.  Select bedroom roof.

48. Roof completed as shown below.

    ![](media\image51.png)

    This concludes Exercise 3. Save the Revit file as: Module02Ex03_Finished.rvt and hand in.
