---
tags: 
parent docs:
  - "[[Navigation]]"
sibling docs: 
child docs: 
media:
---
# [[Hardware]]
1. What is a Form Factor? What are some common desktop form factors? (1.2.1.1)
 The size and shape of the motherboard and the case that the computers components are put into. Common form factors include all-in-one, compact, full-size, and horizontal.

2. What is the purpose of a computer power supply? How does it function? (1.2.1.2) 
 The purpose of the power supply is to supply electrical power to the computer by converting the AC power of the power grid to the lower voltage DC required for computer components. 
 
3. What are the six power connectors described in the Cisco curriculum? What are the most common voltage units supplied by the Power Supply? (1.2.1.3 – 1.2.1.4)
20/24 pin, Molex, 4/8 pin, 6/8 pin, SATA, and Berg Keyed connectors.
3.3, 5, and 12v.
  
4. How can ESD affect computer components? What are two precautions a tech can use to reduce this risk? (1.1.2.2) 
ESD is caused by the discharge of an electric charge with a lot of voltage. When a computer component is exposed to ESD it over-volts the circuitry and prevents it from properly holding a charge. ESD can be reduced by wear anti-static equipment such as mats, and wrist straps, removing metal from the body like jewelry, as well as self grounding via contact with a metal surface such as the computer case or metal furniture.

5. Fill in the blank: _______________ is a name for the circuits on the motherboard that control how system hardware interacts with the CPU and motherboard. 
PC Chipset

6. Generally, what components do the Northbridge and Southbridge chipsets control?(1.2.2.3)
The northbridge controls the timing and operation of faster components like the RAM, CPU, and graphics card, while the southbridge controls slower components such as input peripherals, USB, expansion slots, and the BIOS.

7. What are the two features make up a Motherboard Form Factor? What are the three common motherboard Form Factors?(1.2.2.4)
The size and shape of the the board the components are attached to, the most common of which are ATX, Micro-ATX, and ITX

8. Modern CPU sockets and processor packages are built around the following architectures:
 Pin Grid Array (PGA) in which the pins are on the processor itself, and Land Grid Array (LGA) in which the pins are on the socket instead.

9. What is ROM? What are PROM, EPROM, and EEPROM?(1.2.4.1-1.2.4.2) 
Read-Only-Memory
Programmable ROM
Erasable PROM
Electronically EPROM aka Flash ROMs
 
10. What is RAM and what is it used for? (1.2.4.1)  
Random Access Memory is used for temporary working storage of the computers which means the space is used to storage software and files that are currently being access to the CPU.

11. What type of RAM is typically used as cache memory, and what are some other features about it?(1.2.4.3)  
 Static RAM, its is typically faster than accessing the same information from the main memory or the DRAM.

12. Describe the main differences between DIP, SIMM, DIMM, and SODIMM memory
modules. (1.2.4.4)
Dual Inline Package is a single memory chip with two rows of pins.
Single Inline Memory Module is a single board with multiple chips with a single row of pins, usually 30 or 72.
Dual Inline Memory Module is a SIMM with two rows of pins.
Small Outline DIMM is a condensed version of a DIMM used in mobile devices
 
13. What are the benefits of DDR4 SDRAM? (1.2.4.3) 
It has quadruple the storage of it previous iteration, decreases the voltage to 1.1v, and advanced ECC that can correct multiple errors.
 
14. What is parity memory and how does it differ from ECC memory? (1.2.4.4)
Parity data has a one bit every eight that is dedicated to error-checking, Error correcting code memory has dedicated space on the chip to both error-checking and error-correcting, but it can only do it a single bit at a time.

15. What is the purpose of expansion slots and adapter cards? And what are the most common expansion slots?
Expansion slots increase the functionality of a computer via connectors on the motherboard. Adapter cards add physical components to 
 
16. What are the three types of optical drives? What did these replace? (1.2.7.1)
CD, DVD, and Blu-Ray. Optical media
  
17. What are the benefits of an SSD over a traditional HDD?(1.2.6.4)   
SSDs are non volatile, meaning the memory does not require constant power to be stored, and the storage wears out slower because there is no moving parts, 
 
18. Name the three form factors SSD’s can take:
Tape Drives, M.2, Molex/PATA

19. Describe Virtual Reality. Describe Augmented Reality.(1.2.10.3) 
VR is an I/O system that used lenses and two displays to simulate an environment by blocking out the users immediate environment
 
20. What is NVMe? Why was it created? (1.2.6.4)
Non-Volatile Memory express is an open source standard for optimizing the transfer of data that uses the PCIe bus. It was created to connect SSDs to the motherboard via the PCIe bus without using specialized drivers.
 
21. What are the steps when disassembling a PC?(1.3.2.1)
see [[Computer (Dis-Re)Assembly]]

# [[Computer (Dis-Re)Assembly]]
1. **What are some common factors to keep in mind when selecting a computer case?**
motherboard form factor, power supply, case fans, physical environment, and number of components, 

2. **When selecting a case fan, why do these factors need to be considered?**
number of components, multiple components on a computer create additional heat, which requires more, larger, or faster fans
physical environment, The case fans must be able to disperse enough heat to keep the interior of the case cool. The amount of ambient temp, dust, and humidity must be taken into consideration.

3. **Which factors need to be considered when choosing a power supply?**
wattage for all components plus 25%, case size, type of motherboard and components

4. **List the 6 steps of installing the Motherboard:**
- 1. Align in the right direction
- 2. locate standoffs
- 3. install standoffs, if necessary
- 4. align and install I/O plate
- 5. lower into place
- 6. screw in standoffs to secure motherboard

5. **What six items need to be compatible when** _**replacing**_ **a motherboard:**
- power supply
- CPU
- PSU
- Adapter cards
- case size
- heat sink
- RAM
- Chipset
- bus size and speed

6. **When building a computer, you should choose a motherboard that will meet (Blank).**
your current and future needs

