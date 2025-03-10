---
tags: 
parent docs:
  - "[[Navigation]]"
sibling docs: 
child docs: 
media:
---
# Nav
| ^ [[Navigation|Home]] ^ | > [[Hardware]]> |

---

Troubleshooting requires an organized and logical approach to problems with computers and other components. Sometimes issues arise during preventive maintenance. At other times, a user may contact you with a problem. A logical approach to troubleshooting allows you to eliminate variables and identify causes of problems in a systematic order. Asking the right questions, testing the right hardware, and examining the right data helps you understand the problem and form a proposed solution.

Troubleshooting is a skill that you refine over time. Each time you solve a problem, you increase your troubleshooting skills by gaining more experience. You learn how and when to combine steps, or skip steps, to reach a solution quickly. The troubleshooting process is a guideline that is modified to fit your needs. This section presents an approach to problem-solving that you can apply to both hardware and software.

Always trust the user but verify and double check.

**Note**: The term user, as used in this course, is any user that requires technical computer assistance.

Before you begin troubleshooting problems, always follow the necessary precautions to protect data on a computer. Some repairs, such as replacing a hard drive or reinstalling an operating system, might put the data on the computer at risk. Make sure you do everything possible to prevent data loss while attempting repairs. If your work results in data loss for the user, you or your company could be held liable.

## Data Backup
A copy of the data on a computer hard drive that is saved to another storage device or to cloud storage. Cloud storage is online storage that is accessed via the internet. In an organization, backups may be performed on a daily, weekly, or monthly basis.

If you are unsure that a backup has been done, do not attempt any troubleshooting activities until you check with the user. Here is a list of items to verify with the user that a backup has been performed:
- Date of the last backup
- Contents of the backup
- Data integrity of the backup
- Availability of all backup media for a data restore

If the user does not have a current backup and you are not able to create one, ask the user to sign a liability release form. A liability release form contains at least the following information:
- Permission to work on the computer without a current backup available
- Release from liability if data is lost or corrupted
- Description of the work to be performed

# Methodology
Best practice methodology refers to the use of basic structured principles that should be followed when approaching a troubleshooting situation. While individuals may approach troubleshooting differently, certain **basic principles remain constant**: create a backup, prioritize tasks, and document the process. _Note:_ Questions regarding this section of the exam will come in the form of scenarios.

## Corporate Policies, Procedures, and Impacts
Every corporate enterprise has differing policies and procedures. Always consider corporate policies, procedures, and potential impacts before you begin troubleshooting.

### Observation
#### 1. Identify the Problem
Observation is that first step of any action and is crucial for problem solving. Technical problems with computer systems generally occur in one (or more) of **four areas**: hardware, the operating system, software, and the user. It is vital to accurately identify the problem **before taking action**.
- **Gather information**—To properly identify a problem, begin by gathering information **from the user and the computer system** in question. When gathering information from the user, ask questions to clarify the problem. Clarifying the issue will give you a starting point for further investigation. After questioning the user, examine the device to determine what is working and what is not. Check for common issues such as power problems or issues resolved upon reboot. Look into systems logs or application logs for information. Is the issue a hardware problem or a software problem?
- **Inquire about changes**—Consider all the changes that could affect the user (e.g., network, computer, power issues, external connection, user account) and how those changes can be involved in the problem. As an example, let’s say the network team worked over the weekend performing an upgrade to the infrastructure (switch replacement) and neglected to plug all the cabling back into the switch (as simple as a cable falling behind the wiring channel and being missed). The user might have been the one missed and now they cannot authenticate to the network, access their files, print to the network printer, and, therefore, cannot perform common functions. These things happen daily and other teams can be conducting changes without regard to the effect on employees.

**Conversation Etiquette**
When you are talking to the user, follow these guidelines:
- ask direct questions
- use common terms
- be polite, do not talk down or insult
- do not accuse the user of causing the problem

Information to gather :

| type                   | description                                                   |
| ---------------------- | ------------------------------------------------------------- |
| user Info          | company, contact, address, phone number                       |
| Computer Configuration | manufacturer, model, OS, network environment, connection type |
| Problem Description    | open/close-ended questions                                    |
| Feedback               | error messages, beep sequences, LEDs, POST                    |

**Open-Ended and Closed-Ended Questions**
Open-ended questions allow users to explain the details of the problem in their own words. Use open-ended questions to obtain general information.

Based on the information from the user, you can proceed with closed-ended questions. Closed-ended questions generally require a yes or no answer.

**Documenting Responses**
Document the information from the user in the work order, in the repair log, and in your repair journal. Write down anything that you think might be important for you or another technician. The small details often lead to the solution of a difficult or complicated problem.

**Beep Codes**
Each BIOS manufacturer has a unique beep sequence, a combination of long and short beeps, for hardware failures. When troubleshooting, power on the computer and listen. As the system proceeds through the POST, most computers emit one beep to indicate that the system is booting properly. If there is an error, you might hear multiple beeps. Document the beep code sequence, and research the code to determine the specific problem.

**BIOS Information**
If the computer boots and stops after the POST, investigate the BIOS settings. A device might not be detected or configured properly. Refer to the motherboard documentation to ensure that the BIOS settings are correct.

**Diagnostic Tools**
Conduct research to determine which software is available to help diagnose and solve problems. There are many programs to help you troubleshoot hardware. Manufacturers of system hardware usually provide diagnostic tools of their own. For instance, a hard drive manufacturer might provide a tool to boot the computer and diagnose why the hard drive does not start the operating system.

**Device Manager**
The Device Manager displays all the devices that are configured on a computer. The operating system flags the devices that are not operating correctly with an error icon. A yellow triangle with an exclamation point indicates that the device is in a problem state. A red X means that the device is disabled, removed, or Windows can't locate the device. An arrow down means the device has been disabled. A yellow question mark indicates that the system does not know which driver to install for the hardware.

**Task Manager**
Displays the applications and background processes that are currently running. With the Task Manager, you can close applications that have stopped responding. You can also monitor the performance of the [[Central Processing Unit]] and virtual memory, view all processes that are currently running, and view information about the network connections.

