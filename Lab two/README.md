# Bash Scripting Exercises

This repository contains a collection of Bash scripts aimed at practicing various tasks.

---

## Tasks Overview

### Task 1: Greeting Script
- **Script Name:** `greeting.sh`
- **Description:** Asks for a user's name and sends a greeting to them.

### Task 2: Passing Variables Between Scripts
- **Script 1 Name:** `s1.sh`
  - Contains a variable `x` with a value of `5`.
- **Script 2 Name:** `s2.sh`
  - Attempts to print the value of `x` from `s1.sh` by two different methods.

### Task 3: File Copying Script
- **Script Name:** `mycp.sh`
  - Copies a single file to another location.
  - Copies multiple files to a directory.

### Task 4: Directory Changing Script
- **Script Name:** `mycd.sh`
  - Changes the directory to the user's home directory if called without arguments.
  - Changes the directory to the given directory if an argument is provided.

### Task 5: Directory Listing Script
- **Script Name:** `myls.sh`
  - Lists the current directory if called without arguments.
  - Lists the given directory if provided.

### Task 6: Enhanced Directory Listing Script
- **Script Name:** `myls_enhanced.sh`
  - Supports individual options: `-l`, `-a`, `-d`, `-i`, `-R`.
  - Provides various listing formats and functionalities based on options.
  - Implements multiple options together as per the bonus.

### Task 7: Type and Permission Checking Script
- **Script Name:** `mytest.sh`
  - Checks the type of the given argument (file/directory).
  - Checks the permissions of the given argument (read/write/execute).

### Task 8: User Information and Process Status Script
- **Script Name:** `myinfo.sh`
  - Asks the user for their logname.
  - Prints detailed information about files and directories in the user's home directory.
  - Copies user files and directories to `/tmp` directory.
  - Retrieves the current process status of the user.