7. **Describe the Intel and AMD CPU socket naming schemes.**
Intel is LGA, AMD is PGA, Intel has numbers, AMD has AM(#)

8. **The FSB is used to connect what components?**
- **Power Button:** to turn on the computer
- **Reset Button:** to refresh the system by turning it on and off
- **Power LED:** in dicates the the motherboard is receiving power
- **Drive Activity LEDs:**
- **System Speaker:**
- **Audio:**

9. **Briefly, describe why the speed of the processor is important:**
it sets the clock speed which is use to coordinate communication across the motherboard 

10. **What are the differences between Un-buffered and Buffered memory?**
un-buffered is limited but quick RAM used in laptops and personal desktops, buffered is RAM with a control chip that allows for indefinite scaling that is used for servers and archival storage

11. **List all three internal HDD form factor sizes and some acceptable uses of them.**
- **5.25 in.:** full-size desktops and servers
- **3.5 in":** desktop computers
- **2.5 in":** compact desktop and laptops

12. **What 6 factors should be considered when selecting a Hard Drive:**
- Internal or external
- HDD, SSD, or SSHD
- Hot-swappable
- Heat generation
- Noise generation
- Power requirements

13. **What optical drive has the most capabilities?**
BD-RE

14. **What Optical drive can only read CD and DVD?**
DVD-ROM

16. **Adapter cards can be used to expand the capabilities of a computer, what are some common uses of an expansion card and at least two factors should be considered when selecting them?**
x1, x4, x8, x16
I/O, NIC, sound, video, capture card, external storage
- What are the user’s current and future needs?
- Is there an open and compatible expansion slot available?
- What are the possible configuration options?

17. **A media Reader typically reads what 6 formats?**
SD, Micro SD, Mini SD, compact flash, external SSD/memory stick (flash drive), xD

18. **External Storage can be connected with:**
external USB, eSATA, thunderbolt

19. **What are the purposes of these system panel connectors? Where do they plug into**
- **Power Button:** to turn on the computer
- **Reset Button:** to refresh the system by turning it on and off
- **Power LED:** in dictates the the motherboard is receiving power
- **Drive Activity LEDs:** when the storage
- **System Speaker:** beeping for troubleshooting
- **Audio:** headphone jack, aux port

20. **Name and describe the acronym used to explain fire extinguisher safety.**
- P stands for pull the pin. 
- A stands for aim at the base of the fire Not at the flames
- S stands for squeeze the lever
- S stands for sweep the nozzle from side to side

21. **What interface would most commonly be used in HHD?**
SATA

22. **How do you replace old RAM?**


23. **What is the best safety precaution when operating on a computer?**
tape sharp edges, remove jewelry

# Advanced [[Hardware]]
1. What is the BIOS? (3.1.1.3)
Basic I/O System, a legacy pre-boot system that is used to configure the motherboard and its components

2. What is POST? How does it work with the BIOS? (3.1.1.2 – 3.1.1.3) 
Power On Self Test, the BIOS runs it, tests hardware components for compatibility and errors

3. How do you access the BIOS on your computer? 
it depends on the motherboard manufacturer, esc, f11, shift+enter

4. What are some common security features found in the BIOS/UEFI Systems? (3.1.2.2)
- encryption : TPM chip has the encryption key 
- secure boot : only by UEFI not BIOS
- lojack : used to locate, lock, delete a computer and its data remotely
- passwords : used to protect access level and the changes to the UEFI/BIOS

5. What is the CMOS? (3.1.1.3)
Complementary Metal Oxide Semiconductor, it is a dedicated memory chip that stores the setting of the BIOS

6. List the different Power Fluctuation Types: (3.2.2.1)
- blackout : complete loss of power
- brown out : temporary loss of power below 80%
- noise : variation in the input voltage
- surge : a nanoseconds long jump in power 
- spike : an increase in power over 100%

7. List the Power Protection Devices: (3.2.2.2)
Uninterruptable Power Supply (UPS) - small battery, acts as a buffer between the input power and the computer components, more expensive
Standby Power Supply (SPS) - large battery, used as a backup generator, requires a manual turn on, less expensive

8. Name the two CPU Instruction Sets and how they differ. (3.3.1.1)
Restricted/Complex Instruction Set Computer - restricted is fast and used for smaller instruction sets, complex is for larger and slower instruction sets in larger computers

9. Describe the difference between an integrated GPU and a dedicated GPU (3.3.1.3)
an integrated GPU is built into the CPU, the dedicated GPU is attached to the motherboard using a PCI

10. What is RAID? What are the different levels of RAID? How does RAID store data?(3.3.2.2 – 3.3.2.3)
Redundant Array of Independent Disks is a way to store data across several drives, providing reliability, capacity, economy, or performance depending on the level
RAID 0 - striping, performance, economy, and capacity
RAID 1 - mirroring, reliability and economy
RAID 5 - parity, reliability and capacity
RAID 6 - double parity, reliability, capacity, and performance
RAID 10 - mirroring and striping, reliability, capacity, or performance

11. List and describe the legacy ports: (3.3.3.1)
DVI : has analogue and digital variants
VGA : analogue only, now limited use 
Serial : used for peripherals
Parallel : used most commonly used for old printer
Game : controllers
Ps/2 : key board and mouse
Audio : analogue audio with separate left and right channel connectors

12. Which USB Connection Type is a proprietary connection? Who is the proprietary manufacturer? (3.3.3.3)
lightning connector made by apple

13.  What is a Thick Client? What is a Thin Client? (3.4.2.6)
thick client : self reliant, regular desktop PC, used for personal computing and small networks
thin client : handles basic I/O, processing and memory is offloaded to a network server, used for remote work and call centers that need to scale large networks

14. List the required components for the 5 specialized computer systems described: (3.4.2.1 – 3.4.2.5)

| **Specialized System**              | **Powerful Processor** | **Maximum RAM** | **High End Audio Card** | **High End Video Card** | **Large/Fast HDD** | **Other** |
| ----------------------------------- | ---------------------- | --------------- | ----------------------- | ----------------------- | ------------------ | --------- |
| Thick Clients                       |                        |                 |                         |                         |                    |           |
| Thin Clients                        |                        |                 |                         |                         |                    | x         |
| CAx Workstation                     | x                      | x               | x                       | x                       |                    |           |
| Audio and Video Editing Workstation |                        |                 | x                       | x                       | x                  |           |
| Virtualization Workstation          | x                      | x               |                         |                         |                    |           |
| Gaming PCs                          | x                      |                 | x                       | x                       | x                  | x         |

15. Define NAS. What is it? What does it do? (3.4.2.7)
Network Attached Storage, external storage that links directly to the network allowing the sharing of files

16. What is an SDS? What is the purpose of it? (3.5.1.2)
Safety Data Sheet, used to inform users on how to dispose of computer hardware, and peripherals

17. Describe the dangers of these technology products, and the proper disposal methods for them.

| **Item**                           | **Dangers**                      | **Disposal Methods**        |
| ---------------------------------- | -------------------------------- | --------------------------- |
| Batteries                          | mercury, rare earth metals       | recycling                   |
| Monitors                           | lead, rare earth metals          | recycling                   |
| Toner Kits, Cartridges, Developers | refill cartages my void warranty | recycling                   |
| Chemical Solvents, Aerosol Cans    | water contamination              | local sanitation            |
| Cell Phones, Tablets               | rare earth metals                | check with local regulators |

CPU replacement
- chipset
- power supply 
- socket

Motherboard replacement
- case
- power supply
- compatibility 

Computer upgrade
- old software
- damage
- user requirement

virtualization
- RAM
- CPU cores
- storage

# Preventive Maintenance and [[Troubleshooting]]
1. What are the benefits of preventative maintenance?
improves equipment life and stability, reduces wear and tear, and computer down time, prevents hardware and software problems, increases data protection, saves money via repair costs, and the number of equipment failures.  

2. In your own words, what is troubleshooting?
the process of using observation, testing, and documentation in conjunction with each other to problem solve

3. Give 3 examples each of typical hardware and software maintenance in the chart below: 

| Hardware maintenance                                    | Software maintenance                                                             |
| ------------------------------------------------------- | -------------------------------------------------------------------------------- |
| cleaning dust, checking for damage, and securing cables | updating drivers, software, or security, remove unwanted files, scan for viruses |
|                                                         |                                                                                  |

4. List Cisco’s 6 steps of troubleshooting.  
	1. Identify the problem
	2. Establish a theory of probable cause
	3. Test the theory
	4. Establish a plan of action
	5. Verify the solution and functionality
	6. Document findings and educate user

5. What task should typically be performed before a technician begins repairing a computer?
backing up all data, not practical in small repairs but critical with sensitive information and intensive repairs

6. In what scenario would a technician want to use more closed than open-ended questions?
when a technician needs direct answers, and a quick turn over for information

7. What information does the Event Viewer give that you can’t get from the Device Manager in Windows?
the detailing of the errors within the computer, the device manager only displays the status of

8. What would a technician do before escalating the problem to a technician with more experience?
gather and document the tests they have tried

9. List 4 ways to verify full system functionality.
- reboot the computer and test applications
- verify network connections
- ensure peripherals are functioning
- ensure there are no error messages

10. What are the ideal temperature and humidity ranges for computers? 
45-90 degrees fahrenheit, and 10-80% humidity  

11. What should a technician document during the troubleshooting process?
the questions asked to the user, the steps they took to solve the problem, and the components and tools used in the repair

12. Write a preventative maintenance plan for the laptops in this classroom at the end of each semester. Give your reason for including each task. 
- check the event viewer, task manager, and anti-virus : ensure there is not software problems
- test all ports and their functionality : ensure peripherals and cables can be used
- check all UEFI settings : ensure that there are no errors or problems with the pre-boot system settings
- check battery, motherboard and cables : ensure the functionality of critical hardware
- clean internal and external components : remove dust and debris to maintain hardware


13. led light for the storage is on and a program is running slow, what should you do?
install more RAM, hard drive is being use as 

14. workstation locks up after 5 min
overheating

15. 4 year old computer has slow booting because of BIOS rediscovery
change the CMOS battery

16. before troubleshooting what is the first thing that needs to be done?
back up data

17. where can the tech find the most recent errors in the computer system
the event viewer

18. what is the solution to a problem that requires knowledge a tech does not have
document your testing and attach it to the ticket and escalate 

19. what do you do to figure out what direction the fans spin?
watch it when it is plugged in

the first and last steps have to do with interacting with the customer(s)

# [[Networks]]
1. How are hosts and intermediary devices different? What are 3 types of intermediary devices a tech would find on most modern networks?
Hosts are the leaves on the "tree" of a network, and the intermediary devices are the branches.
- Router : 
- Modem : 
- Switch : 

2. Give an example of the following network topologies:
- PAN: an area network that spans a person personal space such as Bluetooth network connections
- WMN: a wireless network that spans a building used for internet connection
- MAN: an area network that covers a multiple location that are next to one another such as sections of a city, town, or campus
- LAN: a wired area network that covers a set area like the inside of a office or home, often wifi
- VPN: a wide area network that provides an encryption, masks IP addresses
 
3. How do switches direct traffic differently than routers?
they do not separate the network, switches use a MAC address, routers use IP addresses

4. What are the different advantages of the 2 Transport Layer Protocols? Give a scenario for each.
TCP is use for things like HTTP/S used for web applications, UTP is used for real time applications like VoIP

5. How do TCP/UDP use port numbers to keep up with applications conversations when sending data over a network?
use source ports which allow multiple conversations with the network to happen at the same time by dynamically generating one for each application
use static destination ports for reliability

6. What are three common remote access protocols used by TCP/UDP? What are the default ports for these protocols? 
SSH 22
Telnet 23
RDP 3389

7. What group of standards specify speeds and other capacities for WLANs? Which organization is responsible for these? 
802.11a/b/c/g/n/ac/ax
institute of electrical and electronic engineers

8. Give an example of how each close-proximity connection standard below is used. 
- RFID : 
- Zigbee : 
- Z-wave :
- NFC : 

9. What is the purpose of AFH?
Adaptive Frequency Hopping - reduces interference in a PAN like bluetooth by allowing devices to switch their frequency of communication

10. DHCP and DNS do different things. Explain the role of each in accessing a simple webpage.
DHCP - dynamically assigns an IP address from a pool
DNS - translates a webpage URL to an IP address for the client to requestion information from

11. What are some secure protocols that can be used to access data on file server? 
20/21 FTP 
22 SFTP
SCP - secure copy protocol
445 - SMB
69 - TFTP

12. Which two email protocols allow hosts to retrieve email from a server and what are their secure & unsecure ports?
110 unsecure/995 secure - POP3
143 unsecure/993 secure - IMAP 

13. In what 3 ways does the syslog protocol help with the management of multiple networking devices?
- gather logging information for monitoring and troubleshooting
- select the type of logging information that is captured
- specify the destinations of captured syslog messages

14. How would you describe the difference between a repeater and a bridge?
a bridge segments a network and logs the devices in that segment, while a repeater simply amplifies the signals that goes through it

15. Every NIC has a unique MAC. Describe the role the MAC address plays in networks. 
keeps track of where the NIC is on the network, 

16. Switches connect networking devices. Routers connect to area networks.

17. What three network devices are contained in most home or small business integrated routers?
Modem 
Access point/Internal router
Firewall

18. How do IPS and IDS handle threats to a network differently? What does the term “inline” mean?
Intrusion Prevention/Detection System, detection monitors traffic while, prevention polices the traffic, inline mean that all traffic is going through the system for processing

19.  What are some examples of embedded systems? When are embedded devices also considered “legacy?”
SCADA - 
IoT - 

20. How is the purpose of a patch panel different than that of a switch?
a patch panel is a static switch

21. What sorts of devices might require PoE equipment and what IEEE standard is used?
802.3 
laptop screen, VoIP phones, 

22. What tool must I use when attaching RJ-45 connectors to Ethernet cables or RJ-11 to telephone cables?
crimper

23. Why has UTP cable replaced coax for cabling LANs? What are the pros and cons of using STP over UTP?
cost, convenience and troubleshooting
reliability

24. CAT5e and CAT6 both provide speeds up to .  What is different about CAT6? 
more twists and higher transfer rates

25. The two modes of fiber media discussed in the chapter differ primarily in distance covered. Which mode is more popular in LANs and why? 
SC connector - push/pull mechanism 

26. What is a proxy server?
act as storage or a cache for webpages, allowed to act on behalf of a computer to reduce the amount of links between the client and the server

# [[Network Troubleshooting]]
1. What is the purpose of MAC addresses? What are the two parts that make up a MAC?
to identify network devices across a network despite IP address changes,
the vendor the OSI ID or the vendor

2. How is IPv6 different from IPv4? 
IPv4 - 32 bit, four octets, decimal, implemented in the 1980s, no compression, link local is only necessary when there is no IP address assigned
IPv6 - 128 bit, 16 octets, hexadecimal, implemented in 2002, compression rules, link local address is always required

3. When would a technician use a static IP? What network service makes dynamic IP addressing possible?
security, or setting up a small home or office network
DHCP - dynamic host configuration protocol, 

4. What is a Link-Local Address and when would it be used? What is the default Windows IPv4 link-local address name and range?
an addressing service that allows a device to communicate with its local network despite not being assigned a static or dynamic IP address
range from 169.254.0.0/.255.255

5. How do networks use ICMP? What popular command relies on ICMP to function?
Internet Control Message Protocol tests if computers on a network are able to communicate
/ping 

6. After installing a brand-new SOHO router, what steps should a technician take to access the router’s configuration page?
- View the VLAN defaults
- Change the network mode
- Configure SSID
- Configure the channel frequency
- Configure security
- Configure passphrase

7. What is the purpose of a WMN?
to wirelessly access the internet in a local area

8. What is QoS? Why would you configure QoS on a Wireless Router?
Quality of Service, used to prioritize different services to provide 

9. What is a Screened Subnet (DMZ)?
a public part of a local private network used to interact with untrusted networks while protecting the private network 

10. How does port forwarding differ from port triggering? 
port forwarding uses static IP addresses, to manage services provided by ports, a gate within a firewall that manages inbound and outbound port traffic, is a static standard
port triggering is a service that manages the outbound traffic on a range of ports to a single inbound port, is a dynamic 

11. A technician runs the ipconfig command and notices that the computer is displaying an IP address of 169.254.254.2. What are 3 probable causes and possible solutions for this issue? 
- link-local address is assigned -> manually assign static IP or connect to a DHCP server
- router is powered off -> ensure its is properly connected and powered on 
- NIC is damaged -> replace NIC

12. What are some reasons a wireless network may run slowly or users may constantly lose connectivity?
- SSID is public
- number of devices is configured to be lower than the amount present
- channels are not set at 1, 6, and 11 so there is interference 

13. By default, what does a DHCP server automatically assign?
IP address
subnet mask
lease time

14. What is one use for pinging the loopback address?
distinguishing between problems on the host device verses the network

15. What are the rules for compressing an IPv6 address?
- omitting leading zeros
- condense consecutive zero segments with (::)
	- only condense once 

16. What is the significance of channels 1, 6, 11?
the frequency ranges do not overlap 

17. For the following IPv4 address, identify the class, if the address is public or private, and circle the network portion of the address:

| IP address     | Class? | Public or Private? |
| -------------- | ------ | ------------------ |
| 192.168.0.2    | C      | Priv               |
| 10.4.45.127    | A      | Priv               |
| 172.33.33.33   | B      | Priv               |
| 192.166.34.54  | C      | Pub                |
| 172.23.23.10   | B      | Priv               |
| 180.15.0.5     | B      | Pub                |
| 120.8.8.8      | A      | Pub                |
| 13.225.224.47  | A      | Priv               |
| 54.191.191.127 | A      | Pub                |
| 169.254.65.65  | C      | Priv               |

# [[Mobile Devices]]
1. How does a Laptop Motherboard differ from a Desktop Motherboard? 
laptop - proprietary, small for factor, internal PCI/e, SODIMM
desktop - standard sizes, 

2. Define CRUs and describe some examples that would be found in laptops.
Customer Replaceable Unit, battery, optical drives, wireless card, RAM

3. Describe the biggest differences between the following devices?
Laptop - runs desktop level OS, physical keyboard, bluetooth
Tablet - digital key board, high resolution display, touchscreen, mobile OS, no cellular on low end devices
E-Reader - black and white screen, simple OS, limited access to wireless networks, bluetooth
Smartwatch - notifications, simple OS, bluetooth, microprocessor
Fitness Tracker - heartrate, oxygen level, calories burned, bluetooth
Smartphone - SIM card, cellular, mobile OS, bluetooth, GPS, tethering/hotspot

4. What are the three common laptop display types? 
LCD - Liquid Crystal Display
	TN Twisted Nematic - fast refresh, narrow FOV, less color accuracy
	ISP - In-Plane Switching - low refresh, wide FOV, more color accuracy
	VA - Vertical Alignment - better contrast, narrow FOV, ghosting, best 
LED -
OLED -

5. How can you typically distinguish between a port replicator and a docking station?  
docking station - proprietary connection to the laptop, charging capability
port replicator - standardized ports, no charging

6. What are some laptop display features?
viewing angle, refresh rate, brightness, contrast, color accuracy, detachability, cut-off switch, and touch capability

7. How do an inverter and backlight work together? 
the inverter supplies the backlight with power, converts DC to AC, 

8. Summarize the key features of each ACPI power state.
S0 - computer is fully powered
S1 -  CPU and RAM are powered but unused devices are powered off
S2 - CPU is off, RAM is being refreshed, "save to RAM", "suspend mode"
S3 - RAM is put into low refresh rate, "hibernate"
S4 - RAM is turned off, memory is copied to hard drive, "save to disk"
S6 - no power

the refresh rate of the RAM, power to the components, 
 
9. What is the difference between tethering and a hotspot?
tethering can be done through a cable, hotspots are only wireless

10. What type of data typically gets synchronized?
- passwords
- contacts
- documents, music, videos, photo, e-books
- email
- applications
- location data
- bookmarks
- calendar data
- social media

11. What is Bluetooth pairing?
 a short range wireless, radio connection between two devices, through a PIN, to initiate the connection, used to share resources or transfer data

12. What is a probable cause if your mobile device is unresponsive? What is a possible solution?
RAM needs to be cleared - soft or hard reset
apps have been taking up resources - close background apps

13. Team up with a partner who has a different type of phone than you e.g. If you have an android, find someone with an iPhone. List 4 hardware pieces that are different and 2 that are the same.  Differences can be anything, from the number of buttons, to size, to design. 
iphone - home button, lightning, audio jack
android - 
same - touch screen, power and volume 

laptop hdd sizes 1.8" and 2.5"
AFH - Active Frequency Hopping
ACPI - Advance configuration and power interface
bluetooth operates at 4 and 15 GHz
embedded multi media card - eMMD

# [[Printers]]
1. How are quality, speed, and reliability of printers measured? 
quality - dot per inch
speed - pages per minute
reliability - Mean Time Between Failures (MTBF)

2. What are 6 common interfaces for printers? 
ethernet, serial, parallel, USB

3. List the advantages and disadvantages for each printer type: 

| Type    | Pros                                                                                          | Cons                                                                         |
| ------- | --------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------- |
| Inkjet  | low cost, high resolution                                                                     | nozzles prone to clog, ink cartrages are expensive                           |
| Laser   | low cost per page, high PPM, print comes out dry                                              | high cost, heavy, toner cartridges are expensive                             |
| Impact  | hight MTBF, quiet, no ink or toner                                                            | thermal paper is expensive, images degrade over time and can not be in color |
| Thermal | ink ribbons are less expensive, use regular paper or continuous feed, can print cardon copies | loud, low resolution and limited color                                       |


4. Name 5 parts of a 3D Printer:
Hot-end Nozzle
Printing bed 
Axis
Filament 
Feeder

5. Describe the 7 steps in the printing process of a laser printer. 
1:Processing - convert data to a printable form
2:Charging - previous image is removed and imaging drum is charged
3:Exposing - 
4:Developing - 
5:Transferring - 
6:Fusing - 
7:Cleaning - 

6. What is virtual printing? What is cloud printing? 
Virtual - saves data to a file 
Cloud - printing on a network, often a LAN

7. Describe the differences between PostScript and PCL.
used in virtual printing, Post Script was developed by Adobe is higher quality, and PCL was developed by HP and is faster

8. List the 3 types of print servers and the purpose of using a print server. 
Software - hosted by a computer on a network, printer is unavailable when the host is off and uses host resources, Mac OS has a free print server software called Bonjour
Hardware - a simple device that connects to the [[LAN]] and gives printer access to the whole network, usually only a single printer
Dedicated - corporate networks, uses a switch and dedicated computer to operate many printers in parallel

1. What are the global settings? 
the default setting when a printer is shared, these include
configuration options
- paper type
- print quality
- color printing
- black and white
media types
paper output

3. You have been asked to draft a preventative maintenance policy for the printers in a department. What are some of the key ideas you would want to make sure to include? 
Inkjet - printer software utility, 
Laser - use High Efficiency Particulate Air (HEPA)  vacuum cleaner, and maintenance kit
Thermal - cotton swab for damped with isopropyl alcohol
Impact - replace ribbon or print head
3D - consult manual 

4. What is an MFD and what distinguishes it from a standard printer or copier?
Multi-Function Device - it can scan, copy, print, and fax all in one device

5. What is the purpose of a print spooler?
the software that manages the print queue and the print resources

6. A customer calls and says, "I can't connect to the network printer." What are 3 questions you could ask the customer to begin the troubleshooting process?
1:What where you doing when you identified the problem?
2:Can you print a test page?
3:Have you made any software changes recently?
4:Are you able to connect to the network on another device?
5:Can you reproduce the problem?
6:Is the printer connected to the network and powered on?

Remove the orange plastic strips when setting up a printer
resetting the page counter after preventative maintenance 

# [[Virtualization and Cloud Computing]]
1. How are virtualization and cloud computing different? 
virtualization - simulates an OS locally, and is reliant on 
cloud computing - provides access to computational resources via a network connection

2. What is a limiting factor to how many VMs that can run simultaneously? 
the CPU cores, and RAM

3. List three reasons traditional server deployment is being phased out. 
server swamp, wasted resources and single point of failure

4. What resources does a hypervisor allow a user to manipulate via Virtual Machines (VMs)? 
computational resources

5. Name 4 advantages of server virtualization:


6. Define the following: 
Host computer -
Host operating system (host OS) -
Guest operating system (guest OS) -

7. What is the difference between a Type 1 and Type 2 Hypervisors?
Type 1: 
Type 2: 

8. Virtual Machines require a powerful hardware configuration. What are some system requirements to keep in mind when configuring? 


9. List 5 ways we use the cloud. 


10. Briefly describe and provide an example of the following types of cloud services? 
SaaS (Software as a Service): payroll system
PaaS (Platform as a Service):  
IaaS (Infrastructure as a Service):

11. Describe the 4 Cloud Models: 
Public: 
Private: 
Community:
Hybrid:


12. What is the purpose of Software Defined Networking (SDN)? 

# [[Microsoft Windows]]
1.) Define the following terms:
Multi-user - the feature of a computer to have multiple different accounts assigned to different people, allows each user to have a separate access to files and applications
Multitasking - the ability for a computer to run several applications at the same time, all computers in the modern day are capable of multitasking
Multiprocessing - an operating system that can support multiple CPU cores
Multithreading - allows a processor to compute multiple parts of a program at once, such as tabs on a computer

