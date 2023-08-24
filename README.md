# A distributed system for transaction management and scheduling  for distributed system across multiple server

This project focuses on optimizing transaction processing for a major e-commerce platform using a distributed system. It involves designing a process scheduling algorithm to efficiently manage millions of daily transactions across multiple servers and services. Worker threads, each assigned priority levels and resources, process incoming requests. The algorithm prioritizes high-priority threads, allocating resources based on transaction type and availability. Input includes service details, worker attributes, and transaction specifics, with output presenting processed order, average waiting and turnaround times, and rejected requests count. During high traffic, the algorithm reports waiting requests due to limited resources and blocked requests due to unavailability of worker threads. This project enhances transaction efficiency and stability.



## To compile and run the code, you can follow these steps:
- Open a terminal and navigate to the directory where the file is located.
- Compile the code using the command "make". This command will compile the code using the GCC compiler.
- Run the program using the  command "./q3". This command will run the program and execute the code in the main function.
- In order to give input directly from the sample_input.txt file during execution, run "./q3 < sample_input.txt".
