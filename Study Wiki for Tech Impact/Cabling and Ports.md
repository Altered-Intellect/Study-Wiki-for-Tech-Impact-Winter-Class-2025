---
tags: 
parent docs:
  - "[[Hardware]]"
sibling docs: 
child docs: 
last updated: 2025-01-13T20:56:00
media:
---
# Nav
| ^ [[Hardware]] ^ | > [[Computational Memory]] > |

You must be able to describe different cable and their matching port types and their characteristics and uses, including connector types, features, and purposes.

# [[Networks]]
Network cables are used to connect devices such as computers to networking equipment. There are **three primary types** of network cable: **coaxial**, **twisted pair**, and **fiber**. A cable is the medium through which data is transferred from one device to another.

## [[Copper Wiring]]
Copper is the most common medium used in both coaxial and twisted-pair cables. Categories are used to describe performance ratings of twisted-pair cables. Commonly referred to as Cat cables, Category 1 through 8 exist, but for the purposes of the CompTIA A+ exam, we are only concerned with the **most common ratings, Category 5 through 6a**, and their corresponding transmission speeds and distance limitations. All Cat cables 2 through 8 are composed of four pairs of twisted-pairs totaling eight individual cables in one cable sheath.

## [[Optical Wiring]]
Optical is a transmission method that depends on light pulses for data transfer.

## Legacy Ports
Computers have many different types of ports to connect the computer to external peripheral devices. As computer technology has evolved, so have the types of ports used to connect peripheral devices. Legacy ports are typically found on older computers and have been mostly replaced by newer technologies such as USB.

## Tools

### Wire Cutters
used to cut wires. Also known as side-cutters, these wire cutters are specifically designed to snip aluminum and copper wire.

### Wire Strippers
used to remove the insulation from wire so that it can be twisted to other wires or crimped to connectors to make a cable. Wire strippers typically come with a variety of notches for different wire gauges.

### Crimpers
used to attach connectors to wires. The crimper tool shown here can attach RJ-45 connectors to networking cables used for Ethernet and RJ-11 connectors to telephone cables used for land lines.

### Punch-down 
used to terminate wire into termination blocks.

### Multimeter
a device that can take many types of measurements. It measures AC/DC voltage, electric current, and other electrical characteristics to test the integrity of circuits and the quality of electricity in computer components.

### Cable Tester
used to check for wiring shorts, faults, or wires connected to the wrong pins.

### Loopback Adapter
also called a loopback plug, tests the basic functionality of computer ports. The adapter is specific to the port that you want to test. In networking, a loopback plug can be inserted in a computer NIC to test the send and receive functionality of the port.

### Tone Probe and Generator
a two-part tool used to trace the remote end of a cable for testing and troubleshooting. The tone generator applies a tone to the wire to be tested. On the remote end, the probe is used to identify the test wire. When the probe is in near proximity to the cable to which the toner is attached, the tone can be heard through a speaker in the probe.

### Wi-Fi Analyzer
are mobile tools for auditing and troubleshooting wireless networks. Many Wi-Fi analyzers, like the Cisco Spectrum Expert Wi-Fi application, are robust tools designed for enterprise network planning, security, compliance, and maintenance. But Wi-Fi analyzers can also be used for smaller, wireless LANs. Technicians can see all available wireless networks in a given area, determine signal strengths, and position access points to adjust wireless coverage.

Some Wi-Fi analyzers can help troubleshoot a wireless network by detecting misconfigurations, access point failures, and radio frequency interference (RFI) problems.

## Test Access Point : [[TAP]]
Sometimes it is necessary to capture network traffic to analyze it. This can often be done with software such as Wireshark. If this is not possible, a network tap can be used to capture the cable signals and send them to analyzing software. A network tap can be passive or active (powered). 
- **Passive TAP** - This type of TAP is a box with network ports to carry signals in and out. Inside, an inductor or optical splitter is used to copy the signal and send it out a monitor port. The monitor port receives all the traffic from the cable. 
- **Active TAP** - This type of TAP regenerates the signal. Due to the complexity of gigabit signaling, a passive TAP is unable to be used. Also, some fiber links may become corrupt using an optical splitter, so an active TAP is used instead. 

Network sniffing can also be completed using a special port on a network switch. This is known as a switched port analyzer (SPAN)/mirror port. A mirror receives a copy of the traffic that are addressed to a specific port or all other ports.

# [[Peripherals]] 
Peripheral cables attach peripheral devices to a computing device. Input/output (I/O) ports on a computer connect peripheral devices such as printers, scanners, and portable drives. In addition to the ports and interfaces, a computer may also have other ports. 

**Serial**—A **serial cable** is built for serial communications with a corresponding serial connector on the end. The most common serial connection type is **DB9**^[1], which has nine pins. Today, serial ports are sometimes used for making console connections to network devices to perform initial configuration. There are two form factors of serial ports, a 9-pin DB-9 port and a 25-pin port.

