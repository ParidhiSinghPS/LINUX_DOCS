# LINUX
<img src ="/ASSESTS/Linux.jpeg">

# TABLE OF CONTENT
- Introduction to Linux
- Installation and Setup
- Linux Distribution
- Difference between Linux and Unix
- Architecture of Linux
- Basic Commands
- File System Heriarchy
- Networking Commands
- File Editor in Linux
- User and Group
- Partition
- Shell

## LINUX HISTORY
A popular open-source operating system is Linux. It was first made by Linus Torvalds in 1991 when he was studying computer science at the University of Helsinki in Finland. He started Linux as a personal project. The name "Linux" comes from combining Linus (his first name) and Unix, which was the inspiration for his work.

Back then, most operating systems were owned by companies and cost a lot of money. Torvalds wanted to make an operating system that anyone could use for free. So, he released Linux as free software under the GNU General Public License. This meant anyone could use, change, and share the source code.

Nowadays, Linux has many versions called distributions.

- Ubuntu
- Fedora
- Arch
- Plasma
- KDE
- Mint
- Manjaro

## INTRODUCTION TO LINUX

### LINUX:-
- Linux is a free and open-source operating system.
- Its main part is called the Linux kernel.
- It's similar to Unix, so it's often called Unix-like.
- Linux connects the computer hardware to the user and runs programs.
- Linux is an operating system, like Windows or macOS, that works on computers and other devices.
- It's free to use, and anyone can modify or enhance it because its code is open for everyone to see and change.
- It's well-liked because it's very dependable, safe, and can run on lots of different devices, from computers and laptops to servers and smartphones.

### KEY FEATUREOF LINUX:-
- Open Source: Linux lets anyone access and modify its source code freely, allowing for customization and sharing.
- Multi-user Capability: Many people can use a Linux system at the same time, sharing resources like memory and programs.
- Multitasking: Linux can handle multiple tasks or jobs running simultaneously without problems.
- Security: Linux is known for being very secure, with features like user passwords, controls on who can access what, and strong encryption to keep data safe.
- Portability: Linux can run on many different kinds of computers, from small laptops to big supercomputers, without any issues.
- Stability and Reliability: Linux systems are famous for staying stable and not crashing even when they're used for a long time.
- Networking: Linux is great at connecting computers together and is often used to run big networks and servers for websites and other services.
- Command Line Interface (CLI): Linux has a powerful command line where you can type text commands to control the computer, although it also has graphical interfaces for those who prefer them.

### WHY WE USE LINUX ?

There are several reasons why one might choose to use Linux:

- Open-source: Linux is open-source software. This means anyone can use, change, and share the code for free. It has a big community of developers who help improve and maintain it.
- Customizability: Linux is very customizable. Users can easily install and set up different software to fit their needs.
- Stability and security: Linux is known for being stable and secure. It doesn't crash often and is less likely to get viruses compared to other operating systems.
- Cost-effective: Linux is free to download and use, which makes it a budget-friendly choice for both individuals and businesses.

### LINUX ADVANTAGE:- 
1. Cost-Effective:
        Linux and most of its software are free to use, which saves money on licensing fees. 
        You can download a wide range of high-quality software for different tasks without any cost.

2. Reliable and Stable:
        Linux doesn't need frequent reboots to maintain its performance.
        It's less likely to freeze or slow down over time due to memory issues compared to other operating systems.
        It can run continuously for long periods without needing a restart.

3. Performance:
        Linux delivers consistent high performance, whether on individual computers or across networks.
        It handles multiple users simultaneously without slowing down.
        It's efficient enough to make older computers functional again.

4. Network Capabilities:
        Linux was designed with strong support for networking tasks.
        It's easy to set up both client and server systems on Linux platforms.
        Tasks like network backups are faster and more reliable compared to other systems.

5. Versatility:
        Linux can be used for various purposes, from running powerful servers to desktop computers and even embedded systems.
        You can customize installations to include only the software components you need, which saves disk space.
        It allows selective installation of specific applications rather than entire software packages.

6. Compatibility:
        Linux runs software developed for Unix systems.
        It supports a wide range of file formats commonly used across different computing platforms.

### LINUX DIFFERENCE BETWEEN UNIX AND LINUX

| Aspect          |           LINUX                                  |   UNIX                                        |
|--------------   |-----------------------------------------------   |--------------------------------                       |
|Definition       | OS which is freely available.                    | OS which can be only used by its copyrighters.|
|Examples         | Linux has different versions called distros.     | IBM AIX, HP-UX and Sun Solaris.                                                            |
|Operating system | Linux is just the kernel.                        | Unix is a complete package of Operating System.                                                             |
|Usage            | Servers,PC,tablets to mainframes & supercomp.    | Servers, workstations and PCs.                              |
|Cost             | It is freely distributed and downloaded.         | Different costs for their respective Unix OS.               |
|Support 	  | Linux supports more file system than Unix.       | It also supports file system but lesser than Linux.            |                 

