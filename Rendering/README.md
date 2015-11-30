# RENDERING with Vtk library

Rendering code for Linemod database
Linemod_DB: http://campar.in.tum.de/Main/StefanHinterstoisser

## Building
		Libraries
		=========
		This project has been tested with VTK-6.2.0 library 
		
		Build
		=====
		Clone the project and create the build directory	
		Move into build directory
		
		-Linux
		======
			cmake ..
			make

## Running
		You must specify the appropriate folder, where item-data exists.
		Example:  ./Rendering ../driller/ 3
