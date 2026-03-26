# Open Source Audit Project

## Student Details

Name: Chahat Garg
Roll Number: 24BAI10924
Course: Open Source Software

---

## Selected Software

Software: Python (python3)

Python is an open-source programming language created to make coding simple and readable. It is widely used for scripting, automation, web development, and data-related tasks. It is maintained by a global community and distributed under the PSF License.

---

## About the Project

This project is based on analyzing an open-source software and understanding how it works in a Linux environment. Python has been chosen for this audit.

The project includes:

* Study of the software (in the report)
* Practical implementation using shell scripts

---

## Shell Scripts

### 1. system_identity_report.sh

This script shows basic system information such as:

* Linux distribution
* Kernel version
* Current user
* System uptime
* Date and time

It uses variables and basic commands like uname, whoami, uptime, and date.

---

### 2. foss_package_inspector.sh

This script checks whether Python is installed on the system.

It:

* verifies installation using dpkg
* shows version and details
* prints a short note about Python

---

### 3. disk_permission_auditor.sh

This script checks important system directories like /etc, /home, /var/log, etc.

It shows:

* permissions
* owner and group
* size of each directory

It also checks the Python binary location.

---

### 4. log_file_analyzer.sh

This script reads a log file and counts how many times a keyword appears.

* default keyword: error
* also prints last 5 matching lines

It uses loops and conditions.

---

### 5. manifesto_generator.sh

This script asks the user a few questions and creates a small text file based on the answers.

The output file contains a simple open-source statement.

---

## How to Run

Open terminal and go to the project folder.

Make scripts executable:
chmod +x *.sh

Run any script like:
./system_identity_report.sh

For log analyzer:
./log_file_analyzer.sh /var/log/syslog error

---

## Requirements

* Linux system or WSL
* Python installed

Install Python using:
sudo apt update
sudo apt install python3

---

## Files in Repository

* system_identity_report.sh
* foss_package_inspector.sh
* disk_permission_auditor.sh
* log_file_analyzer.sh
* manifesto_generator.sh
* README.md

---

## What I Learned

* Basic Linux commands
* Writing simple shell scripts
* How open-source tools work
* Practical use of Python in Linux

---

## Conclusion

Python is a simple and powerful open-source language. Working on this project helped in understanding both Linux and scripting basics. It also showed how open-source software is used in real systems.

---
