---
tags: 
parent docs:
  - "[[Navigation]]"
sibling docs: 
child docs: 
media: []
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
As a technician, you will be responsible for adding and removing software from your customers’ computers. Most applications use an automatic installation process when the application disc is inserted in the optical drive. The user is required to click through the installation wizard and provide information when requested. Most Windows software installations are attended, meaning the user must be present to interact with the installer software to provide input about the options to use when installing the software. The various types of installations are defined in the table.

| Method              | Definition                                                                                                                                                     |
| ------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Attended            | a user must be present to respond to prompts from the installer software                                                                                       |
| Silent/Unattended   | not prompts are displayed during installation                                                                                                                  |
| Scheduled/Automated | installation that occurs without being started by a user. preconfigured tasks that run according to conditions or timers can install software when appropriate |
| Clean               | all components of any previous version of the software have been removed prior to installation                                                                 |
| Network             | the installation packages are available on a server and the installation occurs across the network                                                             |
### ISO Mountable
An ISO image is a single file that represents all the data on an optical disk. An ISO is usually distributed via the internet. For example, you can download the Windows 10 installation media from the official website of Microsoft. After the ISO image has been downloaded, its authenticity and integrity should be verified using a digital signature or a hash value provided by the source and scanned for malware.

The ISO image can be used to create installation media using a USB flash drive or optical media. Another option is to mount the ISO image directly on your PC as if it is an optical disc. Starting with Windows 10, no third-party tool is needed to mount an ISO image. Right-click the ISO file in File Explorer and select **Mount**. The ISO file is assigned a drive letter. In the figure, the Windows 11 ISO is mounted as `F: \`.

### External Hardware Tokens
An external hardware token is a portable security device that can be a smart card or a USB device. It provides a more secure multi-factor authentication method when used in conjunction with a username and password. The hardware token stores cryptographic information that identifies the user. When the user requests access, the user presents the hardware token and supplies an authorization gesture, such as entering a PIN or scanning a fingerprint to gain access.

### Application Installation
Local installation can occur from the hard drive, CD, DVD, or USB media. To perform a local, attended installation, insert the media or drive, or open the downloaded program file. Depending on autoplay settings, the software installation process may not automatically start. In that case, you will need to browse the installation media in order to find and execute the installer. Installer software usually has an EXE or MSI (Microsoft Silent Installer) file extension.

Note that the user must have the appropriate permissions in order to install the software. They must also not be blocked by group policies that prevent software installation.

After the application is installed, you can run it from the Start Menu or the shortcut icon that the application places on the desktop. Check the application to ensure that it is functioning properly. If there are problems, repair or uninstall the application. Some applications, such as Microsoft Office, provide a repair option within the installation program. In addition to the process described above, Windows 8 and 10 provide access to the Microsoft Store, as shown in the figure. The Microsoft Store allows a user to search for and install apps on Windows devices. To open the Windows Store app, search from the Start Screen taskbar by entering **Store**. Click the **Store** icon when it appears in the search results. The Windows Store app is not available in Windows 7.

### Uninstalling or Changing a Program
If an application is uninstalled incorrectly, you might be leaving files on the hard drive and unnecessary settings in the registry, which wastes hard drive space and system resources. Unnecessary files might also reduce the speed at which the registry is read. Microsoft recommends that you always use the Programs and Features Control Panel utility when removing, changing, or repairing applications. The utility guides you through the software removal process and removes every file that was installed, as shown in the figure.

Some applications may include an uninstall feature that is located in the Windows Start menu with the application.

### Compatibility Mode
Older applications may not run properly on newer Windows operating systems. Windows provides a way that these programs can be configured to run. If older software is not running properly, locate the executable file for the application. This can be done by right-clicking a shortcut for the application and selecting **Open file location**. Right-click the executable file and choose Properties. From the **Compatibility** tab you can run the **Windows compatibility troubleshooter** or manually configure the environment for the application.

### Considerations
When deploying new third-party applications, potential impacts to operation and the business must be considered to maintain a secure computing environment.

#### Security
Allowing users to install software on computers that are owned by a business organization can be a security risk. Users can be tricked into downloading malicious software that can cause data loss, either through theft or destruction. Malicious software, known as malware, can infect all computers that are attached to a network and can cause widespread damage and loss. As a technician, it is important to enforce policies regarding software installation and ensure that antimalware software, such as Windows Defender is active and up to date.

### Impact to Operation
Deploying new applications to hundreds of workstations can be a time-consuming process. Automated deployment tools can save time by automatically deploying, updating, and supporting the applications.

Organizations can use Windows deployment tools such as a Group Policy, to deploy applications to multiple workstations from a server. An administrator sets up the installer packages and copies the packages on the shared network folder for distribution. The administrator creates Group Policy Objects (GPO) in the Group Policy Manager to deploy the application from the network shared folder to the eligible users without any further intervention from the administrator. When the users' power-on the computers, the applications are installed and available.

By using deployment tools, the users are not required to log-on with administrative privileges to install the applications. The users do not require full control, only read and execute, for the program's installation directory. Any custom settings or user files can be saved to the users’ home folders, instead of the program directory. This prevents users from accidentally modifying the files related to the installed programs.

### Impact to Business
Any application deployed in a business must be supported and maintained.
- **Software licensing** – Software licensing establishes the number of devices that can install the software or number of authorized users. Using unlicensed software can expose a business to legal and financial penalties.
- **Technical support** – Depending on the availability and technical expertise of the internal IT staff, some or all the technical support maybe outsourced to the software vendor. The vendor can provide paid technical support that can provide updates and maintenance releases, monitor and fix security issues and provide technical assistance. The impact to the business should be assessed for either support method.
- **User training** – Training on programs should be available to the users if applicable. Training can be a recurring cost as the vendors deploy newer versions of the program or as part of the onboarding process for new employees. The program may also be supported by an internal team who requires more in-depth technical training to support and maintain the programs in a secure manner.

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
The terms 32-bit and 64-bit refer to the amount of data a computer's CPU can manage. A 32-bit register can store 2^32 different binary values. Therefore, a 32-bit processor can directly address 4,94,967,295 bytes. A 64-bit register can store 2^64 different binary values. Therefore, a 64-bit can directly address 18,446,744,073,709,551,615 bytes.
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

This chapter covers the various tools and applications that are available for configuring, maintaining, and troubleshooting Windows. The primary focus of this course will be Windows 10. When relevant, Windows 8 and Windows 7 will be discussed when major differences exist between them and Windows 10.

## Windows Versions
The first version of the Microsoft Windows operating system was released in 1985, over 30 years ago! Since then, over 25 versions, subversions, and varieties have been released. In addition, each version can also have editions, such as Home, Pro, Ultimate, or Enterprise, and come in either 32-bit or 64-bit versions. In the case of Windows 10, twelve editions were developed and released. However, only nine are currently offered.

The table summarizes the important features of the Windows versions that are covered in this course.

| Version | Release Date | End of Support       | Important  Changes                                                                                                                                                   |
| ------- | ------------ | -------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 11      | October 2021 | Not set              | Redesigned taskbar and icons. Increased energy efficiency. Integrated with Microsoft Teams. Improved Settings app.                                                   |
| 10      | July 2015    | October 2020 to 2025 | Improved desktop interface, combines menu entries and tiles in the Start menu. Universal apps, Windows Action Center replaces charms. Removed HomeGroup FIle Sharing |
| 8.1     | October 2013 | January 2023         | Start screen more similar to Windows 7, more interface configuration options                                                                                         |
| 8       | October 2012 | January 2016         | Interface optimized for mobile devices, anti-virus included, File Explorer instead of Windows Explorer. Unpopular and considered hard to learn                       |
| 7       | October 2009 | January 2020         | Improved interface, and taskbar, added libraries and HomeGroup File Sharing                                                                                          |

### Corporate
Corporate and personal users of Windows operating system have different needs. On a corporate network it is usually necessary to manage user accounts and system policies centrally due to the number of devices on the network and higher security requirements. Centralized management is provided through joining an Active Directory domain where the user accounts and security policies are configured on a Domain Controller. Windows Professional, Pro, Enterprise, Ultimate, and Education editions can join an Active Directory domain.

Other corporate features include:
BitLocker - A feature that enables a user to encrypt all data on a disk drive or removable drive. Found on Windows 7 Enterprise and Ultimate, Windows 8 Pro and Enterprise, and Windows 10 Pro, Enterprise, and Education Editions.

Encrypted file system (EFS) - A feature found on Windows 7 Professional, Enterprise and Ultimate, Windows 8 Pro and Enterprise, and Windows 10 Pro, Enterprise, and Education Editions that allows the user to configure file and folder-level encryption.

Branch Cache - Allows remote computers to share access to a single cache of data from shared folders and files or document portals such as SharePoint sites. This can reduce WAN traffic because the individual clients do not each need to download their own copy of cache data. Found on Windows 7 Enterprise and Ultimate, Windows 8 Enterprise, and Windows 10 Pro, Enterprise, and Education Editions.

## System Requirements

### Minimum

| Component                        | Minimum Windows 11                                        | Minimum Windows 10                  | Minimum Windows 8 or 7              |
| -------------------------------- | --------------------------------------------------------- | ----------------------------------- | ----------------------------------- |
| Processor                        | 2GHz or faster, 2 or more cores                           | 1GHz or faster                      | 1GHz or faster                      |
| RAM                              | 4GB                                                       | 1GB for 32-bit, or 2GB for 64-bit   | 2GB                                 |
| Hard Drive Space                 | 64GB                                                      | 16GB for 32-bit or 20GB for 64-bit  | 2GB                                 |
| Graphics Card                    | DirectX 12 or later, WDDM 2.0 driver                      | DirectX 9 or later, WDDM 1.0 driver | DirectX 9 or later, WDDM 1.0 driver |
| Display                          | HD (720p) display, 9" diagonally, 8bits per color channel | 1024px768p                          | 800px600p                           |
| Internet Connection              | necessary, high-speed 1.5Mbps                             | necessary, high-speed 1.5Mbps       | necessary, high-speed 512kbps       |
| [[Trusted Platform Module\|TPM]] | 2.0                                                       | none                                | none                                |

### Graphics
Two popular types of graphic cards found on PCs are integrated and dedicated.

Integrated graphics chips are integrated on the motherboard or the same die as the CPU. These graphics chips rely on the system RAM and share the same memory as the CPU.

For a graphics intensive game or application, a dedicated graphics card with its own video RAM (VRAM) maybe the better choice. A dedicated graphics card can simply be replaced when upgrading; however, the cards are usually more expensive and require more power, air circulation, and heat dissipation than the integrated version. 

## Windows 11
The most current version of Windows, as of this writing, is Windows 11. Windows 11 changes are mostly superficial, but it does require more robust hardware in order to run. Like Windows 10, Windows 11 is an upgrade from the previous version. Most of the changes are visual, like smaller taskbar icons that are placed in the center. There are also other additions such as a better dark mode, transparency changes, and animation changes, among others. Widgets have been expanded and are now more personalized. The settings application has been redesigned with a menu on the left, making navigation easier. There are also minor convenience additions for Windows tablets running Windows 11, including better spacing of taskbar icons and a three-finger swipe to customize actions. Windows 11 is more energy efficient, yet usually performs faster than previous versions. Windows 11 is a 64-bit only operating system, so it will not install on older, 32-bit computers.

## Windows 10 Editions
Windows 10 has had **[15 total editions released]** with **[9 editions still in use]** today. Windows 10 is an update from the previous version of Windows designed for personal computers, tablets, embedded devices, and Internet of Things devices. This version integrated the Cortana virtual assistant, combined the Windows 7 style start menu, the Windows 8 live tiles in desktop mode, and included the new Microsoft Edge Web browser. There are twelve different editions of Windows 10 with varying feature sets and use cases to meet the needs of consumer, business, and education environments. For the purposes of the exam, only the Windows Home, Pro, Pro for Workstations, and Enterprise editions will be focused on.

The retail version of Windows 10 became available in July 2015. Windows 10 offered a return to the desktop computer-oriented interface that had been replaced in Windows 8. It supports an easy transition between a point-and-click interface and the touch interfaces of tablets, phones, and embedded systems like Internet of Things (IoT) single-board computers. Windows 10 includes support for universal apps that run on desktop and mobile devices. It also introduces the Microsoft Edge web browser. It offers enhanced security features, faster logons, and encryption of system files to save disk space. Charms were replaced with a new Windows Action Center that provides notifications and quick settings.

Windows 10 uses a new update model. Twice a year, Microsoft offers feature updates. These updates add new features to Windows and also improve existing features. The updates are numbered, and the description of them is listed on the Microsoft website. It is entirely possible that you will notice changes to the interfaces of some Windows apps and tools after a feature update. Quality updates, or cumulative updates, usually install monthly. They contain patches to fix problems with Windows or they contain security updates to address new threats and vulnerabilities.

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

#### Domain Access 
The ability of the OS to connect to a domain-joined network of computers that provide centralized authentication, administration, and auditing. It is often found in large corporate networks. Domain access is supported in the Windows Pro, Pro for Workstations, and Enterprise editions. 

#### Workgroup
The default mode for the Windows OS and is a decentralized collection of computers or workstations. Windows Home only has the workgroup capability and not domain access. Used for 20 clients and under

#### Desktop Styles/User Interface
The Windows desktop and user interface are very similar to previous editions of Windows going back to Windows 95. Users are, however, able to easily customize and personalize the desktop and user interface through the Settings menu. Standard items found on the Windows desktop include the Start menu, the taskbar, and various icons or shortcuts.

#### Availability of [[Remote Desktop Protocol|RDP]]
Not supported on Windows Home, but it is supported on Windows Pro, Pro for Workstations, and Enterprise.

#### [[Random-Access Memory|RAM]] Support Limitations
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
- cd—The `cd` command allows the user to change directories and is shorthand for the `chdir` command.
- dir— The `dir` command allows the user to view a listing of files and folders/subdirectories in a directory.
- md—The `md` command allows the user to make a directory and is shorthand for the `mkdir` command.
- rmdir— The `rmdir` command allows the user to delete directories. The `rd` command is shorthand for this.

##### Drive Navigation Inputs
The `cd` command allows for navigation within the current drive. To navigate to another drive, you may use the drive letter followed by a semicolon command.
- `C`— Changes to C drive
- `D`— Changes to D drive
- `x`— Changes to X drive

**Note:** the `\` is used to refer to local files in the directory, the `/` is used for remote files on a network

#### Command-Line Tools
Used for numerous other functions, such as testing or tracing network connectivity or paths. You should be familiar with common command-line tools.
- **ipconfig**— The `ipconfig` command is used to display basic connectivity information, such as the IP address, subnet mask, and default gateway to which TCP/IP is bound. This command is highly useful in diagnosing network issues. There are several ipconfig switches and arguments which are useful to know.
	- /all : displays additional network configuration information including DHCP and servers, MAC address, NetBIOS status, and domain name
	- /release : drops the IP address learned from the DHCP server resulting in the network adapter no longer having an IP address
	- /renew : forces a DHCP client to renew its DHCP address from the DHCP server
	- displays the DNS resolver cache which contains host and domain names that have been recently queried
	- /flushdns clears the DNS resolver on the host
- **ping**—The `ping` command is used to verify network connectivity by sending an [[Internet Control Message Protocol|ICMP]] packet to a specified address, such as the default gateway.
- **hostname**—The `hostname` command is used to pull up the identity of the computer the Command Prompt is open on.
- **netstat**— The `netstat` command is used to display all the listening and established connections on the host network.
	- [-s] Lists current NetBIOS sessions and statistics, using NetBIOS names
	- [-S] Lists current NetBIOS sessions and statistics, using IP addresses 
	- [-r] Lists names resolved by local broadcast or a WINS server
	- [-R] Purges and reloads remote cache name table
	- [-RR] Like -R, but first release, then re-registers all NetBIOS name with name server.
	- [-a RemoteName] Lists the NetBIOS table of a remote PC with the specified NetBIOS name
	- [-A IPAddress] Lists the Net BIOS table of a remote PC with the specified IP address
	- [-c] Lists the Net BIOS cache table, including both names and IP addresses
	- [Interval] Repeats results at the specified interval (in seconds) until you press CTRL+C to stop
- **nslookup**—The `nslookup` command is used to verify DNS addresses. This command can be used for inline query or interactively.
- **chkdsk**—The `chkdsk` command is used to view information about the hard disk, including the creation and viewing of reports, as well as to correct file system problems and disk errors. Requires Administrator privilege. Example: chkdsk \<Volume> \<Path> \<FileName>
	- /f - fix disk errors, recovers bad sectors, and recovers readable information
	- /r - same as /f but fixes physical errors if possible
- **net user**—The `net user` command is a subcommand used to list all local accounts on the host system. Displays information about all of the user accounts on a computer. Also allows many settings to be changed for the account as well as the creation of new accounts. 
	- username - The username that you want to work with.
	- /add - after username creates new user
	- /delete - after username deletes user
- **net use**—The `net use` command is used to map drive letters to network shares. One of a series of **net** commands that are for configuring how a computer works on a network. You can display the network resources that a computer is connected to and also connect the computer to resources such as shared drives.
- **tracert**—The `tracert` command is used to show the path a packet takes on a network to arrive at a specified destination.
- **format**— The `format` command is used to remove data from disks and prepare disks for new use. Options allow specification of various file system parameters. Must be used on a new disk or a disk that was used with a different file system. Requires Administrator privilege. Example: format \<volume>
	- /q - quick format, does not scan for bad areas
	- /v: - specify volume name (label)
	- /fs: - specify file system
- **xcopy**—The `xcopy` command is used to copy folders and files.
- **copy**—The `copy` command is used to copy specified files.
- **robocopy**—The `robocopy` command is used to copy files while keeping permissions intact.
- **gpupdate**—The `gpupdate` command is used to update group policies. Group Policies can be set by an administrator and configured on all machines on a network from a central location. gpupdate is used to update a local machine and verify that the machine is getting Group Policy updates.
	- /target:computer - force update of another computer
	- /force - force and update even if Group Policy has not changed
	- /boot - restart computer after update
- **gpresult**—The `gpresult` command is used to view the report/values of the Resultant Set of Policy (RSoP) for a remote user and the users’ computer. Displays the Group Policy settings that are in effect for a currently logged in user. Works locally and for remote computers. Good for checking that computers have received a distributed Group Policy. Options concern the system and system user for whom the policy will be viewed. The type of report to view is also configurable.
	- /s - the system to the view the result on, name or IP address.
	- /r - displays summary data, often still multiple pages
- **shutdown**—The `shutdown` command can be used for scheduling a complete shutdown or a restart remotely or locally.
- **sfc**—System File Checker, or the `sfc` command, is a utility command that verifies and checks the version of the file system on the computer. Requires Administrator privilege.
	- /scannow - scans and repairs
	- /verifyonly - checks only, no repair
- **/?**—The `[command name]/?` command is used to provide help for a specified command.
- **diskpart**—The `diskpart` command is a tool for managing disks, partitions, and volumes. This command opens its own command prompt under which many of the functions of the Windows Disk Management utility can be performed. Requires Administrator privilege.
	- **create** : create a partition
	- **extend** : increase the size of a volume or partition
	- shrink : decrease the size of a partition
- pathping—The `pathping` command is a mixture of the `tracert` and `ping` commands.
- winver—The `winver` command is used to Windows version information in a GUI dialog box. Version information provided includes the current version, the build number, and licensing information.
- tasklist—Displays a list of the processes that are currently running on the local or a remote computer. Options concern the format and filtering of the output of the command and connecting to other PCs on the network. Running process are identified by their process IDs (PID).
- **taskkill**—Allows a running process to be killed. Options permit working on remote computers, means to specify a set of tasks to kill, and the ways in which the processes should be terminated. Example: `taskkill [/pid <ProcessID> | /im <ImageName>]`  
	- /pid - specify task to kill by process ID
	- /im - specify task to kill by image name (name of the process).
	- /f -forcefully terminate process
	- /t - terminate process and any child processes started by it
- **dism**—Deployment Image Servicing and Management. Used to work with system images before they are deployed. Used to create customized system image files that will be installed on computers in the enterprise.
- **shutdown**—Power off a local or remote computer. Options include naming a remote computer, the shutdown mode, messaging to the user, etc. Requires shutdown permissions and Administrator privilege.
	- /m \\ComputerName - specify remote computer
	- /s - shutdown computer
	- /r - restart computer
	- /h - put local computer into hibernation
	- /f - forces running applications to close without user warning

---

### [[Operating System|OS]]
For the exam, you must be able to use common features and tools offered by the Microsoft Windows 10 OS. Questions pertaining to these features will be scenario based.

### File Explorer
File Explorer is a file management application in Window 8 and Windows 10. It is used to navigate the file system and manage the folders, subfolders, and applications on storage media. You can also preview some types of files.

In File Explorer, common tasks, such as copying and moving files and creating new folders, can be done using the Ribbon. The tabs at the top of the window change as different types of items are selected. In the figure, the Ribbon for the File tab is displayed for Quick Access. If the Ribbon is not displaying, click the **Expand the Ribbon** icon, represented by a down arrow, on the upper right corner of the window.

Windows Explorer is the name of the file management application in Windows 7 and earlier. Windows Explorer performs similar functions as File Explorer but lacks the Ribbon.

#### This PC
In Windows versions 10 and 8.1, the This PC feature allows you to access the various Devices and drives installed in the computer. In Windows 7, this same feature is called Computer.

To open This PC, open File Explorer, and it will display the This PC feature by default, as shown in the figure on the left.

In Windows 8.0, or 7, click **Start** and select **Computer**. The figure on the right shows the **Computer** feature in Windows 7.

![[e5a7c0ee21e08c8e44a6510b250d3ffabd08d3d8.jpg]]

#### Run as Administrator
Modern operating systems use a number of methods to improve security. One of these methods is file permissions. Depending on the file permission, only users with enough permission can access the file. System files, other user files, or files with elevated permissions are examples of files that could lead Windows to deny access to a user. To override this behavior and gain access to those files, you must open or execute them as the system administrator.

To open or execute a file using elevated permission, right-click the file and choose **Run as Administrator** as shown in the figure. Choose **Yes** in the User Account Control (UAC) window. UAC is the location where administrators can manage user accounts. In some cases, software will not install properly unless the installer is run with Administrator privileges.

**Note**: An administrator password is required to use these feature if the current user does not belong to the Administrator group.

![[f08225dc9f08665819ae6baa39f3626cc7cbea93.jpg]]

#### Libraries
![[0959d259155e24d3e46854dacd5b42421f5cb14f.jpg]]

Windows Libraries allow you to easily organize content from various storage devices on your local computer and network, including removable media, without actually moving the files. A library is a virtual folder that presents content from different locations within the same view. When Windows 10 is installed, each user has six default libraries, as shown in the figure.

You can search a library, and you can filter the content using criteria such as filename, file type, or date modified. In Windows 10 and Windows 8.1, the libraries are hidden by default. The context menu for the left pane of the File Explorer window contains an option that shows the libraries.

#### Directory Structures
In Windows, files are organized in a directory structure. A directory structure is designed to store system files, user files, and program files. The root level of the Windows directory structure, the partition, is usually labeled drive C, as shown in the figure. Drive C contains a set of standardized directories, called folders, for the operating system, applications, configuration information, and data files. Directories may contain additional directories, as shown in the figure. These additional directories are commonly called subfolders. The number of nested folders is essentially limited by the maximum length of the path to the folders. In Windows 10, the default limit is 260 characters. The figure shows several nested folders in File Explorer along with the equivalent path.

Windows creates a series of folders for each user account that is configured on the computer. These folders appear to be the same in File Explorer for each user, however, they are actually unique to each user account. In this way, users cannot access each other's files, applications, or data.

**Note**: It is a best practice to store files in folders and subfolders rather than at the root level of a drive.

#### File Locations

##### User Folders
By default, Windows stores most of the files created by users in the Users Folder, C:\Users\User_name\. Each user’s folder contains folders for music, videos, websites, and pictures, among others. Many programs also store specific user data here. If a single computer has many users, they have their own folders containing their favorites, desktop items, logs, among others.

##### System Folders
When the Windows OS is installed, most of the files that are used to run the computer are located in the folder C:\Windows\system32. Making changes to the contents of the System Folder could cause problems with Windows operation.

##### Program Folders
The Program Files folder is used by most application installation programs to install software. In 32-bit versions of Windows, all programs are 32-bit and are installed in the folder C:\Program Files. In 64-bit systems, 64-bit programs are installed in the folder C:\Program Files, while 32-bit programs are installed in the folder C:\Program Files (x86).

#### File Extensions
Files in the directory structure adhere to a Windows naming convention:
- A maximum of 255 characters is allowed.
- Characters such as a slash or a backslash (/ \) are not allowed.
- An extension of three or four letters is added to the filename to identify the file type.
- Filenames are not case sensitive.

By default, file extensions are hidden. In Windows 10 and Windows 8.1, in the File Explorer ribbon, click the **View** tab. Then click to check **File name extensions**, as shown in The figure.

![[429c1055190af13769412e778283aad78247984b.jpg]]

#### File Attributes
The directory structure maintains a set of attributes for each file that controls how the file can be viewed or altered. These are the most common file attributes:
- R - The file is read-only.
- A - The file will be archived the next time that the disk is backed up.
- S - The file is marked as a system file, and a warning is given if an attempt is made to delete or modify the file.
- H - The file is hidden in the directory display.

The figure shows the file properties dialog box in which attributes can be viewed or set.

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


### Settings

#### [[Networks]]
Windows 10 has a new Settings app for network settings. It combines many different functions into one high-level app. The links in this app can point to new settings screens, Control Panel items, or even the Action Center. Some of the options, such as Airplane Mode, Mobile Hotspot, and Data Usage are more relevant to mobile devices than to desktop computers.

Mobile devices use Wireless Wide Area Network (WWAN) or cellular Internet access technology. WWAN requires using an adapter to link to a cellular provider’s network through the nearest base station or transmitter. WWAN adapters can be internal or external connected by USB. The bandwidth available over WWAN connections is dependent on the technologies supported by the adapter and the transmitter, such as 3G or 4G. Connection to the WWAN is automatic once the adapter and adapter software are installed.

#### HomeGroup
In Windows networking, a homegroup is a group of computers that are on the same network. Homegroups simplify sharing files on simple networks. They are intended to make networking in the home easier by requiring a minimum of configuration. You can share your library folders on the network, making it easy for other devices to access your music, videos, photos, and documents. Devices that are attached to computers in the homegroup can also be shared. Users will need the homegroup password in order to join the homegroup and access shared resources.

Homegroups were used in Windows 7 and 8. Microsoft has been phasing out the homegroup functionality. In Windows 8.1 homegroups cannot be created, however Windows 8.1 computers can join existing home groups. In newer versions of Windows 10 (version 1803 and higher), home group functionality is not available.

![[1a60db20fb32458ace083943de4fa5aa1d7df625.jpg]]

The previous figure shows the Windows 8 home group configuration screen. In Windows 8, nothing is shared by default. The next figure shows the Windows 7 screen. Note that everything except for documents is shared by default.

![[7e0c3939365cbf14e574dbb338486147754ecf1a.jpg]]

#### Display
In Windows 10, much of the Appearance and Personalization configuration has been moved to the Settings app, as shown in the left figure. The Windows 10 display settings are reached by right-clicking an empty area of the desktop and selecting Display settings from the context menu. Alternatively, the Settings app can be opened. Display settings are available in the System category.

![[938bfdabb47d37a56bcf9aeff9b95277128dbd8a.jpg]]

You can change the appearance of the desktop by modifying the resolution that is output by the graphics adapter. If the screen resolution is not set properly, you might get unexpected display results from different video cards and monitors. You can also change the magnification of the desktop and text size in Windows interface elements. The Windows 8.1 Display control panel item is shown in the next figure. In Windows 7 and 8, the Display Control Panel item is found in the Hardware and Sound category.

![[6da3aeae38faeb0d691a4074b3bb00d3978ffee4.jpg]]

When using an LCD screen, set the resolution to the recommended setting. This will set the resolution to the native resolution, which sets the video output to the same number of pixels that the monitor has. If you do not use native resolution, the monitor does not produce the best picture

![[913e3497c729f272cc41affb3b746721368e1be1.jpg]]

You can adjust the following features in the Windows 8 and 7 Display control panel item:
- **Display** - A specific monitor can be configured if there is more than one monitor.
- **Screen resolution** - This specifies the number of pixels horizontally and vertically. A higher number of pixels provides better resolution. Typically expressed as horizontal pixels x vertical pixels or 1920 x 1080, for example.
- **Orientation** - This determines whether the display appears in Landscape, Portrait, flipped Landscape, or flipped Portrait orientation.
- **Refresh rate** - This sets how often the image in the screen is redrawn. The refresh rate is in Hertz (Hz). 60Hz means the screen is redrawn 60 times per second. The higher the refresh rate, the steadier the screen image appears. However, some monitors cannot handle all refresh rate settings.
- **Display colors** - In older systems, the number of colors to display, or the bit depth, needed to be set to a value that is compatible with graphics adapter and monitor. The higher the bit depth, the greater the number of colors. For example, the 24-bit color (True Color) palette contains 16 million colors. The 32-bit color palette contains 24-bit color and 8 bits for other data such as transparency.
- **Multiple displays** - Some computers or graphics cards permit the attachment of two or more monitors to the same computer. The desktop can be extended, meaning the displays combine to make one large display, or mirrored, meaning the same image is shown on all displays.

### Control Panel Utility
The Control Panel includes tools and utilities to view, change, and troubleshoot system settings. 

Windows 10 usually defaults to the Settings app for configuration changes. This is good for the casual user, however a PC technician frequently needs more configuration options than what is available in the Settings App. The Control Panel offers many configuration tools and its interface is preferred by many experienced Windows administrators. In fact, some Settings actually link to Control Panel items.

To start Control Panel, type Control Panel into the Search box and click the Control Panel Desktop app that appears in the results, as shown in the figure. If you right-click on the result, you can pin it to the Start menu to make it easier to find. You can also open it from the Command Prompt by typing **control**.

In Windows 7, the Control Panel has an entry on the Start menu. In Windows 8.1, it can be accessed by right-clicking the Start button. In Windows 8, it can be opened by searching for Control Panel and clicking the result.

Questions in this section will begin with a scenario.

#### Views
The Windows 10 Control Panel opens to the Categories view by default, as shown in the figure. This helps to organize the forty or more Control Panel items and makes them easier to find. This view also provides a search box which will return a list of Control Panel items that are relevant to a search term.

![[805f7a9e5247e94f7e565a4134f0a3fcd43f4e56.jpg]]

The classic view of Control Panel is reached by changing the setting in the **View by:** dropdown menu to **Small icons**, as shown in the right figure. Note that there will be variations in what is available in Control Panel depending on features of the individual computer.

![[6692bab9f44332e144ecc8f1896c557787038dd3.jpg]]

#### Internet Options
A utility to manage network settings beyond basic IP connectivity. The settings are separated into multiple tabs.

##### General
Configure basic internet settings, such as selecting the default home page, viewing and deleting browsing history, adjusting search settings, and customizing the browser appearance.

##### Security
Adjust the security settings for the internet, local intranet, trusted sites, and restricted sites. Security levels for each zone can range from low (minimal security) to high (maximum security).

##### Privacy
Configure privacy settings for the internet zone, manage location services, and enable the Pop-up Blocker.

##### Content
Access Parental Controls, control content viewed on the computer, adjust AutoComplete settings, and configure the feeds and web slices that can be viewed in IE. Web slices are specific content from websites that allow users to subscribe and view the updated content, such as current temperature and stock quotes.

##### Connections
Set up an internet connection and adjust network settings. Dial-up, VPN, and proxy server settings can be managed in this tab. Use of a proxy server can improve performance and security. Internet requests from the client are sent to the proxy server which forwards them to the Internet. Return traffic is received by the proxy server which then forwards it to the client. The proxy server can cache pages and content that is frequently requested or requested by many clients which can reduce bandwidth. Configuring a proxy is done in **Internet Options > Connections > LAN Settings**.

##### Programs
Make IE the default web browser, enable browser add-ons, select the HTML editor for IE, and select programs used for internet services. Hypertext Markup Language (HTML) is a system that tags text files to affect the appearance of web pages.

##### Advanced
Adjust advanced settings, and reset IE’s settings to the default state.

#### Credentials Manager
Credential Manager helps you to manage passwords that are used for websites and Windows applications. These passwords and usernames are stored in a secure location. Credentials are automatically updated as they are created or changed. You can view, add, edit, or delete the credentials that are stored by Credential Manager. This category has been enhanced since the Windows 7 version although the interface is similar.

**Note**: Web credentials are not saved for sites accessed by browsers other than Internet Explorer and Edge. Credentials created with other browsers must be managed from within that browser.

#### Sync Center
Sync Center allows files to be edited from multiple Windows devices. While accessing networked files from multiple devices is nothing new, Sync Center allows a form of version control. This means that changes made to the networked files by one device will be made on all devices that are configured to synchronize those files. With this synchronization service, there is no need to physically copy a new version of a file from the device on which the changes were made to the device that you are currently working on. The updated file is on the networked storage location and the local versions are updated to the latest version automatically. When changes are made, those changes will be made to networked file too. All devices must be able to connect to the same networked storage location.

Another value to Sync Center is that users can work on files on a device that is offline and the server copy can be updated over the network when the device reconnects.

Using Sync Center requires activation of the Offline Files feature. This sets up a local file location that will store the files to be synchronized. It also requires you to set up a sync partnership with the networked file location. Files can be synchronized manually and synchronization can also be scheduled to occur automatically.

Microsoft OneDrive offers a similar service. OneDrive is a cloud storage service that is available to Microsoft Windows users. Since OneDrive is reachable over the internet, work can be done on any device that can connect to OneDrive from any location with internet access. Sync Center requires access to a network server that may not be reachable from networks in other locations.

#### Devices and Printers
Lists printers, scanners, cameras, monitors, and other connected peripheral devices; the settings of these devices can also be accessed.

#### Programs and Features
This category allows changes to installed programs and Windows updates, including removal. Activation or deactivation of a wide range of Windows features can also be accessed here. Used to view and uninstall desktop applications installed on the OS. 

##### Programs
![[b50a4c69742be66ca8b72edc1fcf55e72c340ae2.jpg]]
Use the Program and Features Control Panel items to uninstall a program from your computer if you no longer use it or if you want to free up space on your hard disk, as shown in the figure. It is important that applications be uninstalled either through the Programs and Features Control Panel item or from an uninstallation menu choice that is associated with the application in the Start menu.

In addition, you can repair the installation of some programs that may have problems. You can also troubleshoot problems with programs that were made for older versions of Windows that are not running correctly.

Finally, you can choose to manually install software from the network. It is possible that your organization provides updates or patches that could require manual installation.

##### Features
You can also activate or deactivate Windows features, as shown in the figure. Programs and Features also allows you to view the Windows updates that have been installed, and uninstall specific updates if they are causing problems and don't have dependencies with other installed updates or software.

#### Network and Sharing Center
In the Network and Sharing Center you can configure network adapters, create new network and dial-up connections, and configure network file and printer sharing. This category allows configuration, verification and troubleshooting of networking and file sharing. It also allows configuration of the default Microsoft browser that is present on the system.

The Network and Sharing Center allows an administrator to configure and review nearly all network settings on a Windows computer. With it, you can do everything from viewing network status to changing properties of the protocols and services that are running on a network adapter. The figures show the Network and Sharing Center for Windows 10, 8, and 7. Note that although they look very similar. Small differences exist between the versions.

Network and Sharing Center shows how your computer connects to a network. Internet connectivity, if present, will also be displayed here. The window displays and allows the configuration of shared network resources. Some useful and common network-related tasks are displayed on the left pane of the window.

Network and Sharing center allows the configuration of file and device sharing through the use of network profiles. The network profiles enable basic sharing settings to change depending on whether you are attached to a private or public network. This enables sharing to be inactive on an insecure public network but active on a private secure network.

#### System and Security
The Control Panel utility that shows the hardware overview. You can view and configure security settings such as Windows Defender Firewall. You can also access administrative tools that enable you to configure a wide range of system functions such as general hardware, storage, and encryption settings and operations.

#### Power Options
The Power Options Control Panel item is part of the System and Security Control Panel category. The Widows 8 Power Options are shown in the figure.

You can choose from the following options:
- Require a password on wakeup (Windows 7 and 8 only)
- Choose what the power buttons do
- Choose what closing the lid does (for laptops only)
- Create a power plan
- Choose when to turn off the display
- Change when the computer sleeps

Selecting **Choose what the power buttons do**, or **Choose what closing the lid does**, configures how a computer acts when power or sleep buttons are pressed, or the lid is closed. Some of these settings also appear as shutdown options for the Windows Start button or the Windows 10 Power button. If users do not want to completely shut down a computer, the following options may be available:
- **Do nothing** - The computer continues to run at full power.
- **Sleep** – Documents, applications, and the state of the operating system are saved in RAM. This allows the computer to power on quickly, but uses power to retain the information in RAM.
- **Hibernate** – Documents, applications, and the state of the operating system are saved to a temporary file on the hard drive. With this option, the computer takes a little longer to power on than the Sleep state, but does not use any power to retain the information on the hard drive.
- **Turn off the display** - The computer operates at full power. The display is turned off.
- **Shut down** - Shuts down the computer.

##### System Control
The System Control Panel item allows all users to view basic system information, access tools, and configure advanced system settings. The System Control Panel item is found under the System and Security category. The Windows 10 System Control Panel item is shown in the figure. The System Control Panel item is very similar in Windows 7 and 8.

The various settings can be accessed by clicking the links on the left panel.

###### Computer Name
View or modify the name and workgroup settings for a computer, as well as change the domain or workgroup.

###### [[Hardware]]
View or modify the name and workgroup settings for a computer, as well as change the domain or workgroup.

###### Advanced
Configure settings for performance, user profiles, startup, and recovery.

###### System Protection
Access System Restore, which will return a computer to an earlier configuration, and configure settings enable system restore points, and the amount of disk space that is used for them.

###### Remote
Adjust settings for Remote Assistance and Remote Desktop. This will allow other people to connect to a computer to view or work on it.

#### Hardware and Sound
This category permits configuration of devices such as printers, media devices, power, and mobility.

##### Device Manager
Device Manager, shown at right, displays a list of all the devices installed in the computer, allowing you to diagnose and resolve device problems. You can view details about the installed hardware and drivers, as well as perform the following functions:
- **Update a driver** - Change the currently installed driver.
- **Roll back a driver** - Change the currently installed driver to the previously installed driver.
- **Uninstall a driver** - Remove a driver.
- **Disable a device** - Disable a device.

Device Manager organizes devices by type. To view the actual devices, expand the appropriate category. You can view the properties of any device in the computer by double-clicking the device name.

The Device Manager utility uses icons to indicate the types of problems that may exist with a device, as indicated in the icons that are shown in the table.

The devices that are available in Device Manager vary from computer to computer. Device Manager is very similar in Windows versions 7, 8, and 10.

| Icons                                             | Meaning                                                                                                                                                                                                                                                                   |
| ------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ![[cfb3bfbf35e82c7f93efa51a3e3665e23dce62d3.png]] | The device has an error. It may be functioning, but requires attention. Right-click on the item in the Device Manager and select Properties to see the problem code in the Device status error of the properties box. The code can be researched to determine the problem |
| ![[a11df5ad415239134fe46053d726d4c7e2295b89.png]] | The device is disabled. the device is installed on the system but no driver is loaded                                                                                                                                                                                     |
| ![[7ca9968408ee6c386c9b5b6c6b085eae1488fd8a.png]] | The device-specific driver for the device is not available. A compatible driver is in use                                                                                                                                                                                 |
| ![[9398617f3b09afa7fbf4bd1581febdd767d15ae5.png]] | This is not a problem icon. It means that the driver has been manually, rather than automatically, installed for the device                                                                                                                                               |

##### Portables Devices and [[Printers]]
Use the Devices and Printers Control Panel item for a high-level view of the devices connected to a computer, as shown in the figure. Devices displayed in the Devices and Printers Control Panel item are typically external devices you can connect to your computer through a port such as USB, or a network connection. Devices and Printers also allows you to quickly add a new device to the computer. In most cases, Windows will automatically install any necessary drivers that are required by the device. Note that the desktop computer device in the figure shows a yellow triangle alert, indicate that there is a problem with the driver. The green check mark next to a device indicates that is to be used as the default device. Right-click on a device to view its properties.

Devices typically shown in Devices and Printers include:
- Portable devices that you occasionally connect to your computer, such as mobile phones, personal fitness devices, and digital cameras.
- Devices you plug into a USB port on your computer, such as external USB hard drives, flash drives, webcams, keyboards, and mice.
- Printers connected to your computer or available on the network.
- Wireless devices connected to your computer, such as Bluetooth and wireless USB devices.
- Compatible network devices connected to your computer, such as network-enabled scanners, media extenders, or Network Attached Storage devices (NAS).

Devices and Printers is very similar in Windows versions 7, 8, and 10.

##### Sound
Use the Sound Control Panel item to configure audio devices or change the sound scheme of the computer. For example, you can change the email notification sound from a beep to a chime. Sound also allows a user to choose which audio device is to be used for playback or recording.

The Sound Control Panel utility is largely unchanged between Windows 7, 8, and 10.

#### Ease of Access
This category provides many options that make Windows easier to use, especially for people who require accommodations for physical or perceptual challenges. Configuration of speech recognition and text to speech services are also found here.

#### Cock, Region, and Language
This category enables configuration of time and date settings and formats. Location and language can also be configured here in some Windows versions.

![[a662fc1ed13231bfec805f5a0de3b3943047cd24.jpg]]

Windows allows you to change the system time and date through the Date and Time control panel item, as shown in the figure. You can also adjust your time zone. Windows will automatically update the time settings when time changes occur. The Windows clock will automatically synchronize with a time authority on the internet. This ensures that the time value is accurate.

Time and Date is accessed through the Clock and Region Control Panel category in Windows 10. In Windows 7 and 8, it is accessed through the Clock, Language, and Region Control Panel category.

##### Region
Windows allows you to change the format of numbers, currencies, dates, and times by using the Region Control Panel item. In Windows 7 there were tabs available to allow changing the system keyboard layout and language, and the computer location. In Windows 8 the keyboard and language tab was removed. Windows 10 attempts to use location services to automatically detect the location of the computer. The location can also be set manually if the location can't be determined. The Windows 8 and Windows 10 Region Control Panel item are shown in the figures below, respectively.

Date and time setting formats can be changed by changing the display patterns available in the Date and Time formats area. Click Additional settings to change number and currency formats and the measurement system used in the region. Additional date and time formats are also available.

##### Language
Windows allows you to change the format of numbers, currencies, dates, and times by using the Region Control Panel item. In Windows 7 there were tabs available to allow changing the system keyboard layout and language, and the computer location. In Windows 8 the keyboard and language tab was removed. Windows 10 attempts to use location services to automatically detect the location of the computer. The location can also be set manually if the location can't be determined. The Windows 8 and Windows 10 Region Control Panel item are shown in the figures below, respectively.

Date and time setting formats can be changed by changing the display patterns available in the Date and Time formats area. Click Additional settings to change number and currency formats and the measurement system used in the region. Additional date and time formats are also available.

#### Appearance and Personalization
This category permits configuration of the taskbar and navigation (via Settings), file explorer, and available fonts. More options are available through the personalization Settings app.

#### Windows Defender Firewall
The Windows Defender Firewall protects the computer by controlling what applications can access the network from this computer and also how this computer can be accessed over the network.

#### Mail
In Mail, emails can be configured, including Microsoft Outlook. Additional data files, RSS feeds, internet calendars, address books, and SharePoint lists can also be configured here.

#### Sound
The Sound screen is where you can manage devices to play and record sounds and configure sounds that the operating system produces for startup, shutdown, alerts, and prompts.

#### User Accounts
This category enables administration of Windows user accounts and user account control (UAC). Management of Web and Windows Credentials including the file encryption certificates that are used to encrypt files stored on the computer can also be accessed here. You can add, manage, and remove local users and their roles for the computer in User Accounts. Each user will have their own profile with different settings and user folders.

An administrative account is created when Windows is installed. To create a user account afterwards, open the User Accounts Control Panel item, as shown in the figure.

Administrator accounts have the ability to change all system settings and access all files and folders on the computer. For that reason, administrator accounts should be carefully controlled. Standard user accounts can manage most configuration settings that don't affect other users. They can only access their own files and folders.

The User Accounts Control Panel item provides options to help you create, change, and delete user accounts. It is very similar between Windows versions.

![[96a3969dd69746967f7237295c8a5c1bb0d45d2f.jpg]]

**Note**: Some features of the User Accounts utility require administrative privileges and will not be accessible with a standard user account.

##### [[User Account Control|UAC]]
The User Account Control (UAC) monitors programs on the computer and warns users when an action might present a threat to the computer. In Windows versions 7 through 10, you can adjust the level of monitoring that the UAC performs. When Windows is installed, the UAC for the primary account defaults to the setting "Notify me only when programs try to make changes to my computer," as shown in the figure. You are not notified when you make changes to these settings.

To change when you are notified about changes that programs may make to your computer, adjust the level of UAC.

#### File Explorer Options
The Folder Option Control Panel item permits changing a variety of settings regarding the way files are displayed in Windows Explorer or File Explorer. This Control Panel item is called File Explorer Options in Windows 10, and Folder Options in Windows 7 and 8.1 The Windows 10 File Explorer Options Control Panel item is shown in the left figure. The Windows 7 and 8 version is very similar. The Windows 8 version is shown in the right figure.

In Windows 10, many of the most commonly used file and folder options can be found in the File Explorer ribbon. In Windows 8.1 some functions are present in the ribbon, but the selection is not as comprehensive as it is in Windows 10. In Windows 7, there is no ribbon, so the Control Panel must be used. The functions of the tabs in Windows 10 are described below.

The **General** tab is used to adjust the following settings:
- **Browse folders** - Configures how a folder is displayed when it is opened.
- **Click items as follows** - Specifies the number of clicks required to open an item.
- **Privacy** - Determines which files and folders are shown in Quick Access. Also allows File History to be cleared.

The **View** tab is used to adjust the following settings:
- **Folder views** - Applies the view settings for a folder being viewed to all folders of the same type.
- **Advanced settings** - Customizes the viewing experience including the ability to view hidden files and file extensions.

The **Search** tab is used to adjust the following settings:
- **What to search (Windows 7**) - Configures search settings based on indexed and non-indexed locations to make files and folders easier to find.
- **How to search** - Choose whether an indexed search is used.
- **When searching non-indexed locations** - Determines whether system directories, compressed files and file contents are included when searching non-indexed locations.

#### Device Manager
Lists all hardware connected to the computer and provides management for drivers of the devices.

After installation, verify that all hardware is installed correctly. The Device Manager is used to locate device problems and install the correct or updated drivers in Windows.

The figure shows the Windows Update and Device Manager utilities on Windows 10.

#### Indexing Options
Systematically indexes files, including Office documents, PDFs, text files, etc.

#### Administrative Tools
A shortcut to tools used in the administration of the OS.

#### Troubleshooting
The Troubleshooting Control Panel item has a number of built-in scripts that are used to identify and solve common problems with many Windows components, as shown in the figure. The scripts run automatically and can be configured to automatically make the changes to fix the problems that are found. You can also view when the troubleshooting scripts have been run in the past by using the View History feature.

![[6ca34a934eeba920d688c60c52496cd1bcd93eaf.png]]

#### BitLocker Drive Encryption

![[bb08809c873a1979f9e0d1acf7068202fd4f67ac.jpg]]

BitLocker is a service provided with Windows that will encrypt an entire volume of disk data so that it can't be read by unauthorized parties. Data can be lost if your computer or disk drives are stolen. In addition, when the computer is taken out of service, BitLocker can help insure that the hard drive can't be read when it has been removed from the computer and scrapped.

The BitLocker Control Panel item, shown in the figure, enables you to control the way BitLocker operates.

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

#### Administrative Tools
The Administrative Tools Control Panel item is a collection of tools that are used to monitor and configure Windows operation. This Control Panel item has evolved over time. In Windows 7 it was somewhat limited. Microsoft added many different utilities in Windows 8.1. In Windows 10, the available tools changed slightly.

The Administrative Tools Control Panel item is unusual in that it is a collection of shortcuts that open in File Explorer. Since each icon represents a shortcut to an application, investigate the properties of each shortcut to see the name of the application file that is run when the shortcut is clicked. You can start the same applications by typing the name of application at the command prompt. Once you become experienced with managing Windows, this may be the most efficient way for you to access the tools you need. The figure shows the Administrative Tools Control Panel item in Windows 10.

![[8c4b77e46004b436dc5daf2df444ad1220f62cea.jpg]]

##### Computer Management
One of the Administrative Tools items is the Computer Management console, shown in the figure. It allows you to manage many aspects of your computer and remote computers in one tool.

The Computer Management console provides access to three groups of utilities. Here we will learn about the System Tools group.

Conveniently, the Computer Management tool can be accessed by right-clicking This PC in Windows 8.1 or 10, or by right-clicking Computer in Windows 7 and 8 and selecting Manage. Administrator privileges are required to open Computer Management.

To view the Computer Management console for a remote computer, follow these steps:

**Step 1**. In the console tree, click **Computer Management (Local)** and select **Connect to another computer**.

**Step 2**. Enter the name of the computer or click **Browse** to find the computer to manage on the network.

###### Event Viewer
Event Viewer, shown in the figure, allows viewing the history of application, security, and Windows system events. These events are stored in log files. They are a valuable troubleshooting tool because they provide information necessary to identify a problem. Event Viewer permits filtering and customization of log views to make it easier to find important information from the various log files that Windows compiles.

Windows logs many events that can originate from applications, the Windows OS, application setup, and security events, by default. Each message is identified by its type or level:

- **Information** - A successful event. A driver or program has executed successfully. Windows logs thousands of information level events.
- **Warning** - Indication of a potential problem with a software component that is not functioning ideally.
- **Error** - A problem exists, but no immediate action is required.
- **Critical** - Immediate attention is required. Usually related to system or software crashes or lockups.
- **Success Audit (security only)** - A security event has been successful. For example, a successful logon from a user will trigger an event with this level.
- **Failure Audit (security only)** - A security event has not been successful. Failed attempts by someone attempting to log on to a computer will trigger this event.

##### Performance Monitor
Performance Monitor allows customized performance graphs and reports to be created from a wide range of hardware and software components. Data Collector Sets are collections of metrics, called performance counters. Windows has a number of default Data Collector Sets and you can create your own. A wide range of counters can be graphed against time and reports can also be generated and read or printed. Data collection can be scheduled to occur at different times and for different durations and stop criterion for a monitoring session can also be set.

The Performance Monitor provided here is different from the performance information that is available through Task Manager and Resource Monitor. The purpose of the Performance Monitor administrative tool is the creation of detailed custom reports from very specific counters. The figure shows a graph derived from a selection of data counters that are available for the CPU.

![[b83abd297cd7f29b585230ce8bf6b84d0fd04c21.png]]

##### Local Users and Groups
Local Users and Groups, shown in the figure, provides an efficient way of managing users. You can create new users and assign those users to membership in Groups. Groups have rights and permissions assigned that are suitable for different types of users. Rather than configuring rights and permissions for each individual user, a user can be assigned an appropriate group. Windows provides default user accounts and groups to make managing users easier:
- **Administrators** - Full control of the computer and access to all folders.
- **Guests** - Guests can access the computer through a temporary profile that is created at logon and deleted on logoff. Guest accounts are disabled by default
- **Users** - Users can perform common tasks such as running applications and accessing local or network printers. A user profile is created and persists on the system.

##### Component Services and Data Sources
Component Services is an administrative tool used by administrators and developers to deploy, configure, and manage Component Object Model (COM) components. COM is a way to allow the use of software components in distributed environments such as in enterprise, internet, and intranet applications.

##### Services
The Services console (SERVICES.MSC) allows you to manage all the services on your computer and remote computers. A service is a type of application that runs in the background to achieve a specific goal, or to wait for service requests. To reduce security risks, only start the necessary services. You can use the following settings, or states, to control a service:
- **Automatic** - The service starts when the computer is started. This prioritizes the most important services.
- **Automatic (delayed)** - The service starts after services that are set to Automatic have started. The Automatic (delayed) setting is available only in Windows 7.
- **Manual** - The service must be started manually by the user or by a service or program that needs it.
- **Disabled** - The service cannot be started until it is enabled.
- **Stopped** - The service is not running.
To view the Services console for a remote computer right-click on **Services (Local)** in the Computer Management window and select **Connect to another computer**. Enter the name for the computer or click **Browse** to allow Windows to scan the network for connected computers.

##### Data Sources
Data Sources is a tool used by administrators to add, remove, or manage data sources using Open Database Connectivity (ODBC). ODBC is a technology that programs use to access a wide range of databases or data sources. The tool is shown in the figure.

![[72fb0d3b8eee641a0608e269058f45586f07811f.png]]

##### Print Management
The Print Management utility, shown in the figure, provides a detailed view of all of the printers that are available to a computer. It is not available in all Windows editions. It is available in Windows servers, Pro, Enterprise, and Ultimate editions. It enables efficient configuration and monitoring of directly attached and network printers, including print queues for all printers to which it has access. It also allows the deployment of a printer configuration to multiple computers on a network through the use of group policies.

![[1a0fee87c263197db3e6eaac3151ba50bacb8fb0.jpg]]

#### Windows Memory Diagnostics
The Windows Memory Diagnostics tool schedules a memory test that will be executed when the computer starts. It can be configured to automatically restart the computer or execute the test the next time the computer starts. After the tests are complete, Windows will restart. The type of diagnostics to be run can be configured by pressing F1 from the diagnostic as it runs, as shown in the figure. The results of the test can be viewed by finding the memory diagnostic test result in the Windows Log folder in Event Viewer.

### System Information
Administrators can use the System Information tool, as shown in the figure, to collect and display information about local and remote computers. The System Information tool is designed to quickly find information about software, drivers, hardware configurations, and computer components. Support personnel can use this information to diagnose and troubleshoot a computer.

You can also create a file containing all the information about the computer to send to someone. To export a System Information file, select File > Export, type the filename, choose a location, and click Save. The System Information utility can also display the configuration of other machines on the network.

The System Information tool can be opened from the command prompt by typing **msinfo32**, or it can be found in the Administrative Tools Control Panel item.

#### System Configuration
System Configuration (MSCONFIG) is a tool used to identify problems that keep Windows from starting correctly. To help with isolating the issue, services and startup programs can be turned off and turned back on one at a time. After you have determined the cause, permanently remove or disable the program or service, or reinstall it.

##### General
Displays three startup selections to aid troubleshooting. **Normal startup**- full startup as normal **Diagnostic startup**- starts with basic services and drivers only **Selective startup**- starts with basic services and drivers by default, can be changed

##### Boot
You can choose the Windows OS version to boot if more than one is present. You can also choose to boot up in **Safe boot** (formerly Safe mode) with different options regarding the way that Windows starts.

##### Services
Displays a list of services that are started with the operating system. Allows individual services to not be loaded on boot for troubleshooting purposes.

##### Startup
In Windows 7, displays a list of all the applications that run automatically when Windows starts. Individual items can be disabled. In Windows 8.1 and 10, the user is referred to the same settings in Task Manager.

##### Tools
Displays a compact and very comprehensive list of diagnostic tools that can be run to help with troubleshooting.

### Microsoft Management Console (MMC) 
Microsoft Management Console (MMC) is an application that allows the creation of custom management consoles for collections of utilities and tools from Microsoft or other sources. The Computer Management console that was previously discussed is a premade MMC. When initially opened, the console is empty. Utilities and tools, known as snap-ins, can be added to the console. You can also add web page links, tasks, ActiveX controls, and folders.

The console can then be saved and reopened when needed. This allows the construction of management consoles for specific purposes. You can create as many customized MMCs as needed, each with a different name. This is useful when multiple administrators manage different aspects of the same computer. Each administrator can have an individualized MMC for monitoring and configuring computer settings.

The figure shows a new empty console with the dialog box for selecting and adding snap-ins.
![[c629fd36f526f332149064f58b3b837a2bffdf74.jpg]]

#### Snap-In
A GUI for running administrative and configuration tools.

**[Event Viewer]** (`eventvwr.msc`)—used to view application error logs, system errors, and security audit records.

**[Disk Management]** (`diskmgmt.msc`)—used to view disk information on the physical disk and the formatted file systems it contains.

**[Task Scheduler]** (`taskschd.msc`)—allows you to configure automated tasks that will run on a schedule at specified times.

**[Device Manager]** (`devmgmt.msc`)—allows you to view the status of devices, view the properties, and modify the configuration parameters.

**[Certificate Manager]** (`certmgr.msc`)—used to manage and view the certificates used by the OS and web browser.

**[Local Users and Groups]** (`lusrmgr.msc`)—As a system administrator, you need to know how to create and delete users and maintain their accounts, as well as how to establish secure passwords.

**[Performance Monitor]** (`perfmon.msc`)—displays in real time how the computer uses memory, disk, CPU, and the network, to help diagnose performance issues.

**[Group Policy Editor]** (`gpedit.msc`)—used to edit the local group policy for the OS.

### DXDiag
DxDiag stands for DirectX Diagnostic Tool. It displays details for all DirectX components and drivers that are installed in a computer, as shown in the figure. DxDiag is run from a search or from the command line.

DirectX is a software environment and interface for multimedia applications, especially games. It defines interfaces for 2D and 3D graphics, audio, media encoders and decoders, etc.

![[c12ddc37dd8ee30487a0665ed017f07ab56ce580.png]]

### Additional Tools
The MMC offers these additional tools beyond the original monitoring and configuration tools.

**[System Information]** (`msinfo32.exe`)—displays advanced hardware and driver information.

**[Resource Monitor]** (`resmon.exe`)—shows how resources are being utilized by the CPU, memory, disk, and network.

**[System Configuration]** (`msconfig.exe`)—can be run by the `msconfig` command. It allows you to change how Windows boots and what programs start with Windows.

**[Disk Cleanup]** (`cleanmgr.exe`)—frees up space while not affecting the integrity of the files.

**[Disk Defragment]** (`dfrgui.exe`)—relocates pieces of large files to continuous space on a disk for optimized performance.

**Registry Editor** (`regedit.exe`)—allows the user to view and change the Windows registry. The registry contains some operating system and application settings that may need to be changed in advanced troubleshooting.

## Windows 8.0/.1

## Windows 7
There are some features of Windows that are aimed at personal use, such as Windows Media Center. This is a Microsoft app that allows the computer to be used as a home entertainment appliance for playing DVDs. Windows Media Center was included in Windows 7 Home Premium, Professional, Enterprise, and Ultimate editions. It was also a paid-for add-on to Windows 8 but was discontinued in Windows 10.

### File Extensions
To display the file extensions In Windows 7, you must disable the **Hide extensions for known file types** setting in the **FolderOptions** control panel utility, as shown in the figure.

The following filename extensions are commonly used:
- .docx - Microsoft Word (2007 and later)
- .txt - ASCII text only
- .jpg - Graphics format
- .pptx - Microsoft PowerPoint
- .zip - Compression format

![[3ee59a11dba6911a5ef22be33cc5de2edd2ccbd9.jpg]]

## Configuration
The first version of the Microsoft Windows operating system was released in 1985. Since then, over 25 versions, subversions, and varieties have been released. As an IT technician and professional you should understand the features of the most prevalent Windows versions in use today, Windows 7, Windows 8, and Windows 10.

In this chapter, you will learn about the different Windows versions and the editions of each that are most suited for corporate and home users. You will learn how to configure the Windows operating system and to perform administrative tasks using the Control Panel in the GUI and commands in the Windows command line (CLI) application and the PowerShell command line utility. You will have an opportunity to put into practice what you learn by working through several labs that involve working with file system commands, disk CLI commands, task and system CLI commands, and others.

You will learn about the two methods for organizing and managing Windows computers on a network, the domain and the workgroup, and how to share local computer resources, such as files, folders, and printers on the network. You will also learn how to configure a wired network connection in Windows. You will perform labs creating and sharing folders on the network and setting access permissions. You will also connect a computer to a wireless router and test the wireless connection as well as configure Windows for remote access using the Remote Desktop and Remote Assistance tools.

You will learn how a preventive maintenance plan can decrease downtime, improve performance, improve reliability, and lower repair costs and that preventive maintenance should take place when it causes the least amount of disruption to users. Regular scans for viruses and malware are also an important part of preventive maintenance. You will perform several labs to schedule a task using the GUI and at the command line and to manage startup applications using the Run key in the Registry.

### Desktop
Windows offers many settings that enable users to personalize the desktop and other aspects of the Windows GUI. The fastest way to get to these settings is to right-click an empty area of the desktop and select **Personalize**. This shows the **Background** settings. Drag the right-hand border of the settings box to widen it. This will reveal the **Personalization** settings menu. The fastest way to change the look and feel of the Windows GUI is to select from the available themes, as shown in the figure. Themes are a preset combination of GUI settings that go together. You can also create themes from settings that you have made so that they can be used later. Themes beyond those that are provided can be downloaded from the Microsoft Store. Many other changes can be made to Windows GUI from here.

![[31c10663b9345a52996a70b744d4bb187ec81f13.png]]

In Windows 8 the Apps environment is highly customizable. To re-arrange the tiles, click and drag the tiles. To rename a tile group, right-click on any empty area of the screen and select Name groups. To add tiles to the main screen, right-click the desired Windows app after searching for it and select Pin to Start. To search for an app, click Search from the Charms bar. Alternatively, you can start typing the name of the app from the Windows Apps environment. Search will start automatically. The figure shows the Windows 8 Apps environment and the Charms bar.

![[b0c7b9b7175c7f85ccf915a577ca7440d6f21dda.jpg]]

In Windows 7 and 8.1, to customize the desktop, right-click anywhere on the desktop and choose **Personalize**. In the Personalization window, you can change the desktop appearance, display settings, and sound settings. The figure shows the Windows 8 Personalization window. It is very similar to the Personalization window in Windows 7.

![[8d1834bdf6a249bd6f248552856ace83ff64b134.png]]

### Performance
To enhance the performance of the OS, you can change the virtual memory configuration settings, as shown in the figure. When Windows determines that system RAM is insufficient, it will create a paging file on the hard drive that contains some of the data from RAM. When the data is required back in RAM, it is read from the paging file. This process is much slower than accessing the RAM directly. If a computer has a small amount of RAM, consider purchasing additional RAM to reduce paging.

![[677900157158acb042391fbd14bf9ea1df94801a.png]]

Another form of virtual memory is the use of an external flash device and Windows ReadyBoost to enhance system performance. Windows ReadyBoost enables Windows to treat an external flash device, such as a USB drive, as hard drive cache. ReadyBoost will not be available if Windows determines that no performance improvement will be gained.

To activate Windows ReadyBoost, insert a flash device and right-click the drive in File Explorer. Click Properties and select the ReadyBoost tab

## Registry
The Windows Registry is a data base that contains settings for Windows and for application that use the Registry. The settings contained in the Registry are vey low-level, meaning that are many of them. Values in the registry are created when new software is installed or new devices are added. Evert setting in Windows, from the background of the desktop and the color in the Registry. When a user makes changes to the Control Panel settings, file associations, system policies, or installed software, the changes are stored in the Registry.

The registry consists of a hierarchical arrangement of keys and subkeys that are represented as a tree. Levels of the subkey tree can be deeply nested with a maximum of 512 levels of permitted. Locating the key for the values you want to see is a matter of working through the hierarchy of trees and subtrees. There are five top-level, or root keys, as shown in the table below.

| Root Key            | Contents                                                                                                                                                            |
| ------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| HKKEY_LOCAL_MACHINE | information about the physical state of the computer including hardware configuration, network log-on and security information, and Plug and Play information, etc. |
| HKEY_CURRENT_USER   | data about the preferences of the currently logged on user, including Personalization settings, default devices, and programs, etc.                                 |
| HKEY_CLASSES_ROOT   | setting about the file system, file associations, and shortcuts. information here is used when you ask Windows to run a file or view a directory                    |
| HKEY_USERS          | all of the configuration settings for the hardware and software configured on the computer for all users                                                            |
| HKEY_CURRENT_CONFIG | information about the current hardware profile of the machine                                                                                                       |
### Regedit
The Registry Editor allows an administrator to view or make changes to the Windows Registry. Using the Registry Editor utility incorrectly could cause hardware, application, or operating system problems, including problems that require you to reinstall the operating system.

The registry editor can only be opened from a search or command prompt. You can search for **regedit** and open it from the search results, or you can open a command or PowerShell prompt and type **regedit**.

The figure shows the **regedit** utility with the value of the OneDrive subkey open for modification.

![[fad0d1c22aa99765c670d08971585614dc2907cf.jpg]]

## Disk Management
The Disk Management utility is part of the Computer Management console. It can be opened by right-clicking on **This PC** or **Computer** and selecting **Manage**. It can also be opened through the Computer Management Control Panel item or in its own Window by using the **Win+X** menu and selecting **Disk Management**.

In addition to extending and shrinking partitions, as demonstrated in the previous chapter, you can also use the Disk Management utility to complete the following tasks:
- View drive status
- Assign or change drive letters
- Add drives
- Add arrays
- Designate the active partition

The figure shows the Disk Management utility in Windows 10.

![[bac09127040122c311a40d99ea223a1148cd9993.png]]

The Disk Management utility displays the status of each disk, as shown in the figure. The drives in the computer display one of the following conditions:

- **Foreign** - A dynamic disk that has been moved to a computer from another computer running Windows
- **Healthy** - A volume that is functioning properly
- **Initializing** - A basic disk that is being converted into a dynamic disk
- **Missing** - A dynamic disk that is corrupted, turned off, or disconnected
- **Not Initialized** - A disk that does not contain a valid signature
- **Online** - A basic or dynamic disk that is accessible and shows no problems
- **Online (Errors)** - I/O errors detected on a dynamic disk
- **Offline** - A dynamic disk that is corrupted or unavailable
- **Unreadable** - A basic or dynamic disk that has experienced hardware failure, corruption, or I/O errors
Other drive status indicators might be displayed when using drives other than hard drives, such as an audio CD that is in the optical drive, or a removable drive that is empty.

### Mounting a Drive
Mounting a drive refers to making a disk image file readable as a drive. A good example of this is an ISO file. It is the entire contents of the disk represented as a single file. ISO images are used as archives of the contents of an optical disk. Disk writer software can take an ISO file and write its contents to the disk.

These ISO files can also be mounted on virtual drives. To mount an image, open File Explorer and locate and select an ISO file. In the ribbon, select the Manage menu under Disk Image Tools. Select Mount. The ISO file will be mounted as a removable media drive. The drive can be browsed and files opened. However, there is actually no drive. The drive is an ISO image mounted as a volume.

You can also create a mount point. A mount point is similar to a shortcut. You can create a mount point that makes an entire drive appear as a folder. This might provide an easy way for users to access files since the mounted folder can appear in their My Documents folder, for example.

### Adding Arrays
In Windows disk management, you can create mirrored, spanned, or RAID 5 arrays from multiple dynamic disks. This is done by right-clicking a volume and selecting the type of multidisc volume that you want to create, as shown in the left figure. Note that there must be two or more initialized dynamic drives available on the computer.

Storage Spaces became available in Windows 8 and 10. Storage Spaces can be configured from a Control Panel item as shown in the right figure. Storage Spaces is the disk array technology that is recommended by Windows. It creates pools of physical hard drives from which virtual disks (storage spaces) can be created. Many different types of drives can be combined. Like other disk arrays, Storage Spaces offer mirrored, striped, and parity options.

### Optimization
To maintain and optimize disk storage, you can use various tools within Windows. Some of these tools include hard drive defragmentation, which consolidates files for faster access.

As files increase in size, some data is written to the next available cluster on the disk. In time, data becomes fragmented and spread over nonadjacent clusters on the hard drive. As a result, it takes longer to locate and retrieve each section of the data. A disk defragmenter gathers the noncontiguous data into one place, making the OS run faster.

**Note**: It is not recommended to perform disk defragmentation on SSDs. SSDs are optimized by the controller and firmware they use. It should not be harmful to defragment Hybrid SSDs (SSHD) because they use hard disks to store data, not solid-state ram.

In Windows 8 and 10, the option is called Optimize, as shown in the left figure. In Windows 7, it is called Defragment Now. It can be accessed from the disk properties menu or from the File Explorer ribbon in Windows 8 and 10.

The right figure shows the Optimize Drives utility. It allows analysis of the drive prior to optimization. The analysis will display the degree of fragmentation of the drive.

![[916f431d1400ab73eb26fed466ddeb1e0ded18b0.jpg]]

You can also optimize the available space by doing a disk Cleanup operation. This will remove unnecessary files from the drive.

### Error-Checking
The Disk Error-Checking tool checks the integrity of files and folders by scanning the hard disk surface for physical errors.

If errors are detected, the tool attempts to repair them. In File Explorer or File Manager, right-click the drive and select **Properties**. Select the **Tools** tab and select **Check** or **Check Now** in Windows 7. In Windows 8, select **Scan Drive** to attempt to recover bad sectors. In Windows 7, select **Scan for and attempt recovery of bad sectors** and click **Start**. The tool fixes file system errors and checks the disk for bad sectors. It also attempts to recover data from bad sectors.

In Windows 8 and 10, if you want to see a detailed report of the results of the scan, click Check Results after the scan has completed. This will open an Event Viewer window that will allow you to view the log entry for the scan. In Windows 7, a report is displayed by the error-checking utility, as shown in the figure.

**Note**: Use the Disk Error-Checking tool whenever a sudden loss of power causes the system to shut down incorrectly.

## [[Command Line Interface|CLI]]
### Powershell
The old Windows command line application was replaced in the Windows Power User menu Win+X with PowerShell. The original command line still exists in Windows 10, and can be opened by typing cmd into the search field on the Taskbar. You can also change which command line is displayed in the menu by changing a Taskbar setting.

PowerShell is a more powerful command line utility. It offers many advanced features, such as scripting and automation. It even comes with its own scripting development environment, called PowerShell ISE, to help with the task of writing scripts. PowerShell uses "cmdlets", or small applications, that represent the commands that are available. PowerShell also allows naming of cmdlets with aliases, so the same cmdlet can be run at the command line with any name that adheres to naming conventions that you choose to assign to it. Microsoft has created aliases for all of the old cmd commands so that it works much like the older command line.

The figure shows Windows ISE, with the PowerShell command line in the lower right window. PowerShell can also be opened as the command line shell alone.

![[32abac697f3baa9986cc8bb8c7305633e67f164f.jpg]]

### The Command Shell
Windows has two command line utilities. One is the classic **command** application, known as **cmd**. This command line is a remnant of the very early days of Microsoft when DOS was the only operating system that Microsoft had to offer. Many users were experienced with using cmd, so it was retained when Windows was developed. It has persisted as the default command line for Windows until Windows 10 build 14791 when PowerShell became the default. To open the command shell, type **cmd** in the search box and click the app in the results. You can also use the **Win+R** key to open a run box. Type **cmd** in the run box and click **OK**. Press **Ctrl+Shift+Enter** to run the command prompt as an administrator. The title bar for the command window will indicate that the command window is open in Administrator mode. You can also use the **whoami** command to display the name of the computer that the prompt is open on and the user account, as shown in the figure.

![[13c0aca7b554cb40ecb788f89d9f972da1944df6.png]]

#### Commands
Here we will focus on the **cmd** command line. All commonly used commands are supported by Windows 7, 8, and 10.
- help or /? : Get information on commands. Enter by itself to see all available commands. Type help followed by a specific command to see information about that command
- cls : Clears the screen. This command deletes all command output and moves the command prompt to the top of the command window.
- up-arrow : Move through previously entered commands. Previously entered commands are saved in the history buffer. The up-arrow key moves through the previously entered commands. If you type a command incorrectly, you can use the up-arrow key to recall it to the command line and edit it to correct it before executing.
- F7 : Display command history in an overlay window. Displays a list of the commands previously entered. Use the arrow keys to select a previously entered command and press `<enter>` to execute it. Use Esc to hide the window.
- ctrl + c : Exit a running command process or script. Press and hold the control key and then tap the c key. This will kill whatever command or script that is running.
- exit : Close the command window. Type exit to stop command execution and close the command window.

##### ls -l
Now that you have learned about some of the file and directory commands, let's examine the **ls -l** command output.
```
iteuser@iteuser:~$ ls -l
total 2
-rwxrw-r-- 1 iteuser staff 11485 Apr 21  2021 My_Awesome_File
drwx------ 2 iteuser staff  4096 Apr 21  2021 My_Private_Folder
iteuser@iteuser:~$
```
**Permission**
-rwxrw-r--
drwx------ 
The permission defines how the user, group, and other access the files and directories.

**Link**
1
2
The number of links or the number of directories inside this directory (My_Private_Folder in this example)

**User**
iteuser
iteuser

It displays the username of the owner of the file or the directory.

**Group**
staff
staff

It displays the name of the group that owns the file or the directory.

**File Size**
11485
 4096

This displays the file size in bytes.

**Date and Time**
Apr 21  2021
Apr 21  2021

This is the date and time of the last modification.

**File Name**
My_Awesome_File
My_Private_Folder

This displays the file or directory name.

#### Syntax
It is important to be able to use technical resources to learn how to use CLI commands. Different software vendors and organizations use different conventions to indicate syntax for commands. Microsoft provided an online command reference that can be found on the web. Many conventions used by Microsoft for CLI commands are summarized in the table.

| Notation                  | Description                   |
| ------------------------- | ----------------------------- |
| no brackets or braces     | must be typed as shown        |
| angle brackets : \<text>  | value that must be supplied   |
| square brackets : \[text] | optional input                |
| braces : {text}           | choose one of a list of items |
| vertical bar : \|         | mutually exclusive items      |
| ellipsis : ...            | repeatable input              |

Special character, called wildcards, can be substituted for character or groups of characters in file names. Wildcards can be used when you only know part of a file name that you are trying to find or when you want to perform a file operation on a group of files that share elements of a filename or extension. The two wildcards that can be used at the Windows command line are:
- the asterisk (\*) : this character matches groups of characters, including entire filenames and file extensions. the asterisk (commonly called the star) will match and character that is permitted in a filename and will also match any group of characters. for example `myfile.*` will match files that are called "myfile" with any file extension. in addition, `my*.txt` will match all filenames that start with my and have the ".txt" file extension
- the question mark (?) : this character stand for any single character. it does not stand for a group of characters. for example, to match `myfile.txt` using the question mark, you would need to use `my????.txt`. this will match filenames that start with my, and any four characters, and that have the ".txt" file extension

### File System Navigation
When working at the command line, there is no File Explorer to help you get to the files and folders that you want to work with. Instead, you need to move through the folder structure using a combination of commands, normally displaying the contents of a drive or directory and changing directories until you find what you are looking for.

For file system navigation at the command line, you can change drives, list contents, and change directories. The examples below show file system navigation at the command line.

\<Drive>: - Display contents from a different drive. Simply type the drive letter followed by a colon at the command prompt. The example shows directories displayed for the C: drive and then the drive is changed, and a directory is displayed for the D: drive.
```
C:\myFolders>dir
Volume in drive C is Windows
Volume Serial Number is 9C9E-C3F4
Directory of C:\myFolders 
04/04/2019  04:34 PM    <DIR>          .
04/04/2019  04:34 PM    <DIR>          ..
04/04/2019  04:37 PM    <DIR>          newfolder_2
0 File(s)              0 bytes
3 Dir(s)  133,658,624,000 bytes free 

