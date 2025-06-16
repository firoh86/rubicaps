# chocV2

## Description
ChocV2 are 1U keycaps based on Mike Holscher's custom caps for pg1316s, adapted to chocV2 with tight placement.  
These keycaps have a side length of 16.5mm and a spacing of 1mm between them.

## Contents
- `Resources/`: You can find the chocV2 datasheets I used to design these keycaps.

## Restrictions
- These keycaps have certain restrictions to consider when using them:
- The positioning of the footprints on the PCB have a spacing of 17mm between them, on both the x and y axes.
- The stem height is 3.337mm. They have been tested with V2 switches with a maximum travel of 2.8mm, for which they were designed. Switches with greater travel could cause the keycaps to get stuck to the switch and also touch the plate, limiting the switch's own travel and preventing bottom out.

## Design
The project design follows a modular structure with 1U keys. It consists of 3 variants: angled, standard, and homing.  
Standard refers to row 2 on a 3x10 keyboard, which is the row with a s d f...  
Homing is a Standard with a pronounced bump for touch typing reference.  
Angled refers to the other rows: row 1 uses normal angled, row 3 uses angled reversed to complete the arc, and the thumb row uses normal angled, which is equivalent to a reversed spacebar in MX.