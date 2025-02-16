---
tags: 
parent docs:
  - "[[Navigation]]"
sibling docs: 
child docs: 
media:
  - "[[f73756dfd104490f30df1db9c1f1cd05095640d5.jpg]]"
  - "[[383a8674485298b94205a526f167d57e93e77ab8.png]]"
  - "[[8b2b12277a5b88a9d258c387224872a1c0ae3107.jpg]]"
  - "[[3fbcd833fe7f9f91432b9d2f7df61bb8150d1c70.jpg]]"
  - "[[02209077c6c1db04168d42388ea2aff5fcd34315.png]]"
  - "[[8f371be19fb7ede8d3fa9f3a1b93e15ab25f1f46.jpg]]"
---
# Nav
< [[Virtualization and Cloud Computing|Previous]] < ^ [[Navigation|Home]] ^ > [[Operational Procedures|Next]] >

---

If every business used a Mac or all businesses used Windows, your job in IT support would be a lot less complicated. But they don’t, so it’s not. To support all clients, an IT technician needs to be conversant in all types of systems, including system configuration and troubleshooting for Mac, Chrome, Android, and Linux [[Operating System|OS]]. You’ll also need to be able to install and support Windows systems. This all-encompassing content is why 31% of the CompTIA A+ 1102 questions are devoted to operating systems. 

An [[Operating System|OS]] has a number of functions. One of its main tasks is to act as an interface between the user and the hardware connected to the computer. The operating system also controls other functions:
- Software resources
- Memory allocation and all peripheral devices
- Common services to computer application software

From digital watches to computers, almost all computers require an operating system before they can be operated. To understand the capabilities of an operating system, it is important to first understand some basic terms. The following terms are often used when describing operating systems:
- **Multi-user** - Two or more users have individual accounts that allow them to work with programs and peripheral devices at the same time.
- **Multitasking** - The computer is capable of operating multiple applications at the same time.
- **Multiprocessing** - The operating system can support two or more CPUs.
- **Multithreading** - A program can be broken into smaller parts that are loaded as needed by the operating system. Multithreading allows different parts of a program to be run at the same time.

The OS boots the computer and manages the file system. Operating systems can support more than one user, task, or CPU.

Over half (64%) of the questions about operating systems will begin with a scenario.

# Function
Regardless of the size and complexity of the computer and the operating system, all operating systems perform the same four basic functions:
- Control hardware access
- Manage files and folders
- Provide a user interface
- Manage applications

## Hardware access
The [[Operating System|OS]] manages the interaction between applications and the hardware. To access and communicate with each hardware component, the OS uses a program called a device driver. When a hardware device is installed, the OS locates and installs the device driver for that component. Assigning system resources and installing drivers are performed with a plug-and-play (PnP) process. The OS then configures the device and updates the registry, which is a database that contains all the information about the computer.

If the OS cannot locate a device driver, a technician must install the driver manually either by using the media that came with the device or downloading it from the manufacturer’s website.

## File and folder management
The [[Operating System|OS]] creates a file structure on the hard disk drive to store data. A file is a block of related data that is given a single name and treated as a single unit. Program and data files are grouped together in a directory. The files and directories are organized for easy retrieval and use.
Directories can be kept inside other directories. These nested directories are referred to as subdirectories. Directories are called folders in Windows operating systems, and subdirectories are called subfolders.

## User interface
The OS enables the user to interact with the software and hardware. Operating systems include two types of user interfaces:  
- **Command-line interface (CLI)** - The user types commands at a prompt.
- **Graphical user interface (GUI)** - The user interacts with menus and icons.

## Application Management
The OS locates an application and loads it into the [[Random Access Memory|RAM]] of the computer. Applications are software programs, such as word processors, databases, spreadsheets, and games. The OS allocates available system resources to running applications. To ensure that a new application is compatible with an OS, programmers follow a set of guidelines known as an [[Application Programming Interface|API]]. An API allows programs to access the resources managed by the operating system in a consistent and reliable manner.
Here are some examples of APIs:  
- **Open Graphics Library (OpenGL)** – This is a cross-platform standard specification for multimedia graphics.
- **DirectX** – This is a collection of APIs related to multimedia tasks for Microsoft Windows.
- **Windows API** – The Windows API provides application developers with user interface controls, file management and graphical elements, such as windows, scroll bars, and dialog boxes.
- **Java APIs** – This is a collection of APIs related to the development of Java programming.

## Account Creation
When users attempt to log on to a device or to access system resources, Windows uses the process of authentication to verify the identity of the users. Authentication occurs when users enter a username and password to access a user account. Windows uses Single-Sign On (SSO) authentication, which allows users to log in once to access all system resources versus requiring them to log in each time they need to access an individual one.

User accounts allow multiple users to share a single computer using their own files and settings. Windows 10 offers two account types: Administrator and Standard User, as shown in the Figure. In previous versions of Windows, there was also a Guest account, but that has been removed with Windows 10.

Administrator accounts have complete control over a computer. Users with this type of account can change settings globally, install programs, get through the User Account Control (UAC) when elevation to perform a task is required.

Standard user accounts have limited control over a computer. Users with this type of account can run applications, but they cannot install programs. A standard user account can change system settings but only settings that do not affect other user accounts

## Installation Methods



# Requirements

## Compatibility
Understanding how a computer will be used is important when recommending an OS to a customer. The OS must be compatible with the existing hardware and the required applications.

To make an OS recommendation, a technician must review budget constraints, learn how the computer will be used, determine which types of applications will be installed, and whether a new computer may be purchased. These are some guidelines to help determine the best OS for a customer:
- **Does the customer use off-the-shelf applications for this computer?** Off-the-shelf applications specify a list of compatible operating systems on the application package.
- **Does the customer use customized applications that were programmed specifically for the customer?** If the customer is using a customized application, the programmer of that application specifies which OS to use.

## [[Hardware]]
Operating systems have minimum hardware requirements that must be met for the OS to install and function correctly.

Identify the equipment that your customer has in place. If hardware upgrades are necessary to meet the minimum requirements for an OS, conduct a cost analysis to determine the best course of action. In some cases, it might be less expensive for the customer to purchase a new computer then to upgrade the current system. In other cases, it might be cost effective to upgrade one or more of the following components:
- RAM
- HDD
- CPU
- Video adapter card
- Motherboard
**Note**: If the application requirements exceed the hardware requirements of the OS, you must meet the additional requirements for the application to function properly.

## 32-bit vs. 64-bit
The processor architecture of the CPU affects the performance of the computer.
The terms 33-bit and 64-bit refer to the amount of data a computer's CPU can manage. A 32-bit register can store 2^32 different binary values. Therefore, a 32-bit processor can directly address 4,94,967,295 bytes. A 64-bit register can store 2^64 different binary values. Therefore, a 64-bit can directly address 18,446,744,073,709,551,615 bytes.
The table shows the main difference between the 32-bit and 64-bit architectures.

| Architectures   | Description                                                                                                                                                                                 |
| --------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 32-bit (x86-32) | processes multiple instructions using a 32-bit space, support maximum of 4GB of RAM memory, supports 32-bit operating systems and applications only                                         |
| 64-bit (x86-64) | adds additional registers specifically for instructions that use a address space, is backwards compatible with the 32-bit processor, supports 32/64-bit operating systems, and applications |
### Registers
memory locations that are a part of the architecture of a CPU

## Upgrades
An OS must be upgraded periodically to remain compatible with the latest hardware and software. It is also necessary to upgrade an OS when a manufacturer stops supporting it. Upgrading an OS can increase performance. New hardware products often require that the latest OS version be installed to operate correctly. While upgrading an OS may be expensive, you can gain enhanced functionality through new features and support for newer hardware.

**Note**: When newer versions of an OS are released, support for older versions is eventually withdrawn.

Before upgrading the operating system, check the minimum hardware requirements of the new OS to ensure that it can be installed successfully on the computer.

## Data Migration
When a new installation is required, user data must be migrated from the old OS to the new one. There are several tools available to transfer data and settings. The tool you select depends on your level of experience and your requirements.

### User State Migration Tool
The User State Migration Tool (USMT) is a command line utility program developed by Microsoft that allows users who are comfortable with scripting languages to transfer files and settings between Windows PCs. USMT is one of many core assessment and deployment tools included in the Windows Assessment and Deployment Kit which can be downloaded from the Microsoft website. You can use USMT version 10.0 to streamline and simplify user state migration during large deployments of Windows operating systems. USMT captures user accounts, user files, operating system settings, and application settings, and then migrates them to a new Windows installation. You can use USMT for both PC replacement and PC refresh migrations.  
  
**Note**: USMT version 10.0 supports data migration from Windows 7 through Windows 10.

