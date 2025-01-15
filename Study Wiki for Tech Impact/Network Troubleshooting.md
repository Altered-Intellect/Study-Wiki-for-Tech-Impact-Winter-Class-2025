---
tags: 
parent docs:
  - "[[Navigation]]"
sibling docs: 
child docs: 
last updated: 2025-01-14T23:32:00
media:
---
# Nav
< [[Hardware|Previous]] < ^ [[Navigation|Home]] ^ > [[Mobile Devices|Next]] >

---

A Technician’s knowledge must extend beyond knowing how to assemble a computer. You need to have in-depth knowledge of computer system architecture and how each component operates and interacts with other components. This depth of knowledge is necessary when you have to upgrade a computer with new components that must be compatible with existing components and also when you build computers for very specialized applications. This chapter covers the computer boot process, protecting the computer from power fluctuations, multicore processors, redundancy through multiple storage drives, and protecting the environment from hazardous materials found inside of computer components. 

You will learn about the computer boot process including the power on self-test (POST) conducted by the BIOS. Explore various BIOS and UEFI settings and how they impact this process. You will explore basic electrical theory and Ohm’s law and calculate voltage, current, resistance, and power. Power fluctuations can damage computer components so you will learn how to mitigate the risk of power fluctuations with surge protectors, uninterruptible power supplies (UPSs), and standby power supplies (SPSs). You will learn how to provide storage redundancy and load balancing using redundant arrays of independent disks (RAID). You will also learn how to upgrade computer components and configure specialized computers. Finally, after upgrading a computer, technicians must dispose of the old parts properly. Many computer components contain hazardous materials, such as mercury and rare earth metals in batteries and deadly voltage levels in power supplies. You will learn the risks posed by these components and how to dispose of them properly.

As an IT support professional, you will be depended upon to fix whatever goes wrong. Any device or network issue will fall within your domain. This is why hardware and network troubleshooting is the most emphasized area on the CompTIA A+ 1101 test, with 29% (nearly one-third) of the questions pertaining to it. It is important to note that _all_ the questions about hardware and network troubleshooting will begin with a scenario.

# [[Motherboards]]
RAM, CPU, and Power
There are many different situations that can arise when various types of hardware components start failing. You must be able to troubleshoot common problems through a scenario.

## Common Symptoms
The **motherboard**, **RAM**, **CPU**, and **power supply** are the most critical components to a computer system. Problems with these components may have the same or similar symptoms. The list below covers general troubleshooting guidelines and causes of common symptoms.


## Pre-Boot System/Software
software that is used to configure various components of a computer before the booting of the OS
### Unified Extendable Firmware Interface (UEFI)
Most computers today run Unified Extensible Firmware Interface (UEFI). All new computers come with UEFI, which provides additional features and addresses security issues with legacy BIOS. You may see “BIOS/UEFI” when booting into your BIOS settings. This is because Intel chips currently support backwards compatibility with legacy BIOS systems. However, by 2020, Intel will end support for legacy BIOS. For more information, do an internet search for “Intel to remove legacy BIOS”.

**Note**: This section uses BIOS, UEFI, and BIOS/UEFI interchangeably. In addition, manufacturers may continue to label their UEFI programs with “BIOS” so that users know it supports the same functions.

UEFI configures the same settings as traditional BIOS but also provides additional options. For example, UEFI can provide a mouse-enabled software interface instead of the traditional BIOS screens. However, most systems have a text-based interface, similar to legacy BIOS systems.

UEFI can run on 32-bit and 64-bit systems, supports larger boot drives and includes additional features such as secure boot. Secure boot ensures your computer boots to your specified operating system. This helps prevent rootkits from taking over the system. For more information, do an internet search for “Secure boot and rootkits”.

**Note**: UEFI setup screens will not look the same as yours. Please refer to your motherboard manufacturer documents.

### Basic Input/Output System (BIOS)
All motherboards need BIOS to operate. BIOS is a ROM chip on the motherboard that contains a small program. This program controls the communication between the operating system and the hardware. 