#### 2. Create a Theory of Probable Cause
Keep it **simple**. Always question the obvious and don’t assume something isn’t relevant. You might think it is common sense to be plugged into the network, but the user might not know this. Using your questioning ability, develop a theory (or two) regarding what the problem might be. When developing a theory, remember to **eliminate possible theories** as well if they do not fit the scenario.
- **External or internal research**—Utilize research resources, which can include internal and external resources. Check previous service **documentation** within the company, refer back to the **device manual**, and check for potential theories using **online** forums and search engines. The internet, when utilized properly, can be extremely helpful for troubleshooting problems.
	- device is powered off
	- power switch for an outlet is turned off
	- surge protector is turned off
	- loose external cable connections
	- non-bootable disk in designated boot drive
	- incorrect boot order in BIOS setup

### Action
#### 3. Test the Theory/Determine the Cause
When you have your theory developed, you need to test it. On a time-sensitive issue, or if you know 100% that the theory is valid, you can implement it based upon corporate policies and/or procedures. In a perfect world, you would be able to replicate the issue within a testing (or laboratory) environment for verification. This isn’t always the case and you should be ready to test your theory at a moment’s notice. When testing a theory, **begin with the most obvious** and simple theories first, such as checking the power supply or ensuring cables are properly seated, before moving onto more complicated theories.
- **If theory is confirmed, determine next steps**—Only **test one possible solution at a time** and only **make one change at a time**. Sounds like a lengthy process? It is, but if you implement multiple changes in one process, how do you know which one worked and which one didn’t? Remember, keep it simple. If your theory is confirmed, then you can skip to the plan of action to implement your theory. If not, then it’s back to testing again. No worries, proper troubleshooting is an art.
- **If theory is not confirmed, establish new theory or escalate**—You’ve tested your theory and the problem still exists. Step back and take a look at your theory to see what other avenues are available and develop a working theory regarding the next possible solution. If you have exhausted all your potential theories, it may be time to escalate the problem.

You can determine an exact cause by testing your theories of probable causes one at a time, starting with the quickest and easiest. The table below identifies some common steps to determine the cause of the problem. Once the theory is confirmed, you then determine the steps to resolve the problem. As you become more experienced at troubleshooting computers, you will work through the steps in the process faster. For now, practice each step to better understand the troubleshooting process.
Common steps to determine a cause 
- ensure the device is powered on
- power switch for an outlet is turned on
- surge protector is turned on
- external cable connections are secure
- the designated boot drive is bootable
- verify the boot order in the BIOS setup

If you cannot determine the exact cause of the problem after testing all your theories, establish a new theory of probable cause and test it. If necessary, escalate the problem to a technician with more experience. Before you escalate, document each test that you tried, as shown in the work order below.

#### 4. Create and Execute a Plan of Action
Always remember: Your **company’s policies and procedures take precedence** and should be in the forefront prior to acting on any plan. The conclusion that you make might affect the whole company, but that might also be needed depending on the breath of the issue. Does correcting the issue require downtime for the company or just a single computer? Can that be scheduled around the users’ workday? Does it need to happen immediately? These are all questions that should be included in your plan of action.
- **Vendor instructions**—When creating a plan of action, remember to take into account vendor instructions. Vendors often provide **documented fixes** to identified issues, which should be considered.

Divide larger problems into smaller problems than can be analyzed and solved individually. Prioritize solutions starting with the easiest and the fastest to implement. Create a list of possible  silutions and implement them one at a time. If you implement a possible solution and it does not correct the problem, reverse the action and try another solution. Continue this process until you have found the appropriate solution
If no solution is achieved in the previous step, further research is needed to implement the solution
- help desk repair logs
- other technicians
- manufacturer FAQ sites
- new groups
- computer manuals
- device manuals
- online forums
- internet search
### Documentation
#### 5. Verify System Functionality
Once the issues have been resolved or appear to be resolved, verify full functionality of the problem system. Remember to verify **full system functionality** and do not focus strictly on the problem system. A fix to one system or component may cause issues with another system or component. Verifying full system functionality confirms that you have solved the original problem while repairing the computer. Whenever possible, have the user verify the solution and system functionality.
- reboot the computer
- ensure multiple applications work properly
- verify network and internet connections
- print a document from one application 
- ensure all attached devices work properly
- ensure no error messages are received

#### 6. Document Findings, Actions, and Outcomes
We can’t express how important it is for issues to be fully documented. **Everything that you have done** from the moment the user contacted you to the moment the user was back online, such as indications, findings, actions, outcomes, scenarios, etc., must be documented. Your **company should have a repository** to keep this information safe. It should also be possible to share among your peers in the event the same type of issue arises in the future. 

If the user is available, demonstrate how the solution has corrected the computer problem. have the user relay the solution and try to reproduce the problem. When the user can verify that the problem has been resolved, you can complete the documentation for the repair in the work order and in your journal. 
Include the following information in the documentation:
- description of the problem, including precautions and complications
- steps to resolve the problem, from description to testing
- components and tools used in the repair

# Common Problems
Computer problems can be attributed to hardware, software, networks, or some combination of the three. You will resolve some types of problems more often than others.

These are some common hardware problems:
- **Storage Device** - Storage device problems are often related to loose, or incorrect cable connections, incorrect drive and media formats, and incorrect jumper and BIOS settings.
- **Motherboard and Internal Components** - These problems are often caused by incorrect or loose cables, failed components, incorrect drivers, and corrupted updates.
- **Power Supply** - Power problems are often caused by a faulty power supply, loose connections, and inadequate wattage.
- **CPU and Memory** - Processor and memory problems are often caused by faulty installations, incorrect BIOS settings, inadequate cooling and ventilation, and compatibility issues.
- **Displays** - Display problems are often caused by incorrect settings, loose connections, and incorrect or corrupted drivers.

## [[Storage]]
Storage devices include persistent storage such as storage drives and RAID storage. The most common causes of storage device problems are **bad adapters**, a **bad or failing drive**, or **improper connection**. You must be able to troubleshoot and diagnose problems with these systems based on a given scenario.

### Common Symptoms
While a bad adapter and an improper connection are relatively simple to detect and test, symptoms of a bad or failing drive are more complicated. Below is a list of common symptoms of a bad or failing drive or RAID.

#### LED Status Indicators
Light-emitting diode (LED) status indicators are typically visible on storage devices. A blinking light typically indicates a busy drive, while a light that does not come on at all or stays solid may be an indicator of a problem. However, you need to look at the **vendor-specific specifications** for indicator lights since the indicator lights on one product may not have the same meaning as lights on another product, such as a RAID display with a light that only comes on when a problem is detected in the array.

