## ![](../../images/icons/Read_OpenFOAM_Case.png) Read OpenFOAM Case - [[source code]](https://github.com/Eddy3D-Dev/Eddy3D/tree/dev/Read%20OpenFOAM%20Case.cs)

![](../../images/components/Read_OpenFOAM_Case.png)

Reads an OpenFOAM case and outputs a Case instance with all its files.

#### Input
* ##### D 
Directory to OpenFOAM case.
* ##### I 
Names of additional files to include

#### Output
* ##### C
The read OpenFOAM case as a Case instance containing all found files as FileContainers.
* ##### B
Boudnary conditions found in the case.
* ##### I
Names of files in the directory that were not `added to the case