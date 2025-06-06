🟢 What is OS ?
```
   An Operating System (OS) is system software that manages computer hardware and software 
   resources and provides common services for computer programs.
   ```


🟢 What if there is no OS ?
```

    No User Interface:
        Users cannot interact with hardware or run programs without an interface.

    Manual Hardware Management:
        Developers must write low-level code for every hardware component (keyboard, display, memory, etc.).

    No Multitasking:
        Only one program can run at a time; switching between tasks becomes very complex.

    No Memory Management:
        No control over memory allocation/deallocation, leading to frequent crashes or memory leaks.

    Lack of Security:
        No access control or protection between user data and programs.

    Difficult Application Development:
        Programmers must write drivers and handle hardware directly, increasing complexity and development time.

    No File System:
        No organized way to store or retrieve files; data handling would be raw and inefficient.

    No Standard APIs:
        Applications can't use consistent system-level functions, reducing software compatibility and reuse.

    Inefficient Resource Usage:
        CPU, memory, and other resources can't be optimized or shared among multiple processes.

    No Error Handling Mechanism:
        System crashes or hardware errors would be harder to detect and fix.
        ```
   

🟢 An OS funtion ?
```
    Access the computer hardware
    Interface between the user and the computer hardware
    Resource Management 
    Hide the underlying complexity of the hardware
    Facilitate executed of application program by providing isolation and protection.
    ```

🟢 What is the main purpose of an OS ? Discuss different type ?
```
   The main purpose of an OS is to act as an interface between the user and the hardware. 
   It manages hardware resources and provides a platform to run applications efficiently.

    Batch OS
        No user interaction.
        Jobs are collected and processed in batches.
        Example: Early mainframe systems.

   Time-Sharing OS
        Multiple users can use the system at the same time.
        CPU time is divided among users.
        Example: UNIX.

    Distributed OS
        Manages a group of independent computers as a single system.
        Resources are shared across the network.
        Example: LOCUS.

    Real-Time OS (RTOS)
        Responds to inputs instantly.
        Used in systems where timing is critical.
        Example: Air traffic control, medical systems.

    Network OS
        Provides features to connect computers and devices over a network.
        Example: Novell NetWare, Windows Server.

    Mobile OS
        Designed specifically for mobile devices.
        Example: Android, iOS.    
        ```

🟢 What is a socket, kernel and monolithic kernel ?
```

    Socket:-  
        A socket is an endpoint for communication between two machines over a network.It allows data to be sent and received between client and server.

    Kernel:- 
        The kernel is the core part of the operating system.
        It manages system resources like CPU, memory, and devices.
        It acts as a bridge between hardware and software.  

    Monolithic Kernel:-    
        A monolithic kernel is a type of kernel where all OS services run in a single large process in kernel space.
        It offers high performance but can be less secure and harder to maintain.
        Example: Linux uses
        ```
    
🟢1. Difference between process and program and thread ? Different type of proces.
```

    Program:
        A set of instructions (passive).
        Example: A .exe file.

    Process:
        A running instance of a program (active).
        Example: Chrome running.

    Thread:
        A lightweight unit of a process.
        Shares memory with other threads in the same process.

    Types of Processes:    
        Foreground Process – Interacts with the user.
        Background Process – Runs in the background.
        Parent Process – Creates other processes.
        Child Process – Created by another process.
        Daemon Process – Runs continuously in the background (e.g., services).
        ```
 
🟢2. Define Virtual memory ,Thrashing , Threads.
```

    Virtual Memory: 
        Virtual memory is a technique that uses part of the hard disk as extra RAM.
        It helps run large programs even if your system has low physical memory.

    Thrashing: 
        Thrashing is a condition where the CPU spends most of its time swapping pages in and out of memory, instead of doing actual work.    

        "Too much page swapping, system becomes slow

    Thread: 
        A thread is the smallest unit of a process that can run independently.
        Multiple threads can run in the same process and share memory.    

        "Tiny task inside a process."
        ```
   
🟢3. What is RAID ? Different type.
```
    RAID (Redundant Array of Independent Disks) is a technology that combines multiple hard drives to work as one.
    It improves data safety, speed, or both.

    Types of RAID:

    RAID 0 (Striping):
        Splits data across drives for faster speed, but no backup.
        If one drive fails, data is lost.

    RAID 1 (Mirroring):
        Copies the same data on two drives for backup.
        If one drive fails, data is safe.

    RAID 5 (Striping with Parity):
        Data and parity (error info) are spread across drives.
        Balances speed and fault tolerance.

    RAID 10 (1+0):
        Combines mirroring and striping for speed and backup.
        ```

🟢4. What is Deadlock ? Different conditions to achive a deadlock.
```
   Deadlock is a situation where two or more processes are waiting for each other to release resources, and none of them can proceed.

   ✅Conditions for Deadlock (4 Necessary Conditions):

    Mutual Exclusion:
        Only one process can use a resource at a time.

    Hold and Wait:
        A process holds at least one resource and waits for others.

    No Preemption:
        Resources cannot be forcibly taken from a process.

    Circular Wait:
        A circular chain of processes exists, each waiting for a resource held by the next.
        ```

