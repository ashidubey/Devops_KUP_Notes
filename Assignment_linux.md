# **Q1. What is GNU project?**

Ans. GNU stands for GNU's not Unix. GNU project was announced by Richard Stallman with the purpose of developing Unix-like, GNU is modular in design. A GNU distribution typically runs a Linux kernel. However, what separates a GNU distribution from any other Linux distribution is the integration of the GNU tool chain, a series of several hundred programs that are free and open source and support the development of new, free software.

# **Q2. Difference between Unix & Linux.**

Ans. The name “Linux” comes from the Linux kernel. It is the software on a computer which enables applications and the users to access the devices on the computer to perform some specific function.

The Unix OS works on CLI (Command Line Interface), but recently, there have been developments for GUI on Unix systems. Unix is an OS which is popular in companies, universities big enterprises, etc.

# ` `**Q3. What do you mean by Integrity check of BIOS**

Ans.  fundamentals of BIOS integrity measurement, such as basic requirements that must be met in order to measure BIOS integrity, and typical data flows for BIOS integrity measurement and reporting. This material provides a foundation for the core of the document, which presents guidelines to hardware and software vendors that develop products that can support secure BIOS integrity measurement mechanisms. These guidelines define in detail the requirements and recommendations for vendors to follow in support of BIOS integrity measurement.

# **Q4. What is UEFI?**

Ans.  Unified Extensible Firmware Interface (UEFI) is a specification for a software program that connects a computer's [firmware](https://whatis.techtarget.com/definition/firmware) to its operating system ([OS](https://whatis.techtarget.com/definition/operating-system-OS)). UEFI is expected to eventually replace basic input/output system ([BIOS](https://whatis.techtarget.com/definition/BIOS-basic-input-output-system)) but is compatible with it. The specification is most often pronounced by naming the letters U-E-F-I.

# **Q5. What is Difference between BIOS & UEFI.**

Ans. 
. UEFI enables users to handle drives that are larger than 2 TB, while the old legacy BIOS couldn't handle large storage drives.

. UEFI supports more than 4 primary partitions with a GUID Partition Table.

. Computers who use UEFI firmware have faster booting process than the BIOS. Various optimizations and enhancement in the UEFI can help your system boot more quickly than it could before.

. UEFI supports secure startup, which means that the validity of the operating system can be checked to ensure that no malware tampers with the startup process.

# ` `**Q6. When should you go for Ubuntu & when for other systems?**

Ans. Windows is a graphical operating system developed by Microsoft. It allows users to view and store files, run the software, play games, watch videos, and provides a way to connect to the internet. Later, it was released on many versions of Windows as well as the current version, Windows 10.

Linux is used in smart devices, Servers and Mainframes, Telecommunication, Security.

# **Q7. List Various Linux distributions & their use cases.**

Ans. 
. Ubuntu: It is based on Debian. It has an elegant GUI and thus designed to help people who transitioned from windows or mac to Linux.

. Debian: Debain is the mother of distros. Ubuntu, Linux Mint are based on Debian. It has high stability and thus can be used in production servers.

. RHEL: Red Hat Enterprise Linux. It is designed for commercial and enterprise purposes. It has a paid support contract.

. Centos: It is based on Red Hat distro. Except it is free and does not provide the paid support contract.

. Fedora: Based on Red Hat distro. Has all the new features and updates and hence less stable.

. Kali Linux: Developed for pentration testing.

# **Q8. What does 5 in systemd.unit(5) mean?**

Ans. Units are the objects that systemd knows how to manage. These are basically a standardized representation of system resources that can be managed by the suite of daemons and manipulated by the provided utilities. 

Service files must include a [Service] section, which carries information about the service and the process it supervises.

# **Q9. What are getty commands and uname commands?**

Ans. 

**getty command**

getty:  The getty command sets and manages terminal lines and ports. The getty command is run by the init command. The getty command is linked to the Terminal State Manager program.

**uname Command**

Uname command is used to display basic information about the operating system and hardware. With options, Uname prints kernel details, and system architecture. Example- $uname –a; $uname –s; $uname –n; $uname –r; $uname –v; $uname –m; : $uname –p; : $uname –i; : $uname –o

# **Q10. What is squashfs file system?**

