# FNA-UWP-Build

![UWP Build](https://github.com/clarvalon/FNA-UWP-Build/workflows/UWP%20Build/badge.svg)
![UWP Build (FNA3D)](https://github.com/clarvalon/FNA-UWP-Build/workflows/UWP%20Build%20(FNA3D)/badge.svg)

This repo is for automating the build of WinRT/UWP libraries for [FNA](https://fna-xna.github.io/).

There are two workflows:

1.  **UWP Build**.  This is for the current version of FNA which will soon be obsolete.  It includes MojoShader (which has issues) and SDL_Image which will soon be removed.

2.  **UWP Build (FNA3D)**.  This is for the beta version of FNA3D which will eventually replace the original version.  See [here](https://github.com/FNA-XNA/FNA/wiki/BETA:-FNA3D) for details.  For WinRT this uses Directx11 by default as the renderer.

Notes:

* Angle DLLs (_libEGL.dll_, _libGLESv2.dll_) are needed for workflow 1 and can be obtained seperately [here](https://github.com/cybik/angle-bootstraps/actions?query=workflow%3A%22Matrixed+UWP+Build%22).
