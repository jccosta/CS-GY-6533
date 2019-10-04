[![Build Status](https://travis-ci.org/danielepanozzo/cg.svg?branch=master)](https://travis-ci.org/danielepanozzo/cg)
[![Build status](https://ci.appveyor.com/api/projects/status/3b1dti4xig8i3c4a?svg=true)](https://ci.appveyor.com/project/danielepanozzo/cg)

# CS-GY 6533 A – Interactive Computer Graphics - Fall 2019

### Course Instructors
*Cláudio Silva (lead instructor)*

370 Jay Street, room 1153 

[csilva@nyu.edu](mailto:csilva@nyu.edu)

Office hours: Friday, 2-4pm, or by appointment.


*Jonathas Costa*

370 Jay Street, room 1140

[jccosta@nyu.edu](mailto:jccosta@nyu.edu)

Office hours: Friday, 2-4pm, or by appointment.

### Lectures:
Thrusdays at 3:20pm - 5:50pm
RH 215

## Course Description

This course provides an introduction to the field of Computer Graphics. We will cover the basic mathematical concepts, such as 2D and 3D transformations, study the interaction of light with geometry to derive  shading models, and implement rendering algorithms such as ray tracing and rasterization. We will investigate how these fundamental components are integrated in current graphics processors and study the corresponding programming APIs. This course will also include a brief introduction to C++.

Students will experiment with modern graphics programming and build small demos in C++ and OpenGL.

By the end of the course, the student must be able to:

* Explain and apply the fundamental mathematical concepts used in  image synthesis algorithms
* Implement a basic rendering system based on ray tracing
* Implement a basic rendering pipeline based on rasterization
* Develop simple graphics programs in C++ using OpenGL and GLSL

*Textbook*:
Fundamentals of Computer Graphics, 4th Edition
December 18, 2015 by A K Peters/CRC Press
Textbook - 734 Pages - 541 Color
ISBN 9781482229394

### Acknowledgement: 
This course is based on the computer graphics course designed by Professor Daniele Panozzo (NYU).

## Assignments

* [General Guidelines](Assignment_1/requirements/General_Rules.pdf) [(latex)](Assignment_1/requirements/General_Rules.tex)

* [Assignment 1: Ray Tracing](Assignment_1/requirements/Assignment-1_Ray_Tracing.pdf) [(latex)](Assignment_1/requirements/Assignment-1_Ray_Tracing.tex)

* [Assignment 2: 2D Vector Graphics Editor](Assignment_2/requirements/Assignment-2_2D_Editor.pdf) [(latex)](Assignment_2/requirements/Assignment-2_2D_Editor.tex)

* [Assignment 3: 3D Scene Editor]

* [Assignment 4: Final Project]

# Compilation Instructions

```bash
git clone --recursive https://github.com/jccosta/CS-GY-6533 # --recursive flag is necessary for dependencies
cd Assignment_N
mkdir build
cd build
cmake ../ # re-run cmake when you add/delete source files
make
```
You can substitute `cmake ../` with the following to make the program run faster
```bash
cmake -DCMAKE_BUILD_TYPE=Release ../ # use this cmake command instead of the previous linefor faster run
```

If you are looking for an IDE, I suggest to use [VSCode](https://code.visualstudio.com) or [CLion](https://www.jetbrains.com/clion/).
