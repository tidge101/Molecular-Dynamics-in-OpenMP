Dillon Tidgewell
tidge101@mail.chapman.edu
002285452
1/24/2018

This is a short technical paper I have written for the High Performance Computing interterm class at Chapman University. This paper describes the importance and use of the OpenMP API to implement multi-threading on a shared-memory architecture. I have included the .c files for the parallel and serial versions of the program I used to demonstrate OpenMP. The parallel version was created by John Burkhardt, and can be found on his website, which is linked within the paper. 

To compile: gcc -fopenmp md_omp.c -o md_omp
For Mac's, some extra flags may need to be included. On my Mac I have to specify gcc-7 and include the flag -std=c++11
