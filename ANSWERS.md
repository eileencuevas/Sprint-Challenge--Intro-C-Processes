**1. List all of the main states a process may be in at any point in time on a standard Unix system. Briefly explain what each of these states means.**

**Running:**  A process that is currently executing/running requests.

**Sleeping:** A process that is waiting for resources in order to continue.

**Stopped**: A process that has finished executing.

**Zombie**: A process that has finished executing, but hasn't been removed from process table.


**2. What is a zombie process?**

A zombie process is a child process that has finished executing, but has not been removed from the process table.


**3. How does a zombie process get created? How does one get destroyed?**

A zombie process gets created when a child process completes it execution while its parent process is still running, and does not see that the child has finished executing. Zombie processes get destroyed once their parent process waits for it to complete execution.


**4. What are some of the benefits of working in a compiled language versus a non-compiled language? More specifically, what benefits are there to be had from taking the extra time to compile our code?**

The main benefit of working in a compiled language is that your code runs faster than code made in a non-compiled language. Because there is no "middleman" to handle your code, your CPU can just run your code immediately.