2.) What are the basic functions of an operating system?
to allow the user to interface with a computer and its hardware and software components 

3.) What hardware may be upgraded to meet OS minimum requirements?
RAM, CPU, HDD/SSD, video card, motherboard

4.) What are the minimum system requirements for Windows 10?
Processor: 1GHz or faster
RAM: 1GB for 32, 2GB for 64
Drive space: 16GB for 32, 20GB for 64
Graphics card: DriectX 9 up, WDDM 1.0 driver and up
Display: 800x600
Internet connection: yes
Trusted Platform Module: none

5.) What are the minimum system requirements for Windows 11?
Processor: 1GHz or faster, 2 or more cores
RAM: 4GB
Drive space: 64GB
Graphics card: DirectX 12 up, WDDM 2.0 driver and up
Display: HD (720p)
Internet connection: yes
Trusted Platform Module: 2.0

6.) Which versions of Windows can be upgraded to Windows 10? For versions of Windows that cannot be upgraded to Windows 10, how can the OS be installed?
Windows 7 and up can be upgraded to Windows 11, for older versions it requires a clean install

7.) What differentiates a 32-bit architecture from a 64-bit architecture?
its determines the amount of data a CPU can handle in the register, and the amount of bits processed in parallel

8.) List 3 migration tools available for Windows:
PC-Mover Express, Windows Easy Transfer, and User State Migration Tool