## INSTALLATION AND SETUP

### Things You Should Know

- To install any version of Linux, you'll need to create a bootable USB drive or CD.
- You can either install Linux alongside your current operating system (dual-boot) or replace your current operating system with Linux.
- There are many different Linux distributions to choose from.

### PART 1:- Creating a Bootable USB Drive
- Download an ISO file for a Linux distribution.
- There are many different Linux distributions available, each designed for specific purposes.
- Visit the official website of the distribution you want and download the ISO file. Here are some Linux distributions you can choose from:

- Ubuntu: Ubuntu is one of the most popular Linux distributions. It is user-friendly and easy to learn, making it suitable for both experienced and beginner Linux users. You can download Ubuntu from: [https://ubuntu.com/download/desktop]

### PART 2:- Create a Bootable USB stick
- To install Ubuntu Desktop, you need to use special software to write the downloaded ISO file to a USB stick, creating the installation media.
- Simply copying the ISO file to the USB stick won't work.
- We'll use balenaEtcher because it works on Linux, Windows, and Mac OS.
- Download and install the version of balenaEtcher that matches your current operating system.
- Select the ISO file you downloaded, choose your USB flash drive, and then click "Flash!" to create the installation media.
- 
### PART 3:-Boot from USB flash drive
- Insert the USB flash drive into the laptop or PC you want to use to install Ubuntu. 
- Then, either turn on the device or restart it. It should detect the USB drive automatically. 
- If it doesn't, hold down the F12 key while the computer is starting up and choose the USB drive from the boot menu.
- (Press F12 for the boot menu on most computers. If not, try Escape, F2, or F10. Look for a quick message when your computer starts to know which key to press.)
  
- Once the installer starts up, you'll be asked to select your language.
<img src ="/ASSESTS/choose language.jpeg" alt="choose language">

- Then, you'll be given the option to choose any accessibility settings you need.
<imf src ="/ASSESTS/accessibilit.jpeg">

- Your keyboard layout.
<img src ="/ASSESTS/keyboard layout.jpeg">

- Next, you'll connect to your network.
<img src ="/ASSESTS/internet connection.jpeg">

- Next, you'll have the option to either try or install Ubuntu.
(If you click "Try Ubuntu," you can test out Ubuntu without making any changes to your computer. You can go back to the installer menu anytime by clicking the "Install Ubuntu" shortcut on the desktop)
<img src = "/ASSESTS/try to install.jpeg">

- To proceed, click Install Ubuntu.

### PART 4:- Installation Setup
- When installing Ubuntu, you'll be asked to choose between Interactive and Automated installation.
- Interactive is the usual choice where you guide the installation step by step.
- Advanced users might prefer Automated installation. This option lets you use a configuration file from a web server to set up multiple installations in a standard way.
- It also allows for additional customizations.
<img src ="/ASSESTS/types of installation.jpeg">

- When installing Ubuntu, you'll choose between Default and Extended selections.
- The Default option gives you the essentials to start with, and you can add more apps later from the App Center.
- The Extended option includes extra office tools and utilities, handy when you're offline.
<img src ="/ASSESTS/application.jpeg">

- Check both boxes to install third-party software for better device support and media format compatibility.
<img src = "/ASSESTS/optimise your computer.jpeg">

### PART 5:-  Type of installation
- Choose "Erase disk and install Ubuntu" if you want Ubuntu to be the only operating system on your hard drive.
- If your device already has another operating system installed, you'll get options to install Ubuntu alongside it instead of replacing it.
<img src = "/ASSESTS/disk setup.jpeg">

### Installing Ubuntu alongside another operating system.
- If you choose this option, you'll see a simple interface to select the drive and adjust how much space Ubuntu will use, without overwriting existing files.
<img src ="/ASSESTS/manual partition.jpeg">

### Erase disk and install Ubuntu
- If you select this option Ubuntu will take up the entire disk space on the selected drive.
<img src ="/ASSESTS/earse disk.png" >
- If your PC has multiple hard drives, you can install Ubuntu alongside another OS, each on its own drive. Be careful to select the correct drive!
<img src ="/ASSESTS/advanced feature.jpeg">

- LVM stands for Logical Volume Management. Using LVM during setup makes it simpler to create and manage partitions after installation.
<img src = "/ASSESTS/disk passphrase.jpeg">

<img src = "/ASSESTS/maual partioning.png">

- If you select encryption, keep your security key safe. You can't access your data without it!
  
### Manual partitioning
- Manual partitioning is for advanced users who want specific configurations. We won't cover detailed setups in this tutorial.
- Here, users can view all existing drives and partitions, and create and manage new partition setups and configurations.

### (Alert) Windows BitLocker is enabled
- If Windows BitLocker is enabled, Ubuntu may not install safely alongside it.
- You'll need to disable BitLocker in Windows before restarting the Ubuntu installer.
<img src ="/ASSESTS/bitlocker ended.png">

- You don't have to disable Windows BitLocker if you're erasing Windows entirely or using a separate, unencrypted drive for Ubuntu. 

### PART 6:- Create Your Login Details
- On this screen, you'll enter your name and choose a name for your computer on the network.
- Then, create a username and a strong password.
- You can set your computer to log in automatically or require a password.
- If you travel with your device, it's best to keep "Require my password to log in" enabled for security.
<img src ="/ASSESTS/create login details.jpeg">

### PART 7:- Choose your Location
- Choose your location and time zone from the map screen, then click Continue.
- If you're connected to the internet, this information will be detected automatically.
<img src ="/ASSESTS/select time zone.jpeg">

### PART 8:- Ready to install
- Clicking Next will show you a summary of your installation settings. 
- You can review everything before clicking Install to begin the installation process.
<img src ="/ASSESTS/ready to install.jpeg">

- (If you selected to import an auto install configuration, you'll confirm its installation on this screen.)
- (Once you proceed, Ubuntu will begin the installation process will begin.)

### PART 9:- Complete the Installation
- Sit back and enjoy the slideshow as Ubuntu installs in the background!
<img src ="/ASSESTS/fast and free.jpeg">

- Alternatively you can see a detailed output of the installation process by clicking the icon in the bottom right corner of the window.
- Once the installation has completed, you will be prompted to restart your machine.
- Click Restart Now.
<img src ="/ASSESTS/installation completed.jpeg">

- When you restart, you will be prompted to remove your USB flash drive from the device. Once you’ve done this, press ENTER.
<img src ="/ASSESTS/enter.png">

- Enter your encryption password if you created one.
<img src ="/ASSESTS/enter your password.png">

- This is then followed by the login screen, where you can enter your username and password.
<img src ="/ASSESTS/userame and password.png">

- And that’s it, welcome to your new Ubuntu Desktop!
<img src ="/ASSESTS/new ubuntu desktop.jpeg">

- Downloading additional apps from Ubuntu Software.
<img src ="/ASSESTS/ready to go.jpeg">

### PART 10:- Don’t forget to Update!
- After installing Ubuntu, it's a good idea to update your system to make sure everything is current and running smoothly.
<img src ="/ASSESTS/software-updater.png">

### PART 11:- You’ve installed Ubuntu!
- I hope you enjoy your new desktop.

## LINUX DISTRIBUTION (OPERATING SYSTEM) NAMES:-
A few popular names:-
- 1. Redhat Enterprise Linux
- 2. Fedora Linux
- 3. Debian Linux
- 4. Suse Enterprise Linux
- 5. Ubuntu Linux

## COMMON THINGS BETWEEN LINUX AND UNIX :-
- Both share many common applications such as:
- 1.GUI, file, and windows managers.
- 2.Shells 
- 3.Various office applications such as OpenOffice.org
- 4.Development tools ( php, python, GNU c/c++ compiler)
- 5.Posix interface

## LAYERED ARCHITECTURE OF LINUX
<img src ="/ASSESTS/architecture-of-linux.png">

- Linux System Architecture is consists of following layers:-
- Hardware layer - Hardware consists of all peripheral devices (RAM/ HDD/ CPU etc).
- Kernel - Core component of Operating System, interacts directly with hardware,provides low level services to upper layer components.
- Shell - An interface to kernel, hiding complexity of kernel's functions from users. Takes commands from user and executes kernel's functions.
- Utilities - Utility programs giving user most of the functionalities of an operating systems.

## BASIC COMMANDS OF LINUX
- 25 Basic Linux Commands For Beginners:-
1. ls command in Linux
- Displays information about files in the current directory.
2.  pwd command in Linux
- Displays the current working directory.
3. mkdir command in Linux
- Creates a directory.
4. cd command in Linux
- To navigate between different folders.
5. rmdir command in Linux
- Removes empty directories from the directory lists.
6. cp command in Linux
- Copy files from one directory to another.
7. mv command in Linux
- Rename and Replace the files
8. rm command in Linux
- Delete files
9. uname command in Linux
- Command to get basic information about the OS
10. touch command in Linux
- Create empty files
11. vi command in Linux
- Edits the file.
12. cat command in Linux
- Display file contents on terminal
13. clear command in Linux
- Clear terminal 
14. ps command in Linux
- Display the processes in terminal
15. wget command in Linux
- download files from the internet.

## LINUX FILE SYSTEM 
- The file system hierarchy in Linux is a structure that organizes files and directories in a tree-like format.
- Here is a simplified overview of the key directories and their purposes:

### 1. / – Root
- Every single file and directory starts from the root directory.
- Only root user has write privilege under this directory.
- Please note that /root is root user’s home directory, which is not same as /.

### 2. /boot
- Having files used by boot loader.

### 3. /sbin – System Binaries
- Just like /bin, /sbin also contains binary executables.
- But, the linux commands located under this directory are used typically by system aministrator, for system maintenance purpose.

### 4. /etc – Configuration Files
- Contains configuration files required by all programs.
- This also contains startup and shutdown shell scripts used to start/stop individual programs.

### 5. /dev – Device Files
- Contains device files.
- These include terminal devices, usb, or any device attached to the system.

### 6. /proc – Process Information
- Contains information about system process.
- This is a pseudo filesystem contains information about running process. For example: /proc/{pid} directory contains information about the process with that particular pid.
- This is a virtual filesystem with text information about system resources. For example:/proc/uptime.
  
### 7. /var – Variable Files
- var stands for variable files.
- Content of the files that are expected to grow can be found under this directory.
- This includes — system log files (/var/log); packages and database files (/var/lib);emails (/var/mail).
### 8. /tmp – Temporary Files
- Directory that contains temporary files created by system and users.
- Files under this directory are deleted when system is rebooted.

### 9. /usr – User Programs
- Contains binaries, libraries, documentation, and source-code for second level programs.
- /usr/bin contains binary files for user programs. 
- /bin, look under /usr/bin. 
- /usr/sbin contains binary files for system administrators.
- /usr/lib contains libraries for /usr/bin and /usr/sbin.
- /usr/local contains users programs that you install from source. 

### 10. /home – Home Directories
- Home directories for all users to store their personal files.
- For example: /home/john, /home/nikita

## NETWORKING COMMANDS
- These are most useful commands for quickly troubleshooting connection issues on a Linux server, such as checking if a system is connected or if a host is responding.
- These tools save a lot of time, especially when fixing connectivity for advanced trading systems.
- Finding host/domain name and IP address - hostname
- Test network connection – ping
- Getting network configuration – ifconfig
- Network connections, routing tables, interface statistics – netstat
- Query DNS lookup name – nslookup

## How to create a file
   We can create a file in two ways:-
### 1. cat command
-  cat linux command concatenates files and print it on the standard output.
### 2. touch command
- Create an empty file.
- Create multiple file.
- Change a timestamp a file.
- Update only access time of file and modify time of file.

## File Editors in Linux 
- Command-Line Editors

1. nano:-Easy to use.
        -Simple and user-friendly.
        -Command: nano filename.

2. vi / vim:-Powerful, extensive shortcuts.
            -Powerful and widely used.
            -Command: vi filename or vim filename.

## USERS AND GROUPS
-  USERS:- A person who use the computer.
1. PREVILEGE USER:- It is a Super user and it has a full power.
2. NON-PREVILEGE USER:- It has a less power.
3. SYSTEM USER:- It make automatically.

## PARTITION 
- What is a Partition?
- A partition is a way to divide a hard disk drive (HDD) or solid-state drive (SSD) into separate sections. Each section acts like an independent drive.
  
### - Types of Partitions

    1. Primary Partitions:
        - You can have up to 4 primary partitions on a single disk.
        - One of these can be an extended partition to allow for more partitions.

    2. Extended Partitions:
        - This is a special type of primary partition.
        - It can hold multiple smaller sections called logical partitions.
        - This lets you have more than 4 partitions on a single disk.

    3. Logical Partitions:
        - These are the sections inside an extended partition.
        - There is no limit to how many logical partitions you can have.

## SHELL
- A shell is a program that acts as the interface between you and the UNIX system, allowing you to enter commands for the operating system to execute.

### Some of the essential basic shell commands in Linux include:

### cd (Change Directory): 
    - Allows navigation between directories. For instance, cd moves into a specific directory, while cd .. moves up one level in the directory structure.
### ls (List): 
    - Lists the contents of a directory. ls -l provides a detailed list with permissions, ownership, size, and modification date.
### mkdir (Make Directory): 
    - Creates a new directory. For example, mkdir creates a directory with the specified name.
### cp (Copy): 
    - Copies files or directories from one location to another. Syntax: cp .
### rm (Remove): 
    - Deletes files or directories. Use rm to remove a file and rm -r for recursive deletion of directories.
### cat (Concatenate): 
    - Displays the contents of a file in the terminal. cat shows the entire content of the specified file.
### grep (Global Regular Expression Print): 
    - Searches for specific text patterns within files. For example, grep "search_term" looks for occurrences of "search_term" in the specified file.

## REFRENCE lINKS
- https://www.geeksforgeeks.org/linux-history/
- https://www.geeksforgeeks.org/basic-linux-commands/
- https://www.javatpoint.com/linux-networking-commands
- https://www.javatpoint.com/architecture-of-linux