#### Grinding Noises
A grinding noise originating from a storage device is a significant **indicator of imminent failure** in a motor or spindle within the device. This grinding sound can also be heard as squealing sounds or nails on a chalkboard. It is important to **back up** the affected drive immediately and **replace** the drive.

#### Clicking Sounds
A rhythmic clicking or ticking sound is an indicator of a drive that is **in the process of failing**. Once again, back up and replace the drive immediately.

#### Bootable Device Not Found
Upon bootup, a storage device is first detected by the **BIOS/UEFI**, and then the OS. The “Bootable Device Not Found” error can be an indicator of a complete failure to boot or a failure of the OS to be found. Check **connection points and cables** between the motherboard and the drive if BIOS/UEFI autodetection fails. If a proper connection does not resolve the issue, it may be a bad drive. If the BIOS/UEFI is able to detect the drive but is unable to detect the OS, the issue may lie in the **master boot record (MBR)**.

#### Data Loss/Corruption
Data loss or corruption can be caused by a **failing or full drive**. To remedy the issue, first attempt to **remove unneeded files** or applications or **defragment** the drive. If this does not remedy the issue, you may attempt to **format** the drive and **reinstall** the OS. If the issue persists, the drive is most likely failing.

#### Extended Read/Write Times
Extended read/write times, like data loss/corruption, can be indicators of a **failing or full drive**. Troubleshoot this issue as you would data loss/corruption.

#### Input/Output Operations Per Second (IOPS)
Input/output operations per second (IOPS) refers to how many reads and writes a storage device can perform in a second and is listed on storage devices, such as NAS and RAID systems. A **steadily declining IOPS** may be an **indicator of drive failure**.

#### Missing Drives in OS
Missing drives in the OS may be indications of a connection issue or an improperly set up storage device. Troubleshoot missing drives by checking connections, checking the **BIOS/UEFI** for the enabled drive, finding the drive in disk management or disk utility, making sure the drive is prepared and partitioned properly, updating drive drivers, and checking for bad sectors, which may cause the OS to show the drive as unreadable.

#### Solutions
Computer does not recognize a storage device.

| Probable Cause              | Possible Solutions                   |
| --------------------------- | ------------------------------------ |
| loose power or data cable   | secure cable                         |
| jumpers are set incorrectly | reset jumpers                        |
| storage device failed       | replace storage device               |
| incorrect BIOS setting      | reset storage device setting in BIOS |
Computer does not recognize an optical disc.

| Probable Cause                                    | Possible Solutions                                       |
| ------------------------------------------------- | -------------------------------------------------------- |
| the disc is inserted upside-down                  | invert disc                                              |
| there is more than one disc inserted in the drive | ensure that there is only one disc inserted in the drive |
| a disc is damaged                                 | replace disc                                             |
| a disc is in the wrong format                     | use the correct disc type                                |
| the optical drive is faulty                       | replace the optical disc                                 |
The computer will not eject the optical disc

| Probable Cause                                | Possible Solutions                                                   |
| --------------------------------------------- | -------------------------------------------------------------------- |
| the optical drive is jammed                   | insert a pin in the small hole next to the eject button on the drive |
| the optical drive has been locked by software | reboot the computer                                                  |
| the optical drive is faulty                   | replace the optical drive                                            |
The computer does not recognize a removable, external drive

| Probable Cause                                       | Possible Solutions                    |
| ---------------------------------------------------- | ------------------------------------- |
| the removeable external drive is not seated properly | remove and reseat the drive           |
| the external ports are disabled in the BIOS settings | enable the ports in the BIOS settings |
| the removable external drive is faulty               | replace the removable external drive  |
A media reader can not read a memory card that works properly

| Probable Cause                                                   | Possible Solutions                                             |
| ---------------------------------------------------------------- | -------------------------------------------------------------- |
| the media reader does not support the memory card type           | use a different memory card type                               |
| the media reader is not connected correctly                      | ensure the media reader is connected correctly in the computer |
| the media reader is not configured properly in the BIOS settings | reconfigure the media reader in the BIOS settings              |
| the media reader is faulty                                       | install a known good media reader                              |
Retrieving or saving data from the USB flash drive is slow.

| Probable Cause                                     | Possible Solutions                                                                         |
| -------------------------------------------------- | ------------------------------------------------------------------------------------------ |
| the motherboard does not support USB 3.0           | replace the motherboard with a USB 3.0 capable motherboard or add a USB 3.0 expansion card |
| the port is set to full speed in the BIOS settings | set the port speed in the BIOS settings to high speed                                      |
The computer does not recognize a removable external drive

| Probable Cause                                                            | Possible Solutions                                                    |
| ------------------------------------------------------------------------- | --------------------------------------------------------------------- |
| the OS does not have the correct drivers for the removable external drive | download the correct drivers for the external drive                   |
| the USB port has too many attached devices to supply power                | attach external power to the device or remove some of the USB devices |
"Can not read from source disk" error is displayed when a use tries to open or save a file.

| Probable Cause | Possible Solutions |
| -------------- | ------------------ |
| failing drive  | replace disk       |

### [[RAID]]
#### Failure
Troubleshooting a RAID failure is similar to troubleshooting a single storage drive. First determine if the problem originates with a single drive or the system as a whole and proceed from there. Check the **indicator lights** on the RAID system for insight. Remember that the problem could originate from the type of RAID that is being employed.

#### S.M.A.R.T. Failure
Self-monitoring, analysis, and reporting technology (S.M.A.R.T.) is software installed on drives that monitors hard drive reliability and performance. S.M.A.R.T. metrics, while in theory useful for diagnosing and predicting drive failure, tend to be overly complicated and difficult to parse. One **useful component** of S.M.A.R.T. is the **ability to create performance benchmarks** that may prove valuable in diagnosing potential drive failures.

#### Solutions
RAID can not be found or stops working

| Probable Cause                                      | Possible Solutions                                                                       |
| --------------------------------------------------- | ---------------------------------------------------------------------------------------- |
| the external RAID controller is not receiving power | check the power connections to the RAID conntroller                                      |
| the BIOS settings are incorrect                     | reconfigure the BIOS settings for the RAID controller                                    |
| the RAID controller has failed                      | replace the RAID controller                                                              |
| missing driver for RAID controller                  | check the drivers are installed and use the RAID configurations utility to verify status |

## [[Motherboards]]