9.) In what situations might you need to perform a clean installation of an OS?
when the data on a computer has become corrupted, the OS has been infected with a virus or other malware, or the OS is too old to be updated or upgraded to the preferred OS

10.) What are the two most common types of data storage devices used today?
[[Hard Drive Disk|HDD]], and [[Solid State Drive|SSD]]

11.) What is a master boot record (MBR)? List defining features.
a 517 byte long table used in conjunction with the BIOS to configure boot order, sets the requirements of the basic disk of four primary partitions, and the behavior of the extended partitions and logical drives

12.) What is a GUID partition table? List defining features
a Global Unique IDentifier table is a UEFI BIOS only partition table, support larger drives

13.) What is a primary partition?
a set of 4 partition used in a master boot record that is used to store the OS and drivers

14.) What is an active partition?
The partition that the computer boots from

15.) What is an extended partition?
if the computer needs more than 4 partitions, one of the primary partitions can be turned into an extended partition that can be further divided into smaller partitions

16.) What is a basic disk? What is a dynamic disk?
basic disk : the default disk partitioning setup, uses primary, extended and logical drives to configure partitions, used either MBR or GPT
dynamic disk : an extended version of the basic disk that allows the table to be set across multiple disks, can be changed at any time and can automatically use up free space regardless if it is contiguous, partitions are unable to be shrunk without repartitioning

