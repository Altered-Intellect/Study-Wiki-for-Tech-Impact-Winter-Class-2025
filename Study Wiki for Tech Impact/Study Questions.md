---
tags: 
parent docs:
  - "[[Navigation]]"
sibling docs: 
child docs: 
last updated: 2025-01-13T07:39:00
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
Redundant Array of Independent Disks is a way to store data across several drives, providing reliability, capacity, or performance depending on the level

11. List and describe the legacy ports: (3.3.3.1)
DVI : has analogue and digital variants
VGA : analogue only, now limited use 
Serial : used for peripherals
Parallel : used most commonly used for old printer

12. Which USB Connection Type is a proprietary connection? Who is the proprietary manufacturer? (3.3.3.3)
lightning connector made by apple

13.  What is a Thick Client? What is a Thin Client? (3.4.2.6)
thick client : self reliant, regular desktop PC
thin client : handles basic I/O, processing and memory is offloaded to a network server

14. List the required components for the 5 specialized computer systems described: (3.4.2.1 – 3.4.2.5)

| **Specialized System**              | **Powerful Processor** | **Maximum RAM** | **High End Audio Card** | **High End Video Card** | **Large/Fast HDD** | **Other** |
| ----------------------------------- | ---------------------- | --------------- | ----------------------- | ----------------------- | ------------------ | --------- |
| Thick Clients                       |                        |                 |                         |                         | x                  |           |
| Thin Clients                        |                        |                 |                         |                         |                    | x         |
| CAx Workstation                     | x                      | x               | x                       | x                       |                    |           |
| Audio and Video Editing Workstation |                        |                 | x                       | x                       | x                  |           |
| Virtualization Workstation          | x                      | x               |                         |                         |                    |           |
| Gaming PCs                          | x                      |                 | x                       | x                       | x                  | x         |

15. Define NAS. What is it? What does it do?(3.4.2.7)
Network Attached Storage, external storage that links directly to the network allowing the sharing of files

16. What is an SDS? What is the purpose of it?(3.5.1.2)
Safety Data Sheet, used to inform users on how to dispose of computer hardware, and peripherals

17. Describe the dangers of these technology products, and the proper disposal methods for them.

| **Item**                           | **Dangers**                           | **Disposal Methods**        |
| ---------------------------------- | ------------------------------------- | --------------------------- |
| Batteries                          | mercury, rare earth metals            | recycling                   |
| Monitors                           | lead, rare earth metals               | recycling                   |
| Toner Kits, Cartridges, Developers | refill cartages my void warranty, and | recycling                   |
| Chemical Solvents, Aerosol Cans    | water contamination                   | local sanitation            |
| Cell Phones, Tablets               | rare earth metals                     | check with local regulators |