RAM, CPU, and Power
There are many different situations that can arise when various types of hardware components start failing. You must be able to troubleshoot common problems through a scenario.

The **motherboard**, **RAM**, **CPU**, and **power supply** are the most critical components to a computer system. Problems with these components may have the same or similar symptoms. The list below covers general troubleshooting guidelines and causes of common symptoms.


### Pre-Boot System/Software
software that is used to configure various components of a computer before the booting of the OS
#### Unified Extendable Firmware Interface (UEFI)
Most computers today run Unified Extensible Firmware Interface (UEFI). All new computers come with UEFI, which provides additional features and addresses security issues with legacy BIOS. You may see “BIOS/UEFI” when booting into your BIOS settings. This is because Intel chips currently support backwards compatibility with legacy BIOS systems. However, by 2020, Intel will end support for legacy BIOS. For more information, do an internet search for “Intel to remove legacy BIOS”.

**Note**: This section uses BIOS, UEFI, and BIOS/UEFI interchangeably. In addition, manufacturers may continue to label their UEFI programs with “BIOS” so that users know it supports the same functions.

UEFI configures the same settings as traditional BIOS but also provides additional options. For example, UEFI can provide a mouse-enabled software interface instead of the traditional BIOS screens. However, most systems have a text-based interface, similar to legacy BIOS systems.

UEFI can run on 32-bit and 64-bit systems, supports larger boot drives and includes additional features such as secure boot. Secure boot ensures your computer boots to your specified operating system. This helps prevent rootkits from taking over the system. For more information, do an internet search for “Secure boot and rootkits”.

**Note**: UEFI setup screens will not look the same as yours. Please refer to your motherboard manufacturer documents.

#### Basic Input/Output System (BIOS)
All motherboards need BIOS to operate. BIOS is a ROM chip on the motherboard that contains a small program. This program controls the communication between the operating system and the hardware. 

Along with the POST, the UEFI/BIOS also identifies:
- Which drives are available
- Which drives are bootable
- How the memory is configured and when it can be used
- How PCIe and PCI expansion slots are configured
- How SATA and USB ports are configured
- Motherboard power management features

The motherboard manufacturer saves the motherboard BIOS settings in a Complementary Metal Oxide Semiconductor (CMOS) memory chip
#### Power On Self Test (POST)
When a computer is booted, the basic input/output system (BIOS) performs a hardware check on the main components of the computer. This check is called a power-on self-test (POST). Within the sample POST test the computer checks whether the computer hardware is operating correctly.

##### Power-on Self-Test (POST) Beeps
A built-in diagnostic program in the BIOS/UEFI. When an error in the POST occurs, the computer performs a series of beeps, called the **beep code**. To identify the issue, listen to the beep code and refer to the **vendor documentation** to match the beep code with the corresponding error. The cause of these beeps could be problems with BIOS configuration or hardware.

**Common Beep Codes**

| **Beep Code**     | **Meaning**            | **Cause**            |
| ----------------- | ---------------------- | -------------------- |
| 1 Beep (No Video) | Memory Refresh Failure | Memory               |
| 2 Beeps           | Memory Parity Error    | Memory               |
| 3 Beeps           | Base 64 Memory Failure | Memory               |
| 4 Beeps           | Timer not Operational  | Motherboard          |
| 5 Beeps           | Processor Error        | Processor            |
| 6 Beeps           | 8042 Gate A20 Failure  | CPU or Motherboard   |
| 7 Beeps           | Processor Exception    | Processor            |
| 8 Beeps           | Video Memory Error     | Video Card or Memory |
| 9 Beeps           | ROM Check-sum Error    | BIOS                 |
| 10 Beeps          | CMOS Check-sum Error   | Motherboard          |
| 11 Beeps          | Cache Memory Bad       | CPU or Motherboard   |
**Installation Tip**: To determine if POST is working properly, remove all of the RAM modules from the computer and power it on. The computer should emit the beep code for a computer with no RAM installed. This will not harm the computer.

#### Settings
change what the computer has access to before the computer has been booted up and running such as Wi-Fi, Bluetooth, LAN, Audio and video card, and SATA ports
controls how quickly the machine will boot
type of OS
##### System Status

##### Boot
the order in which the computer loads its software, all pre-boot software allow the use to configure the order in which 
##### Security
The legacy BIOS supports some security features to protect the BIOS setting. UEFI adds additional security features and is used to set the admin password, user password, and U-key. These are some common security features found in the BIOS/UEFI systems:
- **Passwords** - Passwords allow for different levels of access to the BIOS settings. Usually, there are two password settings that can be altered; the Supervisor Password and the User Password. The Supervisor Password can access all user-access passwords and all BIOS screens and settings. The User Password gives access to the BIOS based on a defined level. The table below displays common levels of user access to BIOS. The Supervisor Password must be set before the User Password can be configured.
- **U-key** - a password set for a specific Flash drive used to prevent foreign data
- **Drive encryption** - A hard drive can be encrypted to prevent data theft. Encryption changes the data on the drive into code. Without the correct password, the computer cannot boot and data read from the hard drive cannot be understood. Even if the hard drive is placed in another computer, the data remains encrypted.
- **LoJack** – This is a security feature that consists of two programs; the Persistence Module and the Application Agent. The Persistence Module is embedded in the BIOS while the Application Agent is installed by the user. When installed, the Persistence Module in the BIOS is activated and cannot be turned off. The Application Agent routinely contacts a monitoring center over the internet to report device information and location. The owner can perform the functions described.
	**Locate** - locate the device using Wi-Fi or IP geo-location to see the last location saved
	**Lock** - lock the device remotely to prevent access to your personal information, and displays a customized message on the screen
	**Delete** - remove all the files on the device to protect personal information and prevent identity theft
- **Trusted Platform Module (TPM)** – This is a chip designed to secure hardware by storing encryption keys, digital certificates, passwords, and data. TPM is used by Windows to support BitLocker full-disk encryption.
- **Secure** **boot** - Secure Boot is a UEFI security standard that ensures that a computer only boots an OS that is trusted by the motherboard manufacturer. Secure boot prevents an “unauthorized” OS from loading during startup.

Hardware Security Module (HSM) - 
Encrypted File System (EFS) - 
###### Access Levels

| Access Level | Description                                                                    |
| ------------ | ------------------------------------------------------------------------------ |
| Full         | All screens and settings are available                                         |
| Limited      | Changes can be made to a certain settings only, for example, the time and date |
| View Only    | All screens are available, but no settings can be changed                      |
| None         | No access is provided to the BIOS set up utility                               |

