---
layout: page
title: Building Envelope - Exercise 1
permalink: /modules/module02/exercise1
exclude: true
---

[Learn Revit](/learnrevit/) > [Modul 2](/learnrevit/modules/module02/) > Övning 1

## Modellera väggtyper, strukturer och Design Features

###  Ändra ytterväggstyper genom substitution på plats

1.  **Ladda ner startfilen [här](Module02Ex01.rvt).**

3.  Öppna Ground Floor plan view.

4.  Följ nu dessa steg för att välja alla ytterväggar av typ Generic -- 8" (200mm).

    a.  Håll muspekaren över en yttervägg.

    ![Image 2](media\image2.png)

    b.  Högerklicka i canvas window och välj Select All
        > Instances\>Visible in View.

    ![Image 3](media\image3.png)

    c.  Välj väggtyp Exterior -- Brick wall.

    ![Image 4](media\image4.png)

5.  Öppna {3D} 3D View. Alla ytterväggar bör nu vara av tegel.

    ![Image 5 ](media\image5.png)

### Skapa en ny inre väggtyp

1.  Öppna Ground Floor plan view.

2.  Klicka på Wall under Architecture fliken.

    ![](media\image6.png)

3.  I Properties Palette välj väggtyp Generic 8\" (200mm).

    a.  Välj Edit Type.

    ![Image 7](media\image7.png)

    b.  Klicka på Duplicate.

    ![Image 8](media\image8.png)

    c.  Bytt namn till: Wood Panel Wall.

    ![Image 9](media\image9.png)

    d.  Klicka på OK.

4.  Du kommer nu att ändra på materialen och strukuren av denna väggtyp:

    a.  Klicka på Edit Structure.

    ![Image 10](media\image10.png)

    b.  Ändra Structure \[1\] to:

        Material = Wood -- Stud Layer

        Thickness = **41mm**

    ![Image 11](media\image11.png)

        *Tips: Använd sökfönstret i Material Browser och skriv namnet på 
        materialet du söker efter.*

> Structure \[1\] används till s.k. structural materials d.v.s. de som är viktiga för väggens hållfasthet. 

c.  Klicka på Insert två gånger för att lägga till två nya skikt i väggentypen.

![Image 12](media\image12.png)

![Image 13](media\image13.png)

1.  Ändra på Layer 2 så här:

    a.  Välj raden Layer 2

    b.  Klicka på Up

    c.  Klicka på Function = Finish 1 \[4\]

> Tips: Function determines a material layers behavior in the model
> environment for cleanup at wall intersections with other wall types.
> Material functions of the same kind will cleanup.
>
> Finish 1 \[4\] används till yttrematerial och har en lägre prioritet än structural materials.

d.  Ändra Material =

    Wood - Horizontal Panel

![Image 14](media\image14.png)

>   *Tips: Använd sökfönstret i Material Browser och skriv namnet på 
        materialet du söker efter.*

e.  Ändra Thickness = **12mm**

![Image 15](media\image15.png)


7.  Redigera i Layer 3 så här:

    a.  Välj rad Layer 3

    b.  Klick två gånger på Down.

    c.  Klick Function = Finish 2 \[5\]

> Tips: Finish 2 \[5\] används till inrematerial och har en lägre prioritet än structural materials.

d.  Ändra Material =

    Wood - Horizontal Panel

e.  Change Thickness = **12mm**

![Image 16](media\image16.png)


1.  Klicka på OK två gånger för att stänga båda dialog fönster.

2.  Klicka på Modify för att avsluta placeringen av väggen.

### Ändra inreväggtyper genom substitution på plats

1.  Du ska nu välja alla innerväggar av typ

    Interior - 3 1/8\" Partition (1-hr) (790mm).

    a.  Håll muspekaren över en innervägg..

     ![Image17](media\image17.png)

    b.  Högerklicka i canvas fönstret och välj Select All
        > Instances\>Visible in View.

    c.  Välj väggtyp Wood Panel Wall.


10. Gå in på Ground Floor plan view.

11. Välj de ytterväggar som syns i bilden. Dessa kommer ändras till väggtyp Wood Panel Wall.

    ![Image18](media\image18.png)

12. I Properties palette, ändra väggtyp till Wood Panel Wall.

13. Öppna {3D} 3D View. Kontrollera att alla innerväggar och utvalda ytterväggar har en träskikt (wood paneling).

    ![Image19](media\image19.png)

14. Spara Revit filen som: Module02Ex01_Finished.rvt och lämna in.

    Du är nu klar med Övning 1.

