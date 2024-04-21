# Process Scheduling Algorithms in Java

This repository contains Java implementations of various process scheduling algorithms used in operating systems. The implemented algorithms include:

- First-Come, First-Served (FCFS)
- Guaranteed Base Group (GBG)
- Round Robin (RR)

Each algorithm is implemented as a separate Java class with a corresponding usage example in the `Main` class.

## Contents

1. [Overview](#overview)
2. [Usage](#usage)
3. [Algorithms](#algorithms)
4. [Contributing](#contributing)
5. [License](#license)

## Overview

Process scheduling algorithms are fundamental in operating systems for managing the execution of processes and allocating system resources such as CPU time and memory. This repository provides Java implementations of three commonly used scheduling algorithms.

## Usage

To use these scheduling algorithms, follow these steps:

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/bllraslen/process-scheduling-algorithms-java.git
Navigate to the project directory:
bash
Copy code
cd process-scheduling-algorithms-java
Compile the Java files:
bash
Copy code
javac Main.java
Run the Main class:
bash
Copy code
java Main
Follow the on-screen instructions to provide input (process details) and observe the scheduling results.
Algorithms
First-Come, First-Served (FCFS)
FCFS is a simple scheduling algorithm that schedules processes based on their arrival time. The process that arrives first gets executed first.

Guaranteed Base Group (GBG)
GBG is another scheduling algorithm that prioritizes processes based on their arrival time. Additional details about GBG can be found in the corresponding Java class.

Round Robin (RR)
Round Robin is a preemptive scheduling algorithm that assigns a fixed time slice (time quantum) to each process. If a process doesn't finish within its time quantum, it's placed back in the queue to be executed later.

Contributing
Contributions to this repository are welcome. If you find any issues or have suggestions for improvements, feel free to open an issue or create a pull request.

License
This project is licensed under the MIT License - see the LICENSE file for details.
