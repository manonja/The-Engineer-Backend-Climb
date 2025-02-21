## **Month 1: Core Systems and Infrastructure Fundamentals**

### **Module 1.1: Operating Systems & Networking Basics**

**Key Concepts:**
- **Operating Systems Fundamentals:**
	- **Deep dive into process scheduling, memory management, file systems, and I/O operations.**
	- Readings:
	    - _Modern Operating Systems_ by **Andrew S. Tanenbaum**
	    - _Operating Systems: Three Easy Pieces_ by **Remzi Arpaci-Dusseau & Andrea Arpaci-Dusseau**
    
- **Networking Essentials:**
	- **TCP/IP, UDP, HTTP, socket programming, and protocols fundamentals.**
	- Readings:
	    - _TCP/IP Illustrated, Volume 1: The Protocols_ by **W. Richard Stevens**
	    - Technical papers by **Van Jacobson** (on congestion control, for instance)
	    
- **Concurrency & Parallelism:**

- **Threading models, synchronization primitives (mutexes, semaphores), and common pitfalls like deadlocks.**
- Readings:
    - Selected chapters from _The Art of Multiprocessor Programming_ by **Maurice Herlihy and Nir Shavit**

**Why It’s Important:**

- A deep understanding of how the OS and network work under the hood will help you build efficient, secure backends.
- These concepts are language-agnostic and essential regardless of whether you choose Rust, Elixir, or any other language.

**Resources:**

- Andrew Tanenbaum’s _Modern Operating Systems_
- Online courses or lectures (e.g., MIT’s _Operating System Engineering_)
- Tutorials from platforms like Coursera, edX, or Udemy on TCP/IP networking

**Hands-on Project:**

- **Mini Network Scanner:** Build a small CLI tool that can scan standard http port and retrieve basic system information [[Port Scanner]]
- **Reflection:** Write a short blog post or journal entry about how OS-level concepts influence high-level backend design.
- **Mini OS Scheduler**: [[Week 2&3 - OS Scheduler emulator]]


### **Module 1.2: Data Structures, Algorithms & Concurrency Basics**

**Key Concepts:**

- **Fundamental Data Structures & Algorithms:**  
    Focus on hash tables, trees, graphs, sorting algorithms, and how to choose the right structure for the problem.
- **Concurrency Basics:**  
    Understand threads vs. processes, synchronization primitives (mutexes, semaphores), and common concurrency issues (race conditions, deadlocks).

**Why It’s Important:**

- Efficient data handling is the backbone of robust backend systems.
- Concurrency is crucial for scaling and managing asynchronous operations in backend systems.

**Resources:**

- Donald Knuth’s _The Art of Computer Programming_ (selected chapters)
- Online coding platforms (LeetCode, HackerRank) for practice
- Papers or blog posts on concurrency in modern systems (e.g., “The Anatomy of a Multithreaded System”)

**Hands-on Project:**

- **Concurrent Data Processor:** Build an application that processes data from multiple sources concurrently. For instance, simulate data ingestion from multiple sensors, handle data aggregation, and process the streams in parallel. [[Week 4 - Concurrent Data Processor]]
- **Reflection:** Document the concurrency issues you encountered and describe how the system’s performance scaled with your improvements.