#### Over-Clocking

#### M-Flash
firmware updates and storage of the UEFI/BIOS via a flash drive

Motherboard manufacturers may publish updated BIOS versions to provide enhancements to system stability, compatibility, and performance. However, updating the firmware is risky. The release notes, such as those shown in the figure, describe the upgrade to the product, compatibility improvements, and the known bugs that have been addressed. Some newer devices operate properly only with an updated BIOS installed. You can usually find the current version on the main screen of the BIOS/UEFI interface.

Before updating motherboard firmware, record the manufacturer of the BIOS and the motherboard model. Use the information to identify the exact files to download from the motherboard manufacturer’s site. Only update the firmware if there are problems with the system hardware or to add functionality to the system.

Early computer BIOS information was contained in ROM chips. To upgrade the BIOS information, the ROM chip had to be physically replaced, which was not always possible. Modern BIOS chips are Electronically Erasable Programmable Read Only Memory (EEPROM) which can be upgraded by the user without opening the computer case. This process is called flashing the BIOS.

To download a new BIOS, consult the manufacturer’s website and follow the recommended installation procedures. Installing BIOS software online may involve downloading a new BIOS file, copying or extracting files to removable media, and then booting from the removable media. An installation program prompts the user for information to complete the process.

Many motherboard manufacturers now provide software to flash the BIOS from within an operating system. For example, the ASUS EZ Update utility automatically updates a motherboard’s software, drivers, and the BIOS version. It also enables a user to manually update a saved BIOS and select a boot logo when the system goes into POST. The utility is included with the motherboard, or it can be downloaded from the ASUS website.

**CAUTION**: An improperly installed or aborted BIOS update can cause the computer to become unusable. Consult the manufacturers website and follow the recommended installation procedures.

##### Hardware Monitor
CPU fan speed, temp, case fan speed, some with settings for an average temp

##### Board Explorer

##### Complementary Metal Oxide Semiconductor (CMOS)
When a computer boots, the BIOS software reads the configured settings stored in CMOS to determine how to configure the hardware.

The BIOS settings are retained by CMOS using a battery. However, if the battery fails, important settings can be lost. Therefore, it is recommended that BIOS settings always be documented.

**Note**: An easy way to document these settings is to take pictures of the various BIOS settings.

**Installation Tip**: If the computer’s time and date are incorrect, it could indicate that the CMOS battery is bad or is getting very low.

### Solutions
The clock on the computer is no longer keeping the correct time or the BIOS setting are changing when the computer is rebooted.

| Probable Cause                  | Possible Solutions |
| ------------------------------- | ------------------ |
| the CMOS batter may be loose    | secure battery     |
| the CMOS battery may be drained | replace battery    |
After updating the BIOS firmware, the computer will not start.

| Probable Cause                                     | Possible Solutions                                                                                                                          |
| -------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------- |
| the BIOS firmware update did not install correctly | contact the motherboard manufacturer to obtain the new BIOS chip. (if the motherboard has two BIOS chips, the second BIOS chip can be used) |
The computer displays the incorrect CPU information when the computer boots.

| Probable Cause                                                 | Possible Solutions                                   |
| -------------------------------------------------------------- | ---------------------------------------------------- |
| the CPU settings are not correct in the advanced BIOS settings | set the advanced BIOS settings correctly for the CPU |
| BIOS does not properly recognize the CPU                       | update the BIOS                                      |
The hard drive LED on the front of the computer does not turn on.

| Probable Cause                                        | Possible Solutions                                                                         |
| ----------------------------------------------------- | ------------------------------------------------------------------------------------------ |
| the hard drive LED cable is not connected or is loose | reconnect the LED cable to the motherboard                                                 |
| the hard drive LED cable is incorrectly oriented      | correctly orient the hard drive LED cable to the front case panel connection and reconnect |
The built-in NIC has stopped working

| Probable Cause              | Possible Solutions                            |
| --------------------------- | --------------------------------------------- |
| the NIC hardware has failed | install a new NIC into an open expansion slot |
The computer does not display any video after installing a new PCIe video card

| Probable Cause                                             | Possible Solutions                                      |
| ---------------------------------------------------------- | ------------------------------------------------------- |
| BIOS settings are set to use the built-in video            | disable the built-in video in the BIOS settings         |
| the monitor cable is still connected to the built-in video | connect the monitor cable to the new video card         |
| the new video card needs auxiliary power                   | connect any required power connectors to the video card |
| the new video card is faulty                               | install a good video card                               |
The new sound card does not work

| Probable Cause                                         | Possible Solutions                                     |
| ------------------------------------------------------ | ------------------------------------------------------ |
| the speaker are not connected to the correct jack      | connect the speakers the correct jack                  |
| the audio is muted                                     | unmute the audio                                       |
| the sound card is faulty                               | install a good sound card                              |
| BIOS settings are set to use the on-board sound device | disable the on-board audio device in the BIOS settings |
System attempts to boot to an incorrect device

| Probable Cause                           | Possible Solutions                                                                              |
| ---------------------------------------- | ----------------------------------------------------------------------------------------------- |
| media was left on a removable drive      | check that the removeable drives do not contain media that is interfering with the boot process |
| the boot order is configured incorrectly | check that the boot order is configured correctly                                               |
User can hear fans spinning but the computer does not start and there are no beeps from the speaker.

| Probable Cause                  | Possible Solutions                                                            |
| ------------------------------- | ----------------------------------------------------------------------------- |
| POST procedure is not executing | faulty cabling, damaged or mis-seated CPU, or the other motherboard component |
Motherboard capacitors are distended, swollen, emitting residue, or bulging.

| Probable Cause                  | Possible Solutions  |
| ------------------------------- | ------------------- |
| heat, ESP, power surge or spike | replace motherboard |
After updating the BOIS firmware, the computer will not start

| Probable Cause                                     | Possible Solutions                                                                                                                                                                                    |
| -------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| the BIOS firmware update did not install correctly | restore the original firmware from the onboard backup if it is available, if the motherboard has two BIOS chips use the second one, or contact the motherboard manufacturer to obtain a new BIOS chip |

### [[Central Processing Unit]]
#### Solutions
The computer will not boot or it locks up

