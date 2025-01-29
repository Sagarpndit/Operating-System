# 🚀 Operating System Coding Problems (150+)

A curated list of **150+ Operating System (OS) coding problems** for interview preparation and system programming practice. Covers **process management, scheduling, memory management, IPC, threads, deadlocks, and more**. 💻

---

## 📌 **Process Management (20 Problems)**
1. Create a child process using `fork()`
2. Print parent and child process IDs
3. Create multiple child processes using `fork()`
4. Use `exec()` to replace a process image
5. Implement `wait()` to synchronize parent and child processes
6. Implement `waitpid()` for child process termination handling
7. Demonstrate zombie process creation
8. Prevent a zombie process using `wait()`
9. Create an orphan process
10. Implement a daemon process
11. Use `getppid()` to get the parent process ID
12. Create multiple processes in a loop
13. Measure execution time of a process
14. Show process hierarchy using `fork()`
15. Simulate process creation in a shell-like environment
16. Implement an infinite loop inside a child process
17. Check process priority using `getpriority()`
18. Set process priority using `setpriority()`
19. Use `nice()` to change process scheduling priority
20. Terminate a process using `kill()`

---

## 📌 **Process Scheduling (20 Problems)**
21. Implement First-Come, First-Served (FCFS) scheduling
22. Implement Shortest Job Next (SJN) scheduling
23. Implement Round Robin (RR) scheduling
24. Implement Priority Scheduling (Preemptive)
25. Implement Priority Scheduling (Non-Preemptive)
26. Implement Multi-Level Queue scheduling
27. Implement Multi-Level Feedback Queue scheduling
28. Implement Highest Response Ratio Next (HRRN) scheduling
29. Simulate a real-world CPU scheduler
30. Implement Lottery Scheduling
31. Simulate scheduling with different time quantum values
32. Implement Longest Remaining Time First (LRTF) scheduling
33. Implement an I/O-burst process scheduler
34. Implement Multi-Threaded Process Scheduling
35. Implement First Fit memory allocation with process scheduling
36. Simulate process scheduling using a Min-Heap
37. Simulate a CPU-bound and I/O-bound process scheduler
38. Implement Dynamic Round Robin Scheduling
39. Implement CPU scheduling using Priority Queues
40. Simulate CPU and I/O scheduling together

---

## 📌 **Inter-Process Communication (IPC) (20 Problems)**
41. Implement IPC using pipes
42. Use `dup()` to duplicate file descriptors for IPC
43. Implement Named Pipes (`FIFO`) for communication
44. Implement Shared Memory (`shmget()`)
45. Use `shmat()` and `shmdt()` for shared memory
46. Implement IPC using Message Queues
47. Implement process synchronization using Message Passing
48. Implement producer-consumer using shared memory
49. Implement chat communication using Pipes
50. Implement Parent-Child communication using Pipes
51. Implement bidirectional communication using Pipes
52. Implement bidirectional communication using Message Queues
53. Implement process synchronization using Semaphores
54. Implement reader-writer problem using Semaphores
55. Implement a file-locking mechanism using Semaphores
56. Implement a counting Semaphore example
57. Implement multiple process communication using Shared Memory
58. Use `mmap()` for inter-process memory sharing
59. Implement multi-threaded producer-consumer problem using Semaphores
60. Implement dining philosophers problem using Semaphores

---

## 📌 **Deadlocks and Synchronization (20 Problems)**
61. Implement the Banker's Algorithm
62. Implement the Resource Allocation Graph (RAG)
63. Detect a deadlock using Wait-For Graph (WFG)
64. Implement deadlock prevention with mutex locks
65. Implement deadlock detection using an adjacency matrix
66. Implement deadlock handling using safe sequences
67. Implement deadlock handling using process rollback
68. Implement deadlock avoidance using request-grant
69. Simulate a deadlock and recover from it
70. Implement an algorithm to break circular wait
71. Use Peterson’s Algorithm for mutual exclusion
72. Use the Bakery Algorithm for mutual exclusion
73. Implement spinlocks for process synchronization
74. Implement thread synchronization using condition variables
75. Implement sleeping barber problem using Semaphores
76. Implement cigarette smokers problem using Semaphores
77. Implement process synchronization using busy waiting
78. Implement multiple producer-consumer synchronization
79. Implement a priority queue with lock-based synchronization
80. Implement real-time scheduling with synchronization

---

## 📌 **Threads and Concurrency (20 Problems)**
81. Create and manage threads using `pthread`
82. Implement thread synchronization using mutex
83. Implement thread synchronization using Semaphores
84. Use `pthread_join()` to ensure thread completion
85. Implement thread synchronization using condition variables
86. Implement a thread-safe queue
87. Implement multiple producer-consumer threads
88. Implement thread pool design
89. Implement readers-writers problem with multiple threads
90. Implement a concurrent server using threads
91. Implement thread-safe logging
92. Implement thread-safe memory allocation
93. Implement parallel matrix multiplication with threads
94. Implement parallel sorting with threads
95. Implement multi-threaded file reading
96. Implement parallel prime number computation
97. Implement thread-based load balancing
98. Implement a worker thread model
99. Implement dynamic thread management
100. Implement a thread scheduler

---

## 📌 **Memory Management (20 Problems)**
101. Implement First-Fit memory allocation
102. Implement Best-Fit memory allocation
103. Implement Worst-Fit memory allocation
104. Implement Paging mechanism
105. Implement Page Replacement using FIFO
106. Implement Page Replacement using LRU
107. Implement Page Replacement using Optimal Algorithm
108. Implement Segmentation-based memory management
109. Implement Buddy System memory allocation
110. Implement dynamic memory allocation using `mmap()`
111. Implement a simple Heap memory manager
112. Implement TLB (Translation Lookaside Buffer) Simulation
113. Implement virtual memory with paging
114. Implement demand paging mechanism
115. Implement Least Frequently Used (LFU) page replacement
116. Implement Most Recently Used (MRU) page replacement
117. Implement multi-level paging
118. Implement memory fragmentation detection
119. Implement swapping between main and secondary memory
120. Implement a simple cache memory simulator

---

## 📌 **File System & Disk Scheduling (20 Problems)**
121. Implement FIFO Disk Scheduling
122. Implement SSTF Disk Scheduling
123. Implement SCAN Disk Scheduling
124. Implement C-SCAN Disk Scheduling
125. Implement LOOK Disk Scheduling
126. Implement C-LOOK Disk Scheduling
127. Implement an inode structure
128. Implement a simple file system simulation
129. Implement indexed file allocation
130. Implement linked file allocation
131. Implement contiguous file allocation
132. Implement file compression and decompression
133. Implement a simple file system using a B-tree
134. Implement file permissions management
135. Implement file locking mechanism
136. Implement basic journaling file system
137. Implement a log-structured file system
138. Implement a simple RAID storage system
139. Implement a file system simulator in memory
140. Implement a directory structure simulation

---

## 📌 **Contribute & Practice**
💡 Fork this repository and try solving these problems. PRs welcome!

🚀 Happy Coding!