C:\myFolders>d:
D:\>dir
Volume in drive D is ADATA DRIVE 
Volume Serial Number is CCD9-AB77

Directory of D:\
03/28/2019  06:37 PM     <DIR> iso
02/06/2019  04:52 PM     5,075,539,968
Win10_1809Oct_English_x64.iso
02/15/2019  02:23 PM     3,320,903,680 Win7_Pro_SP1_English_x64.iso
02/07/2019  10:57 AM     4,320,641,024 Win8.1_English_x64_no_reg.iso 3 File(s) 12,717,084,672 bytes 1 Dir(s)  14,903,140,352 bytes free 

D:\>
```
- dir : Display the contents of the current directory.
- dir \[\<Drive>:] \[\<Path>] \[\<FileName>]  : Has options to display various file attributes and properties. Options will also change how the file list is displayed.  
- /a - to display all files including hidden files.
- /os - to sort files by size
- /b - list file and folder names only
- /w - display wide view, with files and folders arranged in columns
```
C:\Users>dir 
Volume in drive C has no label. 
Volume Serial Number is 5A1B-98AA  
Directory of C:\Users 
03/14/2019  01:53 PM    <DIR>          .
03/14/2019  01:53 PM    <DIR>          ..
04/04/2019  06:12 PM    <DIR>          Admin
04/04/2019  03:34 PM    <DIR>          basic_user
04/02/2019  03:18 PM    <DIR>          drbon
03/06/2019  11:08 AM    <DIR>          Public 
0 File(s)              0 bytes 
6 Dir(s)  36,035,579,904 bytes free 