### Windows Easy Transfer
If a user is switching from an old computer to a new one, use Windows Easy Transfer to migrate personal files and settings. You can perform the file transfer using a USB cable, CD or DVD, a USB flash drive, an external drive, or a network connection. Use Windows Easy Transfer to transfer information to a computer running Windows 8.1 from computers with one of the following operating systems:
- Windows 8
- Windows 7
- Windows Vista

Windows easy transfer is not available in Windows 10 and is replaced with PC-mover Express.

### PC-mover Express
Microsoft has partnered with Laplink to provide PC-mover Express which is a tool for transferring selected files, folders, profiles, and applications from an old Windows PC to a Windows 10 PC. Instead of repurchasing and manually installing programs on the new PC, a user can use **PC-mover** to transfer selected applications to the new PC, and they will be installed and ready to use.

# [[Storage]]
As a technician, you might have to perform a clean installation of an OS. Perform a clean install in the following situations:
- When a computer is passed from one employee to another
- When the OS is corrupt
- When the primary hard drive is replaced in a computer

The installation and initial booting of the OS is called the operating system setup. Although it is possible to install an OS over a network from a server or from a local hard drive, the most common installation method for a home or small business is through external media such as DVDs or USB drives.

**Note**: If the hardware is not supported by the OS, you may need to install third-party drivers when performing a clean installation.

Before the operating system can be installed, a storage media device must be chosen and prepared. Several types of storage devices are available and can be used to receive the new operating system. The two most common types of data storage devices used today are hard disk drives and flash memory-based drives such as solid-state hard drives and USB drives.

When the storage device type has been chosen, it must be prepared to receive the new operating system. Modern operating systems ship with an installer program. Installers usually prepare the disk to receive the operating system, but it is crucial for a technician to understand the terms and methods involved in this preparation.

## HDD Partitioning
A hard drive is divided into areas called partitions. Each partition is a logical storage unit that can be formatted to store information, such as data files or applications. If you imagine a hard drive as a wooden cabinet, the partitions would be the shelves. During the installation process, most operating systems automatically partition and format available hard drive space.

Partitioning a drive is a simple process, but to ensure a successful boot, the firmware must know what disk and partition on that disk has an operating system installed. The partition scheme has direct influence in the location of the operating systems on a disk. Finding and launching the operating system is one of the responsibilities of computer firmware. The partition scheme is very important to the firmware. Two of the most popular partition scheme standards are master boot record (MBR) and globally unique identifier (GUID) partition table (GPT).

### Master Boot Record
Publicly introduced in 1983, the MBR contains information on how the hard drive partitions are organized. The MBR is 512 bytes long and contains the boot loader, an executable program that allows a user to choose from multiple operating systems. MBR has become the de facto standard but has limitations that had to be addressed. MBR is commonly used in computers with BIOS-based firmware.

### GUID Partition Table
Also designed as a partition table scheme standard for hard drives, the GPT makes use of a number of modern techniques to expand on the older MBR partitioning scheme. GPT is commonly used in computers with UEFI firmware. Most modern operating systems now support GPT.

### MBR vs. GPT

| MBR                                         | GPT                                                                   |
| ------------------------------------------- | --------------------------------------------------------------------- |
| max 4 primary partitions                    | max 128 partitions in Windows                                         |
| max partition size of 2TB                   | max partitions size of 9.4ZB (9.4 x 10^21 bytes)                      |
| no partition backup                         | stores a partition table backup                                       |
| partition and boot data stored in one place | partition and boot data stored in multiple locations acresso the disk |
| any computer can boot                       | computer must be UEFI-based and run a 64-bit OS                       |
### Partitions
A hard drive can be segmented into different types of partitions and logical drives. A technician should understand the process and terms relating to hard drive setup.

#### Primary
The primary partition contains the operating system files and is usually the first partition. A primary partition cannot be subdivided into smaller sections. On a GPT partitioned disk, all partitions are primary partitions. On an MBR partitioned disk, there can be a maximum of four primary partitions.

##### Active
On MBR disks, the active partition is the partition used to store and boot an operating system. Note that only primary partitions can be marked active on MBR disks. Another limitation is that only one primary partition per disk can be marked active at one time. In most cases, the C: drive is the active partition and contains the boot and system files. Some users create additional partitions to organize files or to be able to dual-boot the computer. Active partitions are only found on drives with MBR partition tables.

#### Extended
If more than 4 partitions are required on an MBR partitioned disk, one of the primary partitions can be designated an extended partition. After the extended partition is created, up to 23 logical drives (or logical partitions) can be created within this extended partition. A common setup is to create a primary partition for the OS (drive C:) and allow an extended partition to occupy the remaining free space on a hard drive, right after a primary partition. Any extra partitions can be created within the extended partition (drives D:, E: and so on). While the logical drives can’t be used to boot an OS, they are perfect for storing user data. Notice that there can be only one extended partition per MBR hard drive and that extended partitions are only found on drives with MBR partition tables.

##### Logical Drive
A logical drive is a section of an extended partition. It can be used to separate information for administrative purposes. Because GPT partitioned drives cannot have an extended partition, they do not have logical drives.

#### Basic Disk
A basic disk (the default) contains partitions such as primary and extended as well as logical drives which are formatted for data storage. More space can be added to a partition by extending it into adjacent, unallocated space, as long as it is contiguous. Either MBR or GPT can be used as the underlying partition scheme of basic disks.

#### Dynamic Disk
Dynamic disks provide features not supported by basic disks. A dynamic disk has the ability to create volumes that span across more than one disk. The size of the partitions can be changed after they have been set, even if the unallocated space is non-contiguous. Free space can be added from the same disk or a different disk, allowing a user to efficiently store large files. After a partition has been extended, it cannot be shrunk without deleting the entire partition. Either MBR or GPT can be used as the partition scheme of dynamic disks

#### Formatting
This process creates a file system on a partition for files to be stored.

#### Recovery
Some computers that have Windows installed contain a section of the disk that is inaccessible to the user. This partition, called a recovery partition, contains an image that can be used to restore the computer to its original configuration.

The recovery partition is often hidden to prevent it from being used for anything other than restoration. To restore the computer using the recovery partition, you often must use a special key or key combination when the computer is starting. Sometimes, the option to restore from the factory recovery partition is located in the BIOS or a program from the manufacturer that is accessed in Windows. Contact the computer manufacturer to find out how to access the partition and restore the original configuration of the computer.

**Note**: If the operating system has been damaged because of a faulty hard drive, the recovery partition may also be corrupt and not able to recover the operating system.

## File Systems
A new installation of an OS proceeds as if the disk were brand new. No information that is currently on the target partition is preserved. The first phase of the installation process partitions and formats the hard drive. This process prepares the disk to accept the new file system. The file system provides the directory structure that organizes the user’s operating system, application, configuration, and data files. There are many different kinds of file systems and each one has different structure and logic. Different file systems also differ in properties of speed, flexibility, security, size and more. Here are five common file systems:
- **File Allocation Table, 32 bit (FAT32)** - Supports partition sizes up to 2 TB or 2,048 GB. The FAT32 file system is used by Windows XP and earlier OS versions.
- **New Technology File System (NTFS)** - Supports partition sizes up to 16 exabytes, in theory. NTFS incorporates file system security features and extended attributes. Windows 8.1, Windows 7, and Windows 10 automatically create a partition using the entire hard drive. If a user does not create custom partitions using the New option, as shown in the figure, the system formats the partition and begins installing Windows. If users create a partition, they will be able to determine the size of the partition.
- **exFAT (FAT 64)** - Created to address some of the limitations of FAT, FAT32, and NTFS when formatting USB flash drives, such as file size and directory size. One of the primary advantages of exFAT is that it can support files larger than 4GB.
- **Compact Disc File System (CDFS)** - Created specifically for optical disk media.
- **NFS (Network File System)** - NFS is a network-based file system, that allows file access over the network. From the user’s standpoint, there is no difference between accessing a file stored locally or on another computer on the network. NFS is an open standard which allows anyone to implement it.

**Quick Format versus Full Format**
The quick format removes files from the partition but does not scan the disk for bad sectors. Scanning a disk for bad sectors can prevent data loss in the future. For this reason, do not use the quick format for disks that have been previously formatted. Although it is possible to quick format a partition or a disk after the OS is installed, the quick format option is not available when installing Windows 8.1 and Windows 7.

The full format removes files from the partition while scanning the disk for bad sectors. It is required for all new hard drives. The full format option takes more time to complete.

