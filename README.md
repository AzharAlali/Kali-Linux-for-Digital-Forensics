# Kali-Linux-for-Digital-Forensics


### Contributors: 
- [Azhat Alali](https://github.com/AzharAlali)
- [Susan Maharjan](https://github.com/susanmaharjan)
- [Samuel Eagan](https://github.com/samueleagan) 

### Sub-Topics
- [Azhat Alali](https://github.com/AzharAlali) - Linux common comands- how to create "Hello World" using C language with Linux.  
- [Susan Maharjan](https://github.com/susanmaharjan)- show how to download, install, set up and run shell command
- [Samuel Eagan](https://github.com/samueleagan) - Overview of preinstalled applications and their uses


# How to download Kali Linux for Digital Forensics

## Pre-requisites

- Virtual Machine- Oracle VM Virtual Box  

- ISO file of Kali Linux (This file is round 3 gb so it may take some time)

### How to install virtual box

- Go to this link- [https://www.virtualbox.org/](https://www.virtualbox.org/)
- Then click Downloads in the left side.
- Then Click on windows Host link. And follow the steps to install Virtual box.

OR

- Do it through Chocolatey
- Open PowerShell.
- Then install virtual box with the following command
- ```choco install virtualbox```

### How to download Kali Linux ISO file for Windows

- Go to this link- [https://www.kali.org/downloads/](https://www.kali.org/downloads/)
- Click Kali Linux 64-Bit (Installer)

### Steps to install Kali Linux in the virtual machine


## Common Linux commands 

| Command | Description |
| --- | --- |
| mkdir | Create directory |
| rmdir  | remove directory  | 
| nano | create a file | 
| pwd	| It stands for "Print Working Directory" which prints the name of the working directory |
| users	| It will display login names of the user currently logged in to the system |
|  cat	| It is used to create single or multiple files, view contained file, concatenate files, and redirect output in terminal or files | 
| cd	| It is used to change or switch the current working directory | 
| cp	| It is used to copy files |


## How to create "Hello World" in C 

```
#include <stdio.h>
int main() {
   // printf() displays the string inside quotation
   printf("Hello, World!");
   return 0;
}
```
# Output 
``` 
Hello, World!
```

How "Hello, World!" program works?
- `#include` is a preprocessor command that tells the compiler to include the contents of stdio.h (standard input and output) file in the program.
- `stdio.h`  file contains functions such as scanf() and printf() to take input and display output respectively.
- `printf()` is function without writing `#include <stdio.h>`, the program will not compile.
- The execution of a C program starts from the `main()` function.
- `printf()` is a library function to send formatted output to the screen. In this program, `printf()` displays Hello, World! text on the screen.
- `return 0;`  statement is the "Exit status" of the program. In simple terms, the program ends with this statement.
