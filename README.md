# OpenGL template for C++ project
 OpenGL project set up with compile and build tasks in VSCode, for almost automatic compilation of GLFW, GLEW and GLM (requires installation of VSCode, CMake, Make and Clang++). Currently only for MacOS.

## Instructions
- Install VSCode, CMake, Make and Clang++.
- Open VSCode and open the OpenGLTemplate folder as Workspace folder.
- Click Terminal -> Run Task -> BuildLibraries to build GLFW and GLEW (GLM does not need to be compiled).
- Click Terminal -> Run Build Task to build the project. The created application will be located in OpenGLTemplate/build/App.