## Disk Cloning
Installing an OS on a single computer takes time. Imagine the time it would take to install operating systems on multiple computers, one at a time. To simplify this activity, administrators usually elect a computer to act as a base system and go through the regular operating system installation process. After the operating is installed in the base computer, a specific program is used to duplicate all the information on its disk, sector by sector, to another disk. This new disk, usually an external device, now contains a fully deployed operating system and can be used to quickly deploy a fresh copy of the base operating system and any installed applications and data without the lengthy installation process or user involvement. Because the target disk now contains a sector-to-sector mapping of the original disk, the contents of the target disk is an image of the original disk.

If an undesirable setting is accidentally included during the base installation, an administrator can use Microsoft’s System Preparation (Sysprep) tool to remove it before creating the final image. Sysprep can be used to install and configure the same OS on multiple computers. Sysprep prepares the OS with different hardware configurations. With Sysprep, technicians can quickly install the OS, complete the last configuration steps, and then install applications.

To run Sysprep in Windows 10, open Windows Explorer and navigate to C:WindowsSystem32sysprep. You can also just type “sysprep” in the Run command and click “OK.”

The figure shows the Sysprep tool in Windows.
![[8b2b12277a5b88a9d258c387224872a1c0ae3107.jpg]]

# [[Microsoft Windows]]
The most widely used workstation operating system. It can be installed on a wide variety of compatible hardware from many manufacturers, and it is commonly used in homes, schools, and offices. For the CompTIA A+ 1102 exam, you must be able to identify basic features of common editions.

## Windows 11
Like Windows 10, Windows 11 is an upgrade from the previous version. Most of the changes are superficial, like smaller taskbar icons that are placed in the center. There are also other visual additions such as a better dark mode, transparency changes, and animation changes, among others. Widgets have been expanded and are now more personalized. The settings application has been redesigned with a menu on the left, making navigation easier. There are also minor convenience additions for Windows tablets running Windows 11, including better spacing of taskbar icons and a three-finger swipe to customize actions. Windows 11 is more energy efficient, yet usually performs faster than previous versions. Finally, all versions of Windows 11 are 64-bit only, so it will not install on older, 32-bit computers.

## Windows 10 Editions
Windows 10 has had **[15 total editions released]** with **[10 editions still in use]** today. Windows 10 is an update from the previous version of Windows designed for personal computers, tablets, embedded devices, and Internet of Things devices. This version integrated the Cortana virtual assistant, combined the Windows 7 style start menu, the Windows 8 live tiles in desktop mode, and included the new Microsoft Edge Web browser. There are twelve different editions of Windows 10 with varying feature sets and use cases to meet the needs of consumer, business, and education environments. For the purposes of the exam, only the Windows Home, Pro, Pro for Workstations, and Enterprise editions will be focused on.

Windows 10 was offered as a free upgrade from Windows 7, Windows 8, and Windows 8.1. 

#### Home
Windows 10 **[comes preinstalled]** on vendor hardware and is referred to as the original equipment manufacturer (OEM) OS. Windows 10 is also available as a retail product but lacks the ability to join a domain, which other Windows editions offer.

#### Pro
Windows Pro allows the user to join corporate domains, which makes it the **[most common OEM OS]** and the premier Windows retail edition offering.

#### Pro for Workstations
Windows Pro for Workstations supports up to four CPUs and 6 TB of memory as well as remote directory memory access (RDMA) and non-volatile dual inline memory modules (NVDIMM), which makes it **[ideal for high-end workstations]** that require more than two CPUs and over 2 TB of memory.

#### Enterprise
Windows 10 Enterprise offers all the same functionality as Windows Pro for workstations and **can be volume licensed** for larger enterprises.

### Feature Differences
The features that are offered by the Windows OS depend on the edition of Windows purchased or preinstalled.

#### Domain Access vs. Workgroup
**[Domain access]** is the ability of the OS to connect to a domain-joined network of computers that provide centralized authentication, administration, and auditing. It is often found in large corporate networks. Domain access is supported in the Windows Pro, Pro for Workstations, and Enterprise editions. A **[Workgroup]** is the default mode for the Windows OS and is a decentralized collection of computers or workstations. Windows Home only has the workgroup capability and not domain access.

#### Desktop Styles/User Interface
The Windows desktop and user interface are very similar to previous editions of Windows going back to Windows 95. Users are, however, able to easily customize and personalize the desktop and user interface through the Settings menu. Standard items found on the Windows desktop include the Start menu, the taskbar, and various icons or shortcuts.

#### Availability of Remote Desktop Protocol (RDP)
Remote Desktop Protocol (RDP) is not supported on Windows Home, but it is supported on Windows Pro, Pro for Workstations, and Enterprise.

#### Random-Access Memory (RAM) Support Limitations
Windows Home supports 128 GB of RAM and two CPUs. Windows Pro supports 2 TB of RAM and two CPUs. Windows Pro for Workstations supports 6 TB of RAM and four CPUs. Windows Enterprise supports 6 TB of RAM and two CPUs.

#### BitLocker
An **[encryption program]** that allows for drive encryption to protect files. BitLocker is not available with Windows Home edition but is available with Windows Pro, Windows Pro for Workstations, and Windows Enterprise.

#### gpedit.msc
The **[group policy feature]** is available on all of the covered editions except for Windows Home. Group policy allows for all domain-connected computers to have group policies and permissions applied through the domain. Group policies may also be applied locally by using the `gpedit.msc` command.

### Upgrade Paths
Vary depending on the edition of Windows installed. It is recommended that the OS is upgraded with **[like-to-like editions]**. Upgrading to an elevated edition requires the use of an activation key. Also, be aware of the recommendations to upgrade to newer versions of the current version before upgrading to Windows 10. For example, before upgrading to Windows 10 from Windows 8, it is recommended that the OS is first upgraded to Windows 8.1.

#### In-Place Upgrade
An in-place upgrade is a straight upgrade from the current edition to the latest edition as long as system requirements are met.

### Microsoft Command-Line Tools
Microsoft command-line tools are command lines specific to Microsoft operating systems. You will need to know the appropriate command-line tool when given a scenario.

#### Navigation
Using the command line allows the user to navigate the file system using predetermined commands.

cd—The `cd` command allows the user to change directories and is shorthand for the `chdir` command.

dir— The `dir` command allows the user to view a listing of files and folders/subdirectories in a directory.

md—The `md` command allows the user to make a directory and is shorthand for the `mkdir` command.

rmdir— The `rmdir` command allows the user to delete directories. The `rd` command is shorthand for this.

##### Drive Navigation Inputs
The `cd` command allows for navigation within the current drive. To navigate to another drive, you may use the drive letter followed by a semicolon command.

- `C`— Changes to C drive
- `D`— Changes to D drive
- `x`— Changes to X drive

#### Command-Line Tools
Used for numerous other functions, such as testing or tracing network connectivity or paths. You should be familiar with common command-line tools.
- ipconfig— The `ipconfig` command is used to display basic connectivity information, such as the IP address, subnet mask, and default gateway. This command is highly useful in diagnosing network issues.
- ping—The `ping` command is used to verify network connectivity by sending an Internet Control Message Protocol (ICMP) packet to a specified address, such as the default gateway.
- hostname—The `hostname` command is used to pull up the identity of the computer the Command Prompt is open on.
- netstat— The `netstat` command is used to display all the listening and established connections on the host network.
	- [-s] Lists current NetBIOS sessions and statistics, using NetBIOS names
	- [-S] Lists current NetBIOS sessions and statistics, using IP addresses 
	- [-r] Lists names resolved by local broadcast or a WINS server
	- [-R] Purges and reloads remote cache name table
	- [-RR] Like -R, but first release, then re-registers all NetBIOS name with name server.
	- [-a RemoteName] Lists the NetBIOS table of a remote PC with the specified NetBIOS name
	- [-A IPAddress] Lists the Net BIOS table of a remote PC with the specified IP address
	- [-c] Lists the Net BIOS cache table, including both names and IP addresses
	- [Interval] Repeats results at the specified interval (in seconds) until you press CTRL+C to stop
