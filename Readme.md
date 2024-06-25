# LINUX
<img src ="/ASSESTS/Linux.jpeg">

# TABLE OF CONTENT
- Introduction to Linux
- Installation and Setup
- Linux Distribution
- Common things between Linux and Unix
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
|Operating system | Linux is just the kernel.                        | Unix is a complete package of O.Sperating system.                                                             |
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
- Next, you'll connect to your network. This lets Ubuntu download updates and third-party drivers, like NVIDIA graphics drivers, while it installs.
<img src ="/ASSESTS/internet connection.jpeg">
- Next, you'll have the option to either try or install Ubuntu.
(If you click "Try Ubuntu," you can test out Ubuntu without making any changes to your computer. You can go back to the installer menu anytime by clicking the "Install Ubuntu" shortcut on the desktop)
<img src = "/ASSESTS/try to install.jpeg">
- To proceed, click Install Ubuntu.
(Some PCs use Intel RST (Rapid Storage Technology), which Ubuntu doesn't support. If you see this message, you won't be able to continue unless you disable RST in your computer's BIOS menu. For help, visit help.ubuntu.com/rst.)

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
Let’s take a moment to review all of the above options in detail.

### Installing Ubuntu alongside another operating system.
- If you choose this option, you'll see a simple interface to select the drive and adjust how much space Ubuntu will use, without overwriting existing files.
- This view picks the largest partition automatically. For more control, switch to Manual partitioning below.
<img src ="/ASSESTS/manual partition.jpeg">

### Erase disk and install Ubuntu
- If you select this option Ubuntu will take up the entire disk space on the selected drive.
<img src ="/ASSESTS/earse disk.png" >
- If your PC has multiple hard drives, you can install Ubuntu alongside another OS, each on its own drive. Be careful to select the correct drive!
- You can encrypt your entire drive for security. Before proceeding, go to Advanced features and select 'Encrypt the new Ubuntu installation.'
<img src ="/ASSESTS/advanced feature.jpeg">
* LVM stands for Logical Volume Management. Using LVM during setup makes it simpler to create and manage partitions after installation.
* ZFS allows users to create storage pools that use multiple drives together. It also supports snapshots and data repair, making it a powerful choice for advanced users.
- If you choose LVM or ZFS encryption, you'll need to create a security key. You'll need to enter this key when you start your computer before logging in with your username and password.
<img src = "/ASSESTS/disk passphrase.jpeg">
- If you're using TPM-based Full Disk Encryption, after installation, you'll need to run the command `snap recovery --show-keys` to generate a recovery key.
<img src = "/ASSESTS/maual partioning.png">
- If you select encryption, keep your security key safe. You can't access your data without it!
### Manual partitioning
- Manual partitioning is for advanced users who want specific configurations. We won't cover detailed setups in this tutorial.
- Here, users can view all existing drives and partitions, and create and manage new partition setups and configurations.
--------------------------------------
### (Alert) Windows BitLocker is enabled
- If Windows BitLocker is enabled, Ubuntu may not install safely alongside it. You'll need to disable BitLocker in Windows before restarting the Ubuntu installer.
<img src ="/ASSESTS/bitlocker ended.png">
- You don't have to disable Windows BitLocker if you're erasing Windows entirely or using a separate, unencrypted drive for Ubuntu. More details are in the final section of this tutorial.

### PART 6:- Create Your Login Details
- On this screen, you'll enter your name and choose a name for your computer on the network. Then, create a username and a strong password.
- You can set your computer to log in automatically or require a password. If you travel with your device, it's best to keep "Require my password to log in" enabled for security.
<img src ="/ASSESTS/create login details.jpeg">
### PART 7:- Choose your Location
- Choose your location and time zone from the map screen, then click Continue. If you're connected to the internet, this information will be detected automatically.
<img src ="/ASSESTS/select time zone.jpeg">
### PART 8:- Ready to install
- Clicking Next will show you a summary of your installation settings. You can review everything before clicking Install to begin the installation process.
<img src ="/ASSESTS/ready to install.jpeg">
(If you selected to import an autoinstall configuration, you'll confirm its installation on this screen.)
(Once you proceed, Ubuntu will begin the installation process will begin.)

### PART 9:-  Complete the Installation
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
- The welcome widget will help you with some additional setup options, including:
* When you attach a free personal or paid Ubuntu Pro subscription, you get extra security patches for your device. This is only possible if you're using a long-term support (LTS) version of Ubuntu.
* If you choose to share device information with Canonical to help make Ubuntu better, they don't collect this information by default. It's only gathered if you agree to share it.
* Downloading additional apps from Ubuntu Software.
<img src ="/ASSESTS/ready to go.jpeg">

### PART 10:- Don’t forget to Update!
- After installing Ubuntu, it's a good idea to update your system to make sure everything is current and running smoothly.
- To keep your Ubuntu system up to date, use the Software Updater app. Find it in the app menu (the icon with nine squares) and it will check for and install any available updates. This ensures your system stays current and secure.
<img src ="/ASSESTS/software-updater.png">
- You can also update Ubuntu using the terminal.
- Press CTRL+ALT+T to bring up a Terminal window (or click the terminal icon in the sidebar).
- Type in:
- sudo apt update
- You will be prompted to enter your login password.
- This will check for updates and tell you if there are any that need applying. To apply any updates, type:
- sudo apt upgrade
- Type Y, then press ENTER to confirm to finish the update process.

### PART 11:- You’ve installed Ubuntu!
- We hope you enjoy your new desktop.

## LINUX DISTRIBUTION (OPERATING SYSTEM) NAMES:-
A few popular names:
1.Redhat Enterprise Linux
2.Fedora Linux
3.Debian Linux
4.Suse Enterprise Linux
5.Ubuntu Linux

## COMMON THINGS BETWEEN LINUX AND UNIX :-
- Both share many common applications such as:
1.GUI, file, and windows managers (KDE, Gnome)
2.Shells (ksh, csh, bash)
3.Various office applications such as OpenOffice.org
4.Development tools (perl, php, python, GNU c/c++ compiler)
5.Posix interface

## LAYERED ARCHITECTURE OF LINUX
<img src ="/home/adi/Paridhi_Intern/linux/ASSESTS/architecture-of-linux.png">
- Linux System Architecture is consists of following layers
* Hardware layer - Hardware consists of all peripheral devices (RAM/ HDD/ CPU etc).
* Kernel - Core component of Operating System, interacts directly with hardware,provides low level services to upper layer components.
* Shell - An interface to kernel, hiding complexity of kernel's functions from users. Takes commands from user and executes kernel's functions.
* Utilities - Utility programs giving user most of the functionalities of an operating systems.

## BASIC COMMANDS OF LINUX
- 25 Basic Linux Commands For Beginners:-
1. Is command in Linux
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
10. locate command in Linux
- Find a file in the database.
11. touch command in Linux
- Create empty files
12. in command in Linux
- Create shortcuts to other files
13. cat command in Linux
- Display file contents on terminal
14. clear command in Linux
- Clear terminal 
15. ps command in Linux
- Display the processes in terminal
16. man command in Linux
- Access manual for all Linux commands
17. grep command in Linux
- Search for a specific string in an output
18. echo command in Linux
- Display active processes on the terminal
19. wget command in Linux
- download files from the internet.
20. whoami command in Linux
- Create or update passwords for existing users
21. sort command in Linux
- sort the file content
22. cal command in Linux
- View Calendar in terminal
23. whereis command in Linux
- View the exact location of any command typed after this command
24. df command in Linux
- Check the details of the file system
25. wc command in Linux
- Check the lines, word count, and characters in a file using different options

## LINUX FILE SYSTEM 
- The file system hierarchy in Linux is a structure that organizes files and directories in a tree-like format. Here is a simplified overview of the key directories and their purposes:

1. / – Root
- Every single file and directory starts from the root directory.
- Only root user has write privilege under this directory.
- Please note that /root is root user’s home directory, which is not same as /.

2. /bin – User Binaries
- Contains binary executables.
- Common linux commands you need to use in single-user modes are located under this directory.
- Commands used by all the users of the system are located here.
- For example: ps, ls, ping, grep, cp.

3. /sbin – System Binaries
- Just like /bin, /sbin also contains binary executables.
- But, the linux commands located under this directory are used typically by system aministrator, for system maintenance purpose.
- For example: iptables, reboot, fdisk, ifconfig, swapon

4. /etc – Configuration Files
- Contains configuration files required by all programs.
- This also contains startup and shutdown shell scripts used to start/stop individual programs.
- For example: /etc/resolv.conf, /etc/logrotate.conf

5. /dev – Device Files
- Contains device files.
- These include terminal devices, usb, or any device attached to the system.
- For example: /dev/tty1, /dev/usbmon0

6. /proc – Process Information
- Contains information about system process.
- This is a pseudo filesystem contains information about running process. For example: /proc/{pid} directory contains information about the process with that particular pid.
- This is a virtual filesystem with text information about system resources. For example:/proc/uptime.
7. /var – Variable Files
- var stands for variable files.
- Content of the files that are expected to grow can be found under this directory.
- This includes — system log files (/var/log); packages and database files (/var/lib);emails (/var/mail); print queues (/var/spool); lock files (/var/lock); temp files needed across reboots (/var/tmp);

8. /tmp – Temporary Files
- Directory that contains temporary files created by system and users.
- Files under this directory are deleted when system is rebooted.

9. /usr – User Programs
- Contains binaries, libraries, documentation, and source-code for second level programs.
- /usr/bin contains binary files for user programs. If you can’t find a user binary under
- /bin, look under /usr/bin. For example: at, awk, cc, less, scp
- /usr/sbin contains binary files for system administrators. If you can’t find a system binary under /sbin, look under /usr/sbin. For example: atd, cron, sshd, useradd, userdel
- /usr/lib contains libraries for /usr/bin and /usr/sbin.
- /usr/local contains users programs that you install from source. For example, when you install apache from source, it goes under /usr/local/apache2

10. /home – Home Directories
- Home directories for all users to store their personal files.
- For example: /home/john, /home/nikita

## NETWORKING COMMANDS
- These are most useful commands for quickly troubleshooting connection issues on a Linux server, such as checking if a system is connected or if a host is responding. These tools save a lot of time, especially when fixing connectivity for advanced trading systems.
- Finding host/domain name and IP address - hostname
- test network connection – ping
- getting network configuration – ifconfig
- Network connections, routing tables, interface statistics – netstat
- query DNS lookup name – nslookup
- communicate with other hostname – telnet
- outing steps that packets take to get to network host – traceroute
- view user information – finger
- checking status of destination host - telnet

## 15 MOST IMPORTANT LINUX NETWORKING COMMAND 
- Linux is a powerful operating system that often requires commands for effective use. 
- Some commands are restricted to regular users because they are very powerful. 
- Here are the most useful networking commands every Linux user should know:
1. ifconfig/ip: Check and set up network connections.
2. ping: Check if another computer is reachable.
3. netstat: See network connections and stats.
4. traceroute: Track the path to a network host.
5. nslookup/dig: Look up DNS information for domain names.
6. scp: Securely copy files between computers.
7. ssh: Securely connect to another computer.
8. ftp/sftp: Transfer files to and from another computer.
9. curl/wget: Download files from the internet.
10. iptables: Set up firewall rules.
11. nmap: Scan and explore networks.
12. hostname: Show or change the computer’s name.
13. route: Show or change the IP routing table.
14. whois: Get information about domain names.
15. tcpdump: Capture and analyze network traffic.

## LINUX UTILITIES 
1. File Handling
- utilities: Cat
- Command: cat linux command concatenates files and print it on the standard output.
- SYNTAX:
  The Syntax
  is
  cat [OPTIONS] [FILE]..
- OPTIONS:
-A Show all.
-b Omits line numbers for blank space in the output.
-e A $ character will be printed at the end of each line prior to a new line.
-E Displays a $ (dollar sign) at the end of each line.
-n Line numbers for all the output lines.
-s If the output has multiple empty lines it replaces it with one empty line. 
-T Displays the tab characters in the output.
-Non-printing characters (with the exception of tabs, new-lines and form-feeds)-v are printed visibly.
- Example:
To Create a new file:
          cat > file1.txt
          This command creates a new file file1.txt. After typing into the file press control+d
          (^d) simultaneously to end the file.
1. To Append data into the
     file: cat >> file1.txt
- To append data into the same file use append operator >> to write into the file,
else the file will be overwritten (i.e., all of its contents will be erased).
2. To display a
         file: cat
         file1.txt
         This command displays the data in the file.
3. To concatenate several files and
        display: cat file1.txt file2.txt

- The above cat command will concatenate the two files (file1.txt and file2.txt) and it will display the output in the screen. Some times the output may not fit the monitor screen. In such situation you can print those files in a new file or display the file using less command.
cat file1.txt file2.txt | less
4. To concatenate several files and to transfer the output to another file. cat file1.txt file2.txt > file3.txt.
In the above example the output is redirected to new file file3.txt. The cat command will create new file file3.txt and store the concatenated output into file3.txt

2. rm COMMAND: rm linux command is used to remove/delete the file from the directory.
- SYNTAX:
        The Syntax is
             rm [options..] [file | directory]
- OPTIONS:
-f Remove all files in a directory without prompting the user.
-i Interactive. With this option, rm prompts for confirmation before removing any files.
-r (or) -R Recursively remove directories and subdirectories in the argument list. The directory will be emptied of files and removed. The user is normally prompted for removal of any write-protected files which the directory contains.
- EXAMPLE:
1. To Remove / Delete a
         file: rm file1.txt
         Here rm command will remove/delete the file file1.txt.
2. To delete a directory tree:
         rm -ir tmp
        This rm command recursively removes the contents of all subdirectories of the tmp directory, prompting you regarding the removal of each file, and then removes the tmp directory itself.
3. To remove more files at
         once rm file1.txt file2.txt
         rm command removes file1.txt and file2.txt files at the same time

3. cd COMMAND:cd command is used to change the directory.
- SYNTAX:
         The Syntax is    
         cd [directory | ~ | ./ | ../ | - ]
- OPTIONS:
-L Use the physical directory structure.
-P Forces symbolic links.
- EXAMPLE:
1. cd linux-command:- This command will take you to the sub-directory(linux-command) from its parent directory.
2. cd.. :- This will change to the parent-directory from the current working directory/sub-directory.
3. cd ~:- This command will move to the user's home directory which is "/home/username".

## File Editors in Linux 
- Command-Line Editors

1. nano:-Easy to use.
        -Simple and user-friendly.
        -Command: nano filename

2. vi / vim:-Powerful, extensive shortcuts.
            -Powerful and widely used.
            -Command: vi filename or vim filename

## USERS AND GROUPS
* USERS:- A person who use the computer.
1. PREVILEGE USER:- It is a Super user and it has a full power.
2. NON-PREVILEGE USER:- It has a less power.
3. SYSTEM USER:- It make automatically.

Question 1- How to make a user ?
# useradd or #adduser
Question 2 :- How to create the password for user ?
# passwd(user name)
Qusetion 3:- How to delete the user but keep the data ?
# userdel(user name)
Question 4:-How to create a group ?
# groupadd (group name)
# groupdel (grroup name)

## PARTITION 
- What is a Partition?
  A partition is a way to divide a hard disk drive (HDD) or solid-state drive (SSD) into separate sections. Each section acts like an independent drive.
- Types of Partitions

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

    cd (Change Directory): Allows navigation between directories. For instance, cd moves into a specific directory, while cd .. moves up one level in the directory structure.
    ls (List): Lists the contents of a directory. ls -l provides a detailed list with permissions, ownership, size, and modification date.
    mkdir (Make Directory): Creates a new directory. For example, mkdir creates a directory with the specified name.
    cp (Copy): Copies files or directories from one location to another. Syntax: cp .
    rm (Remove): Deletes files or directories. Use rm to remove a file and rm -r for recursive deletion of directories.
    cat (Concatenate): Displays the contents of a file in the terminal. cat shows the entire content of the specified file.
    grep (Global Regular Expression Print): Searches for specific text patterns within files. For example, grep "search_term" looks for occurrences of "search_term" in the specified file.
    man (Manual): Displays the manual page for a specific command. man provides detailed information and documentation about the command.
