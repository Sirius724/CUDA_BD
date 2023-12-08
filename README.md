# Brownian-Dynamics with CUDA

This code is written by CUDA and C++.
Your environment is in linux. to compile, type "./measure_compile.sh".

In this code, I measured center of mass displacement(COM displacement), mean square displacement and self-intermediate scattering function.
In MSD $<\Delta r(t)^2>$ and self-intermediate scattering function $F_s(q,t)$, we must consider COM displacement. so, I did that.

## Compile for this code

In linux, just put "./mearsure_compile.sh". If there is a problem or error message, check the nvcc driver and header file directories.

## With MPI

Must check the directory of MPI header file. and change it in compile file.
