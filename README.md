# SJFSchedulerApplication

A Java-based application that demonstrates the Shortest Job First (SJF) CPU scheduling algorithm.

SJFSchedulerApplication helps students understand how operating systems schedule processes based on their CPU burst times. It provides a practical demonstration of process scheduling and execution order for operating systems coursework.

Developed by Ichiro Yamazaki in January 2024, this project is designed for Java-compatible development environments.

## Features

- Shortest Job First Scheduling: Demonstrates scheduling based on CPU burst time.
- Process Management: Organizes processes according to the SJF scheduling algorithm.
- Scheduling Visualization: Presents scheduling results based on the application's implementation.
- Java Compatibility: Runs in a compatible Java environment.
- Educational Purpose: Helps students understand CPU scheduling and operating systems fundamentals.

## Requirements

- Java Runtime Environment (JRE) compatible with the application.
- Java Development Kit (JDK) if you need to compile the source code.
- A Java-compatible IDE, such as IntelliJ IDEA, Eclipse, or NetBeans, if working with the source code.
- The project source files.

Use a Java version compatible with the application's source code and compiled classes. If you are compiling the project, install a compatible JDK.

## Installation and Setup

### 1. Install Java

Download a compatible Java release from a trusted distribution.

Verify your Java installation:

```bash
java -version
```

If you plan to compile the source code, verify the compiler as well:

```bash
javac -version
```

### 2. Open the Project

1. Open your Java-compatible IDE.
2. Import or open the project directory.
3. Configure the appropriate JDK.
4. Set the main class if required.
5. Build and run the application.

### 3. Compile and Run from the Command Line

If the project contains a standalone source file named `SJFSchedulerApplication.java`, you can compile and run it with:

```bash
javac SJFSchedulerApplication.java
java SJFSchedulerApplication
```

If the project uses multiple source files, packages, or external dependencies, configure the appropriate classpath and compile command for the project structure.

## How SJF Scheduling Works

Shortest Job First selects the eligible process with the shortest CPU burst time.

In non-preemptive SJF scheduling, a process runs until completion once selected. If all processes arrive at time zero, the scheduler can arrange them in ascending order of burst time.

For example:

| Process | Burst Time |
|---|---:|
| P1 | 6 |
| P2 | 2 |
| P3 | 4 |

The execution order is P2, P3, then P1.

```text
0       2           6               12
|  P2   |    P3     |       P1       |
```

This example assumes non-preemptive scheduling and that all processes are available at time zero. The application's actual behavior depends on its implementation.

## Project Information

- Project Name: SJFSchedulerApplication
- Programming Language: Java
- Algorithm: Shortest Job First (SJF)
- Developer: Ichiro Yamazaki
- Build Date: January 2024
- Project Category: Operating Systems and CPU Scheduling

## Disclaimer

This project is intended for educational purposes. Supported inputs, scheduling behavior, and output formats depend on the implementation included in the source code.

## License

No license has been specified. All rights are reserved by the respective copyright holder unless a license is added to this repository.