- nslookup—The `nslookup` command is used to verify DNS addresses. This command can be used for inline query or interactively.
- chkdsk—The `chkdsk` command is used to view information about the hard disk, including the creation and viewing of reports, as well as to correct file system problems and disk errors.
- net user—The `net user` command is a subcommand used to list all local accounts on the host system.
- net use—The `net use` command is used to map drive letters to network shares.
- tracert—The `tracert` command is used to show the path a packet takes on a network to arrive at a specified destination.
- format— The `format` command is used to remove data from disks and prepare disks for new use.
- xcopy—The `xcopy` command is used to copy folders and files.
- copy—The `copy` command is used to copy specified files.
- robocopy—The `robocopy` command is used to copy files while keeping permissions intact.
- gpupdate—The `gpupdate` command is used to update group policies.
- gpresult—The `gpresult` command is used to view the report/values of the Resultant Set of Policy (RSoP) for a remote user and the users’ computer.
- shutdown—The `shutdown` command can be used for scheduling a complete shutdown or a restart remotely or locally.
- sfc—System File Checker, or the `sfc` command, is a utility command that verifies and checks the version of the file system on the computer.
- [command name]/?—The `/?` command is used to provide help for a specified command.
- diskpart—The `diskpart` command is a tool for managing disks, partitions, and volumes.
- pathping—The `pathping` command is a mixture of the `tracert` and `ping` commands.
- winver—The `winver` command is used to Windows version information in a GUI dialog box. Version information provided includes the current version, the build number, and licensing information.

---

### Operating System (OS)
For the exam, you must be able to use common features and tools offered by the Microsoft Windows 10 OS. Questions pertaining to these features will be scenario based.

### Task Manager
A utility that displays and manages running applications and services, logged-in users, and system performance.

#### Services
This tab shows you the name of running services along with identification information, such as its description, group, and status.

#### Startup
This tab shows what services have been set to begin upon startup and their associated identifying information.

#### Performance
This tab shows how the CPU, Memory, Disk I/O, and network resources are utilized. It can be very helpful in identifying a bottleneck in a slow-running computer.

#### Processes
This tab lists the currently running processes and resource consumption.

#### Users
This tab shows currently logged-in users, their status, and applications run by these users.

### Microsoft Management Console (MMC) Snap-In
A GUI for running administrative and configuration tools.

**[Event Viewer]** (`eventvwr.msc`)—used to view application error logs, system errors, and security audit records.

**[Disk Management]** (`diskmgmt.msc`)—used to view disk information on the physical disk and the formatted file systems it contains.

**[Task Scheduler]** (`taskschd.msc`)—allows you to configure automated tasks that will run on a schedule at specified times.

**[Device Manager]** (`devmgmt.msc`)—allows you to view the status of devices, view the properties, and modify the configuration parameters.

**[Certificate Manager]** (`certmgr.msc`)—used to manage and view the certificates used by the OS and web browser.

**[Local Users and Groups]** (`lusrmgr.msc`)—As a system administrator, you need to know how to create and delete users and maintain their accounts, as well as how to establish secure passwords.

**[Performance Monitor]** (`perfmon.msc`)—displays in real time how the computer uses memory, disk, CPU, and the network, to help diagnose performance issues.

**[Group Policy Editor]** (`gpedit.msc`)—used to edit the local group policy for the OS.

### Additional Tools
The MMC offers these additional tools beyond the original monitoring and configuration tools.

**[System Information]** (`msinfo32.exe`)—displays advanced hardware and driver information.

**[Resource Monitor]** (`resmon.exe`)—shows how resources are being utilized by the CPU, memory, disk, and network.

**[System Configuration]** (`msconfig.exe`)—can be run by the `msconfig` command. It allows you to change how Windows boots and what programs start with Windows.

**[Disk Cleanup]** (`cleanmgr.exe`)—frees up space while not affecting the integrity of the files.

**[Disk Defragment]** (`dfrgui.exe`)—relocates pieces of large files to continuous space on a disk for optimized performance.

**Registry Editor** (`regedit.exe`)—allows the user to view and change the Windows registry. The registry contains some operating system and application settings that may need to be changed in advanced troubleshooting.

### Control Panel Utility
The Control Panel includes tools and utilities to view, change, and troubleshoot system settings. Questions in this section will begin with a scenario.

#### Internet Options
A utility to manage network settings beyond basic IP connectivity. The settings are separated into multiple tabs.

#### Devices and Printers
Lists printers, scanners, cameras, monitors, and other connected peripheral devices; the settings of these devices can also be accessed.

#### Programs and Features
Used to view and uninstall desktop applications installed on the OS.

#### Network and Sharing Center
In the Network and Sharing Center you can configure network adapters, create new network and dial-up connections, and configure network file and printer sharing.

#### System
The Control Panel utility that shows the hardware overview.

#### Windows Defender Firewall
The Windows Defender Firewall protects the computer by controlling what applications can access the network from this computer and also how this computer can be accessed over the network.

#### Mail
In Mail, emails can be configured, including Microsoft Outlook. Additional data files, RSS feeds, internet calendars, address books, and SharePoint lists can also be configured here.

#### Sound
The Sound screen is where you can manage devices to play and record sounds and configure sounds that the operating system produces for startup, shutdown, alerts, and prompts.

#### User Accounts
You can add, manage, and remove local users and their roles for the computer in User Accounts. Each user will have their own profile with different settings and user folders.

#### Device Manager
Lists all hardware connected to the computer and provides management for drivers of the devices.

After installation, verify that all hardware is installed correctly. The Device Manager is used to locate device problems and install the correct or updated drivers in Windows.

The figure shows the Windows Update and Device Manager utilities on Windows 10.

#### Indexing Options
Systematically indexes files, including Office documents, PDFs, text files, etc.

#### Administrative Tools
A shortcut to tools used in the administration of the OS.

#### File Explorer Options
Allows you to change how files are shown and searched.

##### Show Hidden Files
**[Hidden]** is a file flag that signifies that users don’t usually need to see certain files, like system and configuration files. Windows settings can be changed to show these files if they need to be accessed.

##### Hide Extensions
In Windows files have extensions at the end of the file name, after a period (e.g., .txt, .docx, .exe). To make the file names cleaner and prevent users from making accidental changes to the extensions, these are usually hidden. This can be changed with this setting.

##### General Options
The General tab of the **[File Options]** utility allows you to change the general behavior of the file browsing interface.

##### View Options
The View tab allows you to change appearance options, including showing hidden files and file extensions.

#### Power Options
You can choose what pressing the power button on the computer should do and configure the monitor and computer power to be reduced after a specified period of inactivity.

##### Hibernate
A power option that saves the current state of the computer and shuts it down. When started again, it restores to the same state, but without consuming power in the meantime.

##### Power Plans
There are three power plans that can be configured and selected depending on the current need: Power Saver, Balanced, and High Performance.

##### Sleep/Suspend
The Sleep or Suspend mode doesn’t shut down the computer like Hibernation does, but instead significantly reduces the power to the components for a quick restart where you left it.

##### Standby
The term _Standby_ is sometimes used interchangeably with _Sleep_ but is not used in the current Windows versions.

##### Choose What Closing the Lid Does
This option is only available on devices that contain a lid closure sensor.

##### Turn on Fast Startup
The Fast Startup function places the system into hibernation during shutdown so that the system can boot more quickly.

##### Universal Serial Bus (USB) Selective Suspend
This function allows the administrator to choose to suspend power to a device connected to a specified USB port.

#### Ease of Access
Ease of Access allows for a Windows OS to be configured for motor- and sensory-impaired users.

## Windows Upgrades
The process of upgrading the OS can be quicker than performing a new installation. The upgrade process varies depending on the version of Windows being upgraded.

The version of an OS determines available upgrade options. For example, a 32-bit OS cannot be upgraded to a 64-bit OS. Also, Windows 7 and Windows 8 can be upgraded to Windows 10 but Windows Vista and Windows XP cannot.

**Note**: Prior to performing an upgrade, back up all data in case there is a problem with the installation. Also, the version of Windows being upgraded must be activated.

To upgrade Windows 7 or Windows 8 to Windows 10, use the Windows 10 Update Assistant available on the Download Windows 10 website shown in the figure. The Windows 10 update assistant installs and runs directly on the computer being upgraded. The tool will walk the user through all the steps in the Windows 10 setup process. It is designed to prepare your computer for upgrading by checking for compatibility issues and downloading all necessary files to start the install.

Computers running Windows XP or Windows Vista do not have an upgrade path to Windows 10 and require a clean installation. Windows 10 installation media can be created using the Create Windows 10 installation media tool. This tool creates installation media (USB flash, DVD, or ISO file) which can be used to perform a clean installation.

### Methods
#### In-place upgrade
The simplest path to upgrade a PC that is currently running Windows 7 or Windows 8.1 to Windows 10 is through an in-place upgrade. This will update the operating system and migrate apps and settings to the new OS. The System Center Configuration Manager (Configuration Manager) task sequence can be used to completely automate the process. The figure shows the Configuration Manager upgrade task sequence for Windows 10.

When upgrading Windows 7 or Windows 8 to Windows 10, the Windows installation program (Setup.exe) will perform an in-place upgrade, which automatically preserves all data, settings, applications, and drivers from the existing operating system version. This saves effort because there is no need for complex deployment infrastructure.

**Note**: Any user data should be backed up before performing the upgrade

