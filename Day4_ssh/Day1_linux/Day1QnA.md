## What is GNU project?

GNU stands for GNU's not Unix. GNU project was announced by Richard Stallman with the purpose of developing a free and open source software so that everyone has the right to copy it, distribute it, study it or modify it. GNU project consisted of bootloader, daemon etc except the kernel. Linux developed by Linus Torvalds was the final part for the GNU project. The GNU project along with the Linux Kernel came to be the first free operating system commonly known as Linux.

## Difference between Unix & Linux
Linux is open source and free operating system. Linux uses Gnome and other GUI. The default shell is bash.

Unix is licensed Operating System. It was initially developed as a command line operating system. The default shell is Bourne shell.

## Integrity check of BIOS
The system integrity test performed by BIOS is called POST(Power On Self Test). POST include routines performed by the firmware once the device is switched on to verify if the hardware is performing as expected otherwise return error messages and beeps. The harware checked include RAM, processors, peripheral devices etc.


## What is UEFI? Difference between BIOS & UEFI.
The Unified Extensible Firmware Interface (UEFI), like BIOS (Basic Input Output System), is a firmware that runs when the computer is booted. It initializes the hardware and loads the operating system into the memory.
1. UEFI supports drive sizes upto 9 zettabytes, whereas BIOS only supports 2.2 terabytes.
2. UEFI provides faster boot time.
3. UEFI offers security like "Secure Boot", which prevents the computer from booting from unauthorized/unsigned applications.
4. UEFI runs in 32bit or 64bit mode, whereas BIOS runs in 16bit mode. So UEFI  is able to provide a GUI involving mouse as opposed to BIOS which allows navigation only using the keyboard.

## Various Linux distributions and uses
1. Ubuntu: It is based on Debian. It has an elegant GUI and thus designed to help people who transitioned from windows or mac to Linux.
2. Debian: Debain is the mother of distros. Ubuntu, Linux Mint are based on Debian. It has high stability and thus can be used in production servers.
3. RHEL: Red Hat Enterprise Linux. It is designed for commercial and enterprise purposes. It has a paid support contract.
4. Centos: It is based on Red Hat distro. Except it is free and does not provide the paid support contract.
5. Fedora: Based on Red Hat distro. Has all the new features and updates and hence less stable.
6. Kali Linux: Developed for pentration testing.

## Various operating systems & there uses
Windows is a graphical operating system developed by Microsoft. It allows users to view and store files, run the software, play games, watch videos, and provides a way to connect to the internet. Later, it was released on many versions of Windows as well as the current version, Windows 10.

Linux is used in smart devices, Servers and Mainframes, Telecommunication, Security.

## What does 5 in systemd.unit(5) mean?
Man Pages are divided into 8 sections.
1. User Commands : Commands that can be run from the shell by a normal user
2. System Calls: Programming functions used to make calls to the Linux kernel
3. C Library Functions: Programming functions that provide interfaces to specific programming libraries.
4. Devices and Special Files: File system nodes that represent hardware devices or software devices.
5. File Formats and Conventions: The structure and format of file types or specific configuration files.
6. Games: Games available on the system
7. Miscellaneous: Overviews of miscellaneous topics such as protocols, filesystems and so on.
8. System administration tools and Daemons:Commands that require root or other administrative privileges to use.


## uname Command
Uname Command- Uname Command is used for displaying the information about this system.
SYNTAX- uname [option]
OPTIONS-      
1. -a: It prints all the system information in the following order: Kernel name, network node hostname, kernel release date, kernel version, machine hardware name, hardware platform, operating system
Syntax: $uname  -a
2. -s: It prints the kernel name.
Syntax: $uname  -s

3. -n: It prints the hostname of the network node (current computer).
Syntax: $uname  -n

4. -r:  It prints the kernel release date.
Syntax: $uname  -r

5. -v:  It prints the version of the current kernel.
Syntax: $uname  -v

6. -m: It prints the machine hardware name.
Syntax: $uname  -m

7. -p:  It prints the type of the processor.
Syntax: $uname  -p

8. -i:   It prints the platform of the hardware.
Syntax: $uname  -i

9. -o:  It prints the name of the operating system.
Syntax: $uname  -o

## getty command
getty, short for "get tty", is a Unix program running on a host computer that manages physical or virtual terminals (TTYs). When it detects a connection, it prompts for a username and runs the 'login' program to authenticate the user.
