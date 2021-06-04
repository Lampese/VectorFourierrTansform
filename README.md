# VectorFourierrTansformer [![](https://img.shields.io/badge/License-GPL-green)](https://github.com/Blukdev/BECBCT/blob/main/LICENSE) ![](https://img.shields.io/badge/OS-Windows/Linux-blue) ![](https://img.shields.io/badge/Author-Lampese-success) ![](https://img.shields.io/badge/Collaborator-KCN-success)
Convert svg to "set.txt" (for BECBCT)

This is a branch of the BECBCT project and the most important part.

## How To Use
### Ready To Work
You need to place a file named "rawvertexes.txt" in which the path of the svg is stored. (The path requirement of svg is exported by Adobe Illustrator)
### Use directly
If you want to use VFTER on the x86 Windows/Linux platform, you can [download it here](https://github.com/Blukdev/VectorFourierrTansformer/releases/tag/v0.1) and use it directly.
### On Linux
```console
#Please make sure to install g++ and python3
g++ VFT.cpp -o Main
g++ Process.cpp -o Process
Python FourierMath.py
./Process
./Main
```
### On Windows
```powershell
#Please make sure to install g++ and python3
g++ VFT.cpp -o Main.exe
g++ Process.cpp -o Process.exe
Python FourierMath.py
./Porcess.exe
./Main.exe
```