#### Clean install
Another way to upgrade to a newer version of Windows is to perform a clean upgrade. Because a clean install will wipe the drive completely, all files and data should be saved to some form of backup drive.

Before a clean install of Windows can be performed, the installation media will need to be created. This can be on a disc or flash drive that the PC can boot from to run the setup. Windows 7, 8.1, and 10 can be downloaded directly from Microsoft. The download Windows web site includes the directions to create the installation media.

![[383a8674485298b94205a526f167d57e93e77ab8.png]]

**Note**: A valid product key is needed for the particular Windows version and edition in order to activate Windows after the installation process.

## Windows Settings
Windows settings is designed to make configuring and personalizing the Windows OS more convenient for end users. Questions on these topics will begin with a scenario.

### Time and Language
Changes related to date, time, and language settings can be configured here.

### Update and Security
Settings related to the configuration of updates and security can be accessed here.

To update the OS after the initial installation, Microsoft Windows Update is used to scan for new software and install service packs and patches.

### Personalization
The personalization applet can be used to change the display settings of the OS, including backgrounds, colors, fonts, etc.

### Apps
The Apps section allows you to change the source of apps as well as uninstall apps.

### Privacy
Privacy allows you to configure privacy settings on the OS.

### System
The System applet offers the option to configure OS settings, including monitor configurations, the display settings, resolution, and scale settings, among others.

### Devices
In the Devices applet, you are able to view, configure, and control connected devices.

### Network and Internet
Here, you can configure network adapters, create new network and dial-up connections, and configure network file and printer sharing.

### Gaming
The Gaming applet provides integration between the XBox platform and the computer through the XBox game bar.

### Accounts
The accounts section is used to manage and configure user accounts and other accounts on the OS.

---

## Networking Features
Windows comes with many abilities to effectively use network resources. You must be able to configure networking features on a client/desktop. This will be presented as a scenario-based question.

### Workgroup vs. Domain Setup
There are three primary networking models in the Windows OS: the homegroup, the workgroup, and the domain. Workgroup allows the OS to be both a server and a client and is primarily used in small office/home office (SOHO) setups. With the domain networking model, the client must be joined to the domain.

#### Shared Resources
Windows allows sharing of files and folders over the network, allowing a shared space for network users. For convenience, **network shares** can be mapped to a drive letter. For the users and applications, the network share appears like a local disk. Other resources, such as hardware-based resources, can also be shared among the networking group.

**[Administrative shares]** are created automatically to allow remote administrators to configure the computer. These shares are not shown and are not accessible to non-administrative users.

#### Printers
You can use the **[printer sharing]** functionality to allow printing from other computers to the printer connected locally. To print using a shared printer on a remote computer, it needs to be **mapped** first, installing the drivers for the printer.

#### File Servers
May also be shared among the networking group.

#### Mapped Drives
Mapping drives allows for network shares to be connected to a specified drive letter for ease of access among the networking group.

### Local OS Firewall Settings
Windows comes with configurable firewall rules to allow or block certain applications or network ports and control security.

#### Application Restrictions and Exceptions
When installing a new application that needs access to the network, Windows may ask if it should be allowed and add an exception to the firewall. You may also apply application restrictions through the firewall.

#### Configuration
Windows Firewall can be manually configured to allow or deny applications and network ports. It can also be switched off completely for the type of network. This effectively allows all network traffic and has to be used extremely carefully to avoid exposing the computer to potential network threats and unauthorized access.

### Client Network Configuration
The client will automatically connect and configure to the connected router or server if the router supports the Dynamic Host Configuration Protocol (DHCP) with an IP address, subnet mask, default gateway, and the DNS server. These configurations may also be configured manually.

#### Internet Protocol (IP) Addressing Scheme
The IP address of a Windows computer can be dynamically acquired from a DHCP server on the network, or configured manually. The IP address needs to be in the same subnet with other hosts and the gateway but be unique.

#### Domain Name System (DNS) Settings
DNS are servers that resolve names (e.g., microsoft.com) to an IP address that the computer can communicate with. More than one DNS server can be configured for reliability.

#### Subnet Mask
A subnet mask determines what hosts are on the same network as the local computer. It needs to match all the computers and network devices on the local network.

#### Gateway
A default gateway is a router that can forward the network traffic from the local network to other remote networks. At least one of its interfaces has to be on the same local network as the computer.

#### Static vs. Dynamic
A **[static IP address]** is a specific IP address that is assigned to a computer on the network. A static IP address will remain the same until manually changed. A **[dynamic IP address]** changes each time the computer connects to the network based on currently available IP addresses.

### Establish Network Connections
There are multiple ways to connect a Windows computer to a local or remote network.

#### Virtual Private Network (VPN)
A virtual private network uses another underlying network, usually the internet. It allows secure access to a remote location over public infrastructure.

#### Wired
Wired connections usually come in a form of **ethernet** to the computers. It requires cabling to every computer and may require other network devices like switches and routers.

#### Wireless
Wireless network connections use Wi-Fi technology to connect. Because it is not physically restricted in the area, the network will usually have another layer of security in the form of a password or **more complex authentication**. Once connected, the functionality is very similar to a wired connection.

#### Wireless Wide Area Network (WWAN)
Similar to mobile phones that can access the internet from anywhere, a WWAN is a cellular network that can be used to connect to the network. Some tablets and laptops come with built-in cellular hardware.

### Proxy Settings
A proxy server is a form of a gateway. A common example is a web proxy that is set up to filter access to the internet from a local network to improve security.

### Public Network vs. Private Network
A public network is one that is accessible to everyone within range while a private network is protected and limited to those who have proper authentication.

### File Explorer Navigation – Network Paths
Within a network, File Explorer navigation is achieved through pre-configured network paths. The Universal Naming Convention (UNC) path is the standard way to navigate to the server and fileshare in the Windows OS.

### Metered Connections and Limitations
Metered connections are **[based on usage]** and come with limitations to keep usage down. When using a metered connection, updates, whether they be for the OS, application, or system security, will not download and install.

## Boot Sequence
After POST, the BIOS locates and reads the configuration settings that are stored in the CMOS memory. The boot device priority, as shown in the figure, is the order in which devices are checked to locate the bootable partition. The boot device priority is set in the BIOS and can be arranged in any order. The BIOS boots the computer using the first drive that contains a valid boot sector. This sector contains the Master Boot Record (MBR). The MBR identifies the Volume Boot Record (VBR) which loads the boot manager, which for Windows is bootmgr.exe.

Hard drives, network drives, USB drives, and even removable media can be used in the boot order, depending on the capabilities of the motherboard. Some BIOS also have a boot device priority menu that is accessed with a special key during computer startup. You can use this menu to select the device to boot as shown in the figure.

![[f73756dfd104490f30df1db9c1f1cd05095640d5.jpg]]

### Windows 7 Startup Modes
Some problems will prevent Windows from starting up. To troubleshoot and fix this kind of problem, use one of the many Windows Startup Modes.

Pressing the F8 key during the boot process opens the Windows Advanced Boot Options menu, as shown in the figure. This allows users to select how they wish to boot Windows. These are four commonly used startup options:
- **Safe Mode** – A diagnostic mode used to troubleshoot Windows and Windows startup issues. Functionality is limited as many device drivers are not loaded.
- **Safe Mode with** Networking - Starts Windows in Safe Mode with networking support.
- **Safe Mode with Command Prompt** - Starts Windows and loads the command prompt instead of the GUI.
- **Last Known Good Configuration** - Loads the configuration settings that were used the last time that Windows started successfully. It does this by accessing a copy of the registry that is created for this purpose.

![[3fbcd833fe7f9f91432b9d2f7df61bb8150d1c70.jpg]]

**Note**: Last Known Good Configuration is not useful unless it is applied immediately after a failure occurs. If the machine is restarted and manages to open Windows, the registry is updated with the faulty information.

### Windows 8 and 10 Startup Modes
Both Windows 8 and Windows 10 boot too quickly to use F8 to access startup settings. Instead, hold the Shift key and select the Restart option in the Power menu. This will display the Choose an Option screen. To get the startup settings, select Troubleshoot, then from the next screen select Advanced options. Inside Advanced options select Startup settings, then on the next screen select Restart. The computer will then restart and display the Startup Settings menu shown in the figure. To choose a startup option use number or function keys F1-F9 that corresponds to the desired option.

![[3e06b6da7ea32545cf42841273d6f5417463415a.jpg]]

## Application Installation and Configuration
There are multiple methods for installing new applications and software. Some things need to be taken into consideration for the successful installation and use of applications. You must be able to apply installation and configuration concepts. Questions on these concepts will be scenario based.