C:\Users>cd Admin 
C:\Users\Admin>dir 
Volume in drive C has no label. 
Volume Serial Number is 5A1B-98AA  

Directory of C:\Users\Admin 
04/04/2019  06:12 PM    <DIR>          .
04/04/2019  06:12 PM    <DIR>          ..
03/14/2019  11:51 AM    <DIR>          3D Objects
03/14/2019  11:51 AM    <DIR>          Contacts
04/02/2019  06:15 PM    <DIR>          data2
03/15/2019  01:08 PM    <DIR>          Desktop
04/03/2019  09:31 AM    <DIR>          Documents
04/02/2019  08:59 AM    <DIR>          Downloads
03/14/2019  11:51 AM    <DIR>          Favorites
04/02/2019  07:50 AM    <DIR>          Level_1
03/14/2019  11:51 AM    <DIR>          Links
04/03/2019  09:31 AM    <DIR>          Music
03/27/2019  12:17 PM    <DIR>          OneDrive
03/14/2019  03:11 PM    <DIR>          Pictures
03/14/2019  11:51 AM    <DIR>          Saved Games
03/14/2019  12:05 PM    <DIR>          Searches
04/03/2019  09:31 AM    <DIR>          Videos
0 File(s)              0 bytes 
17 Dir(s)  36,035,579,904 bytes free 