Along with the POST, the UEFI/BIOS also identifies:
- Which drives are available
- Which drives are bootable
- How the memory is configured and when it can be used
- How PCIe and PCI expansion slots are configured
- How SATA and USB ports are configured
- Motherboard power management features

The motherboard manufacturer saves the motherboard BIOS settings in a Complementary Metal Oxide Semiconductor (CMOS) memory chip
### Power On Self Test (POST)
When a computer is booted, the basic input/output system (BIOS) performs a hardware check on the main components of the computer. This check is called a power-on self-test (POST).

The figure below displays a screen capture of a sample POST being performed. Within this test the computer checks whether the computer hardware is operating correctly.
#### Power-on Self-Test (POST) Beeps
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

### Settings
change what the computer has access to before the computer has been booted up and running such as Wi-Fi, Bluetooth, LAN, Audio and video card, and SATA ports
controls how quickly the machine will boot
type of OS
#### System Status

#### Boot
the order in which the computer loads its software, all pre-boot software allow the use to configure the order in which 
#### Security
The legacy BIOS supports some security features to protect the BIOS setting. UEFI adds additional security features and is used to set the admin password, user password, and U-key. These are some common security features found in the BIOS/UEFI systems:
- **Passwords** - Passwords allow for different levels of access to the BIOS settings. Usually, there are two password settings that can be altered; the Supervisor Password and the User Password. The Supervisor Password can access all user-access passwords and all BIOS screens and settings. The User Password gives access to the BIOS based on a defined level. The table below displays common levels of user access to BIOS. The Supervisor Password must be set before the User Password can be configured.
- **U-key** - a password set for a specific Flash drive used to prevent foreign data
- **Drive encryption** - A hard drive can be encrypted to prevent data theft. Encryption changes the data on the drive into code. Without the correct password, the computer cannot boot and data read from the hard drive cannot be understood. Even if the hard drive is placed in another computer, the data remains encrypted.
- **LoJack** – This is a security feature that consists of two programs; the Persistence Module and the Application Agent. The Persistence Module is embedded in the BIOS while the Application Agent is installed by the user. When installed, the Persistence Module in the BIOS is activated and cannot be turned off. The Application Agent routinely contacts a monitoring center over the internet to report device information and location. The owner can perform the functions described in the figure below.
	**Locate** - locate the device using Wi-Fi or IP geo-location to see the last location saved
	**Lock** - lock the device remotely to prevent access to your personal information, and displays a customized message on the screen
	**Delete** - remove all the files on the device to protect personal information and prevent identity theft
- **Trusted Platform Module (TPM)** – This is a chip designed to secure hardware by storing encryption keys, digital certificates, passwords, and data. TPM is used by Windows to support BitLocker full-disk encryption.
- **Secure** **boot** - Secure Boot is a UEFI security standard that ensures that a computer only boots an OS that is trusted by the motherboard manufacturer. Secure boot prevents an “unauthorized” OS from loading during startup.

Hardware Security Module (HSM) - 
Encrypted File System (EFS) - 
##### Access Levels

| Access Level | Description                                                                    |
| ------------ | ------------------------------------------------------------------------------ |
| Full         | All screens and settings are available                                         |
| Limited      | Changes can be made to a certain settings only, for example, the time and date |
| View Only    | All screens are available, but no settings can be changed                      |
| None         | No access is provided to the BIOS set up utility                               |


### Over-Clocking

### M-Flash
firmware updates and storage of the UEFI/BIOS via a flash drive

Motherboard manufacturers may publish updated BIOS versions to provide enhancements to system stability, compatibility, and performance. However, updating the firmware is risky. The release notes, such as those shown in the figure, describe the upgrade to the product, compatibility improvements, and the known bugs that have been addressed. Some newer devices operate properly only with an updated BIOS installed. You can usually find the current version on the main screen of the BIOS/UEFI interface.

Before updating motherboard firmware, record the manufacturer of the BIOS and the motherboard model. Use the information to identify the exact files to download from the motherboard manufacturer’s site. Only update the firmware if there are problems with the system hardware or to add functionality to the system.

