# CS3210Assignment

To get original file:
wget www.comp.nus.edu.sg/~sooyj/cs3210/As1/mm-cuda.cu

To compile:
nvcc –arch=sm_32 mm-cuda.cu –o mm-cuda –lcuda -lcudart

To run:
./mm-cuda 512
