**Q1. What is squashfs file system?**

- Data, Inodes and directories are compressed
- SquashFS stores full uid/gids (32 bits), and file creation time
- Files up to 2^64 bytes are supported; file systems can be up to 2^64 bytes
- SquashFS can use block sizes up to up to 64 Kb (2.x) and 1Mb (3.x). The default size is 128Kb (3.x), which achieves greater compression ratios than the normal 4K block size
- File duplicates are detected and remove.
- **Inode** is a Linux and other Unix-like data structure used **to keep information about a file on your server**.\*\*
- Unix-like operating systems identify a user by a value called a **user identifier (UID)** along with the **group identifier** **(GID).\*\***

**Q2. What are /dev/loop and /dev/tty ?**

/dev/loopX are virtual devices to mount image files. And they are -read only- so do not get larger or smaller than they are when created. Those mount points are connected to the snapd service.

/dev/tty stands for **the controlling terminal (if any) for the current process** (the process that uses "/dev/tty" in a command). To find out which tty's are attached to which processes use **the "ps -a" command.**

**Q3. What are Linux Signals?**

Signals are **software interrupts sent to a program to indicate that an important event has occurred**. The events can vary from user requests to illegal memory access errors. 

There are **31 standard signals**, numbered 1-31. Each signal is named as " SIG " followed by a suffix.

e.g. SIGILL, SIGBUS, SIGKILL, SIGUSR1. Etc

**Q4. Purpose of hidden files.**

Files that exist on a computer, but don't appear when listing or exploring, are called hidden files. A hidden file is **primarily used to help prevent important data from being accidentally deleted**. Hidden files should not be used to hide confidential information as any user may view them.

**Q5. What is swap & swap memory?**

swap - Swap is a space on a disk that is used when the amount of physical RAM memory is full. When a Linux system runs out of RAM, inactive pages are moved from the RAM to the swap space.

swap memory - The space occupied by these inactive files is called swap memory.

**Q6. How to mount a file system?**

To mount a particular file system for example

mount [OPTION...] DEVICE\_NAME DIRECTORY

mount dev/sdb1 mnt/music

**Q7.**  **What is Linux Directory structure and each directory of it?**

**/bin** : All the executable binary programs (file) required during booting, repairing, files required to run into single-user-mode, and other important, basic commands.

**/boot** : Holds important files during [boot-up process](https://www.tecmint.com/linux-boot-process/), including **Linux Kernel**.

**/dev** : Contains device files for all the hardware devices on the machine

**/etc** : Contains Application’s configuration files, **startup**, **shutdown**, **start**, **stop** script for every individual program.

**/home** : Home directory of the users. Every time a new user is created, a directory in the name of user is created within home directory which contains other directories like **Desktop**, **Downloads**, **Documents**, etc.

**/lib** : The Lib directory contains **kernel modules** and **shared library** images required to boot the system and run commands in root file system.

**/lost+found** : This Directory is installed during installation of **Linux**, useful for recovering files which may be broken due to unexpected **shut-down**.

**/media** :

**/mnt** : Temporary mount directory for [mounting file system](https://www.tecmint.com/how-to-mount-and-unmount-an-iso-image-in-linux/).

**/opt** : Contains third party application software.  

**/proc** :

**/root** : This is the home directory of root user and should never be confused with **‘/**‘

**/run** : This directory is the only clean solution for **early-runtime-dir** problem.

**/sbin** : Contains binary executable programs, required by **System Administrator** 

**/srv** : This directory contains server specific and service related files.

**/sys** : it stores and allows modification of the devices connected to the system.

**/tmp** :System’s Temporary Directory, Accessible by users and root. Stores temporary files for **user** and **system**, till next boot.

**/usr** : Contains executable **binaries**, **documentation**, **source code**, **libraries** for second level program.

**/var** : Stands for variable. The contents of this file is expected to grow.

**Q8.** **What are CGroups?**

Cgroups allows processes to be organized into hierarchial order where then usage can be limited and monitored.It is used in resurce management.

It is a Linux kernel feature that limits, accounts for, and isolates the resource usage (CPU, memory, disk I/O, network, and so on) of a collection of processes.


**Q9. Difference between sbin & usr/sbin.**

sbin - It contains all the files which are needed to boot the system but cannot be run by normal user.

usr/sbin- It contains all the files which are needed for normal run or execution.It is the primary directory for executable program. 

**10. How to check which process running on which port?**

We can use the following command : - **sudo netstat -ano -p tcp**

or **use lsof -i :port number**


**11. How ext4 fs is faster ?**

Ext4 has a large filesystem support , improved resistance to fragmentation, higher performance, and improved timestamps.
Ext4 uses 48-bit internal addressing, making it theoretically possible to allocate files up to 16 TiB on filesystems up to 1,000,000 TiB (1 EiB).

In ext4 the storage blocks are allocated before writing them on the disk. So reading and writing becomes easier.

**12- Examples of awk, grep and sed .**

awk - WIth awk we  can 

\- Define variables.

\- Use string and arithmetic operators.

`  `fOr example

awk -   $ awk '{print "Welcome to knoldus"}' - It prints the statement.

\*grep\* - It is used to search for a string in a particular file or stream.

for exmple - grep option pattern filename

grep -i "a" a.txt

\*sed\*- sed is a stream editor .It can do lot of funtions such as replacing , finding , insertion , deletion , replacement.

example - sed 's/string/stringtobereplaced/g'  filename



