# DEBS2016V2

## Résultats de l'algorithme

### Light Test (3 Ko files)

mean execution time : 120 ms
mean time per event : 4 ms
events treated per second : 250

The weak number of events treated per second is due to the initialisation of the program and the poor number of events it has to handle.

### Medium test (120 Mo)

mean execution time : 33.3 s
mean time per event : 28.3 µs ms
events treated per second : 35 335

This test shows the algorithm at its peak performance as it neither has too many data nor not enough of it.

### Heavy test (4.5 Go)

mean execution time : 25 min 30 s
mean time per event : 35 µs
events treated per second : 28 571

This tests shows one of the weaknesses of our algorithm. Once too much data is processed, memory is satured and the garbage collector acts too much and slow the algorithm.
