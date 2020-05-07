# FNA-UWP-Build

![UWP Build](https://github.com/clarvalon/FNA-UWP-Build/workflows/UWP%20Build/badge.svg)
![UWP Build (FNA3D)](https://github.com/clarvalon/FNA-UWP-Build/workflows/UWP%20Build%20(FNA3D)/badge.svg)
![UWP Build (FNA3D directx11)](https://github.com/clarvalon/FNA-UWP-Build/workflows/UWP%20Build%20(FNA3D%20directx11)/badge.svg)

This repo is for automating the build of WinRT/UWP libraries for [FNA](https://fna-xna.github.io/).

There are three workflows:

1.  **UWP Build**.  This is for the current version of FNA which will soon be obsolete.  It includes MojoShader (which has issues) and SDL_Image which will soon be removed.

2.  **UWP Build (FNA3D)**.  This is for the beta version of FNA3D which will eventually replace the original version.  See [here](https://github.com/FNA-XNA/FNA/wiki/BETA:-FNA3D) for details. 

3.  **UWP Build (FNA3D directx11)**.  This is for the directx11 branch of FNA3D, which will eventually be merged into master (and thus become obsolete). 

Notes:

* Angle DLLs (libEGL.dll, libGLESv2.dll) may also needed and can be obtained seperately [here](https://github.com/cybik/angle-bootstraps/actions?query=workflow%3A%22Matrixed+UWP+Build%22).
