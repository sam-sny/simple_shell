Simple Shell Project

This project is a simple UNIX command line interpreter, or "shell", written in the C programming language.
Usage

To use the shell, simply run the simple_shell executable. The shell will display a prompt and wait for you to type a command. After executing the command, the shell will display the prompt again for the next command.
Features

The shell has the following features:

    Displays a prompt and waits for the user to type a command
    Executes simple commands with arguments
    Handles the PATH environment variable to find executables
    Implements the built-in exit command to exit the shell
    Implements the built-in env command to print the current environment
    Implements the built-in cd command to change the current directory
    Handles the ;, &&, and || command separators and logical operators
    Implements the alias command to define and print aliases
    Handles variables replacement for $? and $$ variables

Requirements

The shell was developed and tested on a Linux operating system using the GNU C Compiler (gcc).
Installation

To install the shell, simply clone the repository and compile the simple_shell.c file using the gcc compiler:

shell

$ git clone https://github.com/your-username/simple-shell-project.git
$ cd simple-shell-project
$ gcc -Wall -Werror -Wextra -pedantic simple_shell.c -o simple_shell

