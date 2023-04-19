# CISC372_hw4
image.c is original c file provided by class

image1.c use pthread 

image2.c use openmp


to compile image.c we use 

gcc your_file.c -o output

gcc image1.c -lpthread -o image_thread -lm  -- for pthread

gcc image2.c -fopenmp -o image_omp -lm  -- for openmp

if you choose compile openmp os Mac Os


please install llvm with libomp via brew 


if Clang occurs error like "unsupport -lthread" 

please consider following link as a hint:

/opt/homebrew/opt/llvm/bin/clang -fopenmp -L/opt/homebrew/opt/llvm/lib image1.c -o omp






