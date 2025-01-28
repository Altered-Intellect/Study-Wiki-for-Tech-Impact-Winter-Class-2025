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

### [[CMOS]] Battery Failure Symptoms
Recognizing the signs of a failing CMOS battery can help you address issues before they become more serious. Here are some common symptoms:
1. **Incorrect System Time and Date**: The most common sign of a failing CMOS battery is the computer consistently showing the wrong time and date, often resetting to a default date (like January 1, 2000) after each restart, which can be verified in the BIOS setup.
2. **BIOS Settings Reset**: If your custom BIOS settings keep reverting to default values, it could indicate a failing CMOS battery.
3. **Boot Issues**: In some cases, a dead CMOS battery can cause problems during the boot process, including failure to POST (Power-On Self-Test) or boot loops.
4. **Error Messages**: You might see error messages related to CMOS or BIOS settings during startup.
5. **Hardware Detection Problems**: The computer may fail to detect or incorrectly configure certain hardware components.
6. **Slow Boot Times**: As the BIOS has to reconfigure settings each time, boot times may become noticeably longer.

---
## [[Mobile Devices]]
Mobile devices are here to stay. For the purposes of the CompTIA A+ exam, the term refers to laptops and smaller devices. The only difference is they are smaller—much smaller—than other devices. Compact and portable, mobile devices can be much **tougher to troubleshoot** than conventional devices. Your company policy will dictate the level of repair you will be required to perform on these. If the device is personally owned, you might not be required to work on it. Keep in mind that the questions about this area will begin with a scenario.

### Common Symptoms
Below are some fairly common symptoms and corresponding questions you should ask with regard to mobile devices. Ensure you have a **very clean workspace** and **sufficient lighting** prior to undertaking a major repair.

#### Poor Battery Health
Poor battery health can be evident by checking to see if a device works when physically plugged into a power source or if a fully charged battery drains very quickly with normal usage; within 30 minutes, for example. For a battery that will not hold a charge at all, replace the battery. With a laptop that holds a poor charge, you can attempt to perform a **battery calibration** before resorting to a battery replacement. With a smartphone, you can **drain** the battery completely and **recharge** before replacing the battery.

#### Swollen Battery
A battery that is visibly distended. **Turn off the device immediately** and **replace** the battery.

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

## [[Networks]]
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
