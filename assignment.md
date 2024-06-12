# Linux Fundamentals Assignment

## Task 1: File System Navigate
# Linux Fundamentals Assignment
1. List the contents of the home directory:
   ```bash
   ls ~
2.Change the current directory to /var/log and list its contents:cd /var/log
ls
3.Find and display the path to the bash executable using the which command.

which bash
4.Find current shell
echo $SHELL

##File and Directory Operations
Create a directory named linux_fundamentals in your home directory.
$ mkdir ~/linux_fundamentals
Inside linux_fundamentals, create a subdirectory named scripts.
$ mkdir ~/linux_fundamentals/scripts
Create an empty file named example.txt inside the linux_fundamentals directory.

touch ~/linux_fundamentals/example.txt
Copy example.txt to the scripts directory.
$ cp ~/linux_fundamentals/example.txt ~/linux_fundamentals/scripts/
Move example.txt from linux_fundamentals to linux_fundamentals/backup.

 mv ~/linux_fundamentals/example.txt ~/linux_fundamentals/backup/

Change the permissions of example.txt to read and write for the owner, and read-only for the group and others:

chmod 640 ~/linux_fundamentals/example.txt
