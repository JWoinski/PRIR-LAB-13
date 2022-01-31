# PRIR-LAB-13

Przykładowe "Hello World" z użytą biblioteką OpenMP.
Przed kompilacją ustawiamy liczbę wątków na, której działamy komendą:
export OMP_NUM_THREADS=[liczba wątków] np.: export OMP_NUM_THREADS=7
Kompilacja:
g++ hello.cpp -o hello.exe -fopenmp
Biblioteke OpenMp deklarujemy poprzez #include <omp.h>
Tid czyli tzw. ThreadId otrzymujemy z funkcji omp_get_thread_num().