Early computer BIOS information was contained in ROM chips. To upgrade the BIOS information, the ROM chip had to be physically replaced, which was not always possible. Modern BIOS chips are Electronically Erasable Programmable Read Only Memory (EEPROM) which can be upgraded by the user without opening the computer case. This process is called flashing the BIOS.

To download a new BIOS, consult the manufacturer’s website and follow the recommended installation procedures. Installing BIOS software online may involve downloading a new BIOS file, copying or extracting files to removable media, and then booting from the removable media. An installation program prompts the user for information to complete the process.

Many motherboard manufacturers now provide software to flash the BIOS from within an operating system. For example, the ASUS EZ Update utility automatically updates a motherboard’s software, drivers, and the BIOS version. It also enables a user to manually update a saved BIOS and select a boot logo when the system goes into POST. The utility is included with the motherboard, or it can be downloaded from the ASUS website.

**CAUTION**: An improperly installed or aborted BIOS update can cause the computer to become unusable. Consult the manufacturers website and follow the recommended installation procedures.

### Hardware Monitor
CPU fan speed, temp, case fan speed, some with settings for an average temp
### Board Explorer

### Complementary Metal Oxide Semiconductor (CMOS)
When a computer boots, the BIOS software reads the configured settings stored in CMOS to determine how to configure the hardware.

The BIOS settings are retained by CMOS using a battery, such as the one shown in the figure below. However, if the battery fails, important settings can be lost. Therefore, it is recommended that BIOS settings always be documented.

**Note**: An easy way to document these settings is to take pictures of the various BIOS settings.

**Installation Tip**: If the computer’s time and date are incorrect, it could indicate that the CMOS battery is bad or is getting very low.
## Proprietary Crash Screens
Operating system-specific error messages that occur when there is a potentially fatal error in the system. The most common proprietary crash screens are the **Windows blue screen of death (BSOD)** and the **macOS rotating pinwheel**. Common causes of these crash screens are **memory issues**, which may cause application crashes or error messages.

#### Black Screen
A black screen is indicative of **no video output**. Common causes of a black screen include problems with the video card, cabling, or the screen itself. Remember that many motherboards have the video card built in, which may indicate an issue with the motherboard itself. In this case, you can attempt to connect an external video card that, once connected, in most cases will disable the onboard video card.

#### No Power
**Power outlet** or **power supply** issues are usually the cause of this. When troubleshooting, begin by testing and replacing the easiest and most obvious components first before removing and replacing the power supply.

#### Sluggish Performance
Sluggish performance is one of the more difficult problems to troubleshoot. Common causes include low memory, low hard drive space, failing primary components, bad applications, too many applications, or malware. A good place to start when troubleshooting on a Windows OS is to view memory usage in Task Manager, which provides real-time statistics on the CPU, RAM, hard drive, and network connection.

#### Overheating
Problems with the fan, heat sink, dust accumulation, or something blocking the **air circulation** can all cause a device to overheat. Examine the device for impediments to the cooling mechanisms, such as excess dust or improper placement for optimal ventilation. **Compressed air** is one way to clean excess dust accumulation, but ensure that you are blowing away from the internal components of the computer rather than further into the device.

#### Burning Smell
A burning smell coming from a computer system is never a good thing. If you detect a burning smell, **shut down the device immediately** and examine it for potential culprits. Look for melted plastic and burn marks on circuit boards. Replace affected components and monitor the new component for failure. A component that fails too quickly may be an indicator of a power supply issue.

#### Intermittent Shutdown
An intermittent shutdown is typically a result of **components overheating and failing**. Intermittent shutdowns may also be caused by a bad hardware installation or improper motherboard connection.

#### Application Crashes
often an indicator of **memory**-related issues, such as failing memory or not enough memory available to run the application properly.

#### Grinding Noise
Grinding noises can only originate from **moving components** within the computer, such as the HDDs, fans, and optical drives. This fact eliminates all non-moving components within the device. Whirring sounds tend to originate from fans, while clicking or squealing sounds often come from the HDD. Optical drive noises are the simplest to diagnose.

