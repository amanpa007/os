# os
C Program for implementing Scheduling Algorithm

This repository contains programs used to implement following  two problems: 
1st problem (Ques 8):-
Sudesh Sharma is a Linux expert who wants to have an online system where he can handle student queries. Since there can be multiple requests at any time he wishes to dedicate a fixed amount of time to every request so that everyone gets a fair share of his time. He will log into the system from 10am to 12am only. He wants to have separate requests queues for students and faculty, where faculty queue is given a higher priority. Implement a strategy for the same. The summary at the end of the session should include the total time he spent on handling queries and average query time.
Solution Proposed for the above problem : 
The given problem is based upon solving queries of Faculties and Students. Thus, these queries can be compared to different processes in terms of operating system where each process has its own demands and time for its execution. And these demands of processes are handled by the CPU. In the given situation, Mr. Sudesh Sharma, Linux expert, is considered as a CPU, who solves the queries of either Faculty or Student by allocating proper resources to their individual demands and processing them by allocating them time accordingly. Now, Mr. Sharma, wants to provide priority for each query based upon its class, as well as, he wants to dedicate a fixed amount of time to every request. Thus in Operating System, if we divide the requests into two separate queues i.e. Faculty and Student such that the first queue contains faculty queries has higher priority and the second contains student queries which has lower priority, then we can resolve the problem, by allocating them required resources based upon their priorities as done in the scheduling algorithm in operating systems.
The above problem is solved by RobinRound algorithm. 

2nd problem(Ques 18):-
