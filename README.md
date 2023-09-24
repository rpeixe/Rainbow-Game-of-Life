# Rainbow-Game-of-Life

Trabalho para a disciplica Programação Concorrente e Distribuída (2023-2)

Consiste em uma implementação do Rainbow Game of Life utilizando multithreading, tanto com PThreads quanto com OpenMP. O objetivo é analisar o ganho de desempenho ao utilizar multiprocessamento.

Aluno:
- Rodrigo Peixe Oliveira

Comandos usados para compilar:

Serial:

`gcc -o rgl rgl.c`

PThread:

`gcc -o rgl-pthread rgl-pthread.c -pthread`

OpenMP:

`gcc -o rgl-openmp rgl-openmp.c -fopenmp`