Mixed-Signal Demo PCB
=====================

Demo board project for the "Mixed-Signal Hardware Design with KiCAD" course, by
Phil Salmony (of Phil's Lab fame) at [FEDEVEL](fedevel.com). 

The project was created from scratch using KiCAD 8.0, following the course lectures.
It comes with all the relevant files, including missing footprints and 3D models.
Several of the 3D models were downloaded, and are not to be used without permission:

- HRO_TYPE-C-31-M-12.step (USB receptacle, from GrabCad.com)
- 31-5640-1010.stp (BNC connectors, from Amphenol.com)
- L_Coilcraft_XxL4020.step (for the matching inductor, from 3DContentCentral.com)

The models for the CMF3216 common-mode choke, and the RGB LED (E6C...) were created
by myself in FreeCAD and are free to use, with appropriate acknowledgment.

The project includes Gerber files, and BOM/Placement files. All relevant parts include
an MNP field with JCLPCB/LCSC part numbers, and the assembly files were generated using
the "Fabrication Toolkit" plugin, which generates JLCPCB-compatible output.
