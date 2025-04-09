# The-Utah-teapot
The famous Utah teapot in Opengl and python
To run OpenGL code with the Utah Teapot in MinGW-w64, you'll need to set up the necessary libraries and compile your program correctly. Here’s a step-by-step guide:

1. Install Required Libraries
You need:

GLFW (for window/context creation)

GLEW (for OpenGL extensions)

GLM (for math operations)

FreeGLUT (optional, if using glutWireTeapot)

Install via MSYS2 (Recommended)
Open MSYS2 MinGW 64-bit terminal and run:

bash

pacman -S mingw-w64-x86_64-glfw mingw-w64-x86_64-glew mingw-w64-x86_64-glm mingw-w64-x86_64-freeglut
