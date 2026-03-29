# Open Source Audit Project

## Student Details
- Name: Neerav
- Registration Number: 24bce11248
- Chosen Software: **Git**
  
## Git
Git is a popular version control system that is commonly used by developers to manage and track changes in their source code. It allows many developers to contribute to a project at the same time.

## Project Description
The project focuses on the exploration of the concept of open-source software, its importance, and how it is used in a Linux operating system environment. This project also emphasizes the benefits that an individual receives using open-source software compared to other types of software.

In addition to this theoretical knowledge, this project also includes five shell scripts. This will bridge the gap between theory and practice.

## Scripts Overview

The project comprises five shell scripts, each intended to carry out a particular function and illustrate the application of various concepts in shell scripting.

### script1.sh — System Identity Report
This script displays essential system information such as the user running the script, the system date and time, and kernel information. It is written to handle cases where some of the commands might not function in the Git Bash environment.

### script2.sh — Package Inspector
This script is intended to check if the system has the Git program installed. If the program is available, it displays the version number and provides a description using conditional statements.

### script3.sh — Disk and Permission Auditor
This script is intended to analyze specific directories and display the size and permissions associated with them. It utilizes loops to carry out the task and includes conditions to handle missing directories.

### script4.sh — Log File Analyzer
This script is intended to search for the number of occurrences of a given keyword in a file. It also displays the latest occurrences of the keyword.

### script5.sh — Manifesto Generator
This script is intended to take user input and create a statement or manifesto that is open source in nature and save it in a text file.

## How to Run Scripts (Using Git Bash)

### Step 1: Open Git Bash
Right-click inside the project folder and select:
`Git Bash Here`

### Step 2: Give execute permission
Run the following commands:

```bash
chmod +x script1.sh
chmod +x script2.sh
chmod +x script3.sh
chmod +x script4.sh
chmod +x script5.sh
```

### Step 3: Run scripts
```
./script1.sh
```
```
./script2.sh
```
```
./script3.sh
```
```
./script4.sh script1.sh echo
```
```
./script5.sh
```