| Probable Cause                | Possible Solutions                                              |
| ----------------------------- | --------------------------------------------------------------- |
| the CPU has over heated       | reinstall the CPU, replace the CPU fan, or add fans to the case |
| the CPU or CPU fan has failed | replace the CPU or CPU fan                                      |
The CPU fan is making an unusual noise

| Probable Cause         | Possible Solutions  |
| ---------------------- | ------------------- |
| the CPU fan is failing | replace the CPU fan |
The computer reboots without warning, locks up, displays error messages or the BSOD

| Probable Cause                                | Possible Solutions                                                                              |
| --------------------------------------------- | ----------------------------------------------------------------------------------------------- |
| the front-side bus is set too high            | reset to the factory default settings for the motherboard, or lower the front-side bus settings |
| the CPU multiplier or voltage is set too high | lower the multiplier or voltage settings                                                        |
| RAM is failing                                | test each RAM module to determine if they are operating correctly                               |
After upgrading from a single core CPU to a dual core CPU, the computer runs more slowly and only show on CPU graph in the Task Manager

| Probable Cause                                 | Possible Solutions                                        |
| ---------------------------------------------- | --------------------------------------------------------- |
| the BIOS does not recognized the dual core CPU | update the BIOS firmware to the support the dual core CPU |
A CPU will not install onto the motherboard

| Probable Cause                | Possible Solutions                                                    |
| ----------------------------- | --------------------------------------------------------------------- |
| the CPU is the incorrect tpye | replace the CPU with the CPU that matches the motherboard socket type |

## [[Computational Memory]]

### Solutions
The computer does not recognize the RAM that was added

| Probable Cause                          | Possible Solutions                |
| --------------------------------------- | --------------------------------- |
| the RAM is faulty                       | replace the RAM                   |
| the incorrect type of RAM was installed | install the correct type of RAM   |
| the new RAM is loose in the memory slot | secure the RAM in the memory slot |
After Upgrading Windows, the computer runs very slowly

| Probable Cause                             | Possible Solutions                           |
| ------------------------------------------ | -------------------------------------------- |
| the computer does not have enough RAM      | install additional RAM, or revert the update |
| the video card does not have enough memory | install a video card that has more memory    |
the computer exhibits slow performance

| Probable Cause                        | Possible Solutions                        |
| ------------------------------------- | ----------------------------------------- |
| the computer does not have enough RAM | install additional RAM                    |
| the computer is overheating           | clean the fans or install additional fans |

## [[Peripherals]]

### Displays
Consider this situation:
	A call comes in to the help desk: The Chief Financial Officer has started a meeting with the “C” level officers (including the Chief Executive Officer) in your company, and the projector won’t power on. This has happened before and will happen again. What’s the next step?
Below are some of the more common symptoms to look for. Watch out, those projector bulbs can be hot!

When troubleshooting issues with video, projectors, and displays, there are some common symptoms that should be considered prior to escalation. Remember to **always check the basics** first.

#### Incorrect Data Source
An incorrect data source means that the input source for the viewing device and the input source selected for the computer are not the same. Viewing devices, such as monitors and projectors, can have multiple data ports on them, including **HDMI**, **DisplayPort**, or **VGA**.

#### Physical Cabling Issues
Physical cabling can cause a wide variety of issues, such as no image being produced or an image that appears and then disappears. **Visually inspect** cabling for imperfections and **switch out cables** with known working cables to diagnose or rule out cabling issues.

#### Burned-Out Bulb
Burned-out bulbs are specific to projectors. Projector bulbs have a limited life. Replace the bulb to solve this issue.

#### Fuzzy Image
Fuzzy images can be caused by different problems depending on the display device. With a **projector**, check the focus mechanism. With an **LCD screen**, fuzzy images can be caused by external interference, cabling issues, or resolution settings.

#### Display Burn-In
Burn-in is when an image or image outline is still visible on the display. This is caused when images remain on the screen and become permanent parts of the display.The only solution is to **replace the display**.

#### Dead Pixels
The result of pixels that do not fire. This issue is typically related to the hardware or the monitor itself. **Replacement** of the display is usually necessary to correct it.

#### Flashing Screen
Often, a malfunctioning screen will either flash or flicker. A flickering screen is most likely caused by a **failing backlight**. Replace the backlight. With a flashing screen or a screen that turns on and off, the most likely cause is a **bad connection cable**.

#### Incorrect Color Display
With an LCD monitor, an incorrect color display is most likely caused by a **failing controller board**, which is responsible for color mapping. Another cause of an incorrect color display may be the **connection cable** or the **pins** on the display device itself. 

#### Audio Issues
Many display devices today have built-in audio. To troubleshoot any audio issues, first check that the audio is **not muted** and the audio **volume is up**. On the computer itself, make sure that the appropriate audio output is selected.

#### Dim Image
caused by either an issue with the display device itself, generally caused by a **failing backlight**, or the computer being set to a **low brightness setting**.

#### Intermittent Projector Shutdown
most commonly caused by **overheating**. Check to ensure proper airflow and unimpeded fans and filters.

#### Solutions
Display has power but no image on the screen

| Probable Cause                                                     | Possible Solutions                                                               |
| ------------------------------------------------------------------ | -------------------------------------------------------------------------------- |
| video cable is loose or damaged                                    | reconnect or replace the video cable                                             |
| the computer is not sending a video signal to the external display | use the Fn key along with the multipurpose key to toggle to the external display |
The display is flickering

| Probable Cause                                      | Possible Solutions                                    |
| --------------------------------------------------- | ----------------------------------------------------- |
| images on the screen are not refreshing fast enough | adjust the screen refresh rate                        |
| the display inverter is damaged or malfunctioning   | disassemble the display unit and replace the inverter |
The image on the display looks dim

| Probable Cause                             | Possible Solutions                                                                                                  |
| ------------------------------------------ | ------------------------------------------------------------------------------------------------------------------- |
| the LCD backlight is not properly adjusted | check the repair manual for the instructions about calibrating the LCD backlight. adjust the LCD backlight properly |
Pixels on the screen are dead, or not generating color

| Probable Cause                       | Possible Solutions      |
| ------------------------------------ | ----------------------- |
| power to the pixels has been cut off | contact the maufacturer |
The image on the screen appears to flash lines or patterns of different color and size (artifacts), the images on a display screen are distorted, or the color patterns on a screen are incorrect

