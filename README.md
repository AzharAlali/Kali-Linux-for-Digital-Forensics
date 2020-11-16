# Kali-Linux-for-Digital-Forensics
---

### Contributors: 
- [Azhat Alali](https://github.com/AzharAlali) [Deomonstration link](https://app.vidgrid.com/view/qTDzEdwa5dzg)
- <img src="https://github.com/AzharAlali/Kali-Linux-for-Digital-Forensics/blob/main/pp.jpg" with=100 height=100> [Susan Maharjan](https://github.com/susanmaharjan) - [Demonstration Link](https://app.vidgrid.com/view/FogyTSu14dhS)

- [Samuel Eagan](https://github.com/samueleagan) - [Demonstration Link](https://youtu.be/8NvbWOsYIos)
---
### Sub-Topics
- [Azhat Alali](https://github.com/AzharAlali) - Linux common comands- how to create "Hello World" in C language using Linux.  
- [Susan Maharjan](https://github.com/susanmaharjan)- show how to download, install, set up and run shell command
- [Samuel Eagan](https://github.com/samueleagan) - Overview examples of preinstalled applications and their uses

---
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
- Go step by step by as in the [How to install kali linux](https://app.vidgrid.com/view/FogyTSu14dhS) video.

- First install virtual box.
- Then download ISO file for kali linux.
- Then start virtual box and create virtual machine. Here you need to define file type as linux and use Debien(64-bit) as version.
- After that set up the space and location.
- Then you need to go to the settings and upload the kali linux ISO file before starting the virtual machine.
- Now you can start and install kali linux in your virtual machine.
- We will choose graphical instalation as our process to install.
- Then choose language, country, language type as you prefer.
- Then give a host name.
- You  can leave the domain name as blank if there is no domain name.
- Then give a user name. I gave susan.
- also give an account name. I gave susan. also setup password. This username and password will allow you to enter kalilinux once it is installed. 
- Then choose the time zone. I choosed central time.
- In partetioning part coose everything as defult except change write partetioning disk to yes.
- Then I have left the Kali linux software selection to defult but you can choose as you want.
- In GRUB boot loader choose the secon option that looks like directories.
- Then finish the instalation.
- After that use the username and password that we created to get to kali linux.
- Then you can go to the command prompt and use the Kali linux commands.

### Reference
[https://www.youtube.com/watch?v=V_Payl5FlgQ&t=919s](https://www.youtube.com/watch?v=V_Payl5FlgQ&t=919s)
---
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
---
# Preinstalled Applications

Kali Linux comes preinstalled with many different applications that have usage in Digital Forensics. Some examples of these are:

| Program | Description |
| --- | --- |
| [Wireshark](https://www.wireshark.org/) | A tool for scanning and analyzing network traffic. |
| [Binwalk](https://tools.kali.org/forensics/binwalk) | A program that can be used to scan binary files for code and files. |
| [HashDeep](http://md5deep.sourceforge.net/) | A program that can be used to auto hash files in multuple different hasing algorithms. |

You can find more examples of these tools at [Linux Hint - Kali Linux Top Forensic Tools (2020)](https://linuxhint.com/kali_linux_top_forensic_tools/) and programs related to hacking at [GeeksforGeeks - Top 10 Kali Linux Tools For Hacking](https://www.geeksforgeeks.org/top-10-kali-linux-tools-for-hacking/)
