# A Simple Shell Project

This is a SimpleShell project written in C. THe shell imitates a basic shell (unix environment) that allows you to execute commands and manage processes.

## Features

- Execute shell commands and programs
- Handle basic shell functionalities (e.g., changing directories, environment variables)
- Support for command execution in the background
- Built-in commands (e.g., `cd`, `exit`, `ls`)

## Getting Started

### Prerequisites

- GCC Compiler
- Unix-like operating system (Linux, macOS)

### Clone the Repository
Clone into the repository by putting this into your terminal;
```shell
git clone https://github.com/NatashaMuhanji/simple_shell.git 
```

### Compile the Code
After cloning, change into the directory;
```
cd simple_shell
```
after which you will run this while in the repository;
```
gcc -Wall -Werror -Wextra -pedantic *.c -o
```

### Run the Shell
To work the shell in interactive mode, run `./hsh`
```
./hsh
```

### Usage
Once the shell is up and running, you can enter commands just like in a regular shell.
Some examples include:

- Executing a program: ls -l
- Changing directories: cd /path/to/directory
- Exiting the shell: exit

### Customization
You can customize the shell by modifying the source code.
Feel free to explore the code and add additional features or functionality according to your needs.

## Contributors
- Anncarl Mwendwa
- Natasha Muhanji