### Partitioning
In the image below, two partitions were created by selecting “Drive 0 Unallocated Space” and clicking “New”. The installer also allows the user to specify the size of the new partition.
![[8f371be19fb7ede8d3fa9f3a1b93e15ab25f1f46.jpg]]

### System Requirements for Applications
The system needs to have **[enough resources]** to allow installation of new applications. The specific requirements depend on the application and can be usually found in the supporting documentation for the application.

#### 32-bit vs. 64-bit Dependent Application Requirements
Application requirements must **[match the architecture of the CPU and OS]** for either 32-bit or 64-bit architectures. However, if the architecture supports 64 bits, it will be able to properly run 32-bit applications.

#### Dedicated Graphics Card vs. Integrated
Also known as a **[discrete graphics card]**, is a separate hardware component designed specifically for rendering graphics and display tasks. On the other hand, an **integrated graphics solution** is typically built directly into the CPU of modern computers, although some older systems might have it on the motherboard. Regardless of the type, it’s essential to ensure that the graphics solution, whether integrated or dedicated, meets the requirements of the applications and OS being used.

#### Video Random-Access Memory (VRAM) Requirements
The VRAM requirements are for graphic-intensive applications, such as **[gaming]**. For the application to function properly, the VRAM requirements of the program must be met by the device.

#### RAM Requirements
To run an application, it needs to be loaded into memory. There should be sufficient RAM available or the application will run slowly, slowing down other processes too, or it will not be able to run at all.

#### Central Processing Unit (CPU) Requirements
The CPU requirements of an application are typically given in gigahertz (GHz) and show the amount of processing power the application requires. These requirements need to be met or exceeded for proper functionality.

#### External Hardware Tokens
Physical devices that can be connected to the device for increased security. The requirements for the hardware token must be met or exceeded by the host computer.

#### Storage Requirements
Before running an application, its files need to be stored on the computer’s disk. There should be enough free disk space to copy and use the program’s files.

### OS Requirements for Applications
An application expects to work with a specific operating system. The installation of the software should be compatible with the OS. Refer to the application’s documentation to find out what operating systems are supported.

#### Application to OS Compatibility
The application needs to be compatible with the host OS. Many applications come in multiple OS-compatible versions so make sure you are installing a Windows-compatible application on a Windows OS.

#### 32-bit vs. 64-bit OS
Applications that require a 64-bit OS will not be compatible with a 32-bit OS, but a 32-bit application will be compatible with a 64-bit OS.

### Installation Methods
A standard installation of Windows is sufficient for most computers used in a home or small office environment but there are cases when a custom installation process is required.

Take, for example, an IT support department; technicians in these environments must deploy hundreds, even thousands of Windows systems. Performing this many installations in the standard way is not feasible.

A standard installation is done via the installation media (DVD or USB drive), provided by Microsoft and is an interactive process; the installer prompts the user for settings such as time zone and system language.

A custom installation of Windows can save time and provide a consistent configuration across computers within a large organization. A popular technique to install Windows across many computers is to perform installation in one computer and use it as a reference installation. When the installation is completed, an image is created. An image is a file that contains all the data from a partition.

When the image is ready, technicians can perform a much shorter installation by simply replicating and deploying the image to all computers in the organization. If the new installation requires any adjustments, those can be done quickly after the image is deployed.

Windows has several different types of custom installations:
- **Network Installation** – This includes Preboot Execution Environment (PXE) Installation, Unattended Installation, and Remote Installation.
- **Image-based Internal partition Installation** - This is a Windows image stored on an internal (often hidden) partition that can be used to restore Windows to its original state when it was shipped from the factory.
- **Other Types of Custom Installations** – This includes Windows Advanced Startup Options, Refresh your PC (Windows 8.x only), System Restore, Upgrade, Repair installation, Remote network installation, Recovery partition, and Refresh/restore.

#### Remote Network Installation
A popular method for OS installation in environments with many computers is a remote network installation. With this method, the operating system installation files are stored on a server so that a client computer can access the files remotely to begin the installation. A software package such as Remote Installation Services (RIS) is used to communicate with the client, store the setup files, and provide the necessary instructions for the client to access the setup files, download them, and begin the operating system installation.

Because the client computer does not have an operating system installed, a special environment must be used to boot the computer, connect to the network, and communicate with the server to begin the installation process. This special environment is known as the Preboot eXecution Environment (PXE). For the PXE to work, the NIC must be PXE-enabled. This functionality may come from the BIOS or the firmware on the NIC. When the computer is started, the NIC listens for special instructions on the network to start PXE.

The figure shows the client loading setup files from the PXE server over TFTP.

**Note**: If the NIC is not PXE-enabled, third-party software may be used to load PXE from storage media.

A Windows PXE Installation
![[02209077c6c1db04168d42388ea2aff5fcd34315.png]]

#### Unattended Network Installation
Unattended installation, another network-based installation, allows a Windows system to be installed or upgraded with little user intervention. The Windows unattended installation is based on an answer file. This file contains simple text that instructs Windows Setup how to configure and install the OS.

To perform a Windows Unattended installation, setup.exe must be run with the user options found in the answer file. The installation process begins as usual but instead of prompting the user, Setup uses the answers listed in the answer file.

To customize a standard Windows 10 installation, the System Image Manager (SIM), shown in the figure, is used to create the setup answer file. You can also add packages, such as applications or drivers, to answer files.

The answer file is copied to the distribution shared folder on a server. At this point, you can do one of two things:
- Run the unattended.bat file on the client machine to prepare the hard drive and install the OS from the server over the network.
- Create a boot disk that boots the computer and connects to the distribution shared folder on the server. You then run a batch file containing a set of instructions to install the OS over the network.

**Note**: Windows SIM is part of the Windows Automated Installation Kit (AIK) and can be downloaded from the Microsoft website.

### Distribution Methods
There are multiple ways to distribute software installation files.

#### Physical Media vs. Downloadable
The only way to install new software on a computer that is not connected to any network is to have the application on a **[portable media]**, **[CD]**, or **[USB disk]**. This can also be useful for large applications or slow networks. The installation files can be run directly from the media or copied to the hard disk first and then installed.

On computers connected to a network, applications can be installed over the network and not from portable media or local files. If the application is acquired from the internet, the files are first copied to the local disk, then installed. Operating systems also include forms of application stores and repositories that make it easy to find and install new software.

#### ISO Mountable
An ISO mountable application installation is one in which the application ISO is downloaded from the vendor and installed directly onto the host machine and acts as a virtual optical drive.

### Other Considerations for New Applications
Besides hardware and compatibility requirements, there are other considerations before a new application is installed.

#### Impact on Device
Installing a new application may allow it access to other files on the computer. Some software can be **malicious** and may need to be researched before installation. Even if there are no ill intentions, some functions of the software may not be suitable for protected corporate environments with sensitive information.

#### Impact on Network
If a new application is installed on a computer that is connected to the network, it will effectively get access to the network and may **[compromise the security]** of other computers on the same network.

#### Impact on Operation
New applications can affect the operations of the OS and its information system. These effects can be negative and may **[compromise the efficiency]** of the computer.

#### Impact on Business
Before installing new applications on a computer connected to a business network, the effects of the application on the functioning of the business should be considered and evaluated for **[potentially harmful effects]** to the business.

---

# Common OS Types

You must be able to identify common OS types and their primary purposes.

### Workstation OSs

Workstation operating systems are designed to be used on a desktop or a laptop computer by one person at a time. These operating systems provide a convenient **[[Graphical User Interface (GUI)]]** and access to files and applications on the computer.

#### Windows

Microsoft Windows is the **[most widely used]** workstation operating system. It can be installed on a wide variety of compatible hardware from many manufacturers, and it is commonly used in homes, schools, and offices.

#### Linux
A **[[Kernel]]**, the core of the operating system. Interfaces and applications can be added to the kernel. These pre-configured combinations are known as distributions. This flexibility allows users to create various versions of systems for different cases. A distribution can have an extensive graphical user interface (GUI), like Ubuntu, or be better adapted to high performance server tasks, like Red Hat.

#### macOS
Apple’s MacOS is the operating system **designed to run on Apple workstations**. It is included with every Macintosh computer and is the second most widely used workstation OS.

#### Chrome OS
An operating system designed on the Chrome web browser and released by Google. The Chrome OS is a cloud-based OS with all of its data stored in Google Drive.

### Cell Phone/Tablet OSs
Phones and tablets are widely used, growing in hardware and performance, and raising the need for complex, powerful, yet convenient operating systems.

#### iPadOS
An iPad-specific OS released by **Apple** that provides better multitasking functionality to the iPad, making it more of a small laptop than a tablet.

