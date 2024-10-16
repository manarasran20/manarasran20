# lab2 readme.text file
## 1. project.shell
### Simple Shell Implementation
## 2.Description
### This project implements a basic Unix-like shell in C. It allows users to execute external commands, handle input/output redirection, change directories, and exit the shell.
## 3. Files Included
### myshell.c: The source file that contains the shell implementation.
### README.txt: This file, explains the structure and usage of the shell.
### Makefile: A simple makefile to compile and clean the project.
## 4. Compilation Instructions
### To compile the shell, run the following command in the terminal:

````
make

````
### This will generate an executable named myshell. If you don’t have make, you can also compile manually:
````
gcc -o myshell myshell.c -ansi

````
## 5. How to Run the Shell
### After compiling, run the shell using:
````
./myshell

````
### The shell will print the current directory as part of the prompt and wait for user input.
## 6. Supported Features
### Built-in commands:
#### cd [directory]: Change the current working directory.
#### exit: Exit the shell.
### Execution of external commands:
##### You can run common Unix commands like ls, ps, pwd, etc.
### Commands with arguments:
##### Example: ls -l, ps -ef, etc.
### Input and output redirection:
##### Example: ls > output.txt (output redirection to a file).
##### Example: cat < input.txt (input redirection from a file).
### Combination of input/output redirection:
#### Example: cat < input.txt > output.txt.
# 7. Usage Examples
## Change directory:
````
cd /home/manar

````
## List files and redirect output:
````
ls -l > lab2.txt

````
## Display a file:
````
cat < lab2.txt

````
## Execute a command:
````
ps -ef

````
# 8. Known Issues/Limitations
## Piping (|) is not implemented in this version.
## Environment variable handling is not yet supported.
## Error messages for incorrect commands or invalid input/output redirection are basic.
## Does not handle advanced shell features like background processes (&) or command history.
# 9. Future Enhancements
## Add support for command piping (e.g., ls | grep txt).
## Implement environment variable handling (e.g., X=100).
## Enhance error handling and reporting for better user experience.
# 10. Contact Information
## If you encounter any issues or have questions, please contact me at: [Your Email Address].
