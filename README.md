# Dynamic-priority-process-scheduling-algorithm
Dynamic priority process scheduling algorithm
（1）	The process of using dynamic priority scheduling algorithm to schedule five processes is realized by programming in C, C++, and Java languages. The data is as follows:
The arrival time and service time of the five processes are shown in the following table, ignore I/O and other overhead time, use dynamic priority algorithm for scheduling, the initial value of priority is 100, please output the completion time, turnaround time, and weighted turnaround time of each process. 

Each process control block PCB used to identify a process can be described in a structure, including the following fields (unused fields can be left undefined).
 Process ID number.
 PROCESS PRIORITY AND STIPULATE THAT THE PROCESS WITH GREATER PRIORITY, THE HIGHER ITS PRIORITY.
 The process has consumed CPU time, CPUTIME.
 The amount of CPU time that the process also needs to occupy is ALLTIME. When the process finishes running, ALLTIME becomes 0.
 Process status STATE.
 QUEUE POINTER NEXT, USED TO QUEUE PCS.
(3) The principle of priority change:
 The process stays in the ready queue for one time slice, and the priority is increased by 1.
 For each time slice of the process runs, the priority is minus 3.
(4) In order to clearly observe the scheduling process of each process, the program should display the situation of the processes in each time slice, including the running processes, the processes in the ready queue.
