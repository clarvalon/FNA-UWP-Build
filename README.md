# FNA-UWP-Build

Repo for automating the build of WinRT/UWP libraries for [FNA](https://fna-xna.github.io/).

Note:

* MojoShader currently compiles ok but fails at runtime.  Not sure why.  The other DLLs seem fine.
* This will need to be reworked once FNA3D goes live (which will eliminate MojoShader anyway, along with SDL_image).
* Angle DLLs (libEGL.dll, libGLESv2.dll) are also needed and can be obtained seperately [here](https://github.com/cybik/angle-bootstraps/actions?query=workflow%3A%22Matrixed+UWP+Build%22).
