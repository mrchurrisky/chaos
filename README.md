# James Gleick's CHAOS: The Software

This is a free release of of a product that was called  "James Gleick's CHAOS: The Software." The software was written by Josh Gordon, Rudy Rucker and John Walker for Autodesk, Inc. Rucker wrote most of the algorithm, except for the Fractal Landscapes algorithms, which are by John Walker.  Gordon did the interface, and much of the implementation of the algorithm code.

The software was originally released by Autodesk, Inc., in 1990, and was placed in copyright to Autodesk at that time.  When the product went out of print in about 1992, Autodesk transferred intellectual property rights for the product to James Gleick.  Gleick agrees that the software can be freely released under a Gnu license.

# Release 1.1

The executable and parameter files. It is possible to run the Chaos program on any virutally any platgorm inside a DOS shell called DOSBox. Details on the release page.

<a url="https://github.com/rudyrucker/chaos/releases/tag/v1.1-chaos">Release 1.1 page</a>

# Source Code

The code is DOS and assembly code.  A makefile is in each directory. The builds were compiled and assembled using Turbo C and Tasm.

The code is in six directories, one for the start Menu, and one for each of the five component Chaos programs.

Start_Menu has the code for the start menu screen which is launched by the chaos.bat file.

Strange_Attractors is the directory with the "Strange At
tractors" module, including the Lorenz attractor, the Logistic map, and others.

Pendulum_Magnets is the "Magnets and Pendulum" which emulates a chaotic physical motion.

Mandelbrot_Julia_Rudy is for the "Mandelbrot Sets" module which also include Julia sets, cubic Mandelbrot sets, and the Rudy set.

Fractal_Landscapes is the director with the "Fractal Forgeries" module that uses fractals to create images resembling landscapes. John Walker wrote all of this code.

Barnsley_Fractals is the "Chaos Game" module that shows fractals in the style invented by Michael Barnsley.

Cellular_Automata is for the "Toy Universe" module which shows cellular automata.

The code is written to work with a DOS GUI called Metashel, which was an early 1980s TSR or "terminate and stay resident" program by MetaGraphics Software Corporation, then in Scotts Valley, CA. Thus metashel.exe is run in DOS before before the chaos program code. A copy of metashel.exe is distributed with the Chaos 1998 release download.
