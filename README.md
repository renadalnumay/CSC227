# CSC227 Memory Management Project

This Java program is designed to manage a contiguous region of memory using a fixed-size partition scheme. It allows users to allocate and de-allocate memory blocks, and provides a status report about the current state of memory. The allocation of memory blocks can be performed using one of three contiguous memory allocation approaches: first-fit, best-fit, or worst-fit.

## Instructions 

To use the program, follow these steps:


1. Run the main class  

2. The program will prompt you to enter the number of partitions (M), Enter a positave Integer, this will be the size of the memory(the number of partitions in the memory).
3. The program will prompt you to enter the size of each partition in KB, Enter a positave Integer, this will be the size of the partition. (note: each partition can have different size)
4. The program will prompt you to enter the allocation strategy (F, B, or W), Enter F for First Fit algorithm, B for Best Fist Algorithm, W for Worst Fit Algorthim.
5. The program will prompt you the following menue. Enter 1, 2, 3 or 4 for the operation that you wish to use:
    1. Allocate a block of memory by entering the process 
       1. The program will prompt you to enter the process ID(a positave integer) 
       2. The program will prompt you to enter the process size(a positave integer).
       3. The program will print whether the opration is successful or not.
       4. The program will print the memory state after allocation, which shows the allocated processes and the available partitions (holes (H)) using a chart. Example: [P1 | H | P3 | H | H | P2].
    2. De-allocate a block of memory by entering the process ID(a positave integer)to be released.
       1. The program will prompt you to enter the process ID(a positave integer) 
       2. The program will print whether the opration is successful or not.
       3. The program will print the memory state after de-allocation, which shows the allocated processes and the available partitions (holes (H)) using a chart. Example: [P1 | H | P3 | H | H | P2].
    3. Report detailed information about regions of free and allocated memory blocks.
       1. The program will output on the console a report of each partition in the memory array with the
          following information, and then will write them to a text file: <br>
          ● Partition status. <br>
          ● Partition size.<br>
          ● Starting address.<br>
          ● Ending address.<br>
          ● Process ID.<br>
          ● Internal fragmentation size.<br>
    5. Exit the program.
       1. the program will stop executing.

## Output

The program will output a report of each partition in the memory array, including the partition status, size, starting and ending addresses, process ID, and internal fragmentation size. It will also display the memory state after allocation, using a chart to show the allocated processes and available partitions.

The program will write this information to a text file called "Report.txt" in the project directory.


## Authors

This project was created by Deema Alzaid, Halah Aldakhiel, Renad Alnamay, Abeer Alhussain as part of CSC227 course at King Saud University.
