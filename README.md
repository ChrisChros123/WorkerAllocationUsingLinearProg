# WorkerAllocationUsingLinearProgramming(IPython)
Function for transforming the worker-to-task allocation problem into a linear program. 

In the worker allocation problem, we wish to minimize the total time T needed to finish s tasks having r workers 
at our disposal. 
The input data ("worker_task_data.csv") contains the information, what ratio p_{i,j} of task j worker i can finish in one hour.
The program aims at a linear prolem as defined in the SciPy library (https://docs.scipy.org/doc/scipy/reference/generated/scipy.optimize.linprog.html) with variables named accordingly.



