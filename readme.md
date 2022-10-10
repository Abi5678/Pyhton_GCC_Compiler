python-GCC-compiler

Python script to automate compilation (with GCC) and running of .c files

**Description**

When compile.py is run, it scans the working directory for all .c files and lists them, allowing the user to choose the file to be compiled (if there is only 1 .c file in the folder, it would be chosen automatically). Python then invokes GCC with the -std=c17 and -Wall flags to compile the c file and then run it within the same shell window. Compilation errors, if any, would be shown. The script uses an infinite while loop to continuously stay open and allow the user to press Enter to re-compile and re-run the C program as the user updates his C code in a separate code editor such as Sublime Text.

