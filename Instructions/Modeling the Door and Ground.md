# Modeling the Door and Ground
## Door Frame
- Add mesh cube
- Scale X 0.1 Y 1.5 Z 0.4
- Move X 0.3 Y -0.9 Z 0.2
- Move Origin to World Center
- Edit Mode
- Loop cut horizontal.  Place in middle.
- Bevel new loop cut edges. Width 0.04 Segments 2
- Select Middle loop
- Scale X 0.65 Y 0.65
- Shear Y 0.33
- Extrude Z 0.02
- Extrude Z 0.02
- Scale middle loop 0.7
- Continue door frame around
- Apply Mirror
- Modify verticies and faces to make unique
## Door
- Add new plane for door
- Rotate and scale
- Cut edge to match door frame
- Inset to doorframe
## Ground
- Insert circle for base
- Extrude and scale in for grassy base
- Extrude and scale out for dirt border
- Move down for bevel
- Extrude and move down for ground thickness