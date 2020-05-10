# OS_Scheduling
My GitHub Repository for Operating System Assignment-Lovely Professional University(LPU,Phagwara,Punjab)
## Question 7:
Design a scheduling program to implements a Queue with two levels.<br>
Level 1 : Fixed priority preemptive Scheduling,<br>
Level 2 : Round Robin Scheduling<br>
For a Fixed priority preemptive Scheduling (Queue 1), the Priority 0 is highest priority. If one process P1 is scheduled and running , another process P2 with higher priority comes. The New process (high priority) process P2 preempts currently running process P1 and process P1 will go to second level queue. Time for which process will strictly execute must be considered in the multiples of 2.
All the processes in second level queue will complete their execution according to round robin scheduling.
### Consider:
1.Queue 2 will be processed after Queue 1 becomes empty. <br>
2.Priority of Queue 2 has lower priority than in Queue 1.<br>
### Notes:
Project.exe is compiled in mingw-w64(Compiler) win32(API) seh(Exception) ver 8.1.0.