17.) List 5 common file systems.
NTFS : new technology file system
FAT32 : file allocation table 32-bit
Ext3/4 : third/fourth extended file system
exFAT : extensible file allocation table
APFS : apple file system

18.) What differentiates a quick format from a full format? What tool is used for this in Windows?
the quick format removes files but does not check the integrity of the disk but is faster, it is not an option in windows 7 and 8.1
full format both removed files and checks the integrity of the disk for failed sectors but takes more time than the quick boot, this is required for new hard drives

19.) What is a boot manager? Which ones are commonly used by Linux and macOS?
a boot manager puts the devices a computer can boot from in a hierarchy, can be configured using the BIOS, or the UEFI. GRUB, GNU gRand Unified Bootloader, is commonly used by Linux and mac

20.) What is Single-Sign On (SSO) authentication?
allows a user to log in once on an OS to access all system resources including user accounts, usually used for single user computers

21.) What are the differences between Administrator and Standard user accounts?
the admin has full access to all of the OSs systems, while the standard user is unable to install programs

22.) What can you do with Microsoft’s System Preparation (SysPrep) tool? How do you run it?
can be a windows solution for installing an OS on multiple computers via disk cloning

23.) What is remote network installation?
the installation of an OS over a network connection, often to multiple computers, a server has a copy of the OS and each computer is installed with an NIC that can load a PXE, and the OS is downloaded onto the computer and booted for configuration

