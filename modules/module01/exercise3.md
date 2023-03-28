---
layout: page
title: Modellering av byggnadselement - Övning 3
permalink: /modules/module01/exercise3
exclude: true
---

[Learn Revit](/learnrevit/) > [Modul 1](/learnrevit/modules/module01/) > Övning 3

## Skapa golv och tak


**I denna övningen skapar du platta tak och sadeltak till huset från föregående övning**

Mål:

- Skapa tak baserat på byggnadens fotavtryck.

- Rita en takgräns och välja de sluttningsdefinierande kanterna.

- Ställ in taknivån och lutningsinstansegenskaperna.

## Skapa ett platt tak

1.   **Ladda ner startfilen [här](Module01Ex03.rvt).**

28. Öppna **Workspace Roof plan view**.

    ![](media\image16.png)

3. **OBS! Var noga med att gå in i rätt planvy när du skissar taket.**


2.  Klicka på Architecture fliken, sedan Roof by Footprint.

    ![](media\image17.png)


29. Välj i Properties palette taktyp Basic Roof Generic - 12" och
    ändra egenskap Base Offset from Level = **0'-0" (0 mm)**.

    ![](media\image18.png)

30. I fliken Modify \| Create Roof Footprint,bekräfta att Boundary Line and
    Line mode är valda.

    ![](media\image19.png)

    a.  Avmarkera Defines slope kryssruta.

    ![](media\image20.png)

31. Skapa en stängd gräns som anges av de fyra numrerade skisslinjerna nedan.Skisslinjerna ska placeras på insidan av väggar.

    ![](media\image21.png)
    a.  Klick Modify kommando för att avsluta skissning.

        *OBS: Linjen måste vara sammanhängande.*

32. Klick Finish Edit Mode för att skapa 3D-takelementet.

    ![](media\image22.png)

    *Obs! Om du får felmeddelanden, bekräfta att ingen av linjerna överlappar sig själv.Försök sedan igen med Finish Edit mode.*

33. Öppna **Carport Roof plan view**.

34. Skapa det andra platta taket med samma metod som i steg 4-8.

    ![](media\image23.png)

35. Klick  Modify för att avsluta skapande av tak.

36. Välj väggen som visas nedan.

    a. Klick Attach Top / Base.

    ![](media\image24.png)

    b.  Klicka på kanten på det platta taket som precis skapats.

    ![](media\image25.png)

## Skapa ett tak med lutningar

1.  Öppna **Living Area Roof plan view**.


3.  På Architecture fliken klicka Roof by Footprint.

    ![](media\image17.png)


37. I Properties palette, välj Basic Roof Generic - 12" taktyp och
    ändra egenskap Base Offset from Level = **0'-0" (0 mm)**.

    ![](media\image26.png)

38. I Modify \| Create Roof Footprint, bekräfta att Boundary Line och
    Line mode är valda.

    ![](media\image19.png)

    a.  Markera Defines slope kryssruta.

    ![](media\image27.png)

39. Skapa en stängd gräns som anges av (10) skisslinjer
    numrerad nedan. Fotavtrycket ska se ut som det röda konturen i vyn.

    ![](media\image28.png)

    a.  Klick Modify command för att avsluta skissning.

        Note: Linework must be contiguous.

40. Ställ in takhöjden för det sluttande linjen.

    a.  Använd en selection window för att välja alla skisslinjerna i takskissen.

    ![](media\image29.png)

    b.  I Properties palette, ändra Slope (stigning) till **3" (76,2 mm)**.

    ![](media\image30.png)


41. Klick Finish Edit Mode för att skapa 3D-takelementet.

    ![](media\image22.png)

    Obs! Om du får ett felmeddelande, bekräfta att ingen av linjerna överlappar sig själv.Försök sedan med Finish Edit Mode igen.*

42. Attach highlighted walls to roof? Klick Yes.

    ![](media\image31.png)

1.  Den färdiga takövningen ser ut som i bilden.

    ![](media\image32.png)

2.  Spara Revit filen som: Module01Ex03_Finished.rvt och lämna in.

   Nu är du klar med övning 3.