**Parallel**—Parallel ports have a 25-pin receptacle used to connect various peripheral devices. As the name implies, parallel ports send data in multiple bits at once, in parallel communication. Because these ports were often used to connect printers, they are often called printer ports.

**Game**—The 15-pin game port was used as a connector for joystick input. Game ports were originally located on a dedicated game controller expansion card and then later integrated with sound cards and on PC motherboards.

**Personal System 2 (PS/2)**—A PS/2 port connects a keyboard or a mouse to a computer. The PS/2 port is a 6-pin mini-DIN female connector. The connectors for the keyboard and mouse are often colored differently. If the ports are not color-coded, look for a small figure of a mouse or keyboard next to each port.

**[[Thunderbolt]]**—Thunderbolt is a combination of PCI Express 2.0 x4 and DisplayPort 1.x technology. Thunderbolt was designed primarily for video transmission but can be used by other peripheral devices as well. There are **four Thunderbolt standards** labeled 1 to 4 with Thunderbolt 1 and 2 terminating in a Mini-DisplayPort connector and Thunderbolt 3 and 4 terminating in a USB-C connector.

**Audio ports**—Audio ports connect audio devices to the computer. Analog ports typically include a line in port to connect to an external source (e.g., stereo system), a microphone port, and line out ports to connect speakers or headphones.

## SCSI Cables
Small Computer Systems Interface (SCSI) is a standard for connecting peripheral and storage devices. SCSI is a bus technology, meaning that all devices connect to a central bus and are "daisy-chained" together. The cabling/connector requirements depend upon the location of the SCSI bus.

**External SCSI Cable** The Centronics connector is used for connecting older external SCSI devices such as scanners and printers. This connector came in 36-pin and 50-pin versions. The pins are arranged in two rows with a plastic bar through the center that holds the contact pins. Squeeze latches or bail locks located on the sides of the connector are used to hold it in place.

**Internal SCSI Cable** A common SCSI connector for internal hard drives is the internal 50-pin SCSI which has 50 pins arranged in two rows and is attached to a ribbon cable.

**IDE Cable** IDE ribbon cables look very similar to internal SCSI cables however IDE uses 40-pin connectors. There are typically three connectors on the cable. One to connect to the IDE port on the motherboard and two for attachment of IDE drives.

## USB
Over the years, the USB protocol has evolved and the various standards can be confusing. USB 1.0 provided a low-speed transfer rate at 1.5 Mbps for keyboards and mice and a full-speed channel at 12 Mbps. USB 2.0 made a significant leap, increasing transfer rates up to High Speed at 480 Mbps. USB 3.0 increased the transfer rate to SuperSpeed 5 Gbps, USB 3.1 increased the transfer rate of SuperSpeed to 10 Gbps, and USB 3.2, the latest USB-C specification supports speeds of up to SuperSpeed+ 20 Gbps.

**USB 2.0**—The **USB 2.0** standard has a max speed of 480 Mbps and is referred to as **Hi-speed**.

**USB 3.0**—The **USB 3.0 standard** has a max speed of 5 Gbps and is referred to as **SuperSpeed**.

**USB Type-A**—This is a rectangular connector found on virtually every desktop PC and laptop, as well as TVs, game consoles, and media players. USB 1.1, 2.0, and 3.0 Type-A connectors and receptacles are physically compatible.

**Mini-USB**—The USB Mini-B connector is rectangular with a small indention on each side. The Mini-USB form factor is being phased out and replaced by the micro-USB connector. A mini USB is the **second smallest** USB connector type, contains **five pins**, and is **direction dependent**.

**Micro-USB**—The Micro-USB connector is found on smartphones, tablets, and other devices. Except for Apple, most manufacturers have adopted the Micro-USB interface. The USB 2.0 Micro-B connector has two corners pushed in at an angle. A micro USB connector is the **smallest** USB connector type, and contains **five pins**.

**USB Type-B**—The USB Type-B connector is commonly used to connect printer and external hard drives. It has a square shape with beveled exterior corners and an extra notch at the top.

**USB Type-C**—The USB Type-C connector is the newest USB interface. It is smaller than the Type-A connector and is rectangular with four rounded corners. Both Thunderbolt 3 and USB Type-C are an example of a multipurpose cable that can be used to attach different kinds of peripheral devices to a PC. USB Type C is the shape of the port. Thunderbolt 3 combines the functionality of USB, Thunderbolt, DisplayPort, and the ability to deliver power to devices through the cable. USB-C contains **24 pins** in an **oval** shape, allowing for **reversible connection**.

