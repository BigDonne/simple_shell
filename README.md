# 0x16. C - Simple Shell
## Description

The simple shell project by ALX Africa Software Engineering is carefully planned and engineered to get individuals to understand how the shell operates and functions are working behind the scene that enables output seen.

The "Gates of shell"  project is done in the first trimester of the program where students are exposed to the C language through project based tasks that helps 
student to understand the advanced concepts behind the shell scripting and processing program which include system processes, system call, 
bit manipulation, file managment, error handling...
Shell is a simple UNIX command interpreter that replicates functionalities of the simple shell (sh).

This program was written entirely in C Language.
**Description**
This is a shell written in C. It is based on the Thompson Shell.

**Environment** :
Our shell was built and tested on Ubuntu 14.04 LTS.

**Features**
. Display a prompt and wait for the user to type a command. A command line always ends with a new line.
. If an executable cannot be found, print an error message and display the prompt again.
. Handle errors.
. Hndling the “end of file” condition (Ctrl+D)
. Hanling the command line with arguments
. Handle the PATH
. Support the exit features and the exit status
. Handle the Ctrl-C to not terminate the shell
. Handling the command seperator ;
. Handling && and || logical operators
. Handle variable replacements $? and $$
. Handle the comments #
. Support the history feature
. Support the file input

**Builtins**
Our shell has support for the following built-in commands:

|Command |	Definition
|exit [n] |	Exit the shell, with an optional exit status, n.
|env |	Print the environment.
|setenv [var][value] |	Set an environment variable and value. If the variable exists, the value will be updated.
|alias[name[='value]] |	Reads aliases name
|unsetenv [var] |	Remove an environment variable.
|cd [dir] |	Change the directory.
|help [built-in] |	Read documentation for a built-in.
**Installation : Getting HSH**

Clone the below repository and compile the files into an executable using the GCC compiler.
[Github repo](https://github.com/BigDonne/simple_shell.git)

**COPYRIGHT**
Copyright (C) 2023 by 
All rights reserved.

**Basic usage** 💡
. First, Fork this Repository Learn how to fork repo.
. Then Clone Learn how to clone.
. Create an executable by running the following command:
. gcc -Wall -Werror -Wextra -pedantic .c -o hsh
. From there, type in the following command and press your enter button.
. ./hsh
. Final step: ENJOY!

**Contributor**
. Donne Yawson Agbesi
. David Kwamena Abew-Baidoo

**Acknowledgments**
The creators of the C language.
Betty Holberton | Alx-Africa .
