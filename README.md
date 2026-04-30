# Operating Systems Lab Projects

This repository contains my academic lab work for the **Operating Systems (BSE 3rd Semester)** course at Fatima Jinnah Women University (FJWU). It showcases practical implementations of Shell Scripting, Process Management, and System Calls.

---

## 📂 Lab 04: Shell Scripting (Bash)
Focused on automation and file management using Bash scripts within the Linux environment.

* **Task 1: File Deletion Logic:** A script that tests the `rm` command's exit status to confirm if a file was successfully deleted or if an error occurred.
* **Task 2: Gross Salary Calculator:** Implementation of conditional logic to calculate HRA (10% or 20%) and total salary based on basic pay input.
* **Task 3: Argument-based Arithmetic:** A script that adds two numbers passed as command-line arguments, including error handling for incorrect argument counts.
* **Task 4: Fibonacci Series:** A mathematical script that generates a Fibonacci sequence up to a user-defined limit.

---

## 📂 Lab 05: Process Management (C Language)
Explored the lifecycle of processes and the hierarchy of parent-child relationships using system calls.

* **Task 1: Sibling Processes:** Using the `fork()` system call to create an architecture where a single parent creates two distinct child processes (P1 and P2).
* **Task 2: Multi-level Hierarchy:** Implementing a deep hierarchy (Grandparent -> Parent -> Child) where each new process is a child of the previous one.

---

## 📂 Lab 07: System Calls & I/O Operations (C Language)
Deep dive into kernel-level file handling and standard I/O operations using C system calls.

### **Part 1: read() & write()**
* **Task 1: Buffer Management:** A program designed to read exactly 15 characters from user input and print them, demonstrating buffer control.
* **Task 2: Character Counting:** Utilizing the return value of the `read()` system call to accurately count and display the total characters processed.

### **Part 2: open() & File Manipulation**
* **Task 1: Data Appending:** Copying data from a source file (F1) to a destination file (F2) using the `O_APPEND` flag to ensure existing data is preserved.
* **Task 2: File Copy Utility:** A complete implementation of a 'copy' command that reads from a source file and writes the entire content into a new destination file.