C:\Users\Admin>
```
- **cd -** Change directory
- **cd** \[/d] \[\<Drive>:] \[\<Path>] :Change the current directory to the path specified after the command.
- \<drive>: - display root directory of another drive
- /d - change drive and directory
- . - refers to current path
- .. - (two dots) to go up the path one level
- - Go to the root of the drive.
```
C:\myFolders>dir
Volume in drive C is Windows
Volume Serial Number is 9C9E-C3F4
Directory of C:\myFolders
04/04/2019  05:10 PM    <DIR> .
04/04/2019  05:10 PM    <DIR> ..
04/04/2019  05:10 PM    6 newfile1.txt
04/04/2019  05:10 PM    <DIR> newFolder_1
04/04/2019  04:37 PM    <DIR> newFolder_2
1 File(s)               6 bytes 4 Dir(s)  133,548,445,696 bytes free 

C:\myFolders>
```
You can create, move, and remove folders using the command line. The examples below show manipulating folders from the command line.
- **md** - Make directory. Create a new directory.
- **md** \[\<Drive>:]\<Path> : Make a new directory at the location specified. If you don't provide a drive and path, the new directory is created at the current location.
```
C:\myFolders>dir
Volume in drive C is Windows
Volume Serial Number is 9C9E-C3F4
Directory of C:\myFolders