24.) What is the Preboot eXecution Environment?
it is a boot environment that allows the installation of an OS over a network connection

25.) What is an unattended installation?
allows an OS to self configure based in an answer file stored on the drive, this contains all of the necessary answers to the options given when setting up an OS

26.) How do you access Windows Advanced Boot Options and what are four common startup options?
press f8 during start-up
- safe mode : used for troubleshooting on-device and start up issues, limited functionality as most drivers are not loaded
- safe mode with networking : allows for network connection and support in safe mode
- safe mode with cmd prompt : safe mode that loads the command prompt instead of the GUI, should only be used by users who are proficient at cmd prompt navigation and features
- last know good config : loads the config setting of the last instance of the Windows OS in the registry 

27.) How do you access startup modes in Windows 8 and 10?
hold the SHIFT key on boot and navigate to desired startup mode

28.) The Windows 10 Start menu consists of three main parts. What are the locations and functions of each part?
shortcut ribbon - includes the power button and common libraries
application list - lists all installed applications
app tiles - groups apps together by type 

29.) What is the Taskbar and where is it typically located?
a ribbon on the bottom of the screen that give the user access to important features on the OS, such as applications, tools, and programs

30.) What is the Task Manager and how can you access it?
an application that displays statistics on the OS, such as a table of running applications, can be used terminate applications so they are no longer using system resources

31.) What does the “Run as Administrator” option do?
allows an admin to access the features of an admin account while another user is logged in

32.) In what folder are 32-bit programs installed in a 64-bit system?
the Program (x86) directory

33.) What are the categories found in Control Panel?
- User and Account Control
- Network and Internet 
- Display Settings
- Power and System
- Hardware and Sound
- Clock Region and Language
- Programs and Features

34.) What is User Account Control (UAC)?
a program that informs the user when an application is making a change on the computer, can be configured to various levels of change on the OS

35.) What are the 4 most common file attributes in Windows?
.exe
.py
.js
.docx

36.) What is the purpose of Sync Center?
to synchronize files between different computers across a network, is now a mostly deprecated feature of older windows systems

37.) What tabs are part of Internet Options?
General, Security, Privacy, Content, Connections, Programs, and Advanced

38.) What is Windows ReadyBoost? How is it enabled?
A windows feature that allows a user to use a flash drive as a temporary RAM, right clicking it in the file explorer

39.) Device Manager allows you to perform what four functions?
downloading and updating drivers, disabling, or uninstalling a device