#### Capacitor Swelling
Capacitors **store electricity** on the motherboard. When a capacitor fails, they tend to swell and produce a brownish-red residue that may seep. This phenomenon is referred to as a **distended capacitor** or **capacitor swelling**. Two options to resolve this issue include replacing the motherboard or replacing the capacitor, which requires specialized training.

#### Inaccurate System Date/Time
Inaccurate system date/time is most likely an indication of a **bad CMOS battery**. The CMOS battery is responsible for retaining the computer’s settings when it is powered off and is located on the motherboard. When the CMOS battery fails, the computer will be unable to retain its BIOS settings.

### [[CMOS Battery]] Failure Symptoms
Recognizing the signs of a failing CMOS battery can help you address issues before they become more serious. Here are some common symptoms:
1. **Incorrect System Time and Date**: The most common sign of a failing CMOS battery is the computer consistently showing the wrong time and date, often resetting to a default date (like January 1, 2000) after each restart, which can be verified in the BIOS setup.
2. **BIOS Settings Reset**: If your custom BIOS settings keep reverting to default values, it could indicate a failing CMOS battery.
3. **Boot Issues**: In some cases, a dead CMOS battery can cause problems during the boot process, including failure to POST (Power-On Self-Test) or boot loops.
4. **Error Messages**: You might see error messages related to CMOS or BIOS settings during startup.
5. **Hardware Detection Problems**: The computer may fail to detect or incorrectly configure certain hardware components.
6. **Slow Boot Times**: As the BIOS has to reconfigure settings each time, boot times may become noticeably longer.

---

## Problems with Storage Drives and RAID Displays
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

#### RAID Failure
Troubleshooting a RAID failure is similar to troubleshooting a single storage drive. First determine if the problem originates with a single drive or the system as a whole and proceed from there. Check the **indicator lights** on the RAID system for insight. Remember that the problem could originate from the type of RAID that is being employed.

#### S.M.A.R.T. Failure
Self-monitoring, analysis, and reporting technology (S.M.A.R.T.) is software installed on drives that monitors hard drive reliability and performance. S.M.A.R.T. metrics, while in theory useful for diagnosing and predicting drive failure, tend to be overly complicated and difficult to parse. One **useful component** of S.M.A.R.T. is the **ability to create performance benchmarks** that may prove valuable in diagnosing potential drive failures.

#### Extended Read/Write Times
Extended read/write times, like data loss/corruption, can be indicators of a **failing or full drive**. Troubleshoot this issue as you would data loss/corruption.

#### Input/Output Operations Per Second (IOPS)
Input/output operations per second (IOPS) refers to how many reads and writes a storage device can perform in a second and is listed on storage devices, such as NAS and RAID systems. A **steadily declining IOPS** may be an **indicator of drive failure**.

#### Missing Drives in OS
Missing drives in the OS may be indications of a connection issue or an improperly set up storage device. Troubleshoot missing drives by checking connections, checking the **BIOS/UEFI** for the enabled drive, finding the drive in disk management or disk utility, making sure the drive is prepared and partitioned properly, updating drive drivers, and checking for bad sectors, which may cause the OS to show the drive as unreadable.

## Problems with Video, Projectors, and Displays
Consider this situation:
	A call comes in to the help desk: The Chief Financial Officer has started a meeting with the “C” level officers (including the Chief Executive Officer) in your company, and the projector won’t power on. This has happened before and will happen again. What’s the next step?
Below are some of the more common symptoms to look for. Watch out, those projector bulbs can be hot!

### Common Symptoms
When troubleshooting issues with video, projectors, and displays, there are some common symptoms that should be considered prior to escalation. Remember to **always check the basics** first.

#### Incorrect Data Source
An incorrect data source means that the input source for the viewing device and the input source selected for the computer are not the same. Viewing devices, such as monitors and projectors, can have multiple data ports on them, including **HDMI**, **DisplayPort**, or **VGA**.

