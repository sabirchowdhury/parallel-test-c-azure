# parallel-c-azure

This repository is a practice task of using the "p_threads" (task 1) and "Message Passing Interface (MPI)" library (task 2) in C programming to execute code in parallel. In both task the goal is to take a N by N matrix and perform relaxation i.e., recursively perform a neighbouring average on all (non-border) cells until the difference between the cell value and the previous cell value is less than a specified tolerance value.

The C files were uploaded and executed on 4 supercomputers using a distributed memory architecture. (task 1 is intended only for use on shared memory architectures).