| Probable Cause                        | Possible Solutions                                            |
| ------------------------------------- | ------------------------------------------------------------- |
| the display is not properly connected | disassemble the display to check the connections              |
| the GPU is overheating                | disassemble and clean the computer, check for dust and debris |
| the GPU is faulty or malfunctioning   | replace the GPU                                               |
| display setting have been changed     | restore display settings to the original factory settings     |
The display has a 'ghost' image

| Probable Cause                      | Possible Solutions                                                                                                                      |
| ----------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------- |
| the display is experiencing burn-in | power off the display and unplug it from the power source for a few hours, replace the battery, or use the degauss feature if it exists |
The images on the display have distorted geometry, or the monitor had oversized images and icons.

| Probable Cause                     | Possible Solutions                                 |
| ---------------------------------- | -------------------------------------------------- |
| the driver has become corrupted    | update or reinstall the driver in safe mode        |
| the display settings are incorrect | use the display's settings to correct the geometry |
The projector overheats and shuts down

| Probable Cause                   | Possible Solutions                                |
| -------------------------------- | ------------------------------------------------- |
| the fan has failed               | replace the fan                                   |
| the vents are clogged            | clean the vent and remove debris                  |
| the projector is in an enclosure | remove the enclosure or ensure proper ventilation |
In a muti-monitor setup, the displays are not aligned or are incorrectly oriented

| Probable Cause                                     | Possible Solutions                                                                           |
| -------------------------------------------------- | -------------------------------------------------------------------------------------------- |
| the settings for the multi-monitor are not correct | use the display control panel to identify each display and set the alignment and orientation |
| the driver had become corrupted                    | update or reinstall the driver in safe mode                                                  |
The display is in VGA mode

| Probable Cause                  | Possible Solutions                          |
| ------------------------------- | ------------------------------------------- |
| the computer is in safe mode    | reboot the computer                         |
| the driver had become corrupted | update or reinstall the driver in safe mode |

### [[Printers]]

Given a scenario, you’ll need to be able to troubleshoot printers. Although a lot of information is being passed digitally, printers still have their uses in offices and IT professionals need to know their way around troubleshooting and maintaining them. **Inkjet** and **laser** are the most common printer types in offices. Other less common printer types are **impact** and **thermal**. Printers can be either directly connected to a computer for local use or shared over a network.

Below are some fairly common symptoms, corresponding troubleshooting steps, and questions you should ask with regard to printers and printing issues.

#### Lines Down the Printed Pages
Lines on the printed page are usually caused by **ink residue**. Follow the printer’s **cleaning procedure**. This may include physically cleaning the internal parts of a printer, or a cleaning process that can be triggered by the printer’s software. Try printing a **test page**—are there streaks too? Sometimes streaks may be caused by **the scanning part** of a copier, and therefore they aren’t a printing problem.

#### Garbled Print
A garbled print may mean a software or connection issue. Are **correct drivers** installed? Is the printer connected firmly with a good **cable**? Is there **enough RAM** free on the printer?

#### Toner Not Fusing to Paper
Toner not fusing (or sticking) to the paper will only happen on laser printers, and it is due to a fuser problem. Try **replacing the fusing roller or the fuser lamp**.

#### Paper Jams
There are many reasons for frequent or sporadic paper jams. The reasons can be categorized as related to the **paper** or to the **printer hardware**. Ensure that the paper size and weight used are as recommended by the printer’s manufacturer. Try using a new, dry pack of good-quality paper. Don’t load too much paper at once. Bend the stack of paper to separate sheets before loading. If the problem is not with the paper, then the printer hardware needs to be checked. Check to see if the printer has been **maintained** per the manufacturer’s recommendations. Some printers have a page counter and recommendations on replacing specific internal parts to prevent paper jams. If the jams are very frequent, check for **broken parts** in the feeding path.

#### Faded Print
Check **toner or ink levels** if the print is faded. Try replacing the cartridges with new ones of known good quality. Check **printing settings**. Are there any **ink-saving settings** enabled that may reduce the amount of ink or toner used?

#### Incorrect Paper Size
If a printer is loaded with the incorrect paper size, it may jam or misprint. Check the printer’s **settings** to ensure the correct **paper size and orientation** is selected to match the desired outcome.

#### Paper Not Feeding
If the paper is not feeding, follow the same troubleshooting steps as for a _paper jam_.

#### Multipage Misfeed
Multiple page misfeeds can be caused by **separation pad** issues or **sticky/damp paper**.

#### Multiple Prints Pending in Queue
Are there specific errors on these pending jobs that can direct to the troubleshooting steps, such as issues with toner, paper, or access? A backed-up queue may also be due to **spooler issues**. **Restart** the spooler service. Try **disabling the spooler** and printing directly to the printer with no queueing.

#### Speckling on Printed Pages
Speckling, small marks, or defects on printed pages are common with frequently used or older laser printers. This is often caused by spilled toner or a crack or chip in the EP drum. To fix, **clean or replace the roller**. Speckling with an inkjet printer is often caused by dust or residue in the printer. **Clean the printer** with compressed air. If the problem persists, it may be a leaking cartridge. **Replace the cartridge.**

#### Double/Echo Images on the Print
Echo images may happen on laser printers due to a **broken cleaning blade** or **bad erasure lamps**. Try replacing the toner cartridge or the erasure lamps.

#### Incorrect Color Settings
Incorrect color production on an inkjet printer, referred to as the **chroma display**, could be caused by incorrect **cartridge placement**, ink bleeding from a **leaking cartridge**, or the incorrect **paper type**. If the paper is correct, try cleaning the print cartridges with the installed software and reprint a test page.

#### Grinding Noise
Impact printers can produce grinding noises with a damaged stepper motor. Replace the motor.

#### Finishing Issues
Many laser printers have finishing options, such as collation, stapling, and hole punching. Issues with the finisher are typically resolved with thorough cleaning.
- **Staple jams**—Problems with the stapling process are typically caused by malfunctions in the finisher. Check to ensure there are staples in the mechanism and that it does not have any jams.
- **Hole punch**—Problems with the hole punch process require the same process as the stapler. Ensure there are no blockages to the hole punch mechanism.

#### Incorrect Page Orientation
Incorrect page orientation is most likely caused by the settings within the printer or software. Ensure that the printer is set to print the correct orientation.

## [[Power Supply]]
The computer will not turn on