**Lightning**—The Lightning connector is a small proprietary 8-pin connector used by Apple mobile devices such as iPhones, iPads, and iPods for both power charging and data transfer. It is similar in appearance to a USB Type-C connector.

## Front Panel
The case will front panel cables that must be connected to a common system panel connector on a motherboard. Writing on the motherboard near the system panel connector shows where each cable is connected.

- **Power Button:** to turn on the computer
- **Reset Button:** to refresh the system by turning it on and off
- **Power LED:** in dictates the the motherboard is receiving power
- **Drive Activity LEDs:** when the storage
- **System Speaker:** beeping for troubleshooting
- **Audio:** headphone jack, aux port

### Installation


# [[Video]]
A video cable and port is designed to transmit data to visual display units, usually connecting a monitor to a computer. Video ports and monitor cables transfer analog signals, digital signals, or both. Computers are digital devices that create digital signals. The digital signals are sent to the graphics card where they are transmitted through a cable to a display.

**[[HDMI]]**—The **high-definition multimedia interface** cable is capable of handling higher motion-picture frame rates and digital audio on a single cable. The most common connector type for an HDMI cable is the **Standard A HDMI** cable which has 19 pins. HDMI was developed specifically for high-definition televisions. However, its digital features also make it a good candidate for computers. VGA is an analog port and is the oldest graphics port likely still used on some PCs, although it is quickly becoming a legacy technology. HDMI connectors are available in three sizes: standard, mini and micro. The majority of HDMI connectors in use today are the Type A (Standard), Type C (Mini) and Type D (Micro). 

**[[DP]]**—**DisplayPort** was developed to use less power than previous video cables. DisplayPort is backward compatible with VGA and DVI. DisplayPort is also capable of transmitting both video and audio signals. A standard DP cable has two hooks on it to lock the cable into place. It is an interface technology that is designed to connect high-end graphics-capable PCs and displays, as well as home theater equipment and displays.  The DisplayPort is a newer technology designed to replace both DVI and VGA for connecting computer monitors. The DisplayPort uses a 20-pin connector for delivering high bandwidth video and audio signals. Like HDMI, there is a miniaturized version of the DisplayPort called the Mini DisplayPort which is primarily used on Apple computers.

DisplayPort can handle up to 20 Gbps with version 2.0. DisplayPort is also capable of connecting multiple monitors to the same video source with a single cable.

**[[DVI]]**—The **digital visual interface** cable was developed to address the shortcomings of analog video transmission. DVI cables are capable of transmitting digital video signals to display units. The **three DVI connector standards** are DVI-A for analog connection only, DVI-D for digital connection only, and DVI-I for both analog and digital signals. DVI cables are typically white. The DVI connector is usually white and consists of as many as 24 pins (three rows of eight pins) for digital signals, up to 4 pins for analog signals, and a flat pin called a ground bar. DVI is disappearing as quickly as it appeared. It's still seen in some monitors alongside VGA, which is finally starting to fade in favor of HDMI.

**Radio Corporation of America (RCA)**—RCA connectors have a central plug with a ring around it and are used to carry audio or video. RCA connectors are often found in groups of three, where a yellow connector carries video and a pair of red and white connectors carries left and right audio channels.

**[[VGA]]**—The **video graphics array** cable is the oldest video standard still in use today. It has 3 rows and 15 pins. It is also sometimes referred to as the DE-15 or HD-15 connector. A VGA cable is **strictly analog** and is typically blue in color. VGA is an analog port and is the oldest graphics port likely still used on some PCs, although it is quickly becoming a legacy technology.

**Thunderbolt 1 or 2**—Thunderbolt allows for high-speed connection of peripherals such as hard drives, RAID arrays, network interfaces, and it can transmit high-definition video using the DisplayPort protocol.

**Thunderbolt 3**—uses the same connector as USB-C. It has twice the bandwidth of Thunderbolt 2, uses less power, and can provide two 4K monitors with video.

# [[Hard Drives]]
Hard drive cables/connectors connect internal components to the motherboard. Hard drive connections, known as **drive interfaces**, can be either **on-board or off-board**. Their attachment standard is based on the hard drive’s requirements and consists of circuitry and a header, or port.

**[[SATA]]**—**Serial Advanced Technology Attachment** is the **most common** type of drive interface. A standard SATA cable is internal and flat with an L-shaped **terminating connector** that can only fit into the motherboard connection port in one way. A SATA data cable has **seven pins**, while a SATA power cable has **15 pins**. SATA revisions 1.0, 2.0, 3.0, and 3.2 support speeds of 1.5 Gbps, 3 Gbps, 6 Gbps, and 16 Gbps, respectively. This cable does not supply any power to the SATA device. A separate power cable provides power to the drive.

