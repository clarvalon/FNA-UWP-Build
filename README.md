# FNA-UWP-Build

![UWP Build (FNA3D)](https://github.com/clarvalon/FNA-UWP-Build/workflows/UWP%20Build%20(FNA3D)/badge.svg)

This repo is for automating the build of WinRT/UWP native libraries for [FNA](https://fna-xna.github.io/), including:

* [FNA3D.dll](https://github.com/FNA-XNA/FNA3D) - 3D graphics library for FNA.
* [FAudio.dll](https://github.com/FNA-XNA/FAudio) - XAudio reimplementation for FNA.
* [SDL2.dll](https://github.com/libsdl-org/SDL) - Simple DirectMedia Layer.
* [libtheorafile.dll](https://github.com/FNA-XNA/Theorafile) - Ogg Theora videos decoder library.

There is currently just one workflow:

1.  **UWP Build (FNA3D)**.  See [here](https://github.com/FNA-XNA/FNA/wiki/BETA:-FNA3D) for details.  For WinRT this uses Directx11 by default as the renderer.  This does *not* require ANGLE.

# Usage

Go to the Actions tab and download the .zip artifact from the latest workflow run.  See the FNA [Xbox instructions](https://github.com/FNA-XNA/FNA/wiki/Appendix-B:-FNA-on-Consoles#xbox-one) for additional details.