| Probable Cause                                                           | Possible Solutions                                                                |
| ------------------------------------------------------------------------ | --------------------------------------------------------------------------------- |
| the computer is not plugged in to the AC outlet or it is faulty          | plug the computer into a good AC outlet                                           |
| the power cord is faulty                                                 | use a good power cord                                                             |
| the power supply switch is not turned on                                 | turn on the power supply                                                          |
| the power supply switch is set to the incorrect voltage                  | set the power supply to the correct voltage                                       |
| the power button is not connected correctly to the front panel connector | correctly orient the power button to the front case panel connector and reconnect |
| the power supply has failed                                              | install a good power supply                                                       |
The computer reboots, turns off unexpectedly; or there is smoke or the smell of burning electronics

| Probable Cause                       | Possible Solutions       |
| ------------------------------------ | ------------------------ |
| the power supply is starting to fail | replace the power supply |

# Tools
## Testers
### Multimeter
used for testing the volts, current, and amperage between two points using metallic leads
## Reference
Good customer service includes providing the user with a detailed description of the problem and the solution. It is important that a technician document all services and repairs and that this documentation is available to all other technicians. The documentation can then be used as reference material for similar problems. Includes the
also know as the knowledge base

### Personal
Personal reference tools include troubleshooting guides, manufacturer manuals, quick reference guides, and repair journals. In addition to an invoice, a technician keeps a journal of upgrades and repairs:
- **Notes** - Make notes as you go through the troubleshooting and repair process. Refer to these notes to avoid repeating steps and to determine what needs to be done next.
- **Journal** - Include descriptions of the problem, possible solutions that have been tried to correct the problem, and the steps taken to repair the problem. Note any configuration changes made to the equipment and any replacement parts used in the repair. Your journal, along with your notes, can be valuable when you encounter similar situations in the future. Also used for a knowledge base article, which are submitted to the company for future referance
- **History of repairs** - Make a detailed list of problems and repairs, including the date, replacement parts, and user information. The history allows a technician to determine what work has been performed on a specific computer in the past.

### Online
The internet is an excellent source of information about specific hardware problems and possible solutions:
- Internet search engines
- News groups
- Manufacturer FAQs
- Online computer manuals
- Online forums and chat
- Technical websites

# Maintenance
Preventive maintenance is something that is often overlooked, but good IT professionals understand the importance of regular and systematic inspection, cleaning, and replacement of worn parts, materials, and systems. Effective preventive maintenance reduces part, material, and system faults, and keeps hardware and software in good working condition.

Preventive maintenance doesn't just apply to hardware. Performing basic tasks like checking what programs run on start-up, scanning for malware, and removing unused programs helps a computer function more efficiently, and can keep it from slowing down. Good IT professionals also understand the importance of troubleshooting which requires an organized and logical approach to problems with computers and other components.

These guidelines are a starting point to help you develop your preventive maintenance and troubleshooting skills. You will also learn the importance of maintaining an optimal operating environment for computer systems that are clean, free of potential contaminants, and within the temperature and humidity range specified by the manufacturer.

## Benefits
Preventive maintenance plans are developed based on at least two factors:
- **Computer location or environment** - Dusty environments, such as construction sites, requires more attention than an office environment.
- **Computer use** - High-traffic networks, such as a school network, might require additional scanning and removal of malicious software and unwanted files.

Regular preventive maintenance:
- Reduces potential hardware and software problems, computer downtime, repair costs, and the number of equipment failures.
- Improves data protection, equipment life and stability, and saves money.

## Cleaning
loose tangled cables
loose screws
missing cables
slot covers
### Dust
The following are considerations to keep dust from damaging computer components:

- Clean/replace building air filters regularly to reduce the amount of dust in the air.
- Use a cloth or a duster to clean the outside of the computer case. If using a cleaning product, put a small amount onto a cleaning cloth and then wipe the outside of the case.
- Dust on the outside of a computer can travel through cooling fans to the inside.
- Accumulated dust prevents the flow of air and reduces the cooling of components.
- Hot computer components are more likely to break down.
- Remove dust from the inside of a computer using a combination of compressed air, a low-air-flow ESD vacuum cleaner, and a small lint-free cloth.
- Keep the can of compressed air upright to prevent the fluid from leaking onto computer components.
- Keep the compressed air can a safe distance from sensitive devices and components.
- Use the lint-free cloth to remove any dust left behind on the component.

**CAUTION**: When you clean a fan with compressed air, hold the fan blades in place. This prevents overspinning the rotor or moving the fan in the wrong direction.

### Internal Components
This is a basic checklist of components to inspect for dust and damage:
- **CPU heat sink and fan assembly** – The fan should spin freely, the fan power cable should be secure, and the fan should turn when the power is on.
- **RAM modules** – The modules must be seated securely in the RAM slots. Ensure that the retaining clips are not loose.
- **Storage devices** - All cables should be firmly connected. Check for loose, missing, or incorrectly set jumpers. A drive should not produce rattling, knocking, or grinding sounds.
- **Screws** - A loose screw in the case can cause a short circuit.
- **Adapter cards** – Ensure that they are seated properly and secured with the retaining screws in their expansion slots. Loose cards can cause short circuits. Missing expansion slot covers can let dust, dirt, or living pests inside the computer.
- **Cables** - Examine all cable connections. Ensure that pins are not broken and bent and that cables are not crimped, pinched, or severely bent. Retaining screws should be finger-tight.
- **Power devices** - Inspect power strips, surge suppressors (surge protectors), and UPS devices. Make sure that the devices work properly and that there is clear ventilation.
- **Keyboard and mouse** - Use compressed air to clean the keyboard, mouse, and mouse sensor.

## Environmental Concerns
An optimal operating environment for a computer is clean, free of potential contaminants, and within the temperature and humidity range specified by the manufacturer.

These guidelines help ensure optimal computer operating performance:
- Do not obstruct vents or airflow to the internal components.
- Keep the room temperature between 45 to 90 degrees Fahrenheit (7.2 to 32.2 degrees Celsius).
- Keep the humidity level between 10 and 80 percent.
- Temperature and humidity recommendations vary by computer manufacturer. Research the recommended values for computers used in extreme conditions.

## [[Software]]
Verify that installed software is current.
- Follow the policies of the organization when installing security updates, operating system, and program updates.

Create a software maintenance schedule to:
- Review and install the appropriate security, software, and driver updates.
- Update the virus definition files and scan for viruses and spyware.
- Remove unwanted or unused programs.
- Scan hard drives for errors and defragment hard drives.