04/04/2019  03:56 PM    <DIR>    .
04/04/2019  03:56 PM    <DIR>    ..
0 File(s)    0 bytes 
2 Dir(s)  133,642,625,024 bytes free 

C:\myFolders>md New_Folder 

C:\myFolders>dir 
Volume in drive C is Windows
Volume Serial Number is 9C9E-C3F4  
Directory of C:\myFolders
04/04/2019  04:21 PM    <DIR>    .
04/04/2019  04:21 PM    <DIR>    ..
04/04/2019  04:21 PM    <DIR> New_Folder
0 File(s)    0 bytes 
3 Dir(s)  133,642,625,024 bytes free 

C:\myFolders>
```
- **rd** - Remove directory. Delete a directory.
- **rd** \[\<Drive>:]\<Path>  
- /s - remove all subdirectories and files.
- /q - quiet mode, do not request confirmation when deleting subdirectories and files.
```
C:\myFolders>dir
Volume in drive C is Windows
Volume Serial Number is 9C9E-C3F4  

Directory of C:\myFolders
04/04/2019  04:21 PM    <DIR>    .
04/04/2019  04:21 PM    <DIR>    ..
04/04/2019  04:21 PM    <DIR>    New_Folder
0 File(s)    0 bytes 
3 Dir(s)    133,639,602,176 bytes free 

C:\myFolders>rd New_folder 

C:\myFolders>dir
Volume in drive C is Windows 
Volume Serial Number is 9C9E-C3F4  

Directory of C:\myFolders 

04/04/2019  04:27 PM    <DIR>    .
04/04/2019  04:27 PM    <DIR>    .. 
0 File(s)    0 bytes 
2 Dir(s)  133,639,602,176 bytes free 

C:\myFolders>
```
- **move** - Move a file or directory from one directory to another.
- **move** \[source]\[target] : The source can be in the current folder, but the destination must be another folder. Full paths including different drives can be supplied.
```
C:\myFolders>dir
Volume in drive C is Windows
Volume Serial Number is 9C9E-C3F4  

Directory of C:\myFolders
04/04/2019  04:33 PM    <DIR>    .
04/04/2019  04:33 PM    <DIR>    ..
04/04/2019  04:33 PM    <DIR>    newfolder_1
04/04/2019  04:33 PM    <DIR>    newfolder_2
0 File(s)    0 bytes 
4 Dir(s)    133,645,930,496 bytes free 

C:\myFolders>move newfolder_1 newfolder_2 
1 dir(s) moved. 

C:\myFolders>cd newfolder_2 

C:\myFolders\newfolder_2>dir
Volume in drive C is Windows
Volume Serial Number is 9C9E-C3F4  

Directory of C:\myFolders\newfolder_2 

04/04/2019  04:34 PM    <DIR>          .
04/04/2019  04:34 PM    <DIR>          ..
04/04/2019  04:33 PM    <DIR>          newfolder_1
0 File(s)              0 bytes 
3 Dir(s)  133,646,000,128 bytes free 

C:\myFolders\newfolder_2>
```
- **ren** - Rename a directory or file.
- **ren** \[path:old name] \[new name] : Renames a folder or file. The renamed folder must appear in the same folder as the original.
```
C:\myFolders\newfolder_2>dir
Volume in drive C is Windows
Volume Serial Number is 9C9E-C3F4  

Directory of C:\myFolders\newfolder_2 
04/04/2019  04:34 PM    <DIR>    .
04/04/2019  04:34 PM    <DIR>    ..
04/04/2019  04:33 PM    <DIR>    newfolder_1 
0 File(s)    0 bytes 
3 Dir(s)    133,540,413,440 bytes free 

C:\myFolders\newfolder_2>ren newfolder_1 newfolder 

C:\myFolders\newfolder_2>dir
Volume in drive C is Windows
Volume Serial Number is 9C9E-C3F4  

Directory of C:\myFolders\newfolder_2 
04/04/2019  04:37 PM    <DIR>    .
04/04/2019  04:37 PM    <DIR>    ..
04/04/2019  04:33 PM    <DIR>    newfolder 
0 File(s)    0 bytes 
3 Dir(s)    133,540,274,176 bytes free 

