[linux.txt](https://github.com/user-attachments/files/16746692/linux.txt)[02-FileSystem.pdf](https://github.com/user-attachments/files/16746650/02-FileSystem.pdf)

     [Uploading*Linux is a free, open-source operating system that's known for its reliability, security, and flexibility. It's used in many devices and enterprise solutions, and has a large community for support and development. Linux is made up of a kernel that manages hardware resources, multitasking, and more. It also has a command-line environment that users can use to operate and configure the system. 

*The Linux kernel manages hardware resources, multitasking, and other aspects of computing devices. Understanding how the kernel works can help you understand the need for operating systems.
*Open source
Anyone can access and modify Linux, allowing users and developers to customize it to their needs.
*Shell
A shell is an interpreter that understands user commands and passes them on to the computer for processing. Shells also allow users to run a set of commands and user settings from a file called a shell script.
*Command line
Linux's command-line environment is a powerful way to operate and configure the system. Knowing a variety of commands is important for effective system administration and day-to-day operations. 
1.structure:-
The Linux architecture is highly modular and configurable, offering a high degree of customization and flexibility to users and developers. It is a layered structure comprising several components, including the kernel, system libraries, system calls, shell, applications, graphical user interface, and device drivers.

2.file syatem:-Linux file system is generally a built-in layer of a Linux operating system used to handle the data management of the storage. It helps to arrange the file on the disk storage. It manages the file name, file size, creation date, and much more information about a file.

basic linux commands and utilites:-
A:-  https://users.soict.hust.edu.vn/linhtd/courses/CompLit_EN/part01-linux/02-FileSystem.pdf (for commands )
     *https://www.geeksforgeeks.org/introduction-to-linux-operating-system/ (importantsite )
B:-A utility of the Linux OS is the Linux Command. All primary and advanced tasks can be done by executing commands. The commands are performed on the Linux terminal. The terminal is a command line similar to the command prompt in Windows OS. Commands in Linux are case-sensitive.

What is Linux Operating System?
==>The Linux Operating System is a type of operating system that is similar to Unix, and it is built upon the Linux Kernel. The Linux Kernel is like the brain of the operating system because it manages how the computer interacts with its hardware and resources. It makes sure everything works smoothly and efficiently. But the Linux Kernel alone is not enough to make a complete operating system. To create a full and functional system, the Linux Kernel is combined with a collection of software packages and utilities, which are together called Linux distributions. These distributions make the Linux Operating System ready for users to run their applications and perform tasks on their computers securely and effectively. Linux distributions come in different flavors, each tailored to suit the specific needs and preferences of users.

==>Linux File Hierarchy Structure

The Linux File Hierarchy Structure or the Filesystem Hierarchy Standard (FHS) defines the directory structure and directory contents in Unix-like operating systems. It is maintained by the Linux Foundation. 

In the FHS, all files and directories appear under the root directory /, even if they are stored on different physical or virtual devices.
Some of these directories only exist on a particular system if certain subsystems, such as the X Window System, are installed.
Most of these directories exist in all UNIX operating systems and are generally used in much the same way; however, the descriptions here are those used specifically for the FHS and are not considered authoritative for platforms other than Linux. 

basic linux file system :-
/bin ==> basic programs (ls,cd, mv etc )
/sbin ==>>system programs (sysctl,mkfs etc )
/etc ==>> configration files 
/tem ==>> temprory files
/user/bin ==>> applications (apt, nmap, etc )
/user/share ==>> application support and data files 
/home ==>> personal directories of users 
/root ==>> home directory of super user (admin)

commanly used commands in linux :--
*mkdir 
 pwd 
 ls
 help
 man - manual 
 cat - read file or folder 
 sudo su - root user
 gedit- file editor software 
 chmod- change directory permission 
nano - linux file editior 
 dir - works same as ls
 mv -move a file or folder 
 cp - copy a file or folder
 rm- remove (delete) file or folder
   

 linux.txt…]()

 
