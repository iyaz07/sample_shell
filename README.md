# The simple shell
## What is Shell?
* A shell is a special user program that provides an interface for the user to use operating system services. Shell accepts human-readable commands from users and converts them into something which the kernel can understand. It is a command language interpreter that executes commands read from input devices such as keyboards or from files. The shell gets started when the user logs in or starts the terminal.

## How to:-
### Build:
* To build this program, you'll need a Unix-like operating system/enviroment, good knowledge of the C language, the C compiler (e.g., gcc). You can check if you have a C compiler installed by running gcc --version.

### Run:
* To run the program, simply execute the simple_shell binary. This will start the shell and display a prompt ($ ) indicating that it's ready to accept commands.

### Test:
* To run the tests, you'll need to have the check unit testing framework installed. You can install it on Ubuntu or Debian-based systems by running sudo apt-get install check.
* Once you have check installed, run make test to build and run the tests.

## Overview:
### This simple shell supports the following features:

* Command execution: You can execute any command that's available in your system's $PATH.
* Piping: You can pipe the output of one command to another command, e.g., ls | grep foo.
* Redirection: You can redirect the output of a command to a file, e.g., ls > files.txt.
* Background execution: You can run a command in the background by appending & to the command, e.g., sleep 10 &.
* Environment variables: You can read and set environment variables using the export command, e.g., export MYVAR=hello.
* Built-in commands: The shell supports a few built-in commands, such as cd, pwd, and exit.
