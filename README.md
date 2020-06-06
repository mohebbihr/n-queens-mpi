# n-queens-mpi
Backtracking algorithms are used to methodically and exhaustively search a solution space for an optimal solution to a given problem. A classic example of a backtracking algorithm is illustrated by finding all solutions to the problem of placing N-queens on an N × N chess board such that no two queens attack each other.  This repository contains source code of my B.Sc. final project which I used MPI to implement the n-qeens problem more efficiently. 

In this project, I used a task parallelism approach to at consider the task of finding a place for a queen for each MPI thread. I benched marked my solution and compare it with serial version and showed its effectiveness by 14% improvement on speedup. We solved the 24-queens problem using a 34 threads in 22 days.  


