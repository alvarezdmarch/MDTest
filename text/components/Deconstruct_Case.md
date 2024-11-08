## ![](../../images/icons/Deconstruct_Case.png) Deconstruct Case - [[source code]](https://github.com/Eddy3D-Dev/Eddy3D/tree/dev/Deconstruct%20Case.cs)

![](../../images/components/Deconstruct_Case.png)

Deconstructs a Case instance, exposing all types of file containers.

#### Inputs
* ##### C []
Case to deconstruct.

#### Outputs
* ##### N
Case name.
* ##### AR
Air region in the case
* ##### VR
Vegetation regions in the case
* ##### SR
Solid regions in the case
* ##### I
OpenFOAM initial condition dictionaries found in the directory, stored in file containers.
* ##### D
OpenFOAM dictionaries found in the directory, stored in file containers.
* ##### L
OpenFOAM lists found in the directory, stored in file containers.
* ##### S
Scripts found in the directory, stored in file containers.
* ##### M
Meshes found in the directory, stored in mesh containers.
* ##### T
Files that do not meet other categories.
* ##### P
Name of the patches found in the case initial conditions.