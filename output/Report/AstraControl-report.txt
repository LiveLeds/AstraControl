# PCB

Board size: 102.0x96.0 mm (4.02x3.78 inches)

- This is the size of the rectangle that contains the board
- Thickness: 1.61 mm (63 mils)
- Material: FR4
- Finish: ENIG
- Layers: 4
- Copper thickness: 35 / 15 µm

Solder mask: TOP / BOTTOM

- Color: Top: #0000004d / Bottom: Black

Silk screen: TOP / BOTTOM

- Color: Top: White / Bottom: #0000004d


Stackup:

Impedance controlled: YES

| Name                 | Type                 | Color            | Thickness | Material        | Epsilon_r | Loss tangent |
|----------------------|----------------------|------------------|-----------|-----------------|-----------|--------------|
| F.SilkS              | Top Silk Screen      | White            |           |                 |           |              |
| F.Paste              | Top Solder Paste     |                  |           |                 |           |              |
| F.Mask               | Top Solder Mask      | #0000004D        |        10 |                 |           |              |
| F.Cu                 | copper               |                  |        35 |                 |           |              |
| dielectric 1         | prepreg              |                  |       210 | FR4             |       4.4 |        0.020 |
| In1.Cu               | copper               |                  |        15 |                 |           |              |
| dielectric 2         | core                 |                  |      1065 | FR4             |       4.6 |        0.020 |
| In2.Cu               | copper               |                  |        15 |                 |           |              |
| dielectric 3         | prepreg              |                  |       210 | FR4             |       4.4 |        0.020 |
| B.Cu                 | copper               |                  |        35 |                 |           |              |
| B.Mask               | Bottom Solder Mask   |                  |        10 |                 |           |              |
| B.Paste              | Bottom Solder Paste  |                  |           |                 |           |              |
| B.SilkS              | Bottom Silk Screen   | #0000004D        |           |                 |           |              |

# Important sizes

Clearance: 0.2 mm (8 mils)

Track width: 0.19 mm (8 mils)

- By design rules: 0.15 mm (6 mils)

Drill: 0.5 mm (20 mils)

- Vias: 0.5 mm (20 mils) [Design: 0.4 mm (16 mils)]
- Pads: 0.5 mm (20 mils)
- The above values are real drill sizes, they add 0.1 mm (4 mils) to plated holes (PTH)

Via: 0.8/0.4 mm (31/16 mils)

- By design rules: 0.3/0.3 mm (12/12 mils)
- Micro via: yes [0.2/0.1 mm (8/4 mils)]
- Buried/blind via: yes
- Total: 318 (thru: 318 buried/blind: 0 micro: 0)

Outer Annular Ring: 0.09 mm (4 mils)

- By design rules: 0.09 mm (4 mils)

Eurocircuits class: 10B
- Using min drill 0.5 mm for an OAR of 0.09 mm


# General stats

Components count: (SMD/THT)

- Top: 89/63 (SMD + THT)
- Bottom: 0/0 (NONE)

Defined tracks:

- 0.3 mm (12 mils)
- 0.35 mm (14 mils)
- 0.5 mm (20 mils)
- 1.0 mm (39 mils)

Used tracks:

- 0.19 mm (8 mils) (27) defined: no
- 0.28 mm (11 mils) (40) defined: no
- 0.3 mm (12 mils) (18) defined: yes
- 0.35 mm (14 mils) (394) defined: yes
- 0.5 mm (20 mils) (78) defined: yes
- 1.0 mm (39 mils) (58) defined: yes

Defined vias:

- 0.55/0.25 mm (22/10 mils)
- 0.7/0.3 mm (28/12 mils)
- 0.8/0.4 mm (31/16 mils)

Used vias:

- 0.8/0.4 mm (31/16 mils) (Count: 318, Aspect: 2.0 A) defined: yes

Holes (excluding vias):

- 0.4 mm (16 mils) (73)
- 0.6 mm (24 mils) (2)
- 0.73 mm (29 mils) (26)
- 0.9 mm (35 mils) (51)
- 1.7 mm (67 mils) (20)
- 5.8 mm (228 mils) (4)

Oval holes:

- 0.62x1.4 mm (24x55 mils) (2)
- 0.62x1.7 mm (24x67 mils) (2)

Drill tools (including vias and computing adjusts and rounding):

- 0.5 mm (20 mils) (391)
- 0.6 mm (24 mils) (2)
- 0.7 mm (28 mils) (4)
- 0.85 mm (33 mils) (26)
- 1.0 mm (39 mils) (51)
- 1.8 mm (71 mils) (20)
- 5.9 mm (232 mils) (4)




# PCB Layers

![Prints the PCB using a mechanism that is more flexible than `pdf_pcb_print` and `svg_pcb_print`.](../PCBPrint/AstraControl-assembly.pdf){ width=16.5cm height=11.7cm }

