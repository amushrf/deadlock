CS641: Advance Operating Systems
Deadlock Avoidance

Name: Ahmed Almusharraf:2401615, Osama Aljuhani:2301317, Fahd Farooq:2403854.


     
     
Project Goal: To design and implement a program that simulates the job scheduling and CPU
scheduling of an operating system with Deadlock avoidance by Bankers Algorithm.

Algorithms
A) Job Scheduling: 
1. Hold Queue 1: Shortest Job First (SJF)
The shortest length job is served first.

2. Hold Queue 2: First in First Out (FIFO)
The job that arrives first is served first.

B) Process Scheduling:
1. Round Robin (FIFO).
It is like the FIFO but with added preemption. Each job is served for the time interval and then preempted to serve another job.

C) Deadlock avoidance: Bankers Algorithm.


# Compilation
1.Open the terminal in the deadlock Folder
2.type "make"
3.type "./deadlock inputs.txt"

