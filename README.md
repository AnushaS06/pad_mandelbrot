# pad_mandelbrot
Mandelbrot with OpenGL and Pthread

Done with TDM-GCC in Windows environment (it was not tested in linux, it might work)

You can download freeglut [here](http://www.transmissionzero.co.uk/computing/using-glut-with-mingw/). Just add the headers and libs to gcc folder and insert the DLL into the folder's project.

Compiling:

g++ -c -o mandelbrot.o mandelbrot.cpp
g++ -o mandelbrot.exe mandelbrot.o -lfreeglut -lopengl32