#### iOS
The operating system on Apple’s iPhones and older iPads. It cannot be installed on devices not manufactured by Apple.

#### Android
An operating system developed by Google specifically for mobile devices. It is based on the Linux kernel and is free and open source. Many devices from different manufacturers around the world make phones and tablets that run the Android operating system. It is the most used mobile OS.

### Various Filesystem Types

The file system allows storing, managing, and accessing files on a partition. A partition is a segment of a hard disk that functions as a separate entity. An operating system usually supports different file systems, and a partition needs to be **formatted** with a specific file system before usage.

#### New Technology File System (NTFS)

NTFS is a file system that allows users to set and manage **permissions** for files and folders for specific users and groups, making it very useful for secure network file sharing. Additionally, it provides indexing (for faster file search), compression, and encryption on the file system level. NTFTS is much **more advanced than FAT32** and is supported by all modern Windows versions.

#### File Allocation Table 32 (FAT32)
Providing very **basic features**, FAT32 is supported by many operating systems and supports partitions up to 2 TB in size.

#### Third Extended Filesystem (ext3)
ext3 is a default filesystem for **Linux OSs**.

#### Fourth Extended Filesystem (ext4)
An updated version of ext3 that supports larger partitions and a larger number of files and improves performance.

#### Apple File System (APFS)
APFS is **proprietary to Apple** and replaces the HFS and HFS+ filesystem on Apple OSs. It is the default filesystem on macOS Sierra 10.12.4 and iOS 10.3 and later.

#### Extensible File Allocation Table (exFAT)
**Designed for small flash and SSD drives** and is optimized for performance and media file storage.

### Vendor Life-Cycle Limitations
Once an operating system is installed, it can continue running. But there are some limitations that you need to keep in mind and consider updating.

#### End-of-Life (EOL)
When an operating system reaches the end-of-life phase of its developer, there will be **no more updates**, patches, or technical support. There will probably be no more applications developed or supported for this OS version.

#### Update Limitations
When the OS **developer stops supporting** a specific version, there will be no more security patches released for that OS version. As new vulnerabilities get discovered, this may leave the computer with an outdated operating system exposed to security risks.

### Compatibility Concerns Between OSs
Applications that are available for one operating system may not be available for others. The developer of the application may limit its efforts to only one operating system. Some applications may be available for macOS and Windows (for example, Microsoft Office). Some applications may be available for macOS, Windows, and Linux (for example, Google Chrome). In any case, these are **different installation files of similar software**.

Another compatibility concern may be caused when updating an operating system to a newer version. **New versions** of operating systems can cause **issues with previously installed** hardware and applications. Many large organizations choose to not update their operating systems without thorough testing of the new version with the existing hardware and business-critical software.

## OS Installations and Upgrades
To start using an operating system, it needs to be installed on the computer. To start the installation process, the computer needs to be **booted with the installation media**. You must be able to install and perform upgrades in various OS environments. Questions about these concepts will be scenario based.

### Boot Methods
A boot method allows the user to select how to boot a computer and what media to use. There are **multiple ways** to boot a computer.

#### USB
An **external device** may be connected to a computer from which to boot. There are many types of external devices, for example: external optical drive, external hard disk, and external flash drive. Common interfaces used to connect the external drives are **Universal Serial Bus (USB)** and **eSATA**. A USB **flash drive** is a very common way to install an operating system.

#### Optical Media
A computer may have a **built-in drive** to read optical discs. A computer can be booted from this device with an installation disc. This is another common way to install an operating system on a computer.

#### Network
A network-based installation is the **most effective** way to install and upgrade when dealing with a **large network**. The installation media is uploaded onto a file share with read-only access for the installer.

#### Solid-State/Flash Drives
An **internally connected hard disk** may be used to boot. The disk can include the operating system installation image or have the operating system installed. This is the most common way to boot a computer after the operating system installation was completed.

#### Internet-Based
With an internet-based boot, the information needed to boot is stored and retrieved from the internet via an internet connection.

#### External/Hot-Swappable Drive
An external or hot-swappable drive can be connected to a device for boot functions. The boot information is stored on the external drive and not locally stored.

#### Internal Hard Drive (Partition)
It’s important to distinguish between a hard disk and a partition. In many simple configurations, there is one bootable partition on a disk. But one disk can have more than one partition, as it may be useful to have different operating systems on the same computer (**multi-boot**). Also, one logical partition can span multiple physical hard disks.

### Types of Installations
Depending on the current state of the computer, available hardware and environment, and desired setup, there are multiple ways to install an operating system.

#### Upgrade
This is an installation method that installs a newer operating system over an older one. Depending on the OS and versions, it may **preserve the settings, files, and applications**.

#### Recovery Partition
Some operating systems provide an option to create a recovery partition during the installation. It will be a bootable partition that can be used later and contains diagnostic and repair tools, or it may be used for a repair installation.

#### Clean Install
This installation disregards previous data in the destination. It can be used if the computer doesn’t have any operating system installed or if the intent is to completely delete the previous operating system, files, applications, and settings.

#### Image Deployment
If many computers have identical hardware and need identical operating systems, settings, and applications, it can be accomplished with image deployment. There are different software tools for this task, but usually the process involves the following steps:

1. Select one computer.
2. Perform a clean installation of the desired operating system, configure, and install applications.
3. Create the image from this computer.
4. Make this image available on the network or portable media.
5. Copy the image to other computers.

#### Repair Installation
Some operating systems provide this option. It is usually initiated by booting with the installation media of the same version of operating system that was previously installed, then selecting the **repair option** from the menu. It rewrites system files and settings while keeping the user files. This mode may be useful for repair purposes if the installed operating system is not bootable or shows serious issues that can’t be fixed otherwise.

#### Remote Network Installation

The **Preboot eXecution Environment (PXE) network boot** can use a remote server with the operating system’s installation files to install the OS on the computer. Depending on the configuration of the server, the installation process may require selecting installation options, just like booting from a CD, or it can be an unattended installation.

#### Other Considerations

It’s important to consider unplanned consequences of an installation. These potential consequences include data loss, application support, and hardware compatibility.

##### Third-Party Drivers

Third-party drivers must be compatible with the installed OS.

### Partitioning
Creates one or more logical drives on a physical disk. Each partition can be separately formatted and have a separate file system. In Windows, each partition can have a separate drive letter.

#### Master Boot Record (MBR)
Used with traditional BIOS and is the standard partition table. MB can have a maximum of four primary partitions or three primary partitions and one extended partition.
- 512 bytes long

#### Globally Unique Identifier (GUID) Partition Table
A GUID Partition Table (GPT) contains information on how the disk is partitioned and is used with **UEFI BIOS** only. Compared to the MBR, it supports larger drives and more partitions per drive with up to 128 primary partitions.

### Drive Format
Formatting drives when partitioning is included in the Windows installation. Drives can be formatted with a quick format or a full format.

### Upgrade Considerations
Here are some other considerations to keep in mind when upgrading and configuring the operating system.

#### Backup Files and User Preferences
When upgrading to a newer version of the Windows OS, a backup of all files should be made to ensure recoverability if the installation goes wrong. The Windows upgrade process is designed, however, to retain files and most user preferences.

#### Application and Driver Support/Backward Compatibility
Windows upgrades are typically designed to be backward compatible with older versions. How far back the compatibility reaches depends on the upgrade version. This applies to applications and driver support as well.

#### Hardware Compatibility
Ensure that the system’s hardware is supported to install and configure the desired operating system. The essential BIOS, CPU, and RAM need to support the installation. The hardware should have supported drivers to be used optimally by the OS.

### Feature Updates
Available for older OS versions and will continue to be available until the end-of-life (EOL) date for the version. Technicians must be aware of EOL as it relates to feature updates for their OS version(s).

#### Product Life Cycle
The product life cycle begins when a product is released and ends when the product is no longer supported, its EOL.

---

# macOS/Desktop OS Features and Tools
macOS and Linux operating systems come with similar utilities, tools, and commands for configuration and maintenance. You must be able to identify common features and tools of the macOS/Desktop OS.

## Installation and Uninstallation of Applications
Installing applications on the macOS is similar to the Windows OS. The application must be provided to the OS, mounted to the OS, and then installed on the OS. Applications on the macOS are available through Apple’s proprietary App Store.

#### File Types
There are multiple common types of files for the macOS, including ZIP, ISO, DMG, PKG, and APP.

**.dmg**—A .dmg file is a disk imaging file and acts just like an ISO or ZIP file.
**.pkg**—A .pkg file is an automated package installer file and can be found in a DMG, ZIP, and physical media.
**.app**—An .app file contains applications and includes files and resources the application needs as well as the executable.