C:\myFolders\newfolder_2>
```
- **>** : Redirect. Send the output of a command to a file. Example: `dir > directory.txt` will send the output of the directory command to a text type file. Because the output is redirected, it does not display on the screen.
- **type** : Display the contents of a file. A very simple command for displaying the contents of a text type file. If the file name has spaces in it, use quotes around it. Combine with a pipe and **more** to display one screen at a time. Example: `type [<Drive>:][,<Path>] <FileName>`  
- **more** : Display the contents of a file one screen at a time. The more command can be used directly as a command to view a file one screen at a time. Example: `more [<Drive>:][,<Path>] <FileName>`
- **del** : Delete a file or folder. The del command will take a list of files or folders and wildcards. Files deleted with this command are not normally recoverable. Parameters allow deletion of files with specific attributes. Example: `del <name>`
- **copy** : Make a copy of a file. Copy a file to the destination filename and location. The same folder as the source is the default if no path is specified. Many parameters provide flexibility to the command. Example: `copy <source> [<destination>]`
- xcopy : Extended copy. Copy files of entire directory trees. A more powerful way to copy files and directories with many useful options. Microsoft now recommends the use of **robocopy** instead of **xcopy**. Example: `xcopy <source> <destination>`
- **robocopy** : Robust copy. Copy files and entire directory trees. This command is extremely powerful with many options for the way that files are copied, the types of files to include in the copy action, and the file attributes to include for the destination files. Example: `robocopy <source> <destination>`
- **move** : Move a file from a source location to a destination location. Removes the file from the source location and moves it to the destination. Example: `move <source> <destination>`

## Running System Utilities
The Windows run line utility can be opened by pressing the **Win+R** keys and entering **cmd** to open the command line window, as shown in the figure. The following windows utilities and tools can also be run by entering the commands shown in the run line utility.
- **EXPLORER** - Opens File Explorer or Windows Explorer.
- **MMC** - Opens Microsoft Management Console (MMC). Specify the path and .msc filename to open a saved console.
- **MSINFO32** - Opens the System Information window, which shows a summary of system components, including hardware components and software information.
- **MSTSC** - Opens the Remote Desktop utility.
- **NOTEPAD** - Opens the Notepad basic text editor.

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
Windows settings is designed to make configuring and personalizing the Windows OS more convenient for end users. 

The Settings App first appeared in Windows 8 as shown in the figure. It provided access to fewer settings than the Windows 10 version, which has now become robust. Note that a search field enables you to find settings without taking a lot of time clicking through menus.

![[29422b97e5e7636210cbdfdc95a757afd4479bb1.png]]

Questions on these topics will begin with a scenario.

### Default Programs
The Default Programs Control Panel item provides the means to configure the way that Windows handles files and the applications that are used to work with them, as shown in the figure. For example, if you have multiple web browsers installed, you can choose which web browser will open to view a link that you have clicked on in an email or other file.

This can be done by choosing default applications, or by choosing which application opens for a specific file type. For example, you configure a JPEG graphics file to open in a browser, for viewing, or in a graphics editor.

Finally, you can choose how AutoPlay works. You can select how Windows will automatically open files of different types depending on the type of removable storage media that they are stored on. You can select to have audio CDs open automatically in Windows Media Player, or have a Windows File Explorer display a directory of the disk contents.

Windows 10 uses a settings app for all but the AutoPlay configuration. Windows 7 and 8 use Control Panel utilities.

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

### Workgroup vs. Domain 
There are three primary networking models in the Windows OS: the homegroup, the workgroup, and the domain. Workgroup allows the OS to be both a server and a client and is primarily used in small office/home office (SOHO) setups. With the domain networking model, the client must be joined to the domain.
- **Domain** - A domain is a group of computers and electronic devices with a common set of rules and procedures administered as a unit. Computers in a domain can be located in different locations in the world. A specialized server called a domain controller manages all security-related aspects of users and network resources, centralizing security and administration. For example, within a domain, Lightweight Directory Access Protocol (LDAP) is a protocol used to allow computers to access data directories that are distributed throughout the network.
- **Workgroup** - A workgroup is a collection of workstations and servers on a LAN that are designed to communicate and exchange data with one another. Each individual workstation controls its user accounts, security information, and access to data and resources.

All computers on a network must be part of either a domain or a workgroup. When Windows is first installed on a computer, it is automatically assigned to a workgroup. The control panel used to change these settings is shown in the figure.

#### Shared Resources
Windows allows sharing of files and folders over the network, allowing a shared space for network users. For convenience, **network shares** can be mapped to a drive letter. For the users and applications, the network share appears like a local disk. Other resources, such as hardware-based resources, can also be shared among the networking group.

**[Administrative shares]** are created automatically to allow remote administrators to configure the computer. These shares are not shown and are not accessible to non-administrative users.

#### Printers
You can use the **[printer sharing]** functionality to allow printing from other computers to the printer connected locally. To print using a shared printer on a remote computer, it needs to be **mapped** first, installing the drivers for the printer.

#### File Servers
May also be shared among the networking group.

#### Network and File Sharing
Network file sharing and mapping network drives is a secure and convenient way to provide easy access to network resources. This is especially true when different versions of Windows require access to network resources.

Determine which resources will be shared over the network and the type of permissions users will have to the resources. Permissions define the type of access a user has to a file or folder.
- **Read** - The user can view the file and subfolder names, navigate to subfolders, view data in files, and run program files.
- **Change** - In addition to Read permissions, the user can add files and subfolders, change the data in files, and delete subfolders and files.
- **Full Control** - In addition to Change and Read permissions, the user can change the permission of files and folders in an NTFS partition and take ownership of files and folders.

#### Mapped Drives
Mapping drives allows for network shares to be connected to a specified drive letter for ease of access among the networking group. 

Mapping a local drive is a useful way to access a single file, specific folders, or an entire drive between different operating systems over a network. Mapping a drive is done by assigning a letter (A to Z) to the resource on a remote drive, and allows you to use the remote drive as if it was a local drive.

### HomeGroup
A homegroup was a feature introduced in Windows 7 and is also available in Windows 8 to simplify secure access to shared resources such as folders, pictures, music, videos, and printers on a home network. Homegroup has been removed from Windows 10 with the release of Windows 10 (1803).

All Windows computers that belong to the same workgroup can also belong to a homegroup. There can only be one homegroup per workgroup on a network. Computers can only be a member of one homegroup at a time. Homegroups are secured with a simple password. A homegroup can be a mix of Windows 7 and Windows 8 computers.

One user in the workgroup creates the homegroup. The other users can join the homegroup, provided they know the homegroup password. Homegroup availability depends on your network location profile:
- **Home Network** - allowed to create or join a homegroup
- **Work Network** - not allowed to create or join a homegroup, but you can view and share resources with other computers
- **Public Network** - homegroup not available

When a computer joins a homegroup, all user accounts on the computer, except the Guest account, become members of the homegroup. Being part of a homegroup makes it easy to share pictures, music, videos, documents, libraries, and printers with other people in the same homegroup. Users control access to their own resources.

**Note**: If a computer belongs to a domain, you can join a homegroup and access files and resources on other homegroup computers. You are not allowed to create a new homegroup or share your own files and resources with a homegroup.

### Sharing Local resources
Windows 10 controls which resources are shared and how they are shared by turning specific sharing features on and off. Advanced Sharing Settings, located in the Network and Sharing Center, manages the sharing options for three different network profiles; Private, Guest or Public, and All Networks. Different options can be chosen for each profile. The following items can be controlled:
- Network discovery
- File and printer sharing
- Public folder sharing
- Password protected sharing
- Media Streaming

To access Advanced Sharing Settings, use the following path: **Start > Control Panel > Network and Internet > Network and Sharing Center**

To enable sharing resources between computers connected to the same workgroup, Network Discovery and File and printer sharing must be turned on, as shown in the figure.

There are simple file sharing mechanisms developed by OS vendors. Microsoft’s file sharing mechanism is called Nearby Sharing. Nearby Sharing was introduced in Windows 10, partly replacing the previous Homegroup feature. Nearby Sharing provides the ability to share content with a nearby device using both Wi-Fi and Bluetooth.

AirDrop is supported by Apple iOS and macOS and uses Bluetooth to establish a Wi-Fi direct connection between devices for the file transfer to take place. There are also many third-party and open source alternatives, however, there is the potential for security vulnerabilities that allow unsolicited transfers.

#### [[Printers]]
Printing is one of the most common tasks for users in both home and business environments.

A print device can be directly attached to a computer via USB or direct network connection. This is considered a “local” printer and the PC it is attached to is acting as the print server. The local printer can be shared on the network via the Sharing tab on the Printer Properties dialog box as shown in the figure. Once a printer is shared, users with the correct permissions can connect to the network shared printer. Drivers for the print device can also be installed on the local computer so that clients obtain the driver when they connect to the print share.  
To find the network shared printer users can browse through network resources using the Network object in File Explorer.



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

To communicate and share resources over a network that is not secure, a Virtual Private Network (VPN) is used. A VPN is a private network that connects remote sites or users together over a public network, like the internet. The most common type of VPN is used to access a corporate private network.

The VPN uses dedicated secure connections, routed through the internet, from the corporate private network to the remote user. When connected to the corporate private network, users become part of that network and have access to all services and resources as if they were physically connected to it.

Remote-access users must install a VPN client on their computers to form a secure connection with the corporate private network. Special routers can also be used to connect computers connected to it to the corporate private network. The VPN software encrypts data before sending it over the internet to the VPN gateway at the corporate private network. VPN gateways establish, manage, and control VPN connections, also known as VPN tunnels. A VPN client software is shown in the left figure.

A VPN in Windows 10 can be set up from the Network and Sharing Center is shown in the right figure.

Windows supports several VPN types, however, for some VPNs, third-party software may be required.

##### Telnet and SSH
Telnet is a command-line terminal emulation protocol and program. The Telnet daemon listens for connections on TCP port 23. Telnet is sometimes used for troubleshooting services and for connecting to routers and switches for entering configurations. Telnet is not installed in Windows by default but can be added using Programs and Features. There are also third-party and free terminal emulation programs available that have support for Telnet. Telnet messages are sent in clear text. Anyone with a packet sniffer can capture and see the contents of Telnet messages. This is why it is advisable to use a secure connection rather than Telnet.

Secure Shell (SSH) is a secure alternative to Telnet and other file copy programs such as FTP. SSH communicates over TCP port 22 and uses encryption to protect the session. There are several methods in which a client can authenticate to an SSH server:
- **Username/Password** - The client sends credentials to the SSH host, which are then verified against a local user database or sent to a centralized authentication server.
- **Kerberos** - Networks which use Kerberos authentication protocol, such as Windows Active Directory, allow for Single Sign-On (SSO). SSO allows users to sign in to multiple systems with only one username and password.
- **Host-based authentication** - The client requests authentication with a public key. The server generates a challenge with this key which the client must decrypt with the matching private key to complete the authentication.
- **Public key authentication** - This provides additional protection over host-based authentication. The user must enter a passphrase to access the private key. This helps prevent the private key from becoming compromises.

#### Wired
Wired connections usually come in a form of **ethernet** to the computers. It requires cabling to every computer and may require other network devices like switches and routers.

#### Wireless
Wireless network connections use Wi-Fi technology to connect. Because it is not physically restricted in the area, the network will usually have another layer of security in the form of a password or **more complex authentication**. Once connected, the functionality is very similar to a wired connection.

Wireless networks can be added in Windows 10 by going to Settings > Network & Internet > Wi-Fi > Manage known networks, as shown in the figure. Enter the network name and select a security type that matches the configuration on the wireless router. There are four security type options:
- **No authentication (Open)** – Data is sent unencrypted and with no authentication
- **WEP** – Provides very weak security and should not be relied upon for confidentiality
- **WPA2**-Personal – Uses the Advanced Encryption Standard (AES) cipher and a Pre-shared Key (PSK) to encrypt communications.
- **WPA2-Enterprise** – Authentication is passed from the access point to a centralized authentication server running Remote Authentication Dial-in User Service (RADIUS)

Remote authentication for wireless devices can be provided by a scalable authentication architecture by using RADIUS or Terminal Controller Access Control System Plus (TACACS+). Both technologies use a separate server (an Authentication, Authorization, and Accounting (AAA) server) that performs the authentication on behalf of network devices. Rather than the network devices storing and validating user credentials directly, they pass the request to the AAA server and forward the response to the user.

#### Wireless Wide Area Network (WWAN)
Similar to mobile phones that can access the internet from anywhere, a WWAN is a cellular network that can be used to connect to the network. Some tablets and laptops come with built-in cellular hardware.

### Proxy Settings
A proxy server is a form of a gateway. A common example is a web proxy that is set up to filter access to the internet from a local network to improve security.

### Network Profiles
The first time a computer with Windows 10 connects to a network, a network profile must be selected. Each network profile has different default settings. Depending on the profile selected, file and printer sharing, or network discovery can be turned off or on, and different firewall settings can be applied.

Windows 10 has two network profiles:
- **Public** – The public profile disables file and printer sharing and network discovery on the link. The PC is hidden from other devices. It is accessible to everyone within range.
- **Private** – The private profile allows the user to customize the sharing options. This profile is for use on trusted networks. The PC is discoverable by other devices. A private network is protected and limited to those who have proper authentication.

### File Explorer Navigation – Network Paths
Within a network, File Explorer navigation is achieved through pre-configured network paths. The Universal Naming Convention (UNC) path is the standard way to navigate to the server and fileshare in the Windows OS.

### Metered Connections and Limitations
Metered connections are **[based on usage]** and come with limitations to keep usage down. When using a metered connection, updates, whether they be for the OS, application, or system security, will not download and install.

### Wired Network Interfaces
Windows 10 network settings are managed through the Network & Internet section in the Settings App. From the Network & Internet window, there are links to View network properties and to the Network and Sharing Center. Available network connections, both wired and wireless, can be viewed by selecting the Change Adapter Options link. From there, each network connection can be configured.

Network card properties are configured in the Advanced tab of the adapter properties window. Navigate to Device Manager. Locate and right click the network adapter. Choose **Properties > Advanced** tab. A list of properties allows configuration of features such as Speed & Duplex, QoS, Wake-on LAN, and many others. Click the desired feature in the **Property:** drop down list. Each property has configurable values in the Value: drop list.

The Windows Internet Protocol Version 4 (TCP/IPv4) Properties window includes an Alternate Configuration tab which allows an administrator to configure an alternative IP address for the PC to use if it is unable to contact a DHCP server. Note that this tab is not visible if a static IPv4 address configuration is configured in the General tab.

#### Configuring a Wired NIC
After the NIC driver is installed, the IP address settings must be configured. A computer can be assigned its IP configuration in one of two ways:
- **Manually** – The host is statically assigned a specific IP configuration.
- **Dynamically** – The host requests its IP address configuration from a DHCP server.

From the properties window of the wired NIC, both IPv4 and IPv6 addresses and other options such as the default gateway and DNS server address can be configured, as shown in the figure.

The default setting for both IPv4 and IPv6 is to obtain the IP settings automatically using DHCP in the case of IPv4 and Stateless Automatic Address Configuration (SLAAC) in the case of IPv6.

**Note**: Most computers today come with an onboard NIC. If you are installing a new NIC, it is considered a best practice to disable the onboard NIC in BIOS settings.

#### IPv4 Configuration
To configure the IPv4 setting manually click **Use the following IP address** and enter the appropriate IPv4 address, subnet mask, and default gateway. If a Windows machine fails to obtain an IPv4 address dynamically it will use an Automatic Private IP Addressing (APIPA) address from a reserved range in the 169.254.x.y network space.

Windows 10 allows for an alternative IPv4 address configuration for a computer if it cannot access a DHCP server and if APIPA is unsuitable or not desired. This is useful for mobile devices that move between a network with DHCP and another network that needs a static IPv4 address.

#### IPv6 Configuration
To configure IPv6 settings click **Internet Protocol Version 6 (TCP/IPv6) > Properties** to open the Internet Protocol Version 6 (TCP/IPv6) Properties window. Click **Use the following IPv6 address** and enter the appropriate IPv6 address, prefix length, and default gateway.

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

## Preventative Maintenance
To ensure that an OS remains fully functional, you must implement a preventive maintenance plan. A preventive maintenance plan provides many benefits to users and organizations such as decreased downtime, improved performance, improved reliability, and lower repair costs.

Preventive maintenance plans should include detailed information about the maintenance of all computers and network equipment. The plan should prioritize equipment that would affect the organization the most if that equipment fails. Preventive maintenance for an OS includes automating tasks to perform scheduled updates. Preventive maintenance also includes installing service packs that help keep the system up to date and compatible with new software and hardware. Preventive maintenance includes the following important tasks:
- Hard drive error checking, defragmentation, and backup
- Updates to the operating system, applications, antivirus, and other protective software

Perform preventive maintenance regularly, and record all actions taken and observations made. A repair log helps you determine which equipment is the most or least reliable. It also provides a history of when a computer was last fixed, how it was fixed, and what the problem was.

Preventive maintenance should take place when it causes the least amount of disruption to the users. This often means scheduling tasks at night, early in the morning, or over the weekend. There are also tools and techniques that can automate many preventive maintenance tasks.

### Security
Security is an important aspect of your preventive maintenance program. Install virus and malware protection software and perform regular scans on computers to help ensure that they remain free of malicious software. Use the Windows Malicious Software Removal Tool to check a computer for malicious software. If an infection is found, the tool removes it. Each time a new version of the tool is available from Microsoft, download it and scan your computer for new threats. This should be a standard item in your preventive maintenance program, along with regular updates to your antivirus and spyware removal tools.

### Startup Programs
Some programs, such as antivirus scanners and spyware removal tools, do not automatically start when the computer boots. To ensure that these programs run each time the computer is booted, add the program to the Startup folder of the Start Menu. Many programs have switches to allow the program to perform a specific action such as starting without being displayed. Check the documentation to determine if your programs allow the use of special switches.

### Updates
Windows Update is a website located at update.microsoft.com. The site hosts maintenance updates, critical updates, and security patches as well as optional software and hardware updates for Microsoft Windows versions 7, 8 and 10. There is also a program called Microsoft Update which can keep Microsoft Office software patched at the same time. A control installed in Windows allows the OS to browse the update site and select updates for download and installation using the Background Intelligent Transfer Service, or BITS, protocol.

Microsoft releases updates on the second Tuesday of each month, unofficially known as Patch Tuesday.

Windows 10 automatically downloads and installs updates to make sure your device is secure and up to date. This means you receive the latest fixes and security updates, helping your device run efficiently and securely. In most cases, the only user interaction required is the restarting of your device to complete the update.

You can manually check for updates in Windows 10 via Settings > Update and Security as shown in the figure. You can choose which updates to apply and configure update settings.

A windowsupdate.log file stored in the **%SystemRoot%** directory contains records of update activity. If an update fails to install properly you can check the log file for an error code that can be referenced on the Microsoft Knowledge Base. If an update causes problems, it can be uninstalled from **Settings > Update and Security > View Update History**.

#### Device Drivers
Manufacturers occasionally release new drivers to address issues with the current drivers. Check for updated drivers when your hardware does not work properly or to prevent future problems. It is also important to update drivers that patch or correct security problems. If a driver update does not work properly, use the Roll Back Driver feature to revert back to the previously installed driver.

#### Firmware
Firmware updates are less common than driver updates. Manufacturers release new firmware updates to address issues that might not be fixed with driver updates. Firmware updates can increase the speed of certain types of hardware, enable new features, or increase the stability of a product. Follow the manufacturer’s instructions carefully when performing a firmware update to avoid making the hardware unusable. Research the update completely because it might not be possible to revert to the original firmware.

---

# Common OS Types
macOS and Linux operating systems come with similar utilities, tools, and commands for configuration and maintenance. You must be able to identify common features and tools of the macOS/Desktop OS.

You must be able to identify common OS types and their primary purposes.

## Open vs. Closed Source
Before users can analyze and modify software, they must be able to see the source code. Source code is the sequence of instructions that is written in human readable language, before it is turned into machine language (zeroes and ones). The source code is an important component of free software as it allows the users to analyze and eventually modify the code. When the developer chooses to provide the source code, the software is said to be open source. If the program’s source code is not published, the software is said to be closed source.

### Android
Android is an open source, Linux based smartphone/tablet operating system developed by the Open Handset Alliance, primarily driven by Google. Released in 2008 on the HTC Dream, the Android OS has been customized for use on a wide range of electronic devices. Because Android is open and customizable, programmers can use it to operate devices like laptops, smart TVs, and e-book readers. There have even been Android installations in devices like cameras, navigation systems, and portable media players. The figure shows Android running on a tablet.

### iOS
iOS is a closed source Unix based operating system for Apple’s iPhone smartphone and iPad tablet. Released in 2007 on the first iPhone, the Apple iOS source code was not released to the public. To copy, modify or redistribute iOS requires permission from Apple. The figure shows iOS running on an iPhone.

### Windows Mobile
iOS is not the only closed source OS for mobile devices. Microsoft also created a version of Windows for their mobile devices. This includes Windows CE, Windows Phone 7, shown in the figure, and Windows Phone 8. With the development of Windows 10 Mobile, Microsoft provides a very similar user interface and use of code an all of their devices. This includes their Windows 10 Mobile phones and tablets they develop under the name Surface.

## Disk Utilities
To help diagnose and solve disk-related problems, most modern operating systems include disk utility tools. Ubuntu Linux includes a disk utility called Disks. With Disks users can perform the most common disk-related tasks including partition management, mount or unmount, format disks and query Analysis and Reporting Technology, (S.M.A.R.T.). macOS includes Disk Utility. In addition to supporting the main disk maintenance tasks, Disk Utility also supports Verify Disk Permissions and Repair Disk Permissions. Repair Disk Permission is a common troubleshooting step in macOS. Disk Utility can also be used to backup disks to image files and perform an image recovery to disk from image files. These files contain the entire contents of a disk.

Below are a few common maintenance tasks that can be performed using disk utility software:
- **Partition management** – When working with computer disks, partitions may need to be created, deleted or resized.
- **Mount or Unmount disk partitions** – On Unix-like systems, mounting a partition relates to the process of binding a partition of a disk or a disk image file (usually a .iso) to a folder location.
- **Disk Format** – Before a partition can be used by the user or the system, it must be formatted.
- **Bad Sector Check** –When a disk sector is flagged as bad, it becomes harmless to the OS because it will no longer be used to store data. Many bad sectors could be an indicator of a failing disk. Disk utilities can salvage data stored in bad sectors by moving it to healthy disk sectors.
- **Query S.M.A.R.T. attributes** – S.M.A.R.T. can detect and report attributes about a disk’s health. The goal of S.M.A.R.T. is to anticipate disk failure, allowing the user to move the data to a healthy disk before the failing disk becomes inaccessible.

## Security
Usernames, passwords, digital certificates, and encryption keys are just a few of the security credentials associated to a user. Due to the increasing number of necessary security credentials, modern operating systems include a service to manage them. Applications and other services can then request and utilize the credentials stored by the security credentials manager service.

### Security Credentials Service on Ubuntu
Security Credentials Service on Ubuntu Gnome-keyring is a security credentials manager for Ubuntu Linux. To access Gnome-Keyring on Ubuntu Linux use the following path:  
	**Click Dash > Search for Key > Click Passwords and Keys**

### Security Credentials Service on Ubuntu
Security Credentials Service on Ubuntu Gnome-keyring is a security credentials manager for Ubuntu Linux. To access Gnome-Keyring on Ubuntu Linux use the following path:  
	**Click Dash > Search for Key > Click Passwords and Keys**

## Mobile
### Android Main Home Screen
One screen is designated as the home screen. Additional screens are accessed by sliding the home screen to the left or right. Each screen contains navigation icons, the main area where icons and widgets are accessed, and notification and system icons. The screen indicator displays which screen is currently active.

The Android® OS uses the system bar to navigate apps and screens. The system bar is always displayed at the bottom of every screen.  
  
The system bar contains the following buttons:
- **Back** - Returns to the previous screen. If the on-screen keyboard is displayed, this button closes it. Continuing to press the Back button navigates through each previous screen until the home screen is displayed.
- **Home** - Returns to the home screen.
- **Recent Apps** - Opens thumbnail images of recently used apps. To open an app, touch its thumbnail. Swipe a thumbnail to remove it from the list.
- **Menu** – If available, Menu shows additional options for the current screen.

Each Android® device has an area that contains system icons, such as the clock, battery status, and radio signal status for Wi-Fi and provider networks. Apps such as email, text messaging, and Facebook® often display status icons to indicate communication activity.

To open the notification area on Android® devices, swipe down from the top of the screen. You can do the following when notifications are open:
- Respond to a notification by touching it.
- Dismiss a notification by swiping it off the screen to either side.
- Dismiss all notifications with the icon.
- Toggle often-used settings.
- Adjust the brightness of the screen.
- Open the Settings menu with the quick settings icon.

### iOS Home Screen Items
The iOS interface works in much the same way as the Android interface. Screens are used to organize apps, and apps are launched with a touch. There are some very important differences:
- No navigation icons - A physical button may have to be pressed instead of touching navigation icons.
- No widgets - Only apps and other content can be installed on iOS device screens.
- No app shortcuts - Each app on a home screen is the actual app, not a shortcut.

Home button
Unlike Android, iOS devices do not use navigation icons to perform functions. On iPhone versions prior to the iPhone X, a single physical button called the Home button performs many of the same functions as the Android navigation buttons. For these older phones, the Home button is at the bottom of the device and can perform many functions. Some common functions performed by the home button with explanations of how these functions are performed on the iPhone X, which has eliminated the home button, are shown below:
- **Wake the device** - When the device’s screen is off, press the Home button once to turn it on. On iPhone X you can wake the device using either facial recognition or by raising the phone and tapping the screen. (Raise to wake is also available on iPhone versions 6s or later.)
- **Return to the home screen** - Press the Home button while using an app to return to the last home screen that was used. On iPhone X return to the home screen by swiping the screen up from the bottom.
- **Start Siri or voice control** – Press and hold the Home button to start Siri or voice control. Siri is special software that understands advanced voice controls. On iPhone X Siri is launched by pressing and holding the side button.

Notification Bar
iOS devices have a notification center that displays all alerts in one location. To open the notification area on iOS devices, touch the top center of the screen and swipe down. This will show the phone's lock screen. Any notifications will appear in the middle area of the screen, as shown in the figure. From here, you can browse notifications and alerts, dismiss them, clear them, and adjust them as necessary.

Commonly used Settings
iOS devices allow the user to quickly access common settings and switches, even if the device is locked. To access the commonly used settings menu, swipe down from the top right corner.

The Control Center comes with some default controls that are always available. You can configure addition controls by navigating to **Settings > Control Center**. In the figure, the user has added the Flashlight, Timer, Calculator, Camera, and other apps to the Control Center screen.

iOS Spotlight
From any screen of an iOS device, touch the screen and drag down to reveal the Spotlight search field. Any part of the screen except the very top or the very bottom should work. When Spotlight search field is revealed, type what you're looking for. Spotlight shows suggestions from many sources including your installed apps, Setting, the internet, iTunes, App Store, movie show times, and nearby locations. Spotlight also automatically updates the results as you type.

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

### Screen Orientation
Most mobile devices can be used in either portrait or landscape mode. A sensor inside the device known as an accelerometer, detects how it is being held and will change the screen orientation appropriately. Users can choose the viewing mode that is the most comfortable for them for different types of content or applications. Content is automatically rotated to the position of the device. This feature is useful, for example, when taking a photograph. When the device is turned to landscape mode, the camera app also turns to landscape mode. Also, when a user is writing a text, turning the device to landscape mode automatically turns the app to landscape mode, making the keyboard larger and wider.

Some devices also have gyroscopes to provide more accurate movement readings. Gyroscopes allow a device to be used as a control mechanism for driving games where the phone or tablet itself functions as a steering wheel.

#### Android Screen Auto-Rotation Setting
When using an Android device, to enable auto rotation, open the notifications panel and turn on the auto-rotate function by tapping the screen rotation icon, indicated in the figure.

#### iOS Screen Auto-Rotation Setting
When using an iOS device, to enable automatic rotation use the following procedure:  
	**Swipe up from the bottom or down from the top to open the control center, depending on your device. > tap the lock icon.**

### Screen Calibration
When using a mobile device, you may need to adjust the brightness of the screen. When bright sunlight makes the screen difficult to read, increase the brightness level. Inversely, very low brightness is helpful when reading a book on a mobile device at night. Some mobile devices can be configured to auto-adjust the brightness depending on the amount of surrounding light. The device must have a light sensor to use auto-brightness.  
The LCD screen for most mobile devices uses the most battery power. Lowering the brightness or using auto-brightness helps conserve battery power. Set the brightness to the lowest setting to get the most battery life from the device.

#### Android Brightness Menu
When using an Android device, to configure screen brightness use the following path:  
	**Swipe down from the very top of the screen > Display > Brightness > slide the brightness to the desired level**  
  
Alternatively, tap the **Adaptive Brightness** toggle to allow the device to decide the optimal screen brightness based on the amount of ambient light.

#### iOS Display & Brightness Menu
When using an iOS device, to configure screen brightness, use the following path:  
  
Swipe up from the very bottom of the screen > slide the brightness bar up or down to vary the brightness.  
  
Alternatively, to configure brightness in the Settings menu, use the following path:  
	**Settings > Display & Brightness > slide the brightness to the desired level.**  
  
Alternatively, tap the **Auto-Brightness** toggle to allow the device to decide the optimal screen brightness based on the amount of ambient light.

### [[Global Positioning System|GPS]]
Another common feature of mobile devices is the Global Positioning System (GPS). GPS is a navigation system that determines the time and geographical location of the device by using messages from satellites in space and a receiver on Earth. A GPS radio receiver uses at least four satellites to calculate its position based on the messages. GPS is very accurate and can be used under most weather conditions. However, dense foliage, tunnels, and tall buildings can interrupt satellite signals. GPS receivers must have line-of-sight to GPS satellites and do not work indoors. Indoor Positioning Systems (IPS) can determine device location by triangulating its proximity to other radio signals such as Wi-Fi access-points.

GPS services allow app vendors and website to know the location of a device and offer location-specific services (such as local weather and advertising). This is called geotracking.

#### Android location services
To enable GPS on Android devices use the following path:  
	**Settings > Location > Tap on the toggle to turn location services on**

#### iOS location services
To enable GPS on iOS devices use the following path:  
	**Settings > Privacy > Location services > Turn location services on**

### Wi-Fi Calling
Instead of using the cellular carrier's network, modern smartphones can use the internet to transport voice calls by taking advantage of a local Wi-Fi hotspot. This is called Wi-Fi calling. Locations, such as coffee shops, work places, libraries, or homes, usually have Wi-Fi networks connected to the internet. The phone can transport voice calls through the local Wi-Fi hotspot. If there is no Wi-Fi hotspot within reach, the phone will use the cellular carrier's network to transport voice calls.

Wi-Fi calling is very useful in areas with poor cellular coverage because it uses a local Wi-Fi hotspot to fill the gaps. The Wi-Fi hotspot must be able to guarantee a throughput of at least 1Mbps to the internet for a good quality call. When Wi-Fi calling is enabled and in use during a voice call, the phone will display "Wi-Fi" next to the carrier name.

#### Wi-Fi Calling on Android
To enable Wi-Fi calling on Android use the following path:  
	**Settings > More (under Wireless & networks section) > Wi-Fi Calling > Tap on the toggle to turn it on**

#### Wi-Fi Calling on iOS
To enable Wi-Fi calling on iOS use the following path:  
	**Settings > Phone and turn on Wi-Fi Calling**  
  
**Note:** Not all cellular carriers allow Wi-Fi calling. If you cannot enable it on your phone, your carrier or mobile device probably does not support it.

### [[Near Field Communication|NFC]]

#### Premium SMS Based Transactional Payments
Consumers send an SMS message to a carrier's special phone number containing a payment request. The seller is informed the payment has been received and is cleared to release the goods. The charge is then added to the customer's phone bill. Slow speed, poor reliability, and poor security are a few shortcomings of this method.

#### Direct Mobile Billing
Using a mobile billing option during check-out, a user identifies their self (usually through two-factor authentication) and allows the charge to be added to the mobile service bill. This is very popular in Asia and has the following benefits: security, convenience, and no need for bank cards or credit cards.

#### Mobile Web Payments Contactless
The consumer uses the web or dedicated apps to complete the transaction. This method relies on the Wireless Application Protocol (WAP) and usually requires the use of credit cards or a pre-registered online payment solution, such as PayPal or Venmo.

#### Contactless NFC
[[Near Field Communication|NFC]] is a mobile payment method used mostly in physical store transactions. A consumer pays for good or services by waving the phone near the payment system. Based on a unique ID, the payment is charged directly against a pre-paid account or bank account. NFC is also used in mass-transportation services, the public parking sector, and many other consumer areas.

### Virtual Assistants
A digital assistant, sometimes called a virtual assistant, is a program that can understand natural conversational language and perform tasks for the end user. Modern mobile devices are powerful computers, making them the perfect platform for digital assistants. Popular digital assistants currently include Google Now for Android, Siri for iOS, and Cortana for Windows Phone.

These digital assistants rely on artificial intelligence, machine learning, and voice recognition technology to understand conversational-style voice commands. As the end user interacts with these digital assistants, sophisticated algorithms predict the user's needs and fulfill requests. By pairing simple voice requests with other inputs, such as GPS location, these assistants can perform several tasks, including playing a specific song, performing a web search, taking a note, or sending an email.

#### Google Now
To access Google Now on an Android device simply say "Okay google" and Google Now will activate and start listening to requests.

#### Siri
To access Siri on an iOS device, press and hold the Home button. Siri will activate and start listening to requests. Alternatively, Siri can be configured to start listening to commands when it hears "Hey Siri". To enable "Hey Siri", use the following path:  
	**Settings > Siri & Search > Toggle Listen for "Hey Siri".**

### [[Security]]

#### Restrictions on Failed Login Attempts
When a passcode has been properly implemented unlocking a mobile device requires entering the correct PIN, password, pattern, or another passcode type. In theory, a passcode, such as a PIN, could be guessed given enough time and perseverance. To prevent someone from trying to guess a passcode, mobile devices can be set to perform defined actions after a certain number of incorrect attempts have been made.

For Android devices, the number of failed attempts before lockout depends on the device and version of Android OS. It is common that an Android device will lock when a passcode has failed from 4 to 12 times. After a device is locked, you can unlock it by entering the Gmail account information used to set up the device.

##### IOS 
Erase Data
For iOS devices, you can turn on the Erase data option as shown. If the passcode fails 10 times, the screen goes black, and all data on the device is deleted. To restore the iOS device and data, if you have backups, use either the Restore and Backup option in iTunes or the Manage Storage option in iCloud.

iOS GUI
On iOS, to increase security, the passcode is used as part of the encryption key for the entire system. Because the passcode is not stored anywhere, no one can gain access to the user data on iOS devices, including Apple. The system depends on the user to provide the passcode before the system can be unlocked and decrypted for use. A forgotten passcode will render user data unreachable, forcing the user to perform a full restore from a backup saved in iTunes or iCloud.

### Cloud-Enabled Services

#### Remote Backup
Mobile device data can be lost due to device failures or the loss or theft of the device. Data must be backed up periodically to ensure that it can be recovered if needed. With mobile devices, storage is often limited and not removable. To overcome these limitations, remote backups can be performed. A remote backup is when a device copies its data to cloud storage using a backup app. If data needs to be restored, run the backup app and access the website to retrieve the data.

Most mobile operating systems come with a user account linked to the vendor’s cloud services, such as iCloud for iOS, Google Sync for Android, and OneDrive for Microsoft. The user can enable automatic backups to the cloud for data, apps, and settings. There are also third-party backup providers, such as Dropbox, that can be used. Mobile devices can also be backed up to a PC. iOS supports backups on iTunes running on a PC. Another option is to configure Mobile Device Management (MDM) software to automatically backup user devices.

#### Locater Applications
a mobile device is misplaced or stolen, it is possible to find it using a locator app. A locator app should be installed and configured on each mobile device before it is lost. Both Android and iOS have apps for remotely locating a device.

Similar to Apple’s Find My iPhone, Google Find My Device allows a user to locate, ring, or lock a lost Android device, or to erase data from the device. To manage a lost device, the user must visit Google Find My Device hosted at https://www.google.com/android/find and log in with the Google account used on the Android device. Google Find My Device is included and enabled by default on Android 5.x and can be found under **Settings > Biometrics Security > Find My Mobile**.

iOS users can use the Find My iPhone app, as shown in the figure. The first step is to install the app, start it, and follow the instructions to configure the software. The Find My iPhone app can be installed on different iOS devices to locate the lost device.

**Note**: If the app is unable to locate the lost device, the device might be turned off or disconnected. The device must be connected to a cellular or wireless network to receive commands from the app, or to send location information to the user.

After the device is located, you might be able to perform additional functions, such as sending a message or playing a sound. These options are useful if you have misplaced your device. If the device is close by, playing a sound indicates exactly where it is. If the device is at another location, sending a message to display on the screen allows someone to contact you if it has been found.

#### Remote Lock/Wipe
If attempts to locate a mobile device have failed, there are other security features that can prevent data on the device from being compromised. Usually, the same apps that perform remote location have security features. Two of the most common remote security features are remote lock and remote wipe.  

The remote lock feature for iOS devices is called "lost mode". The Android Device Manager calls this feature "Lock". It allows you to lock the device with a passcode, so others cannot gain access to the data in the device. For example, the user can display custom messages, or keep the phone from ringing due to incoming calls or text messages.

The remote wipe feature for iOS devices is called "erase phone". The Android Device Manager calls this feature "Erase". It deletes all data from the device and returns it to a factory state. To restore data to the device, Android users must set up the device using a Gmail account, and iOS users must synchronize their device to iTunes.

Most mobile device operating systems provide a full device encryption feature. Full device encryption can prevent anyone in possession of the device from circumventing the device’s access controls and reading the raw data stored in memory.

All user data on an iOS device is always encrypted and the key is stored on the device. When used to “wipe” the device, the OS deletes the key, and the data becomes inaccessible. Data Protection encryption is enabled automatically when a password lock is configured on the device.

On Android OS, encryption is enabled through **Settings > Security**. Android uses full-disk encryption with a passcode-derived key.

**Note:** For these remote security measures to function, the device must be powered on and connected to a cellular or Wi-Fi network.

### [[Software]]
#### Antivirus
All computers are vulnerable to malicious software. Smartphones and other mobile devices are computers and are also vulnerable. Antivirus apps are available for both Android and iOS. Depending on the permissions granted to antivirus apps when they are installed on an Android device, the app might not be able to scan files automatically or run scheduled scans. File scans must be initiated manually. iOS does not allow automatic or scheduled scans. This is a safety feature to prevent malicious programs from using unauthorized resources or contaminating other apps or the OS. Some antivirus apps also provide locator services, remote lock, or remote wipe.

Mobile device apps run in a sandbox. A sandbox is a location of the OS that keeps code isolated from other resources and other code. It is difficult for malicious programs to infect a mobile device because apps are run inside the sandbox. An Android app asks for permission to access certain resources upon installation. A malicious app has access to any resources that were allowed permission during installation. This is another reason why it is important to download apps only from trusted sources. A trusted app source is one that is authenticated and authorized by a service provider. The service provider issues the developer a certificate to use to sign their apps and identify them as trusted.

Due to the nature of the sandbox, malicious software does not usually damage mobile devices; it is far more likely for a mobile device to transfer a malicious program to another device, such as a laptop or desktop. For example, if a malicious program is downloaded from email, the Internet, or another device, the malicious program could be placed on a laptop the next time it is connected to the mobile device.

To prevent the malicious program from infecting additional devices, a firewall can be used. Firewall apps for mobile devices can Monitor app activity and prevent connections to specific ports or IP addresses. Because mobile device firewall must be able to control other apps they logically work at a higher (root) permission level. No root firewalls work by creating a virtual private network (VPN) and then controlling app access to the VPN.

#### Rooting and Jail Breaking
Mobile operating systems are usually protected by a number of software restrictions. An unmodified copy of iOS, for example, will only execute authorized code and allow very limited user access to its file system.

Rooting and Jailbreaking are two methods for removing restrictions and protections added to mobile operating systems. They are a means of circumventing the usual operating of the device operating system to gain super-user or root administrator permissions. Rooting is used on Android devices to gain privileged or root level access for modifying code or installing software that is not intended for the device. Jailbreaking is typically used on iOS devices to remove manufacturer restrictions allowing them to run arbitrary user-code, grant users full access to the file system and full access to kernel modules.

Rooting or jailbreaking a mobile device usually voids the manufacturer's warranty. It is not recommended that you modify a customer’s mobile device in this way. Nevertheless, a large group of users choose to remove their own devices' restrictions. By rooting or jailbreaking a mobile device the GUI can be heavily customized, modifications can be made to the OS to improve the speed and responsiveness of the device, and apps can be installed from secondary or unsupported sources.

Jailbreaking exploits vulnerabilities in iOS. When a usable vulnerability is found, a program is written. This program is the actual jailbreak software and it is then distributed on the internet. Apple discourages jailbreaking, and actively works towards eliminating vulnerabilities that make jailbreaking possible on iOS. In addition to the OS updates and bug fixes, new iOS releases usually include patches to eliminate known vulnerabilities that allow jailbreaking. When iOS vulnerabilities are fixed by updates, it forces hackers to start over.

**Note**: The jailbreak process is completely reversible. To remove the jailbreak and bring the device back to its factory state, connect it to iTunes and perform a Restore.

#### Patching and Updating [[Operating System]]s
Like the OS on a desktop or laptop, you can update or patch the OS on mobile devices. Updates add functionality or increase performance. Patches can fix security problems or issues with hardware and software.

Because there are so many different Android mobile devices, updates and patches are not released as one package for all devices. Sometimes a new version of Android cannot install on older devices where the hardware does not meet the minimum specifications. These devices might receive patches to fix known issues, but not receive OS upgrades.

Android updates and patches use an automated process for delivery. When a carrier or manufacturer has an update for a device, a notification on the device indicates that an update is ready, as shown in the figure. Touch the update to begin the download and installation process.

iOS updates also use an automated process for delivery, and devices that do not meet the hardware requirements are also excluded. The easiest method to check for iOS updates is on the iPhone, go to **Settings** > **General** > **Software** **Update**.

There are two other types of updates for mobile device radio firmware that are important. These are called baseband updates and consist of the Preferred Roaming List (PRL) and the Primary Rate ISDN (PRI). The PRL is configuration information that a cellular phone needs to communicate on networks other than its own so that a call can be made outside of the carrier’s network. The PRI configures the data rates between the device and the cell tower. This ensures that the device is able to communicate with the tower at the correct rate.

### Applications
Apps are the programs that are executed on mobile devices. Apps are written and compiled for a specific mobile operating system such as Apple iOS, Android, or Windows. Mobile devices come with a number of different apps preinstalled to provide basic functionality. There are apps to make phone calls, send and receive email, listen to music, take pictures, and play video or video games.

Apps are used on mobile devices the same way that programs are used on computers. Instead of being installed from an optical disk, apps are downloaded from a content source. Some apps can be downloaded for free, and others must be purchased.

#### iOS
Apps for Apple iOS mobile devices are available for free or purchase from the App Store. Apple uses a walled garden model for their apps meaning the apps must be submitted to and approved by Apple before they are released to users. This helps prevent the spread of malware and malicious code. Third-party developers can create apps for iOS devices by using Apple’s Software Development Kit (SDK) Xcode and the Swift programming language. Note that Xcode can only be installed on computers running OS X.

#### Automobile Apps
Many new cars have navigation built in them. Some also have what are known as in-vehicle entertainment systems. A growing trend is to use many of the apps on your mobile device through this entertainment system. Your tablet or smartphone is connected to the system via USB or Bluetooth to enable what is known as Android Auto or Apple CarPlay. Navigation is one of the most common uses for this connection. You can also access the music that is on your mobile device and play it over the car stereo. Other features include talk-to-text, hands-free calling, access to digital assistants, and also display the contents of your calendar.

#### Android
Android apps are available from both Google PlayTM and third-party sites, such as Amazon’s App store. Android Studio, a Java-based SDK, is available on Linux, Windows, and OS X. Android apps run in a sandbox and have only the privileges enabled by the user. A prompt will appear if an app needs to obtain permissions. Permissions are granted via the app’s Settings page.  
Third-party or custom programs are installed directly using an Android Application Package (apk) file. This gives users the ability to directly install apps without going through the storefront interface. This is known as sideloading.

## Unix
Unix is a proprietary operating system written in the C programming language. macOS and iOS are based upon the Berkley Standard Distribution (BSD) version of Unix.  
GNU-Linux is an open-source, independently developed operating system which is compatible with Unix commands. Android, and many OS distributions rely upon the Linux kernel.

### File and Directory Permissions
To organize the system and reinforce boundaries within the system, Unix uses file permissions. File permissions are built into the file system structure and provide a mechanism to define permissions to every file and directory. Every file and directory on Unix systems carries its permissions which define the actions that the owner, the group, and others can do with the file or directory.

The only user who can override file permissions in Unix is the root user. Having the power to override file permissions, the root user can write to any file. Because everything is treated as a file, the root user has full control over the Unix operating system. Root access is often required before performing maintenance and administrative tasks.

777 : `-rwxrwxrwx`
There is no restrictions on permissions. Anybody may do anything: read, write, or execute the file. It is generally not a desirable setting.

755 : `-rwxr-xr-x`
With this permission only file's owner may read, write, and execute the file. All others may only read and execute the file. This setting is common for programs that are used by all users on the system.

700 : `-rwx------`
The file's owner may read, write, and execute the file. Nobody else has any rights. This setting is useful for programs that only the owner may use and must be kept private from others.

666 : `-rw-rw-rw-`
All users may read and write the file, but no users can execute the file.

644 : `-rw-r--r--`
Only the file owner may read and write a file, while all others on the system may only read the file. A common setting for data files that all the users may read, but only the owner may change.

600 : `-rw-------`
The owner may read and write a file. All others cannot read, write or execute the file. The settings is used when the owner wants to keep the data file private.

#### Octal Codes

| Binary | Octal | Permission | Descriptions        |
| ------ | ----- | ---------- | ------------------- |
| 000    | 0     | ---        | No access           |
| 001    | 1     | --x        | Execution           |
| 010    | 2     | -w-        | Write               |
| 011    | 3     | -wx        | Write and Execution |
| 100    | 4     | r--        | Read                |
| 101    | 5     | r-x        | Read                |
| 110    | 6     | rw-        | Read Write          |
| 111    | 7     | rwx        | All access          |


**Note**: Because Linux and OS X are based on Unix, both operating systems are in full compliance with Unix file permissions.

### Linux
Linux operating systems are used in embedded-systems, wearable devices, smartwatches, cellphones, netbooks, PCs, servers and super computers. There are many different distributions (or distros) of Linux, including SUSE®, Red Hat®, CentOS®, Fedora®, Debian®, Ubuntu®, and Mint®. Each distro adds specific packages and interfaces to the generic Linux kernel and provides different support options. Most distributions provide a GUI interface.  
Most distributions are a complete Linux implementation that includes the kernel, shell, applications, and utilities. Each Linux distro software vendor packages and distributes installation media and provides support.

Two file systems used on most Linux operating systems are ext3, which is a 64-bit file system with support for journaling, and ext4, which delivers significantly better performance than ext3. Linux can also support FAT and FAT32. In addition, Network File System (NFS), can be used to mount remote storage devices into the local file system.

Most installations of Linux also support creation of a swap partition to use as swap space. The swap partition is used by the operating system to supplement system RAM. If applications or data files use up all the available space in RAM, data is written to the swap space on a disk and is treated as if it were stored in RAM.

The Linux Client/Desktop OS has its own set of OS-specific common features and tools that you must be able to identify.

#### [[Graphics User Interface|GUI]]
Different Linux distributions ship with different software packages, but users decide what stays in their system by installing or removing packages. The graphical interface in Linux is comprised of a number of subsystems that can also be removed or replaced by the user. While the details about these subsystems and their interactions are beyond the scope of this course, it is important to know the Linux GUI as whole can be easily replaced by the user. Because there are so many Linux distributions, this chapter focuses on Ubuntu when covering Linux.

Ubuntu Linux uses Gnome as its default GUI. The figure shows a breakdown of the main components of Ubuntu Gnome Desktop. Another feature in the Linux GUI is the ability to have multiple desktops or workspaces. This allows the users to arrange the windows on a particular workspace.

##### Launcher
A dock placed on the left side of the screen that serves as application launcher and switcher. Right-click any application hosted on the Launcher to access a short list of tasks the application can perform.

##### Search box
Holds the Search tool and a list of recently used applications. Dash includes lenses at the bottom of the Dash area, which allow the user to fine tune Dash search results. To access Dash, simply click the Ubuntu button on the top of the Launcher.

##### Tope Menu Bar
A multipurpose menu bar containing the currently running application, buttons to control the active window, and system controls and notifications.

##### System and Notification Menu
Many important functions are located in the indicator menus at the top right corner of your screen. Use the indicator menu to switch users, shut down your computer, control the volume level, or change network settings.

#### Linux terminal emulators
A program called a shell interprets the commands from the keyboard and passes them to the operating system. When a user logs in the system, the login program checks the username and password; if the credentials are correct, the login program starts the shell. From this point on, an authorized user can begin interacting with the OS through text-based commands.

Users interact with the kernel through a shell. In other words, the shell acts as an interface layer between the user and kernel. The kernel is responsible for allocating CPU time and memory to processes. It also manages the file system and communications in response to system calls. On Linux, popular terminal emulators are Terminator, eterm, xterm, konsole, gnome-terminal.

#### Common Commands
To be successful in using Linux operating systems, you will need to be familiar with at least the most basic Linux commands. Being able to navigate the Linux terminal using these basic commands will be very beneficial. It’s important to note that Linux commands are case sensitive, so take note of the case you are using when typing them.

ls—The `ls` command is known as the **list command** in Linux. This is because the command will list all the files or folders in a given directory. In order to use this command, navigate to the folder or directory you’re interested in and type “ls”. After hitting enter, a list of all the files and folders in that location will be displayed.

pwd—While many people see the term _pwd_ and think “password,” it actually means something very different in Linux. The `pwd` command stands for **present working directory**, and it displays the full path of the current working directory.

mv— The `mv` command in Linux is the **move** command. This command allows a user to move a specified file to another location. Move is similar to a cut and paste command in Windows.

cp—The `cp` command in Linux stands for **copy**. Its functionality is similar to that of the move file, except that it places a copy in the new location while leaving the file in the original location.

rm—The `rm` command stands for **remove** in the Linux operating system. This is similar to a delete functionality, as it removes the file, directory, or other objects from the location.

chmod—To **modify Linux file permissions**, you must use the `chmod` command. Before changing Linux file permissions, it’s important to first understand how they are represented. In this case, a script is made executable using octal mode, and reverted using reference mode. Each permission is represented by a letter: r–the read permission; w–the write permission; x–the execute permission.

chown—While the `chmod` command changes the permissions, the `chown` command **changes the ownership** of a file, directory, or other objects.

su/sudo—The `su` command stands for **switch user** (or substitute user). The `su` command can be used by adding a username that you wish to switch to after the command (example: su linuxuser1) or it can be used by itself, which will by default switch it to the root user. The `sudo` command switches the user for a single command, while `su` switches the user until it’s switched back.

apt-get—APT stands for “advanced packaging tool.” The `apt-get` command is a tool for **handling packages** in Linux. It is used to retrieve packages from authenticated sources for installation, upgrade, and removal of packages, along with their dependencies.

yum—The `yum` command is used in file management to **update and install packages for Red Hat**-based distributions.

ip— The `ip` command is used to **display and configure information** related to a network interface card (NIC).

df—The `df` command is used in **processing files and displays the total free disk space** for a directory.

grep—The `grep` command stands for **global regular expression print**. The `grep` command is a search command. You can use it to search for a string of characters within a file or standard text output. For example, if you are viewing a file in the terminal and type the command `grep “unix”`, the terminal will display all of the instances of the word “unix” in that file.

man—The `man` command displays system **help for executable files**.

top—The `top` command also displays a list of **running processes**.

find—The `find` command can be used for **searching** for specific text within a file hierarchy.

dig—The `dig` command is used in networking and is a **DNS query utility**.

cat—The `cat` command displays the **contents** of a file.

nano—The `nano` command is a text-based **editor** for files.

##### Admin Commands
Administrators use the terminal to monitor and control users, processes, ip addresses, and other tasks. The commands on this page can be executed by users without any special privileges.

If you have an Ubuntu distribution, click **Activities** in the upper left hand corner and type “terminal”. Opening the terminal in other Linux distributions varies depending on the interface.

- `passwd` : Allows users to change their own password at the terminal. To change a password, the user must know their current password. For security reasons, neither the characters nor an asterisk is displayed while typing. The passwd command is often confused with the pwd command, which is an acronym for Print Working Directory.
- `ps` : Displays all of the currently running processes and their process numbers. The second use of the **ps** command in this example uses the **-e** option indicating everything. The output of the command is piped into the **grep** command to search for output lines that match the word gnome (pronounced Gee-Nome). For this command, the “ps” stands for **process status**.
- `kill` : Allows users to end the processes that they have started. In this example, Firefox was started in the background using the ampersand (&). The **kill** command was used to abruptly end the firefox process. Use **man kill** to view useful options for the **kill** command.
- `ifconfig` : Used in much the same way as the Windows ipconfig command. This command is deprecated and the ip address command should be used instead.
- `iwconfig` : One of many wireless commands that start with the letters “iw”. The iwconfig command allows users to set and view their wireless settings. In this case, no wireless connections are being used.

##### Commands Requiring Root access
Some commands may be used without special privileges. Other commands require root access some of the time or all of the time. Typically, a user can manipulate the files within their own home directory, but changing files and settings throughout the server requires either sudo (Super User DO) or root access. For a deeper understanding of these commands and Linux, enroll in the NDG Linux Essentials curriculum located here.

#### Backup and Recovery
The process of backing up data refers to creating a copy (or multiple copies) of data for safekeeping. When the backing up process is complete, the copy is called a backup. The primary goal is the ability to restore or recover the data in case of failure. Gaining access to an earlier version of the data is often seen as a secondary goal of the backing up process.

While backups can be achieved with a simple copy command, many tools and techniques exist to make the process automatic and transparent to the user.

Linux does not have a built-in backup tool. However, there are many commercial and open source backup solutions for Linux such as Amanda, Bacula, Fwbackups, and Déjà Dup. Déjà Dup is an easy and efficient tool for backing up data. Déjà Dup supports a number of features including local, remote, or cloud backup locations, data encryption compression, incremental backs up, periodic scheduled backups, and GNOME desktop integration. It also restores from any particular backup.

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

## macOS
Apple Mac workstations have their own file system, Extended Hierarchical File System (HFS Plus). This file system supports many of the same features as NTFS in Windows, but not native file/folder encryption. In macOS High Sierra and later, HFS Plus updated to the Apple File System (APFS), which does support native file encryption. HFS Plus has a maximum volume and file size of 8 ExaBytes.

The operating system for Macintosh computers, macOS, is developed from the UNIX kernel, it is however, a closed source operating system.  
Since its release in 2001, macOS has undergone regular updates and revision to keep pace with Apple Mac hardware updates. Updates and new OS versions are distributed for free through the App Store. Some older Mac computers may not be able to run the newest macOS versions. You can check support.apple.com/specs for the technical specifications of any macOS release.  
macOS supports remote network installation similar to Preboot eXecution Environment (PXE) called NetBoot.

#### macOS terminal emulator
macOS includes a terminal emulator called Terminal, but a number of third-party emulators are available.

### Installation and Uninstallation of Applications
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

### [[Graphics User Interface|GUI]]
Among the major differences between older versions of OS X and macOS is the addition of the Aqua GUI. Aqua was designed around the theme of water, with components resembling droplets and a deliberate use of reflection and translucency. The latest release of macOS at the time of writing is 10.14 Mojave. The figures below breakdown of the macOS Aqua desktop.

The Apple Magic Mouse and the Magic Trackpad of a MacBook both support gestures to control the user interface. Gestures are finger movements on a trackpad or mouse that enable a user to scroll, zoom, and navigate desktop, document, and application content. Available gestures can be viewed and changed under **System Preferences > Trackpad.**

With macOS, Mission Control is a quick way to see everything that is currently open on your Mac. Mission Control can be accessed by using a three or four finger swipe up gesture, depending on your touch pad or mouse settings. Mission Control allows you to organize your apps on multiple desktops. To navigate the file system, macOS includes Finder. Finder is very similar to the Windows File Explorer.

Most Apple laptops do not have an optical drive. To install software from optical media, Remote Disk can be used. Remote Disk is an app which lets the user access a CD/DVD drive on another Mac or Windows computer. Remote Disk sharing is set up in **System Preferences > Sharing** and then check the DVD or CD sharing check box.

macOS also allows screen sharing. Screen sharing is a feature that lets other people using Macs to be able to view your screen. They can even be allowed to take control of your computer. This is very useful when you may need help or wish to help someone else.

#### Menu Bar
Contains the Apple menu, currently active application menus, status menus and indicators, Spotlight, and Notification Center.

#### Apple Menu
Access system preferences, software updates, power controls, and more.

#### Application Menu
Displays the name of the active application in bold and the menu of the active application.

#### Status Menu
Displays date and time and status of your computer and some features, such as Bluetooth and wireless.

#### Spotlight
Spotlight is a file system search feature in macOS. It can be used to find almost anything on the macOS. Starting a new search requires clicking the magnifying glass in the menu bar or pressing Command + Space to bring up the search box. Changing the document type being searched is done in Preferences. To specifically exclude locations from a Spotlight search, click the Privacy button to specify folders or drives to be excluded.

#### Notification Center
Allows the user to see all notifications.

#### Dock 
Displays thumbnails of frequently used applications and the running applications that are minimized. One of the important functions included in the Dock is Force Quit. By right-clicking a running application in the Dock, the user can choose to close an unresponsive application.

### Backup and Recovery
macOS includes a backup tool called Time Machine. With Time Machine, users choose an external drive to be used as a backup destination device and connect it to the Mac via USB, FireWire or Thunderbolt. Time Machine will prepare the disk to receive backups and, when the disk is ready, it performs incremental backups periodically.

If the user has not specified a Time Machine destination disk, Time Machine will ask if the newly connected external disk should be used as the destination backup disk. Time Machine stores some backups on your Mac, so if the Time Machine backup disk is not available, you may be able to restore a backup directly from your Mac. This type of back up is called a local snapshot.

To enable Time Machine, go to **System Preferences > Time Machine**, slide the switch **On** and select the disk where the backups are stored, as shown in the figure. Clicking the **Options** button allows the user to select or unselect the files, folders, or drives to backup. By default, Time Machine performs hourly backups for the past 24 hours, daily backups for a month, and weekly backups for all previous months. When the destination backup drive becomes full, Time Machine removes the oldest backup files to free up space.

To restore data from Time Machine, make sure the destination backup disk is connected to the Mac and click **Enter Time Machine** in the Time Machine menu. A timeline on the right-hand side of the screen will show the available backups. Time Machine allows the user to restore the data to any previous version currently available in the destination backup disk.

## OS Best Practices

### Scheduled Tasks
Computer systems need periodic preventive maintenance to ensure best performance. Maintenance tasks should be scheduled and performed frequently to prevent or detect problems early. To avoid missing maintenance tasks due to human error, computer systems can be programmed to perform tasks automatically. Two tasks that should be scheduled and performed automatically are backups and disk checks.

Backups and disk checks are usually time-consuming tasks. An additional benefit of scheduled maintenance tasks is that it allows the computer to perform these tasks when no users are using the system. The CLI utility known as cron, can schedule these tasks during off-peak hours.

In Linux and macOS, the cron service is responsible for scheduled tasks. As a service, cron runs in the background and executes tasks at specific dates and times. cron uses a schedule table called a cron table that can be edited with the crontab command.

The cron table is a plain text file that has six columns, as shown in the table. A task is usually represented by a command, a program or a script. To schedule a task, the user adds a row to the cron table. The new row specifies the minute, hour, day of the month, and the day of the week the task should be executed by the cron service. When the specified date and time arrives, the task is executed.

| Minute | Hours | Days | Months | Weekdays           | Commands                                  |
| ------ | ----- | ---- | ------ | ------------------ | ----------------------------------------- |
| 0-59   | 0-23  | 1-31 | 1-12   | 0-6                | varies                                    |
|        |       |      |        | 0=Sunday, 6=Monday | Must be compatible with the shell and use |
|        |       |      |        |                    |                                           |

The cron table shown has two entries. The first entry tells the cron service to execute myFirstTask script, located at **/myDirectory/**, on the first and fifteenth day of each month and also on Mondays, always at midnight (**0h0m**). The second entry shows that the cron service will execute **mySecondTask** script, also located at **/myDirectory/**, every Thursday at **2h37m** in the morning.

To create or edit the cron table, use the **crontab –e** command from a terminal.

To list the current cron table, use the **crontab –l** command.

To remove the current cron table, use **crontab –r** command.

### Updates
Despite continued efforts to create a perfectly secure operating system, vulnerabilities still exist. When a vulnerability is found, it can be used as basis for the creation of a virus or other malicious software. Measures can be taken to help prevent malicious software from infecting a computer system. The most common of these are operating system updates, firmware updates, antivirus, and antimalware. Also known as patches, OS updates are released periodically by OS companies to address any known vulnerability in their operating systems. While companies have update schedules, the release of unscheduled OS updates is common when a major vulnerability is found in the OS code. Modern operating systems will alert the user when updates are available for download and installation, but the user can check for updates at any time. The figure shows an update alert window for Apple macOS.

**Firmware Updates**

Usually held in non-volatile memory, such as ROM or Flash, firmware is a type of software designed to provide low-level functionality for a device. Check for firmware updates with the manufacturer and update the system if new versions are available.

**Antivirus and Antimalware**

In general, antivirus and antimalware rely on code signatures to operate. Signatures or signature files are files containing a sample of the code used by viruses and malware. Based on these signature files, antivirus and antimalware scan the contents of a computer disk comparing the contents of the files stored on the disk with the samples stored in the signature file. If a match is found, the antivirus or antimalware alerts the user of the possible presence of malware. New malware is created and released every day; therefore, the signature files of antivirus and antimalware programs must be updated just as frequently.

### Installations and Upgrades
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

# Nav
< [[Virtualization and Cloud Computing|Previous]] < ^ [[Navigation|Home]] ^ > [[Operational Procedures|Next]] >