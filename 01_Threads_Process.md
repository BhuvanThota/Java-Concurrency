

# Threads & Process

## Thread

### What is a Thread?

- A thread is a single sequential flow of control within a program.
- Single Sequential flow of control
- Sequence of programmed instruction that can be managed independently
- Allows the prgram to split into simultaneously running tasks
- Ex: Building a Wall - Instructions
    - Get mortar/ Cement
    - Add a layer on the top of built wall
    - get brick
    - Firmly place brick on layer of mortar
    - Loop until done


- Imagine having single builders doing whole process it takes lot of time
- Now if we have multiple builders then the works completes faster.

- This is a simple analogy to compare to multi-thread
    - Builder - Processor Core

___________________________________________

## Process

### What is a Process?

- Ex : Running/ Opening an application
    - Load program to memory
    - Allocate Resoucres
    - "Execute" the program

- This whole steps is called a Process.
- Execution -> Process 

### Process Order

- Binary instructions loaded into memory
- Gets access to resources like memory
- Loads Its own stack, heap, register
- Resource is protected from other processes
- Loads the application

### Processes are independent

- Can be started and stopped without affecting others
- Cannot access each other (Unless mechanism are coded into them)

____________________________________


## Process Vs Threads

- Simple analogy -> A Process (Application) by default runs in concurrent mode, It uses a Processor (Builders) to leverage the multi builders the process try to run a set of instructions in parallel (Multiple builders working a wall). 
- This is called Multi-Threads (Multiple Builders)


### Single Thread w.r.t Process

- A process could have multi-threads
- Single Thread is unit of execution within a process
- Does the work of a process
- Usually had a shared objective
- Has shared resources like memory, heap storage


_________________________________________