![1 Laptop Ports Side View.png](https://uniontestprep.com/rails/active_storage/blobs/redirect/eyJfcmFpbHMiOnsibWVzc2FnZSI6IkJBaHBBM1JPQVE9PSIsImV4cCI6bnVsbCwicHVyIjoiYmxvYl9pZCJ9fQ==--bf422897b499365392991749a31bdad61eb579b9/1 Laptop Ports Side View.png)

_Image retrieved from: https://pixabay.com/photos/usb-hdmi-vga-1394-lan-laptop-1884/_

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

---
## Problems with Mobile Devices
Mobile devices are here to stay. For the purposes of the CompTIA A+ exam, the term refers to laptops and smaller devices. The only difference is they are smaller—much smaller—than other devices. Compact and portable, mobile devices can be much **tougher to troubleshoot** than conventional devices. Your company policy will dictate the level of repair you will be required to perform on these. If the device is personally owned, you might not be required to work on it. Keep in mind that the questions about this area will begin with a scenario.

### Common Symptoms
Below are some fairly common symptoms and corresponding questions you should ask with regard to mobile devices. Ensure you have a **very clean workspace** and **sufficient lighting** prior to undertaking a major repair.

#### Poor Battery Health
Poor battery health can be evident by checking to see if a device works when physically plugged into a power source or if a fully charged battery drains very quickly with normal usage; within 30 minutes, for example. For a battery that will not hold a charge at all, replace the battery. With a laptop that holds a poor charge, you can attempt to perform a **battery calibration** before resorting to a battery replacement. With a smartphone, you can **drain** the battery completely and **recharge** before replacing the battery.

#### Swollen Battery
A battery that is visibly distended. The image below shows how this might appear. **Turn off the device immediately** and **replace** the battery.

![2 Swollen Battery Side Image.png](https://uniontestprep.com/rails/active_storage/blobs/redirect/eyJfcmFpbHMiOnsibWVzc2FnZSI6IkJBaHBBM1ZPQVE9PSIsImV4cCI6bnVsbCwicHVyIjoiYmxvYl9pZCJ9fQ==--fe7d785e1d384d5604b85ab09ad5e9853d9c97f7/2 Swollen Battery Side Image.png)

#### Broken Screen
A broken screen will have to be **replaced** if the break is severe enough to affect functionality.

#### Improper Charging
Most mobile devices have a charging indicator light or icon of some sort. While it is rare for the indicator to fail, it may happen. To check for this issue, plug the device in with a known working charger and see if the indicator is on. Improper charging is typically caused, however, by a connection issue, such as a **damaged cable** or the use of an **aftermarket cable** that is not fully compatible with the device.

#### Poor/No Connectivity
When troubleshooting poor/no connectivity, begin by checking to make sure the appropriate connectivity method is on, such as Bluetooth® or wireless. If the **connection method is enabled**, check the **signal strength** of the connection. Poor connectivity can be caused by too much distance between the sending and receiving devices.

#### Liquid Damage
Liquid damage can cause significant issues with a mobile device. If liquid damage is suspected, **turn off the device immediately** and let the device **air dry**. A laptop with significant liquid damage may be disassembled and cleaned using demineralized water and a lint-free cloth.

#### Overheating
Overheating can cause a device to shut down or not function properly. If overheating is suspected, **shut down the device immediately** and allow it to **cool**. To reduce the likelihood of overheating, ensure that the device is allowed proper **airflow** and keep all flow components clean and clear of dust and debris.

#### Digitizer Issues
To address digitizer issues on a laptop, you may go into the settings of the device and attempt to **recalibrate** the digitizer. If the digitizer cannot be calibrated or fixed, you may be able to work around the issue by **using a mouse and keyboard** for input. With a **mobile phone**, the only method for fixing the digitizer is to **fully power off** the device and **power it back on**. If this does not fix the issue, the screen will need to be replaced.

#### Physically Damaged Ports
With a physically damaged port, the only solution is to **replace** the port.

#### Malware
Malware is any malicious software designed to disrupt the usage of, cause damage to, or gain unauthorized access to an infected device. If malware is suspected, **antivirus and antimalware software** can identify, isolate, and remove most malware as well as defend against incoming malware. A **firewall** can also be used to help prevent infection.

#### Cursor Drift/Touch Calibration
Cursor drift is most commonly caused by a faulty pointing stick. You may **move** the input device around in an attempt to resolve the issue, or you can also attempt to **recalibrate** it. Recalibration can also be used to remedy faulty calibrations on touch screens.

---

## Issues with [[Printers]] 
Given a scenario, you’ll need to be able to troubleshoot printers. Although a lot of information is being passed digitally, printers still have their uses in offices and IT professionals need to know their way around troubleshooting and maintaining them. **Inkjet** and **laser** are the most common printer types in offices. Other less common printer types are **impact** and **thermal**. Printers can be either directly connected to a computer for local use or shared over a network.

### Common Symptoms
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

## Wired and Wireless Network Problems
Given a scenario, you will need to troubleshoot common wired and wireless network problems. Networks are at the heart of today’s computing. A failure in network access has a good chance of preventing users from doing their work or information from being accessed. It needs to be addressed effectively.

### Common Symptoms
Below are some fairly common symptoms and corresponding troubleshooting steps and questions you should ask with regard to networking and connectivity issues. Some basic **troubleshooting tactics remain constant:** check physical cables, connection, and speed or duplex mismatch first.

#### Intermittent Wireless Connectivity
Intermittent connectivity occurs when wireless connectivity appears and disappears. Intermittent connectivity is the most difficult to troubleshoot. When troubleshooting intermittent connectivity, try to narrow down the issue by addressing **latency**, **jitter**, **port flapping**, and **slow network speeds**.

#### Slow Network Speeds
Slow network speeds on a wired connection are mostly due to overload of the network. Solutions include adding a switch or creating **VLANs** with switches. A wireless connection with slow speed can also be caused by overload to the **wireless access point (WAP)** or wireless router. Distance from the WAP can also cause slow network speeds.

#### Limited Connectivity
Limited connectivity is a state in which a device is connected to the network but can’t reach outside of the local network. Even some local resources may be unreachable.
- For **Wi-Fi** networks, this is frequently caused by an **incorrect password**. Try reconfiguring the Wi-Fi connection with the correct password.
- For **wired ethernet networks**, the issue is usually due to the device not getting an **IP address** from the DHCP server, or it’s due to having a static IP address that doesn’t match the router network configuration. Does the device have the IP address configured manually? Is the default gateway configured correctly and does it match the IP address of the router on the network? For dynamic IP addresses, does the device get an IP address assigned? Is it in valid range on the same network as the router on the network?

#### Jitter
Jitter is **variable latency**. Jitter can be caused by overloaded networks, both wired and wireless, or, with a wired device, a poor cable connection.

#### Poor VoIP Quality
Intermittent network connectivity or a slow network can cause poor Voice over Internet Protocol (VoIP) quality. Most managed systems running VoIP have a **priority setting** for different streams of networks. To increase VoIP quality, rank the VoIP connection as a high priority.

#### Port Flapping
Port flapping causes intermittent connectivity when a switch opens and closes a port very quickly. To troubleshoot port flapping, check cables, the connection, and the duplex. Another place to check for port flapping is the error logs on the switch for which layer the error occurs at. Also, reseat the **small form-factor pluggable (SFP)** connector. If this does not remedy the issue, switch to a known working SFP.

#### High Latency
High latency may cause the connection to appear intermittent. Troubleshoot high latency as you would intermittent connections.

#### External Interference
External interference is caused when an external device interferes with the wireless signal of a WAP or wireless router. External devices that may cause interference include radio signals, physical barriers, microwaves, motors, or fluorescent lights. If external interference is suspected, **change the positioning of the WAP or the external device** if possible.

---
# Nav
< [[Hardware|Previous]] < ^ [[Navigation|Home]] ^ > [[Mobile Devices|Next]] >