🟢5. What is fragmentation ? Type of fragmentation.
```
   Fragmentation happens when memory is used inefficiently, leaving small unused spaces that can’t be used to store new data.

   ✅ Types of Fragmentation:

    Internal Fragmentation:
        Wasted space inside allocated memory blocks because the allocated space is bigger than needed.

    External Fragmentation:
        Free memory is split into small pieces scattered outside, so even if total free memory is enough, it can’t be used for big requests.
        ```
   
🟢6. What is Spooling ?
```
   Spooling is a process where data is temporarily stored on a disk before being sent to a device like a printer.
   ```
   
🟢7. What is semaphore and mutex ?
```
    A semaphore is a variable used to control access to shared resources by multiple processes.

    A mutex (mutual exclusion) is a lock that allows only one process to access a resource at a time.
    ```

🟢8.  difference between semaphore and mutex ?
```
 
    Point                Semaphore                                     Mutex
 
    Purpose      Controls access for multiple processes          Allows access to only one process at a time

    Value        Can have any non-negative value                 Binary (0 or 1) – locked or unlocked

    Ownership    No ownership; any process can signal            Has ownership; only the locking process can unlock

    Use case     Used for signaling and resource counting        Used for mutual exclusion (locking)
    ```

🟢9. Define Binary semaphore.
```
    A binary semaphore is a synchronization tool that has only two values, 0 or 1, used to allow or block access 
    to a resource, working like a lock that is either locked or unlocked.
    ```
   
🟢10. Belady's Anomaly ?
```
   Belady's Anomaly is a situation in some page replacement algorithms where increasing the number of page 
   frames causes more page faults instead of fewer.
   ```



🟢11. Starving and Aging in OS
```
    Starving: A process waits too long because other high-priority processes keep executing.
    Aging: Gradually increases a process's priority to avoid starvation.
    ```

🟢12. Why does trashing occur?
```
    Trashing happens when the system spends more time swapping pages in and out of memory than
    executing processes. This slows down the system.
    ```

🟢13. What is paging and why do we need it?
```
    Paging is a memory management method that divides memory into fixed-size blocks (pages).
    We need it to avoid fragmentation and use memory efficiently.
    ```

🟢14. Demand Paging, Segmentation
```
    Demand Paging: Pages are loaded only when needed. Saves memory.
    Segmentation: Divides memory based on logical sections like code, data, stack. Helps in better organization.
    ```

🟢15. Real Time Operating System, types of RTOS
    
    ```RTOS is used in time-critical systems (e.g., medical, automotive).

    Types:

        Hard RTOS: Strict timing (miss = failure).
        Soft RTOS: Timing is important but not critical.
        ```

🟢16. Difference between main memory and secondary memory
```

    Main Memory: RAM, fast, temporary.

    Secondary Memory: HDD/SSD, slower, permanent.
    ```

🟢17. Dynamic Binding
```
    Dynamic binding means deciding which method to call at runtime, not compile time.
    Used in OOP (e.g., method overriding).
    ```

🟢18. FCFS Scheduling
```
    First Come First Serve: Processes are executed in the order they arrive. Simple but may cause waiting.
    ```

🟢19. SJF Scheduling
```
   Shortest Job First: Process with the smallest burst time is executed first. Reduces average waiting time.
   ```

🟢20. SRTF Scheduling
```
   Shortest Remaining Time First: Preemptive version of SJF. Chooses process with least remaining time.
   ```

🟢21. LRTF Scheduling
```
   Longest Remaining Time First: Opposite of SRTF. Executes process with the most remaining time first.
   ```

🟢22. Priority Scheduling
```
   Processes are scheduled based on priority. Higher priority runs first. Can cause starvation.
   ```

🟢23. Round Robin Scheduling
```
   Each process gets equal time (time slice). Good for time-sharing systems. Fair and simple.
   ```

🟢24. Producer Consumer Problem
```
   A classic problem where producer adds data and consumer uses it. Needs synchronization to avoid conflicts.
   ```

🟢25. Banker’s Algorithm
```
   Used to avoid deadlock. Checks if resources can be safely allocated without leading to a deadlock.
   ```

🟢26. Explain Cache
```
   Cache is a small, fast memory that stores frequently used data. Speeds up CPU access.
   ```

🟢27. Diff between direct mapping and associative mapping
```

    Direct Mapping: One block maps to one cache location. Simple, fast.

    Associative Mapping: Block can go anywhere in cache. More flexible, slower search.
    ```

🟢28. Diff between multitasking and multiprocessing
```

    Multitasking: One CPU runs multiple tasks by switching quickly.

    Multiprocessing: Multiple CPUs run multiple tasks at the same time.
    ```







