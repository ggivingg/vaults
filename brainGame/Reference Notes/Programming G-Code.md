.stl is the 3D object in a file. To print in a printer it goes to a slicer program.
The slicer program end result is the G-code file which is the assembly language that the printer uses to print the object originally in the .stl file.


G code lets you fix problems and customize prints. 

G code is a CNC (computer numerical control) language 

![[gCodeStructure.png]]
![[gCodeStructure02.png]]
* G90 - absolute positioning
	*  G0 x50 y50 -> G0 x100 y 100 = position now x100 y 100
* G91 - relative positioning (to last position ) 
	* G0 x50 y50 -> G0 x100 y 100 = position now x150 y 150
	* usually used

###  Reference

[video](https://youtu.be/2TByiMNduss?si=mpJDAZN4CnKCEp8l)
[PrusaSlicer - G code generator for 3D printers](https://github.com/prusa3d/PrusaSlicer)
[CuraSlicer - G code generator for 3D printers](https://github.com/Ultimaker/Cura)


  