40.) Where can you find Event Viewer and what does it do?
the event viewer is an application that keeps track of all of the executed tasks on the OS including user inputs and outputs
 
41.) What is System Configuration (MSCONFIG)?
manages the boot order and devices, system services, and the startup preferences

42.) What is the Windows Registry? How is it used? How can you access Registry Editor?
a database of low level settings that the OS and applications, it allows a user to configure these settings 

43.) What do the following Windows Registry Keys do?
HKKEY_LOCAL_MACHINE – config info for the whole machine, abbreviated as HKLM
HKEY_CURRENT_USER – config info for the current user
HKEY_CLASSES_ROOT – subkey of HKLM, config info for the windows explorer
HKEY_CURRENT_CONFIG – config info on the hardware profile

44.) What does “mounting a drive” refer to? What is a common file type used in drive mounting?


45.) What are the five methods of installation?
clean installation, upgrade installation, network installation, custom installation, and unattended installation

46.) What is Compatibility Mode?
A windows feature that allows a program that can only be executed in a previous version of windows to be run on a more recent version

47.) Define each listed Command Prompt command:
md – create a directory at specified location
rd – deleting a selected directory
move – move file to specified directory
del – delete selected file
copy – copy selected file

48.) Define each listed Task operations command:
tasklist – lists all currently running applications
taskkill – terminates a running application
dism – used to work with system images before they are deployed
sfc – repairs system files
shutdown – powers off a local or remote computer

49.) Define each listed command:
chkdsk – check a disk for errors or bad sectors
format – creating a disk partition
gpupdate – updates the group policy
net use – network configuration

50.) Define each run line utility command:
EXPLORER – opens the file explorer
MMC – 
MSINFO32 – opens the system information
MSTSC – opens the remote desktop connection

51.) What are the local file sharing mechanisms used by each OS vendor:


52.) What does each ipconfig option do?
/all - brings up all of the IP information of the host computer
/release - removes the IP of the computer
/renew - reassigns 
/displaydns - brings up the DNS information such as the IP of the DNS server

53.) List and define the two network profiles in Windows 10:
public and private

54.) What do the following network connectivity commands do?
ping – sends 32 bytes over the network to a specified IP
tracert – 
nslookup – 

55.) How do RADIUS and TACACS+ operate?
They are both AAA servers

56.) Under what situations should a technician create a restore point with System restore?
before changing the OS in any way, such as updating 

57.) You get an “Invalid Boot Disk” error. What setting loads the correct drive and where is it?


58.) What RAID levels are supported by Windows 10?
0,1,5

59.) What is the difference between GP update and GP result
gpupdate updates the group policy
gpresult brings up the info for the group policy

60.) Define the netstat command and its utility.
displays all network connections on the OS

61.) List and define file attributes
R - 
A - admin
S - system
H

# [[Operating System]]
1.) Which mobile OS(s) are open source? Which are closed source?
Open source - 
Closed source - 

2.) Which mobile OS allows for the direct installation of apps from third party websites? What is this process called? What is the proper storefront for this mobile OS?
Apple, side loading, App Store

3.) Apple uses what app distribution model for their Apple iOS mobile devices? What are the benefits?
 walled garden, allows for increased security, and quality of applications at the cost of higher priced apps and a smaller developer base

4.) Where is the system bar displayed in Android OS? What buttons does it contain?
the bottom of the screen, contains the Back, Home, and Recent Applications buttons

5.) How do you access the notification area on Android devices? How do you dismiss a notification?
by swiping down from the top of the screen, swiping left or right on the notification

6.) What three items are present on the Android interface and are missing from the iOS interface?
no nav icons, app shortcuts and widgets

7.) What differentiates iOS app icons from Android OS app icons?
Android apps icons are shortcuts while the iOS icon are not

8.) What iOS search field shows suggestions from many sources including your installed apps, Settings, the internet, iTunes, App Store, and nearby locations? How do you access it?
Spotlight, swiping down from the top of the screen

9.) How do you access iOS voice control? What is the name of the advanced iOS voice control software?
press and hold the home button on older iphones, and the increase volume button on new iphones

10.) What issues are resolved by adjusting the brightness level of a mobile device?
visibility

11.) What is Wi-Fi calling? What are the advantages of it?
using cellular services over a Wi-Fi connection

12.) How can a mobile device running iOS be accessed if the passcode is forgotten?
using a system restore via a backup on iTunes or iCloud

13.) How can you unlock an Android device after it has been locked due to passcode failure?
entering the gmail information used to set up the device

14.) What is a remote backup? What are the cloud services for each OS vendor?
a copy of all information on an computer that is stored on a file server on the cloud
android - google sync
apple - iTunes, or iCloud
microsoft - onedrive

15.) What is a locator app used for? What are its data sources?
 to find a device if it is misplaced or stolen, uses GPS, cellular services, and network connections to locate the device

16.) What are the names of iOS and Android remote lock features? What are the remote wipe names?
iOS - lost mode, erase phone
Android - lock, erase

17.) What is the Primary Rate ISDN (PRI)?
the rate of data transfer between a device and the cellular network, both need to be synced in order for data to be transferred

18.) What are Rooting and Jailbreaking?
respectively, the android and apple versions of giving the user elevated permissions of the OS

19.) Which file systems are most used on Linux operating systems? Describe their features.
ext3/4, they are the 64 bit versions of the FAT32 system, it support larger partitions with larger files while also improving performance

20.) What is NetBoot? What OS supports it?
a PXE like service that perform OS installation over a network, used by macOS

21.) What file systems are used by Apple Mac workstations and macOS High Sierra and later? Which one supports native file encryption?
APFS or Apple File System, and HS+ or High Sierra Plus, which supports encryption

22.) What is Force Quit in macOS? How do you access it?
a way to terminate applications, accessed by pressing the quit button in the Activity Monitor

23.) What does the crontab command do? What are the six columns?
displays the current scheduled commands, each columns is a detail about the time, such as the month, day, hour and second

24.) What are signature files? How are they used?
sections of code used in malware, it is used by anti-malware applications to identify if the system has been infected

25.) What is the kernel? How can a user interact with the kernel?
the core of the operating system that manages the resources, and firmware of the computer, it can be interacted with through the shell via commands

26.) Define the following Linux commands:
ls – lists the items in the current directory
cp – the copy function, used to copy directories or files
grep – search command, allows the user to search files for text
man – the manual, allows the user to read on the function of a command