**[[eSATA]]**—The **external SATA** cable, as the name suggests, is **external** to the housing. Standard eSATA cables are for data transmission only and do not provide power. An eSATA that provides power is called Power over eSATA, eSATA+, eSATAp, or eSATA/USB. eSATA connectors do not have an “L” shaped key like the SATA connector. However, an eSATA port does have a key feature to prevent inadvertent insertion of a USB connector, which is similar in size and shape.

**[[SCSI]]**—**Small Computer System Interface** is a type of hard drive to motherboard connector that is most commonly used for **storage device connection**. SCSI cables can be either ribbon cables or round cables containing 50, 68, or 80 wires. Up to 16 devices, including the motherboard or SCSI controller card. It is an older standard that originally connected to one SCSI cable or **daisy-chained** together, used in parallel rather than serial, data transfers. A new version of SCSI known as Serially Attatched SCSI (SAS) has been developed and seen use in server storage.

**[[IDE]]**—**Integrated drive electronics** cables, renamed **parallel advanced technology attachment (PATA)**, are a 34-pin or 40-pin ribbon cable with a colored strip along one edge to indicate the location of pin 1. There are three separate connectors on a PATA cable, one for power and two for drives. The 34-pin cable used for floppy drives and the 40-pin cable for hard drives and optical drives.

# [[Adapters]]
There are many connection standards in use today. Many are interoperable but require specialized components. These components are called adapters and converters
**Adapter** –This is a component that converts one type of connection or cable technology to another.
- **DVI-to-VGA**
- **DVI-to-HDMI**
- **USB-to-ethernet**
- **USB to PS/2**
- **Molex to SATA**

## Converter
This performs the same function as an adapter but also translates the signals from one technology to the other. For example, a USB 3.0 to SATA converter enables a hard disk drive to be used as a flash drive.
- **HDMI to VGA converter**

# Connector Types
installed at the terminating points of cables to provide connection to compatible components and peripherals. The connector type used depends on the type of cable and the desired receptacle compatibility.

**Direction Dependency**—when a cable is asymmetric and is only able to be connected with a specific orientation
**Data Pins**—
**Power Pins**—

- **RJ11**—A **registered jack (J)** is a **standard for telecommunication network interfaces** for voice and data equipment connection to a service provider or carrier. RJ11 is used with twisted pair cables to connect four to six wires to traditional telephone lines of modems.
- **RJ45**—RJ45 is used with twisted pair cables for eight-wire connections. A twisted pair cable with RJ45 connectors is commonly called an **ethernet cable**.
- **F-type**—An F-type connector (or just **F connector**) is used with coaxial cables for cable and satellite data connections.
- **ST**—A **straight tip** connector is a **bayonet style** connector used with fiber optic cables.
- **SC**—A **subscriber connector** is a push/pull-style connector used with fiber optic cables.
- **LC**—A **lucent connector** is a push/pull-style connector used with fiber optic cables that is half the size of an SC, making it more suitable for office and data center usage.
- **Punchdown block**—A punchdown block is an electrical connection device that allows for multiple copper wires to be “punched down” or inserted into a slot providing insulation as well as electrical connection to attached wires.
- **Molex™**—Molex is an older **two-piece** pin-and-socket interconnection type used for drive connections.
- **Lightning port**—Lightning port is an **eight-pin Apple** proprietary connector type that has **reversible** orientation.
- **DB9**—The DB9[1](https://uniontestprep.com/comptia-a-core-series-exam/study-guide/220-1101-hardware/pages/1#footnote_1) is a **trapezoid**-shaped nine-pin connector arranged in **two rows of four and five pins**. It is used for serial connections to network device consoles or management ports.

---
_1. The term “DB9” is commonly used but is technically incorrect; the proper name is “DE9,” referring to the size of the connector’s shell and the number of pins, with DE indicating a smaller shell size than DB. However, given that this misconception has been prevalent for so long in the industry, the CompTIA objectives use the term DB9._
## [[Power Supply]]
These connectors are used to power various internal components such as the motherboard and disk drives. The connectors are “keyed” which means that they are designed to be inserted in only one orientation.

**A 20-pin or 24-pin slotted connector**
• Connects to the motherboard  
• The 24-pin connector has two rows of 12 pins each  
• The 20-pin connector has two rows of 10 pins each

**SATA keyed connector**
• Connects disk drives  
• Connector is wider and thinner than a Molex connector

**Molex keyed connector**
• Connects hard drives, optical drives, or other devices

**Berg keyed connector**
• Connect to legacy floppy drives  
• Smaller than a Molex connector

**4-pin to 8-pin auxiliary power connector**
• Connector has two rows of two to four pins and supplies power to different areas of the motherboard  
• The auxiliary power connector is the same shape as the main power connector but smaller

**6/8-pin PCIe power connector**
• Connector has two rows of three to four pins and supplies power to internal components

# Data transfer

attenuation
distance