#### App Store
The App Store is where applications for the macOS can be downloaded and purchased with a valid Apple ID.

#### Uninstallation Process
Applications that need to be uninstalled can be located using the Finder menu. The application being deleted is moved into the trash bin. Alternatively, you can simply select the application and press “Command” + “Delete”.

### Apple ID and Corporate Restrictions
The Apple ID is the **digital identity of the user** of a device. One Apple ID can be used on multiple devices and is linked to the Apple Wallet and App Store for purchases. Apple retains complete control over what is published to the App Store via corporate restrictions. Open-source applications are not available on the macOS unless submitted to and approved by Apple.

### Best Practices
There are some best practices for maintaining the system, data, and performance. These are the most important ones.

#### Backups
Scheduled backups create a **copy of data and configuration** that can be restored later if needed. The best practice is to frequently create backups of files and have a copy of important files at a **remote location**. This remote location may be cloud storage that can be accessed over the internet.

#### Antivirus
Antivirus software often depends on the signatures of viruses and other malicious software that needs to be updated. Make sure that the security software is configured to get frequent updates after installing it.

#### Updates/Patches
In macOS, the **System Preferences** for the **App Store** provide the configuration for system updates. You can choose to either manually or automatically download and install the updates.

Patches are smaller updates, usually addressing specific functions and features, security, and bugs. These are managed similarly to system updates. The best practice is to allow **automatic installation** of patches to improve security if the environment allows this disruption.

Drivers and hardware firmware sometimes get updated too. These are managed similarly to system updates. Again, the best practice is to **install driver updates as quickly as possible** after they’re released to improve hardware performance, but after ensuring there are no compatibility issues.

### System Preferences
The macOS is highly customizable through System Preferences and can be personalized to fit preferences and requirements.

#### Displays
In the Displays preference section, you can adjust display resolution and brightness as well as color tone and AirPlay preferences.

#### Networks
The Networks preference section controls the network connectivity of the device, such as Wi-Fi preferences, as well as geographically controlled network preferences.

#### Printers and Scanners
The Printers & Scanners section displays all relevant printer preferences, such as print priority, and settings related to connected printers and scanners. Scanners are likewise located in and configured in the Printers & Scanners preferences section.

#### Privacy
The Security & Privacy section contains numerous settings and preference choices to ensure the security of the device, such as the lock screen, the FileVault, and the firewall.

#### Accessibility
The Accessibility section allows for the customization of preferences to accommodate visual-, hearing-, and motor skills-impaired users.

#### Time Machine
The macOS’s automated backup feature and can be set to make specified backups, both incremental and full.

### Features
macOS comes with many features that are unique compared to other operating systems. It’s important to understand these features so that you can get the most out of using a Mac.

#### Multiple Desktops
The Multiple Desktop feature allows you to create multiple Spaces that can be used to organize what the user is working on. These multiple desktops can be switched back and forth as needed.

#### Mission Control
A program that allows you to view everything that is open and also quickly swap between programs. Mission Control also allows you to create multiple desktops.

#### Keychain
The Keychain feature in the Mac operating system is a tool used for password management. Items that can be stored in Keychain include passwords, private keys, certificates, and secure notes.

#### Spotlight
a search feature on the macOS. It creates an index of all the items and files on your system so you can look up items quickly.

#### iCloud
The iCloud program comes as a default on all Apple products. It is a method for storing data in the cloud. This is beneficial as a backup method for Mac users.

#### Gestures
Apple Gestures are small motions that a user can make using the trackpad to complete simple tasks. For example, to move between pages of a document, swipe left or right with two fingers. All the Gestures for Mac devices can be found under System Preferences, then by selecting Trackpad.

#### Finder
the default file manager for Mac operating systems, similar to the FIle Explorer program in Windows. Finder allows users to search for, open, and delete files from one location.

#### Remote Disc
allows smaller Mac devices that do not have a disc drive to essentially “borrow” the disc drive of a nearby device. It allows the computer without the disc drive to access the files on a disc that is being used on another device.

#### Dock

Dock in macOS is similar to the taskbar in Windows. It is the launching pad for all applications on Mac operating systems.

### Disk Utility
In macOS, the Disk Utility can be used to create and restore **disk images**. It can also be used to check for **disk errors**.

### FileVault
FileVault allows you to configure disk-level encryption for files and set user authentication for access.

### Terminal
where the user can run command lines on the macOS.

### Force Quit
If an application becomes unresponsive and needs to be closed, you may need to force quit. It will **terminate the application** and you will lose unsaved work. It can be accomplished by selecting the application and pressing the quit button in the Activity Monitor.

## Linux Client/Desktop OS
The Linux Client/Desktop OS has its own set of OS-specific common features and tools that you must be able to identify.

### Common Commands
To be successful in using Linux operating systems, you will need to be familiar with at least the most basic Linux commands. Being able to navigate the Linux terminal using these basic commands will be very beneficial. It’s important to note that Linux commands are case sensitive, so take note of the case you are using when typing them.

ls—The `ls` command is known as the **list command** in Linux. This is because the command will list all the files or folders in a given directory. In order to use this command, navigate to the folder or directory you’re interested in and type “ls”. After hitting enter, a list of all the files and folders in that location will be displayed.

pwd—While many people see the term _pwd_ and think “password,” it actually means something very different in Linux. The `pwd` command stands for **present working directory**, and it displays the full path of the current working directory.

mv— The `mv` command in Linux is the **move** command. This command allows a user to move a specified file to another location. Move is similar to a cut and paste command in Windows.

cp—The `cp` command in Linux stands for **copy**. Its functionality is similar to that of the move file, except that it places a copy in the new location while leaving the file in the original location.

rm—The `rm` command stands for **remove** in the Linux operating system. This is similar to a delete functionality, as it removes the file, directory, or other objects from the location.

chmod—To **modify Linux file permissions**, you must use the `chmod` command. Before changing Linux file permissions, it’s important to first understand how they are represented. Each permission is represented by a letter: r–the read permission; w–the write permission; x–the execute permission.

chown—While the `chmod` command changes the permissions, the `chown` command **changes the ownership** of a file, directory, or other objects.

su/sudo—The `su` command stands for **switch user** (or substitute user). The `su` command can be used by adding a username that you wish to switch to after the command (example: su linuxuser1) or it can be used by itself, which will by default switch it to the root user. The `sudo` command switches the user for a single command, while `su` switches the user until it’s switched back.

apt-get—APT stands for “advanced packaging tool.” The `apt-get` command is a tool for **handling packages** in Linux. It is used to retrieve packages from authenticated sources for installation, upgrade, and removal of packages, along with their dependencies.

yum—The `yum` command is used in file management to **update and install packages for Red Hat**-based distributions.

ip— The `ip` command is used to **display and configure information** related to a network interface card (NIC).

df—The `df` command is used in **processing files and displays the total free disk space** for a directory.

grep—The `grep` command stands for **global regular expression print**. The `grep` command is a search command. You can use it to search for a string of characters within a file or standard text output. For example, if you are viewing a file in the terminal and type the command `grep “unix”`, the terminal will display all of the instances of the word “unix” in that file.

ps—The `ps` command in Linux displays all of the currently running processes and their process numbers. For this command, the “ps” stands for **process status**.

man—The `man` command displays system **help for executable files**.

top—The `top` command also displays a list of **running processes**.

find—The `find` command can be used for **searching** for specific text within a file hierarchy.

dig—The `dig` command is used in networking and is a **DNS query utility**.

cat—The `cat` command displays the **contents** of a file.

nano—The `nano` command is a text-based **editor** for files.

### Best Practices
Best practices for the Linux OS are very similar to best practices for both Windows and Apple OSs.

#### Backups
Regular backups should be made of the system and stored in a separate location, such as a removable drive or the cloud.

#### Antivirus
Antivirus programs are available for Linux distributions and should be monitored and kept up to date.

#### Updates/Patches
Linux distros manage updates differently. In Ubuntu, the settings are very similar to macOS and accessed via the Software & Updates settings. The best practice is to install updates as quickly as possible after they’re released but after ensuring there are no compatibility issues. This practice applies to patches as well.

### Tools
You should be aware of Linux-specific tools and their uses.

#### Shell/Terminal
The shell/terminal, like other operating systems, is where the OS can be accessed via the command line. While there is GUI available for the Linux OS, the shell is a primary method of interaction with the system for many users.

#### Samba
a free and open-source software (FOSS) package that can be installed on the Linux OS to make its underlying file-system compatible with a Windows file server via the SMB Protocol.

---
# Nav
< [[Virtualization and Cloud Computing|Previous]] < ^ [[Navigation|Home]] ^ > [[Operational Procedures|Next]] >