27.) Define what users have what permissions for the following file permissions: -rwx--x-w-
admin - all access
standard - execute
guest - write

28.) Provide the permission octal for the related account permissions:
-rw-r--r--	     A.) 344
-rwxrwxrwx	      A.) 377
-r--rw--wx	      A.) 46

29.) Define the following administrative commands:
ps – displays all of the currently running applications
kill – terminate application
iwconfig – manage and configure network interfaces
chmod – modify user permissions

30.) Define the following commands involving root access:
sudo – super user do, allows an admin to use their privileges in while another user is logged in
chown – changes the ownership of a directory
apt-get – download an application from a server
shutdown – powers off the computer

31.) Linux or macOS freezes on startup and exhibits kernel panic with a stop screen. What are the possible causes?
the boot loader or driver on the system has become corrupted
# [[Security]]
1.) Define “malware” and give two examples of this type of computer problem. 
malicious software : a program designed to attack an end user or computer
- files are encrypted and a pop up demand a payment in bitcoin
- computer slows with no visible applications in the cache

2.) Banners and ads are examples of what type of computer nuisance?
popups or notificaitons

3.) How does a computer “worm” work to harm a computer?
self replicates

4.) Which type of software is downloaded onto the computer of a user without the knowledge of the user and causes information about various products to be displayed on the user's monitor?
adware

5.) What kind of attack is involved with “phishing?”
the impersonation of a trusted sources such as a company or staff to get an end user to submit information to the attacker

6.) What is involved in a DDoS attack on a network? 
a network of malware on multiple computers targeting a server or network resources

7.) Give two examples of ways to prevent social engineering attacks.
staff training, and personal authentication methods

8.) How can you best protect yourself and confidential information when getting rid of old hard drives? 
using a low level format, a degaussing wand, incinerator or shredder, to dispose of the data on the drive

9.) How are “acceptable use” policies different from “remote access” policies? 
AUP : how company resources are able to be used an congfigured
remote access : how an end user is able to connect to the network and the security methods put in place

10.) What are the 5 types of NTFS file permissions? 
read, write, read and execute, modify and full control 

11.) What is required to enable and use BitLocker? 
Windows Pro or better

12.) What do antivirus and antimalware programs use to identify and classify viruses on a machine? 
signatures - known sections of malware code that an antimalware program can use to identify malware on a system

13.) What three separate levels of password protection can be used to protect a computer?
text, image, and graphical

14.) What is the difference between port forwarding and port triggering? 
port forwarding is making an indefinite exception for a service, and port triggering is a temporary port forward that has a times leased

15.) How do software and hardware firewalls impact computers differently?
software firewalls take up computational resources, and hardware firewalls take up network resources

16.) What is the most important step to take before updating your computer system? 
that you have a back up of important data

27.) Explain the principle of least privilege. 
each end user gets the least needed privileges to accomplish their work

28.) What is a consideration that should be taken when securing laptops rather than PC towers?
a cable lock so that it cannot be stolen

29.) \______________________ encryption requires both sides of an encrypted conversation to use an encryption key to be able to encode and decode the data. The sender and receiver must use identical keys. 
symmetric

30.) \______________________ encryption uses public and private keys. 
asymmetric 

31.) A(n) \___________ creates a secure tunnel through the Internet.
a VPN
# [[IT Professional]]
1.) What are some ways to establish a good relationship with the customer at the beginning of the call?
introduce yourself, and exchange names

2.) Give an example of an open ended and a close ended question to the following problems:
I can't access the email client.
Open: when was the last time it was working?
Closed: have you checked your wifi connection

3.) I don't remember my password.
Open: when was the last time you used it?
Closed: did you write it down anywhere?

4.) My computer won't turn on.
Open: what have you done to check the power?
Closed: have you checked if it is plugged in?

5.) Why is it important to follow up with a customer after a problem has been solved?
to educate and reassure the customer 

6.) Which 3 of the professional behaviors on the list in 14.1.3.1 do YOU need to practice or work on most? 
interruption by accident and not using jargon

7.) Which type of customer would be hardest for you to work with? Why? What can you do to provide good customer service? 
the rude or angry customer, i have a hard time taking criticism 

8.) Rephrase the technician responses below for the difficult customer type indicated:
“Remove the dongle from the machine before rebooting” for an Inexperienced Customer
- take out the device that you plugged in earlier be fore you turn the computer off and back on again.
“You messed up the DRM when you tried to copy your library” for an Angry Customer
- I am sorry that happened, from your description the Digital Rights Management was misconfigured when you copied the files, this is an easy fix
“Open Internet Explorer and click on the gear at the top right, then go to Manage Add-ons” for a Knowledgeable Customer
- go to the browser settings and navigate to Manage Add-ons and you should find the option there
“Just restart and then try whatever you were doing again” for a Rude Customer
- I think the best course of action is to start from the first step and make sure we are not missing a step

9.) Why is documentation important, and what are the four categories of documentation discussed? 
Documentation is used to preserve information about operational procedures
the four types of documentation are Policy, User, Project, and Operational 

10.) Why is change management important to a company? 
to ensure that upgrades and installations go smoothly

11.) What should be considered in a disaster recovery plan? 
to prevent data lost, downtime and recovery time

12.) What are some guidelines around dealing with private customer information?
keep it safe, and do not use it without their explicit information

13.) Why must IT professionals be aware of cyber law? 
so that they are able to comply with local regulations and to not break the law and recognize when it is being broken

14.) What are two data types that are important to someone conducting a forensics study on computers?
volatile and nonvolatile

15.) Name 4 things you should document as a first responder to suspected illegal activity on a computer.
the location of the computer, the reason you are accessing the computer, the 

16.) What is Chain of Custody and why is it important?  
information about how data is stored, by who, if it has been change, and what the change is, peripherals, network connections, and the evidence of illegal material or actions 

17.) What are the differences between Level one and Level two technicians’ responsibilities? 
level one : deals with ticket documentation, simple problems, and basic troubleshooting
level two : escalation of problems, complex troubleshooting, and hardware handling

18.) What is a script and how can it help you as a technician? 
a file that contains a list of commands that can be run manually or automatically

19.) What is the difference between a scripting language and a compiled language? Give an example of each. 
C+, C++, C#, and Javascript

20.)  What is the purpose of each in scripting: variables, conditional statements, and loops? 
statements : to tell the computer to perform an action
variables : to hold section
loops : recursive logic 
constants : values that do not change
variables : values that can be written into