Ans. SquashFS is an open source, read only, extremely compressible file system. Like other file systems, SquashFS is capable of de-duplicating the data passed to it, which helps it compress data further. Although not fully necessary to operate correctly, SquashFS is typically paired with some kind of union [file system](https://wiki.gentoo.org/wiki/Filesystem "Filesystem") when used for Live media.

# **Q11.  What are /dev/loop and /dev/tty?**

Ans. 

**/dev/loop** devices treat files with a filesystem image as if they were block devices. The loop devices are snaps because snap packages are created that way.

**/dev/tty** is a synonym for the controlling terminal that is associated with the process group of the current process.

**/dev/tty** is particularly useful to make sure that messages are written or read from that terminal, no matter how input or output is redirected.

# ` `**Q12. What are Linux Signals?**

Ans. A signal is an event generated by the UNIX and Linux systems in response to some condition. Upon receipt of a signal, a process may take action.

A signal is just like an interrupt; when it is generated at the user level, a call is made to the kernel of the OS, which then acts accordingly. Two types- Maskable and Non-Maskable.
 
# ` `**Q13. What is the purpose of creating hidden files?**

Ans. A hidden file is a file which has the hidden attribute turned on so that it is not visible to users when exploring or listing files. Hidden files are used for storage of user preferences or for preservation of the state of utilities. They are created frequently by various system or application utilities. 

# **Q14. How ext4fs is faster/better?**

Ans. ext4 as a stopgap technology which significantly extends ext3 but is still reliant on old technology. He expects it to be supplanted eventually by a true next-generation file system. 

In general, file content takes up much more space then the indexes on most modern file systems (ext4 and NTFS included). The file systems just store the content differently, which (as I mentioned, in some cases) allows for higher performance.

# **Q15. What is swap & swap memory?**

Ans.

swap - The primary function of swap space is to substitute disk space for RAM memory when real RAM fills up and more space is needed.

swap memory - whenever RAM runs out of memory in Linux, it borrows some memory from the secondary storage to store its inactive content. RAM finds sufficient space to hold a new process within it. Here, the borrowed space from the hard disk is called Swap Memory. In this article, we will try to learn the concept of swap memory in detail.

# **Q16. How to mount a file system?**

Ans. To mount a particular file system for example

mount [OPTION...] DEVICE\_NAME DIRECTORY

mount dev/sdb1 mnt/music

# **Q17. Mention a ZFS use case**

Ans. In a nutshell, ZFS is a combined filesystem and logical volume manager. It is intended, first and foremost, to maintain data integrity, but also to protect data from the hardware and from the user and simplify storage administration. ZFS is typically used on large storage servers and works well there. Many also boot their operating system from it.

# **Q18.  How to check port no of a process?**

Ans. We can use the following command : - sudo netstat -ano -p tcp

or use lsof -i :port number

# **Q19. What is Unix Time Sharing (UTS)?**

Ans. Time sharing is the sharing of a computing resource among many users by means of multiprogramming and multitasking at the same time whereas multitasking is the concurrent execution of multiple tasks or processes over a certain period of time. Thus, this is the main difference between time sharing and multitasking.

# **Q20. What are Control Groups?**

Ans. Control Groups provide a mechanism for aggregating/partitioning sets of tasks, and all their future children, into hierarchical groups with specialized behaviour. 

# **Q21. What is Difference between sbin & usr/sbin?**

Ans.

**sbin** - For binaries with superuser (root) privileges required. usable before the /usr partition is mounted. This is used for trivial binaries used in the very early boot stage or ones that you need to have available in booting single-user mode. Think of binaries like cat, ls, etc.

**usr/sbin-** Same as first, but for general system-wide binaries.

# **Q22. Examples of awk, grep and sed.**

Ans. 

` awk `  awk - $ awk '{print "Hello"}' - It prints the statement.

` grep `  grep -i "a" a.txt

` sed ` sed 's/string/stringtobereplaced/g' filename

# **Q23. How many tables are there in iptables?**

Ans. iptables contains five tables:

1. Filter Table
1. NAT table
1. Mangle table
1. Raw table
1. Target Values

# **Q24. What is prot, opt, in, out, source & destination?**

Ans. 

**prot:** prot is a combination of the following access flags: PROT\_NONE or a bitwise-or of the other values in the following list: PROT\_NONE The memory cannot be accessed at all. PROT\_READ The memory can be read. PROT\_WRITE The memory can be modified. PROT\_EXEC The memory can be executed.

**Opt:** It means reserved for the installation of add-on application software packages. In this context, “add-on” means software that is not part of the system; for example, any external or third-party software.

**In:** packets coming from the network and going to your server.

# **Q25. Why are rules added to the top?** 

Ans. iptables is Linux administration tool for IPv4 packet filtering and NAT. One can use iptables/ip6tables to set up, manage, and examine the tables of IPv4 and IPv6 packet filter rules in the Linux kernel. This page shows how to use Iptables to insert rule at top of tables.

# **Q26. What type of rules can we add to the iptables?**

Ans. 

- Delete Existing Rule
- Set Default Chain Policies
- Block a Specific ip-address. 
- Allow ALL Incoming SSH. 
- Allow Incoming SSH only from a Specific Network.
- Allow Incoming HTTP and HTTPS. 
- Combine Multiple Rules Together using Multi Ports. 
- Allow Outgoing SSH.
- Allow Outgoing SSH only to a Specific Network
- Allow Outgoing HTTPS

# **Q27. Can we block a website by its domain name only?**

Ans. Blocking a domain name involves ordering a domain name lookup service (for most users, a function performed by their ISP) not to respond to any user request to look up the IP address associated with that name.

# **Q28. How can we persist rules in iptables?**

Ans. Iptables rules will not survive through a server reboot! Find out how to accomplish saving your firewall rules (along with some handy commands) on Debian/Ubuntu and CentOS/RedHat servers.Let's dive into some useful commands and see how to persist Iptables rules.

# sudo apt-get install -y iptables-persistent; sudo service iptables-persistent start;  sudo iptables-save > /etc/iptables/rules.v4;  sudo service iptables-persistent restart

# ` `**Q29. How can we save rules in iptables?**

Ans.  Saving iptables firewall rules permanently on Linux

sudo iptables-save > ~/rules.v4 

# **Q30. What is Difference between ufw & iptables?**

Ans. iptables is a command line interface of netfilter, which is the underlying mechanics in the kernel for all of the work related. It has been (mostly) replaced by nftables (netfilter-tables) which provides more (advanced) features and a unified interface for IPv4/IPv6/ARP/Ethernet Bridges. But both iptables and nftables requires manually writing rules since they are kind of low-level.

UFW wraps around nftables (used to be iptables&ip6tables) and provides a much-easier-to-use command line interface for managing basic firewall functionalities, hence its name.

# **Q31. What are public & private keys?**

Ans. The public key is, as its name implies, public and open to anyone in the system. The public key is used to encrypt data. The private key however is private. It is stored on user's device and is used to decrypt data.

# **Q32. How does ssh work?**

Ans. SSH, or Secure Shell, is a remote administration protocol that allows users to control and modify their remote servers over the Internet. It provides a mechanism for authenticating a remote user, transferring inputs from the client to the host, and relaying the output back to the client.

# **Q33. Difference between HTTP & HTTPS.**

Ans. 

1. HTTP URL in your browser's address bar is http:// and the HTTPS URL is https://.
1. HTTP is unsecured while HTTPS is secured.
1. HTTP sends data over port 80 while HTTPS uses port 443.
1. HTTP operates at application layer, while HTTPS operates at transport layer.
1. No SSL certificates are required for HTTP, with HTTPS it is required that you have an SSL certificate and it is signed by a CA.

# **Q34. What is SSL?**

Ans. SSL provides a secure channel between two machines or devices operating over the internet or an internal network. One common example is when SSL is used to secure communication between a web browser and a web server.
 
# **Q35. Difference between apt update and apt upgrade.**

Ans. The command to update new versions of currently installed packages is "apt upgrade". That's why you want to first run "apt update" and then "apt upgrade".

You can chain these commands to help speed up the process by typing "sudo apt update && sudo apt upgrade". If you're logged in as the 'root user' then you don't need to type sudo before the commands.

# **Q36. What do repositories contain in the Linux System?**

Ans. A Linux repository is a storage location from which your system retrieves and installs OS updates and applications. Each repository is a collection of software hosted on a remote server and intended to be used for installing and updating software packages on Linux systems.

# **Q37. What are package managers used in Linux?**

Ans.

1. DPKG – Debian Package Management System. ...
1. RPM (Red Hat Package Manager) ...
1. Pacman Package Manager – Arch Linux. ...
1. Zypper Package Manager – openSUSE. ...
1. Portage Package Manager – Gentoo.

# **Q38. What does the number represent after the file permission?**

Ans. Linux divides the file permissions into read, write and execute denoted by r,w, and x. The permissions on a file can be changed by ‘chmod’ command which can be further divided into Absolute and Symbolic mode. 

# **Q39. What is the Difference between apt and apt -get?**

Ans. The apt commands have been introduced to solve this problem. apt consists some of the most widely used features from apt-get, apt-cache and apt-config leaving aside obscure and seldom used features.

With apt, you don’t have to fiddle your way from apt-get to apt-cache to apt-config. apt is more structured and provides you with necessary options needed to manage packages.

# **Q40. How can 1 give access to someone to my AWS instance?**

Ans.

Here are the high level steps for giving another person ssh and sudo access to your EC2 instance running Linux:

\1. Create a new user on the instance (adduser).

\2. Ask the person for their public ssh key and add it to the .ssh/authorized\_keys file in the new home directory. Create the directory and file if they do not exist, making sure they are both owned by the user and both do not allow world read/execute permission.

\3. Update /etc/sudoers or add a new file under /etc/sudoers.d/ to allow the new user to sudo.

\4. Provide the person with the IP address of the instance and new username.

The specific commands and file edits depend on the OS you're running and your particular preferences.

# **Q41. What are daemon applications?**

Ans. A *daemon* is a program with a unique purpose. They are utility programs that run silently in the background to monitor and take care of certain subsystems to ensure that the operating system runs properly. A printer daemon monitors and takes care of printing services. A network daemon monitors and maintains network communications, and so on.

- Web applications 
- Desktop applications 
- Web APIs 

# **Q42. What .d represents after a file?**

Ans. "d" is a collection of configuration files and points to compartmentalize configuration concerns to increase maintainability.

# **Q43. What happens when a pem gets deleted?**

Ans. PEM files are used to store SSL certificates and their associated private keys.This is the file you use in nginx and Apache to encrypt HTTPS without it we can’t access your instance from our system.

# **Q44. What is in the host file?**

Ans. The hosts file ("hosts.txt") is a plain-text file that contains a list of host names and their corresponding IP addresses. It is essentially a database of domain names that is used by the operating system for identifying and locating a host in an IP network.

# **Q45. What is SCP & what does this command do?**

Ans. The Secure Copy Protocol, or SCP, is a file transfer network protocol used to move files onto servers, and it fully supports encryption and authentication. SCP uses Secure Shell (SSH) mechanisms for data transfer and authentication to ensure the confidentiality of the data in transit. 

The server controls the file downloads for security risks if the client is unintentionally connected to a malicious server. SCP is in fact a native command in most operating systems, such as macOS, Windows, or Linux.

# **Q46. How port forwarding works?**

Ans. Port forwarding achieves by creating an association called a *map* between a router’s public, wide area network (WAN) IP and a private, local area network (LAN) IP address for a device on that private network.Using ports lets a device run a myriad of different processes and services. Each service has its own port - for example, email servers usually use port 587 while websites use port 80.

# **Q47. How can we connect without IP to AWS instance?**

Ans. Go into the EC2 dashboard, then in the NETWORK & SECURITY menu go to Elastic IPs. Click on Allocate a new address. Right click on the new IP and select Associate address. Associate it with your EC2 instance that doesn't have an elastic IP.

# **Q48. What is an SSH Agent?**

Ans. Your public SSH key is like your username or identity, and you can share it with everybody. Your private SSH key is like a password, and is saved locally on your computer. But, this is like storing your passwords on a sticky note—anyone can view them if they have access to it. So, for security, SSH will ask you for a passphrase when you generate your keys (hopefully you didn’t skip that step) and it will use that passphrase to encrypt and decrypt your private key.

# **Q49. Create a unit file for any application.**

Ans. For unit file check (https://github.com/ashidubey/Devops_KUP_Notes/blob/master/Day1_linux/custom.service)

# **Q50. What is RHEL?**

Ans. Red Hat Enterprise Linux (RHEL) is a Linux-based operating system from Red Hat designed for businesses. RHEL can work on desktops, on servers, in hypervisors or in the cloud. Red Hat and its community-supported counterpart, Fedora, are among the most widely used Linux distributions in the world.
