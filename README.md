# priority-scheduling-

Lab Report: Implementation of Priority Scheduling Algorithm

Introduction :
Priority Scheduling is a non-preemptive process scheduling algorithm where each process is assigned a priority value. The CPU executes the process with the highest priority first. If two processes have the same priority, FCFS order is used as a tiebreaker. Priority values can be fixed or dynamic (e.g., based on process characteristics or user input).

Objective :
To implement the Priority Scheduling algorithm and evaluate its performance.

Implementation Details :
Assign a priority value to each process (higher values indicate higher priority).
Add processes to the ready queue based on their priority.
Execute the process with the highest priority until it completes or is preempted.
If a higher-priority process arrives, preempt the currently executing process.


Advantages:
Prioritizes important tasks.
Can be customized for specific requirements.

Disadvantages:
May lead to starvation (low-priority processes never get CPU time).
Preemption can introduce overhead.

Conclusion:
Priority Scheduling is useful when different processes have varying levels of importance. 
However, care must be taken to prevent starvation and ensure fairness.
