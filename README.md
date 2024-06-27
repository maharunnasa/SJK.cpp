# Shortest Job First Scheduling Algorithm

This program implements the Shortest Job First (SJF) Scheduling algorithm in C++. It allows the user to input the burst times for a set of processes and calculates the waiting time and turn around time for each process, displaying them in a Gantt chart format.

## Features

- Calculates waiting time and turn around time for each process.
- Displays a Gantt chart for the process execution order.
- Calculates and displays the average waiting time and turn around time.

## Getting Started

### Prerequisites

- A C++ compiler (e.g., g++)

### Installation

1. Clone this repository or download the source code.
2. Navigate to the directory where the source code is located.

### Compilation

To compile the program, run the following command in your terminal:

```bash
g++ -o sjf_scheduling sjf_scheduling.cpp

*Example*
Enter The Total Number of Processes: 3

Enter CBT of Processes:
10
5
8

========================================================
        Shortest Job First Gantt Chart
========================================================
P2  |  P3  |  P1  
--------------------------------------------------------
00    05    13    

--------------------------------------------------------
Process         CBT     Waiting Time    Turn Around Time
--------------------------------------------------------
P[2]            5       0               5
P[3]            8       5               13
P[1]            10      13              23


Average Waiting Time: 6
Average Turn Around Time: 13

*Acknowledgements*

### Explanation:

1. **Introduction**: Briefly explains what the program does.
2. **Features**: Lists the key features of the program.
3. **Getting Started**: Provides instructions on prerequisites, installation, and compilation.
4. **Running the Program**: Explains how to run the compiled program.
5. **Example Usage**: Provides an example of how the program works with sample input and output.
6. **License**: Indicates the type of license under which the program is distributed.
7. **Acknowledgements**: Credits or acknowledgments for inspiration or support.

