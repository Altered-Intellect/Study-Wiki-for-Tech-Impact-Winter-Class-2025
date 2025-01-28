---
tags: 
parent docs:
  - "[[Navigation]]"
sibling docs: 
child docs: 
last updated: 2025-01-14T23:34:00
media:
---
# [[Hardware]]
1. What is a Form Factor? What are some common desktop form factors? (1.2.1.1)
 The size and shape of the motherboard and the case that the computers components are put into. Common form factors include all-in-one, compact, full-size, and horizontal.

2. What is the purpose of a computer power supply? How does it function? (1.2.1.2) 
 The purpose of the power supply is to supply electrical power to the computer by converting the AC power of the power grid to the lower voltage DC required for computer components. 
 
3. What are the six power connectors described in the Cisco curriculum? What are the most common voltage units supplied by the Power Supply? (1.2.1.3 – 1.2.1.4)
20/24 pin, Molex, 4/8 pin, 6/8 pin, SATA, and Berg Keyed connectors. 3.3, 5, and 12v.
  
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
Small Outline DIMM is a condensed version of a DIMM
 
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
