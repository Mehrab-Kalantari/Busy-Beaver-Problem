# Busy-Beaver-Problem
![bb](https://catonmat.net/wp-content/uploads/2009/10/busy-beaver-turing-machine.jpg)
---
The busy beaver problem is a fun theoretical computer science problem. Intuitively, the problem is to find the smallest program that outputs as many data as possible and eventually halts. More formally it goes like this – given an n-state Turing Machine with a two symbol alphabet {0, 1}, what is the maximum number of 1's that the machine can print on an initially blank tape (filled with 0's) before halting?
####
Let's denote B(n) to be the number of 1s that the busy beaver managed to put on the tape. This function B(n) is called the busy beaver function and it is the solution to the busy beaver problem.
It grows like this:
* B(1) = 1
* B(2) = 4
* B(3) = 6
* B(4) = 13
* B(5) = 4098 (the exact result has not yet been found)
* B(6) = 4.6 · 101439 (the exact result shall never be known)
