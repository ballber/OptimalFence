
Compile : gcc -fopenmp optimalfence-omp.c -o optfence_parallel -lm
Execute :  ./optfence_parallel 15arboles.txt

Part I – OpenMP implementation
Taking as a base the serial version provided, write an OpenMP implementation
to the optimal fence problem using the same input/output definitions than the
serial. Name this source code optimalfence-omp.c.
The aim of this part is to be familiar with the different clauses provided by
OpenMP to exploit fully the API to get the maximum performance. Be
particularly careful with synchronization and load balancing.

