# Min-CNC

Her vil jeg dele mit arbejdet med at designe og bygge en cnc maskine.

For 3D-Printe mine FreeCAD filer, bruger jeg:

* Ultimaker-Cura-5.0.0-linux.
  * Low Quality - 0.28mm
  * Infill: 20%
  * Support: Touching Buildplate
  * Build Plate Adhesion: Skirt
* [OctoPrint](https://octoprint.org/)
  * OctoPi running on Raspberry 4B
  * [Download & Setup OctoPrint](https://octoprint.org/download/)
* 3D-Printer: Creality CR-10 Mini
* Filement: 
  * Fra: Spectrum Group
  * Type: PLA:
  * Printing temp: 220°
  * Hot pad temp: 60°

Se hvordan mine tegninger udvikler sig her:

* Tegninger for 3D Print
  * [DragChain](./FreeCad-files/DragChain/README.md)
  * X_Axis
    * [X_Axis-Mount](./FreeCad-files/X_Axis/X_Axis-Mount/README.md)
    * [X_Axis-Sled](./FreeCad-files/X_Axis/X_Axis-Sled/README.md)
  * Y_Axis
  * Z_Axis

* Tegninger kun for brug med Assembly4
  * [AluProfile](./FreeCad-files/AluProfile/README.md)
  * [Kuglelejer](./FreeCad-files/BallBearing/README.md)
  * [Gevindstænger](./FreeCad-files/Gevinstang/README.md)
  * [Nema17_Motor](./FreeCad-files/Nema17/)
  * Skruer og møtrikker

Jeg har to Controller som jeg kan bruge i dette project
* GeeeTech 
  * ![](./Controller/Images/GT2560_layout.png)
  * [GT2560 Manual](https://www.geeetech.com/wiki/index.php/GT2560)
  * ![](./Controller/Images/700px-GT2560_wiring.jpg)
* BigTreeTech ![BTT_SKR_V1.4.png](./Controller/Images/BTT_SKR_V1.4.png)
  * [BTT SKR V1.4](https://github.com/bigtreetech/BIGTREETECH-SKR-V1.3/tree/master/BTT%20SKR%20V1.4)
