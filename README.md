EX-No.4 – 3D Modelling and Orthographic Projection of Shaft Support Bracket

AIM

To design the 3D solid model of the Shaft Support Bracket in Autodesk Fusion and convert it into orthographic views.

REQUIREMENTS

1. Autodesk Fusion 360
2. Windows 10 / Windows 11 (64-bit)
3. 4 GB of RAM (6 GB or more recommended)
4. 2.5 Mbps or faster download; 500 Kbps or faster upload

COMMANDS USED

1. Create Sketch:

Creates the 142 mm × 92 mm baseplate profile, concentric Ø55 mm / Ø30 mm bearing hub circles at 58 mm center height, and tapered rib outlines.

2. Extrude:

Extrudes the baseplate to 14 mm thickness, the central support web, and the 45 mm long cylindrical bearing hub symmetrically about the XZ midplane.

3. Fillet:

Applies R10 mm corner fillets to all four vertical corners of the baseplate.

4. Hole & Rectangular Pattern:

Cuts the four Ø18 mm through-holes on the baseplate positioned 21 mm from the edges at 100 mm × 50 mm spacing.

5. Rib & Mirror:

Creates the 15 mm thick side and front/rear stiffening ribs supporting the Ø55 mm cylindrical hub.

6. Drawing from Design:

Generates aligned Front, Top, Side, and Isometric views in the Autodesk Fusion Drawing workspace with ISO dimensions and title block.

PROCEDURE

STEP 1: Identifying the Given Model

Review the Shaft Support Bracket dimensions (baseplate 142 mm × 92 mm × 14 mm, hub Ø55 mm outer / Ø30 mm bore × 45 mm length, center height 58 mm) and set Autodesk Fusion units to millimeters (mm).

STEP 2: Creating the Filleted Baseplate

On the XY plane, sketch a center rectangle measuring 142 mm × 92 mm, Extrude upward by 14 mm, and apply Modify > Fillet (R10 mm) to all four vertical corners.

STEP 3: Drilling the Four Mounting Holes

Sketch a Ø18 mm circle located 21 mm from the outer edges (X = ±50 mm, Y = ±25 mm), apply Rectangular Pattern (2 × 2 at 100 mm × 50 mm spacing), and Extrude Cut (All) through the baseplate.

STEP 4: Modelling the Cylindrical Hub and Support Column

On the XZ plane, sketch concentric circles of Ø55 mm and Ø30 mm centered at Z = 58 mm from the base bottom, and Extrude symmetrically to 45 mm. Sketch the central support column (41 mm wide) connecting the baseplate to the hub underside and Extrude symmetrically to 45 mm (Join).

STEP 5: Adding the 15 mm Stiffening Ribs

On the XZ midplane, sketch the tapered side ribs connecting the baseplate to the Ø55 mm cylinder and Extrude symmetrically by 15 mm. On the YZ midplane, sketch the front and rear ribs (22 mm shoulder height) and Extrude symmetrically by 15 mm (Join).

STEP 6: Converting to Orthographic Views

Save the file and select Design > Drawing > From Design (ISO, A3, mm). Place the Base View (Front), project the Top, Side, and Isometric views, insert center marks and full dimensions, and fill the Title Block.

INPUT
<img width="772" height="590" alt="image" src="https://github.com/user-attachments/assets/abcb9aee-7927-4ecc-a371-6811a075d183" />

"Shaft Support Input Sketch" (shaft-support-input-sketch.png)

3D MODEL VIEW
<img width="1487" height="920" alt="image" src="https://github.com/user-attachments/assets/491a148d-b503-40f6-8075-4358131aa76b" />

"Shaft Support 3D Model" (shaft-support-3d-model.png)

OUTPUT
<img width="1286" height="912" alt="image" src="https://github.com/user-attachments/assets/d77882bf-f0f7-4d95-8b3f-598f3370c4b3" />

"Shaft Support Orthographic Drawing" (shaft-support-orthographic-drawing.png)

RESULT

Thus, the 3D solid model of the Shaft Support Bracket has been designed in Autodesk Fusion and converted into orthographic views.

CREATED BY: BUTHATI BALASUBRAHMANYAM
