# Process Schedueling Algorithms

The experiment folders as given above contain, the schedueling information in the following order:

- __Experiment-3__ : First Come First Serve Algorithm (FCFS)
- __Experiment-4__ : Shortest Job First ALgorithm (SJF)
- __Experiment-5__ : Shortest Remaining Time First Algorithm(SRTF)
- __Experiment-6__ : Priority Schedueling Algorithm
- __Experiment-7__ : Round Robin Schedueling Algorithm

### Description: 

The following codes have been implemented in C++, and are made especially for handling the difficult situation cases such as varied arrival times in the CPU, handling starvation and other such faults which are not covered by the standard codes found on various sites. I have tried to cover and code the pre-emptive and non-preemptive version of all the schedueling algorithms (if it's possible to make a schedueling algorithm). If not it's definitely going to be added in the future updates. 

I have used __vector, map and priority queue STL__ to code the algorithms. __OOPS__ has been used to provide modularity, and to easily replicate the working of a __PCB__. Also __Ready Queue__ has been replicated in the code to a certain extent using priority queues. Main idea of all the codes is based on the __time steps and time stamps__. The algorithm in most cases iterates over each second to accomodate the various changes, and keep track of all the process waiting, in the ready queue or running on the CPU.

#### First Come First Serve Algorithm (FCFS)

First Come First Serve (FCFS) is an operating system scheduling algorithm that automatically executes queued requests and processes in order of their arrival. It is the easiest and simplest CPU scheduling algorithm. In this type of algorithm, processes which requests the CPU first get the CPU allocation first. This is managed with a FIFO queue. The full form of FCFS is First Come First Serve.

As the process enters the ready queue, its PCB (Process Control Block) is linked with the tail of the queue and, when the CPU becomes free, it should be assigned to the process at the beginning of the queue.

#### Shortest Job First ALgorithm (SJF)

Shortest Job First (SJF) is an algorithm in which the process having the smallest execution time is chosen for the next execution. This scheduling method can be preemptive or non-preemptive. It significantly reduces the average waiting time for other processes awaiting execution. The full form of SJF is Shortest Job First.

#### Shortest Remaining Time First Algorithm(SRTF)

Shortest Remaining Time First (SRTF) is the preemptive version of Shortest Job Next (SJN) algorithm, where the processor is allocated to the job closest to completion.

This algorithm requires advanced concept and knowledge of CPU time required to process the job in an interactive system, and hence can’t be implemented there. But, in a batch system where it is desirable to give preference to short jobs, SRT algorithm is used.

However, SRT involves more overheads than SJN, as the OS is required to frequently monitor the CPU time of the jobs in the READY queue and perform context switching.

####  Priority Schedueling Algorithm

Priority Scheduling is a method of scheduling processes that is based on priority. In this algorithm, the scheduler selects the tasks to work as per the priority.

The processes with higher priority should be carried out first, whereas jobs with equal priorities are carried out on a round-robin or FCFS basis. Priority depends upon memory requirements, time requirements, etc.

#### Round Robin Schedueling Algorithm

Round-robin (RR) is one of the algorithms employed by process and network schedulers in computing.[1][2] As the term is generally used, time slices (also known as time quanta)[3] are assigned to each process in equal portions and in circular order, handling all processes without priority (also known as cyclic executive). Round-robin scheduling is simple, easy to implement, and starvation-free. Round-robin scheduling can be applied to other scheduling problems, such as data packet scheduling in computer networks. It is an operating system concept.


### Future Updates:

- Uploading images of outputs on the terminal
- adding the pre-emptive version of Priority schedueling
- adding the varied arrival time version for Round Robin Schedueling
- More schedueling algorithms

### CopyRight:

Written and Documented by Daksh Gupta.
