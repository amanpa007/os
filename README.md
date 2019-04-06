# os
C Program for implementing Scheduling Algorithm

This repository contains programs used to implement following  two problems: 

Problem 1 :(Ques 18):-
Ten students (a,b,c,d,e,f,g,h,i,j) are going to attend an event. There are lots of gift shops, they all are going to the gift shops and randomly picking the gifts. After picking the gifts they are randomly arriving in the billing counter. The accountant gives the preference to that student who has maximum number of gifts. Create a C program to define order of billed students. 

Solution Proposed for the above problem :
The above problem is based upon the priority of students who have more gifts .If the student has more gifts than he will get the bill first .If two students have same number of gifts then the student who camed first will get billed first .here the students are considered as the processes .The process having maximum brust time will be implemented first.

Problem 2 :(Ques 8):-
Sudesh Sharma is a Linux expert who wants to have an online system where he can handle student queries. Since there can be multiple requests at any time he wishes to dedicate a fixed amount of time to every request so that everyone gets a fair share of his time. He will log into the system from 10am to 12am only. He wants to have separate requests queues for students and faculty, where faculty queue is given a higher priority. Implement a strategy for the same. The summary at the end of the session should include the total time he spent on handling queries and average query time.

Solution Proposed for the above problem : 
The given problem is based upon solving queries of Faculties and Students. Thus, these queries can be compared to different processes in terms of operating system where each process has its own demands and time for its execution. And these demands of processes are handled by the CPU. In the given situation, Mr. Sudesh Sharma, Linux expert, is considered as a CPU, who solves the queries of either Faculty or Student by allocating proper resources to their individual demands and processing them by allocating them time accordingly. Now, Mr. Sharma, wants to provide priority for each query based upon its class, as well as, he wants to dedicate a fixed amount of time to every request. Thus in Operating System, if we divide the requests into two separate queues i.e. Faculty and Student such that the first queue contains faculty queries has higher priority and the second contains student queries which has lower priority, then we can resolve the problem, by allocating them required resources based upon their priorities as done in the scheduling algorithm in operating systems.
The above problem is solved by RobinRound algorithm. 
