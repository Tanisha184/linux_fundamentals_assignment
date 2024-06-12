# Linux Fundamentals Assignment

## Task 1: File System Navigate
# Linux Fundamentals Assignment
1. List the contents of the home directory:
   ```bash
   ls ~
2. Change the current directory to /var/log and list its contents:
   ```bash
   cd /var/log
   ls
3. Find and display the path to the bash executable using the which comman:
   ```bash
   which bash

4. Find current shell:
   ```bash
   echo $SHELL

## Task 2: File and Directory Operations
1. Create a directory named linux_fundamentals in your home directory.
   ```bash
   $ mkdir ~/linux_fundamentals
2. Inside linux_fundamentals, create a subdirectory named scripts.
   ```bash
   $ mkdir ~/linux_fundamentals/scripts
3. Create an empty file named example.txt inside the linux_fundamentals directory.
   ```bash
   touch ~/linux_fundamentals/example.txt
4. Copy example.txt to the scripts directory.
   ```bash
   $ cp ~/linux_fundamentals/example.txt ~/linux_fundamentals/scripts/
5. Move example.txt from linux_fundamentals to linux_fundamentals/backup.
   ```bash
   mv ~/linux_fundamentals/example.txt ~/linux_fundamentals/backup/
##Permissions
-Change the permissions of example.txt to read and write for the owner, and read-only for the group and others:
```bash
chmod 640 ~/linux_fundamentals/example.txt

