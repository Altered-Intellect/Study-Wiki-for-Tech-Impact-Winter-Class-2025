---
tags: 
parent docs:
  - "[[Navigation]]"
sibling docs: 
child docs: 
last updated: 
media:
---
# Nav
< [[Mobile Devices|Previous]] < ^ [[Navigation|Home]] ^ > [[Virtualization and Cloud Computing|Next]] >

---

Understanding all types of networks and their corresponding connections is vital if you are in an IT support position. You will need to know everything about TCP/IP, Wi-Fi, and SOHO connections. About 20% of the CompTIA A+ 1101 test concerns various aspects of networking. Around 25% of the questions concerning networking will begin with a scenario.

## Network Icons
Networks are systems that are formed by links. Computer networks connect devices and users to one another. A variety of networking icons are used to represent different parts of a computer network.

**Host Devices**
The network devices that people are most familiar with are called end devices or host devices, as shown in the figure. They are called end devices because they are at the end or edge of a network. They are also called host devices because they typically host network applications, such as web browsers and email clients, that use the network to provide services to the user.

**Intermediary Devices**
Computer networks contain many devices that exist in between the host devices. These intermediary devices ensure that data flows from one host device to another host device. The most common intermediary devices are shown in the figure:
- **Switch** - connects multiple devices to the network.
- **Router** - forwards traffic between networks.
- **Wireless** **router** - connects multiple wireless devices to the network and may include a switch to connect wired hosts.
- **Access point (AP)** - connects to a wireless router and is used to extend the reach of a wireless network.
- **Modem** - connects a home or small office to the Internet.

**Network Media**
Communication across a network is carried on a medium. The medium provides the channel over which the message travels from source to destination. The plural for medium is media. The icons in the next figure represent different types of network media. Local area network (LANs), wide area networks (WANs), and wireless networks are discussed further in this topic. The cloud is typically used in network topologies to represent connections to the internet. The internet is often the medium for communications between one network and another network.

# Ports and Protocols
For this exam, you should know the following TCP/UDP port numbers, the protocols that run over those ports, and the **primary use** for each. A port is the unique identifier number for transmission control and direction. A protocol is a set of rules that govern communications.

For the CompTIA A+ exam, you must be able to **compare and contrast** TCP and UDP ports and protocols and their respective purposes. **Memorizing port numbers** is highly recommended for this section.

## Transmission Control Protocol (TCP) 
a transport protocol that is designed for reliability, with guaranteed delivery, and data assembled in the proper order, required a digital handshake.

TCP transport is analogous to sending packages that are tracked from source to destination. If a shipping order is broken up into several packages, a customer can check online to see the order of the delivery.
#### Connection-Oriented
TCP is a connection-oriented which establishes a set connection before data flow begins between two devices. 

With TCP, there are three basic operations of reliability:
- Numbering and tracking data segments transmitted to a specific device from a specific application
- Acknowledging received data
- Retransmitting any unacknowledged data after a certain period of time

| Port  | Protocol           | Application                                      | Description                                                                                                                                                                                                                                             |
| ----- | ------------------ | ------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 20/21 | File Transport     | File Transfer Protocol : [[FTP]]                 | used to manipulate files. FTP can copy files, list and manipulate directories, and view file contents. **Port 21** is mainly used for file management and **port 20** is used for data transfer. FTP is **not secure** and transmits in **plain text**. |
| 22    | Remote Access      | Secure Shell : [[SSH]]                           | connection-oriented protocol used to set up secure Telnet connections for remote logins. SSH is **secure**.                                                                                                                                             |
| 23    | Remote Access      | Telnet                                           | a terminal emulation program that allows for remote access to text on another computer. Telnet is **not secure** and transmits **plaintext**.                                                                                                           |
| 25    | Email and Identity | Simple Mail Transfer Protocol : [[SMTP]]         | used to send **email only** and is a **push protocol**. It may also be used to relay email messages from source to destination email servers.                                                                                                           |
| 80    | World Wide Web     | Hypertext Transfer Protocol : [[HTTP]]           | manages communications between a web server and a client to view internet content using a set of notation. HTTP is **not secure** and transmits in **plain text**.                                                                                      |
| 110   | Email and Identity | Post Office Protocol 3 : [[POP3]]                | used for **downloading email**.                                                                                                                                                                                                                         |
| 143   | Email and Identity | Internet Message Access Protocol : [[IMAP]]      | currently in its fourth version, or IMAP4, and is used for downloading email. IMAP4 is **secure** and runs over **port 143**.                                                                                                                           |
| 389   |                    | Lightweight Directory Access Protocol : [[LDAP]] | used for **accessing information** stored in an information directory.                                                                                                                                                                                  |
| 548   | File Transfer      | Apple Filing Protocol : [[AFP]]                  | proprietary port for file transfer for Apple devices                                                                                                                                                                                                    |



### The TCP/IP Model
The TCP/IP model consists of layers that perform functions necessary to prepare data for transmission over a network. TCP/IP stands for two important protocols in the model: Transmission Control Protocol (TCP) and Internet Protocol (IP). TCP is responsible for tracking all the network connections between a user’s device and multiple destinations. The Internet Protocol (IP) is responsible for adding addressing so that data can be routed to the intended destination.

The two protocols that operate at the transport layer are TCP and User Datagram Protocol (UDP), as shown in the figure.

TCP is considered a reliable, full-featured transport layer protocol, which ensures that all of the data arrives at the destination. In contrast, UDP is a very simple transport layer protocol that does not provide for any reliability. The next figure highlights the TCP and UDP properties.

## User Datagram Protocol : [[UDP]] Ports
a transport protocol that is designed for speed, transferring the data as quickly as possible, with some tolerance for data loss

UDP is similar to placing a regular, non-registered, letter in the mail. The sender of the letter is not aware of the availability of the receiver to receive the letter. Nor is the post office responsible for tracking the letter or informing the sender if the letter does not arrive at the final destination.

#### Connectionless
UDP is a connectionless protocol which allow for data to flow without guaranteeing an established connection. This allows for faster data flow but does not guarantee reliable data flow. 

UDP provides the basic functions for delivering data segments between the appropriate applications, with very little overhead and data checking. UDP is known as a best-effort delivery protocol. In the context of networking, best-effort delivery is referred to as unreliable because there is no acknowledgment that the data is received at the destination.

| Port  | Protocol           | Application                                                       | Description                                                                                                                                               |
| ----- | ------------------ | ----------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 67/68 | Network Operations | Dynamic Host Configuration Protocol : [[DHCP]]                    | **assigns IP addresses** dynamically to network clients through a lease. DHCP uses **port 67** for the server and **port 68** for the client.             |
| 69    | File Transfer      | Trivial File Transfer Protocol : [[TFTP]]                         | a **faster version of FTP** that **uses UDP** rather than TCP as its transport protocol.                                                                  |
| 161   | Network Operations | Simple Network Management Protocol : [[SNMP]]                     | used for network management. SNMP uses **port 161** for sending and receiving requests and **port 162** for receiving transmissions from managed devices. |
| 445   | File transport     | Server Message Block (SMB)/Common Internet File System : [[CIFS]] | primarily a **Microsoft protocol** used for **shared file access**. Common Internet File System (CIFS) is an enhanced version of SMB.                     |

## TCP vs. UDP
**Transmission Control Protocol (TCP)** is a connection-oriented protocol used to send and receive data over a network. Before data is sent, a connection is established with the receiving host. It is considered a **reliable protocol** because the receiving host acknowledges that it received the data. TCP is used in cases where receiving the proper data is more important than speed. **User Datagram Protocol (UDP)** is a **connectionless protocol**. Data is sent without any assurance that the receiving host is actually receiving the data. For that reason, it is considered an **unreliable protocol**. The advantage of UDP over TCP is that it is faster.

TCP and UDP use a source and destination port number to keep track of application conversations. The source port number is associated with the originating application on the local device. The destination port number is associated with the destination application on the remote device. These are not physical ports. They are numbers that are used by TCP and UDP to identify the applications that should handle the data.

The source port number is dynamically generated by the sending device. This process allows multiple conversations to occur at the same time for the same application. For example, when you use a web browser, you can have more than one tab open at a time. The destination port number is 80 for regular web traffic or 443 for secure web traffic. These are called well-known port numbers because they are consistently used by most webservers on the Internet. Source port numbers will be different for each tab opened. This is how your computer knows which browser tab to deliver the web content to. Similarly, other network applications like email and file transfer have their own assigned port numbers.

| Port    | Protocol           | Application                                                         | Description                                                                                                                                                                                                                                               |
| ------- | ------------------ | ------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 53      |                    | Domain Name System : [[DNS]]                                        | used to resolve hostnames to IP addresses for Web, Email, and other Internet services. It uses UDP for request and information transfer between DNS servers. TCP will be used for DNS responses if required                                               |
| 137/139 | Network Operations | Network Basic Input/Output System : [[NetBIOS]] over TCP/IP (NetBT) | an API for **communication between computers** over a network. NetBIOS works over OSI layer 4 and needs to work with a layer 5 protocol, namely TCP/IP, to function properly. NetBIOS over TCP/IP is called NetBT. NetBIOS runs on **ports 137/139**.<br> |
| 427     |                    | Service Location Protocol : [[SLP]]                                 | allows computers and other devices to locate services on a LAN without previous configuration. Usually uses UDP, but can use TCP.                                                                                                                         |
| 443     |                    | Hypertext Transfer Protocol Secure : [[HTTPS]]                      | the **secure version of HTTP**. HTTPS used encryption and authenticates your connect with the webserver                                                                                                                                                   |
| 3389    | Remote Access      | Remote Desktop Protocol : [[RDP]]                                   | allows for remote connection to computers.                                                                                                                                                                                                                |

## Common Networking Hardware
Networking hardware includes the physical components used to achieve network connectivity. You must be able to **compare and contrast** common networking hardware.

### Routers
A router is a device that connects multiple network devices and determines the best path for reaching a specified device using routing tables. Routers are **OSI Layer 3** devices and make decisions based on logical addresses. Key functions of a router include **connecting multiple network devices** to one another, breaking up broadcast domains, and connecting one LAN to another LAN on a WAN.

### Switches
A switch is a device that works at **OSI Layer 2**, examines the header of incoming packets for the MAC address, and forwards the packet to the correct location. Switches can be managed or unmanaged.

#### Managed
A managed switch is one that **allows for port configuration**, traffic management, and traffic monitoring. Managed switches offer quality of service (QoS), redundancy, port mirroring, and VLANs.

#### Unmanaged
An unmanaged switch does _not_ allow for configuration and passes on all data for a MAC address to its ports.

### Access Points
An access point is technically any device to which a host can connect in order to access a network. Wired access points include **hubs** and **switches**. However, the term usually refers to a wireless access point (WAP) that allows Wi-Fi devices to connect to a network.

### Patch Panel
A patch panel is a dumb device that is essentially a large rack-mounted HUB whose sole purpose is to **connect cables** together. A **dumb device** is a device that broadcasts all data coming in through the input port out over all output ports. A dumb device, like a patch panel, makes no logical decisions and simply serves as a connection and relay point.

### Firewall
A firewall is a **security appliance**, either hardware or software, that filters network traffic based on a preconfigured set of rules.

### Power over Ethernet : [[PoE]]
Power over Ethernet (PoE) is a technology that **delivers power to devices** over data lines, such as an ethernet cable, rather than having a separate power cord.

#### Injectors
An injector is a **midspan device** that sits between the switch and the access point and supplies power via an ethernet connection.

#### Switch
A switch sits in front of the midspan injector device and provides **power to the ethernet cable**.

#### PoE Standards
PoE standards are the **IEEE 802.3 standards** that define PoE specifications.

- **PoE- 802.3af-15.4 W**—WAPs, static surveillance cameras, VoIP phones
- **PoE+- 802.3at-30W**—alarm systems, PTZ cameras, video IP phones
- **PoE++- 802.3bt (Type 3)-60 W**—multi-radio WAPs, video conferencing equipment
- **PoE++- 802.3bt (Type 4)-100 W**—laptops, flat-screen monitors

### Hub
A HUB is a dumb **Layer 1** device that sends all incoming data to all connected devices as a broadcast. Hubs are also known as **multiport repeaters**.

### Cable Modem
A cable modem is a device that connects to a cable line to provide **connectivity**. A cable modem is technically no longer a modem, however, since it does not modulate and demodulate analog signals.

### Digital Subscriber Line : [[DSL]]
A digital subscriber line (DSL) modem provides connectivity **via a telephone line**.
DSL is an always-on service, which means that there is no need to dial up each time you want to connect to the internet. Voice and data signals are carried on different frequencies on the copper telephone wires. A filter prevents DSL signals from interfering with phone signals.

Very high-speed DSL (VDSL) attains much higher bit rates than DSL. A symmetric link can carry as much as 26 Mbps in both directions while an asymmetric link can carry as much as 52 Mbps download and 6 Mbps upload. VDSL2 can carry as much as 100 Mbps in both directions.
### Optical Network Terminal : [[ONT]]
An optical network terminal (ONT) modem is one that provides connectivity **via a fiber-optic line**.

### Network Interface Card : [[NIC]]
A network interface card (NIC), also known as a **network adapter card**, is used to provide the physical interface between a computer and the cabling used for connectivity.

### Software-Defined Networking : [[SDN]]
Software-defined networking (SDN) sets up a network virtually **via the cloud**. The SDN replaces the functionality of the router in a network.

---

## Protocols for Wireless Networking
You must be able to **compare and contrast** wireless networking protocols and what they have in common and where they differ.

### Frequencies
The frequency of a wireless protocol refers to the audio range in which the technology broadcasts. The **two operating frequencies for Wi-Fi** are 2.4 GHz and 5 GHz. The frequency has an impact on transmission range and data throughput.

**2.4 GHz**—This relatively low frequency (compared with 5 GHz) has a **greater transmission range** because it passes through objects such as walls and floors better. On the negative side, **throughput is slower** and it is an open frequency range that other devices use. Devices like cordless phones and microwave ovens can **interfere** with it.

**5 GHz**—At this higher frequency, **throughput is faster**. On the negative side, the **transmission range is shorter** as the signal is attenuated by objects such as walls and floors.

### Channels
Channels are different frequencies that are used for communications between the end-user device and the wireless access point. The **2.4 GHz range** has 14 channels, but the top three cannot be used in **North America**, so the U.S. has **11 available channels**. Devices will automatically select a channel, but if there seems to be interference, we can manually select another channel. The **5 GHz range** also has channels, but there is more room in the RF spectrum at that range, so we never have to set those channels.

#### Regulations
The Federal Communications Commission (FCC) has defined 14 different 22 MHz communications channels but only allows for the use of the first 11 channels.

#### 2.4 GHz vs. 5 GHz
There are 25 defined 20 MHz channels at 5 GHz, 24 of which can be used for Wi-Fi communications, while 2.4 GHz only has 14 defined channels, 11 of which can be used.

### Bluetooth
Bluetooth allows devices to communicate over short distances (10 meters) in a personal area network (PAN). It is typically used to **connect peripherals**, such as headphones, to a laptop or smartphone. It is the IEEE 802.15.1 standard.

### 802.11
The Wi-Fi specification 802.11 is part of the IEEE 802 wireless networking standards. It is used for Wi-Fi communications. They all use the ethernet protocol and carrier sense multiple access with collision avoidance (CSMA/CA) media access method. The main characteristics that differentiate them are their operating frequencies, theoretical maximum data speed, and throughput.

**a**—5 GHz frequency, 54 Mbps maximum throughput, 120 meters range, no backwards compatibility

**b**—2.4 GHz frequency, 11 Mbps maximum throughput, 140 meters range, no backwards compatibility

**g**—2.4 GHz frequency, 54 Mbps maximum throughput, 140 meters range, backward compatible with 802.11b

**n**—5/2.4 GHz frequency, 600 Mbps maximum throughput, 250 meters range, backward compatible with 802.11a/b/g

**ac (Wi-Fi 5)**—5 GHz frequency, 6.5 Gbps maximum throughput, 140 meters range, backward compatible with 802.11a/n

**ax (Wi-Fi 6/6e)**—5/2.4 GHz frequency, 9.6 Gbps maximum throughput, 140 meters range, 6e has 1 and 6 GHz frequency, backward compatible with 802.11a/b/g/n/ac

### Long-Range Fixed Wireless

A long-ranged fixed wireless connection is a point-to-point wireless technology that employs the use of directional antennas to send and receive network signals usually from **10 to 20 km**.

#### Licensed
Licensed frequencies are frequencies whose use is granted by the **FCC** in the US.

#### Unlicensed
Unlicensed frequencies are frequencies that can be used by anyone, such as 2.4 and 5 GHz. The common use of these frequencies, however, often causes **interference** and can create susceptibility to **eavesdropping**.

#### Power
Power can be transmitted via long-range fixed wireless and is commonly known as wireless power transfer (WPT). Power is generated by the transmitting station and sent via microwave or laser light to the receiver who turns the transmission back into electricity.

#### Regulatory Requirements for Wireless Power
WPT technology is regulated by the FCC in the US.

### Near-Field Communication (NFC)
Near-field communication (NFC) has a **very short range** of a few inches. It is used for contactless communications between devices that are right next to one another. The most common use today is for contactless payment systems.

### Radio-Frequency Identification (RFID)
Radio-frequency identification (RFID) uses a **radio signal** to send information from an RFID tag with identifying information. This is commonly used to streamline the inventory of tracking applications.

## Networked Host Services
You need to have a working understanding of the properties and purpose of network-delivered services in a client-server environment and know how to **summarize** them. Know the difference between a **client application** and a **server application**. Client applications request services from a server application.

### Server Roles
You are expected to have a working understanding of the following network services. A server is not necessarily a stand-alone piece of hardware. A server is usually a **process running in memory** on a networked system that responds to requests from a remote client system.

#### DNS
**Domain name system** (DNS) servers resolve hostnames to IP addresses. Two public DNS servers are needed for an enterprise to host a website, with one DNS server acting as redundancy. Records of hostname IP address sets are held in a zone file. If the DNS address is not located in the zone file, it requests the information from a higher-level DNS server called the **root server**.

#### DHCP
A Dynamic Host Configuration Protocol (DHCP) server provides **IP configuration information**, such as an IP address, subnet mask, default gateway, and DNS server address, automatically to clients. The scope of a DHCP server is the information that is permitted to be shared with a client, including the IP address, subnet mask, default gateway, Domain name, and any other information the DHCP server may hold.

#### Fileshare
A fileshare or file server is a **central repository** for the storage, management, and access of network files. A network can also use network-attached storage (NAS) for a file server.

#### Print Servers
A print server is a server that manages print requests and connects printers to a network.

#### Mail Servers
A mail server is responsible for sending, receiving, and managing emails. A mail server must be running a **specialized server package**, such as Microsoft Exchange, Sendmail, Postfix, or Exim, to be considered a mail server.

#### Syslog
The syslog server in a client-server model is responsible for **collecting information** obtained through system monitoring, such as **login events or errors**. Messages compiled in a syslog server include the facility code, the severity level, and a textual description of the logged events. Syslog servers are composed of **three primary components**: the listener, the database, and the management and filtering software.

#### Web Servers
A web server listens for incoming requests. The requests are executed by the web server and provide the requested content, including text, images, videos, and the running of scripts. Common web server platforms include Microsoft’s Internet Information Services (IIS) and Apache.

#### Authentication, Authorization, and Accounting (AAA)
An authentication, authorization, and accounting (triple A or AAA) server is an access control server that acts as a gatekeeper for critical network components. AAA servers are also known as domain controllers. Examples of AAA servers include remote access service (RAS), Remote Authentication Dial-In User Service : [[RADIUS]], Terminal Access Controller Access-Control System Plus : [[TACACS+]], and Kerberos.

### Internet Appliances
An internet appliance is a device that aids in internet access and helps users access the internet safely.

#### Spam Gateways
A spam gateway, also known as an **antispam gateway**, is an internet appliance whose purpose is to **block malicious emails** from accessing the network.

#### Unified Threat Management : [[UTM]]
Unified threat management (UTM) acts to **centralize security management** on a network. UTM typically provides packeting filtering and inspection, IPS, gateway antimalware, spam blocking, malicious website blocking, and application control.

#### Load Balancers
A load balancer is responsible for **evenly distributing** requests over servers to balance the system. Common load balancing configurations include identical, cross-region, and content-based load balancing.

#### Proxy Servers
A proxy server **makes requests for resources** on behalf of a client. The proxy server acts as an intermediary between the client and the target server.

### Legacy/Embedded Systems
**Legacy systems** are older systems that for one reason or another have not been updated. It is usually due to essential applications that will not run on the updated platform. **Embedded systems** are devices other than computers that have computer technology running within. Like legacy systems, these may not be able to stay updated.

#### Supervisory Control and Data Acquisition : [[SCADA]]
Supervisory control and data acquisition (SCADA) is an example of a **critical legacy system category**. A SCADA system is a high-level management system used to control manufacturing machines and processes, manage large-scale infrastructure settings, and run building components.

### Internet of Things : [[IoT]] Devices
An internet of things (IoT) device connects to the network through a central controller or coordinating device. Common examples of IoT devices include **smart devices** such as thermostats and home automation and security devices.

---

## Basic Wired/Wireless Small Office/Home Office : [[SOHO]] Networks

When setting up a small office/home office (SOHO) network, keep the following steps in mind:

- Understand relevant regulations.
- Make a map.
- Locate the server(s).
- Identify client computer locations.
- Locate network resources.
- Determine user connectivity type.
- Designate additional connectivity options if needed.

You must be able to install and configure basic wired and wireless SOHO networks. On the CompTIA A+ exam, these concepts will be addressed in scenario-based questions.

### Internet Protocol : [[IP]] Addressing

Internet protocol (IP) addressing is the assignment of a unique device identifier on a local network or the internet. The IP address is responsible for managing logical network addresses.

#### IPv4

An IPv4 address is a **32-bit hierarchical address** that identifies a host on a network and is typically written in dotted-decimal notation. The 32-bit address is divided into 4 bytes, or octets, containing 8 bits each (ex: 192.168.10.55). IPv4 addresses are divided into designated classes, A, B, C, D, E, and F, based on the first 3 bits of the IP address. IPv4 addresses are **finite** and are running out.

**Private addresses**—A private IP address is **not routable** on the internet.

**Class A private address range:** 10.0.0.0–10.255.255.255  
**Class B private address range:** 172.16.0.0–172.31.255.255  
**Class C private address range:** 192.168.0.0.–192.168.255.255

**Public addresses**—Public addresses are **routable on the internet**. Public addresses are purchased and **only one computer** can hold any given public address at a time.

#### IPv6

IPv6 addresses are **128-bit addresses** expressed in **hexadecimal notation** and are composed of eight 16-bit fields separated by colons (ex: 2001:0db8:3c4d:0012:0000:0000:1234:56ab, which can be reduced to 2001:db8:3c4d:12::1234:56ab)

#### Automatic Private IP Addressing (APIPA)

Automatic private IP addressing (APIPA) assigns an IP address to a device that was not assigned a static or dynamic IP address. The address will be **in the 169.254.0.0 network**. This is generally not useful, other than being an indication that the device failed to get an IP address through normal means. These addresses are also referred to as link-local addresses.

#### Static

A static address is one that is **set manually** by a user or administrator. A device that is assigned a static address will keep that address until someone changes the configuration.

#### Dynamic

A dynamic address is one that is **automatically assigned**, typically by a router or DHCP server. The next time a device that was dynamically assigned an IP address joins the network, it may be assigned a different IP address.

#### Gateway

A gateway is a **router that connects your network** to another network, typically the Internet. When configuring a device on the network, you specify the internal IP address of the gateway as a default destination to send traffic.

## Configurations
You must be able to **compare and contrast** common network configuration concepts for the CompTIA A+ exam.

### DNS

The domain name system (DNS) has only one function: to **resolve hostnames to IP addresses**. DNS settings are usually given out via DHCP along with IP address information, but this can be done manually as well. This allows the user (client) to resolve domain names to IP addresses in order to perform searches or lookups. These are usually given out in a primary and secondary fashion for redundancy purposes.

#### Address

Addresses are contained on the DNS server in **zone files**. The zone file maintains records of hostname-to-IP address mappings and contains information such as the name of the server or computer, internet protocol address, record type, computer address, and comments.

**A**—_A_ is a common DNS record type that signifies that the host record is an **IPv4** address.

**AAAA**—_AAAA_, pronounced “quad A”, is a common DNS record type that signifies the host record is an **IPv6** address.

#### Mail Exchanger : [[MX]]
A mail exchanger (MX) record is a common DNS record type that signifies that the host record is the name or address of an email server.

#### Text : [[TXT]]
A text (TXT) record is a common DNS record type that signifies that the host record is a text record for human-readable or machine-readable data.

##### Spam Management
the process of determining if data is spam or valid.

**DKIM**—DomainKeys Identified Mail (DKIM) is a type of spam management that authenticates using **encryption** through a public-private key pair.

**SPF**—Sender Policy Framework (SPF) is a type of spam management that authenticates an email server **based on its IP address**.

**DMARC**—Domain-based Message Authentication, Reporting and Conformance (DMARC) is a type of spam management that **combines DKIM and SPF** in one framework and offers **more control** over what the user can do with spam email.

### Dynamic Host Protocol : [[DHCP]]
DHCP automatically assigns all of the settings needed to access resources on your LAN or the internet. It can provide IP address, subnet, gateway, and DNS information. If you want to ensure that a device gets a specific IP address, you can configure a DHCP reservation in the DHCP server.

#### Leases
A lease is a temporary IP configuration assigned by the DHCP server to a client. A lease typically includes an IP address, subnet mask, default gateway, and DNS server address.

#### Reservations
A reservation is the reserving of an IP address for a specific client based on the client’s MAC address and is primarily used for devices that require a static IP address.

#### Scope
The scope is information provided outside the IP address and the subnet mask issued by the DHCP server, such as the default gateway, DNS server address, or domain name.

### Virtual LAN : [[VLAN]]
A virtual local area network (VLAN) is a **logical subnet**, typically configured on a switch, that acts as a separate subnet. They allow an administrator to segment the ports on a single switch as if it were multiple switches. This provides more efficient forwarding of data by isolating traffic to only those ports where it is required. 

VLANs also allow end devices to be grouped together for administrative purposes. Without VLANs, every device connected to a switch would be on the same subnet. By configuring VLANs on the switch, you can have devices on that one switch in different subnets or VLANs.

Virtual LANs (VLANs) provide segmentation and organizational flexibility in a switched network. A group of devices within a VLAN communicate as if each device was attached to the same switch. VLANs are based on logical connections, instead of physical connections. An administrator can segment VLANs based on factors such as function, team, or application, without regard for the physical location of the users or devices.

By default, all switch ports are assigned to VLAN 1. However, you can assign the PCs to different VLANs by configuring their interconnecting port.

Once the VLAN information is configured on the other switches, the faculty member using PC1 would be able to communicate with PC4 because they are on the same VLANs. If the faculty member wanted to send something to PC5 which is assigned to VLAN 30, then the services of a router would be required.

VLANs help reduce excessive broadcast traffic and implement access and security policies between groups of users.

### Virtual Private Network : [[VPN]]
A virtual private network (VPN) is an **encrypted connection** between two networks or between a host and a network. When a host connects to a network over a VPN, it is assigned a separate IP address that is in the network’s address range.
The most common type of VPN is used by teleworkers to access a corporate private network. Teleworkers are network users that are offsite or remote. In the figure, the fat links between Teleworker 1 and the router at the Company Headquarters represent a VPN connection.

## Internet Connection Types and Network Types

For this exam, you should understand the specific networks and internet connections listed below and **understand the differences** between them.

### Internet Connection Types

Internet connection types are methods, either wired or wireless, through which a device can connect to the internet.

**Satellite**—A satellite connection is a wireless connection type that employs the use of satellites to achieve connectivity. Satellite connections are typically slower than wired broadband connections and require a satellite dish. Weather and misalignment can affect connectivity.

**Fiber**—A fiber connection is a type of wired connection that uses a fiber-optic cable made of thin flexible glass or plastic fiber surrounded by a rubberized outer sheath to send data via light signals. Fiber offers fast data transmission. There are **two types** of fiber varieties: **single-mode fiber (SMF)** and **multimode fiber (MMF)**. 

**Cable**—A cable connection is a type of wired connection that uses a cable, either **coaxial/coax** or **twisted pair**, for data transmission. Coax and twisted pair cables use different connector types and cable specifications. 
A cable internet connection does not use telephone lines. Cable uses coaxial cable lines originally designed to carry cable television. A cable modem connects your computer to the cable company. You can plug your computer directly into the cable modem. However, connecting a routing device to the modem allows multiple computers to share the connection to the internet.

**DSL**—A digital subscriber line (DSL) is a type of **wired connection** that uses existing phone lines paired with a DSL modem to provide internet service.

**Cellular**—A cellular connection is a type of wireless connection type that uses a **provider’s cellular network** for connectivity.
It relies on cell towers distributed throughout the user’s coverage area to provide seamless access to cell phone services and the internet. With the advent of the third-generation (3G) of cellular technology, smartphones could access the internet. Download and upload speeds continue to improve with each iteration of cell phone technology.

In some regions of the world, smartphones are the only way users access the internet. In the United States, users are increasingly relying on smartphones for internet access. According to the Pew Research Center, in 2018 20% of adults in the United States do not use broadband at home (28% for adults 18-29). Instead, they use a smartphone for personal internet access. Search for “pew internet research” for more interesting statistics.

**WISP**—A wireless internet service provider (WISP) is a wireless connection type in which an internet service provider (ISP) offers connectivity using wireless technology. WISP connections are **fixed point-to-point connections**.

**Broadband**
uses different frequencies to send multiple signals over the same medium. For example, the coaxial cables used to bring cable television to your home can carry computer network transmissions at the same time as hundreds of TV channels. Your cell phone can receive voice calls while also using a web browser.
Some common broadband network connections include cable, digital subscriber line (DSL), ISDN, satellite, and cellular.
### Topology
Network types define the general area that is covered by a network.

Local Are Network : [[LAN]]— a collection of devices connected to one another in **one physical area**, such as an office building, and can be small or large. The distinguishing characteristic for LANs today is that they are typically owned by an individual, such as in a home or small business, or wholly managed by an IT department, such as in a school or corporation.

Wide Area Network : [[WAN]]—a network that covers a **large geographical area** and is composed of multiple LANs. Individuals and organizations contract for WAN access from a service provider. The internet is the largest WAN.

Personal Area Network : [[PAN]]—composed of primarily **Bluetooth-connected devices**.

Metropolitan Area Network : [[MAN]]—a network larger than a LAN but smaller than a WAN and **limited to a smaller geographical area**, such as a city or a campus. The network consists of various buildings connected through wireless or fiber optic media.

Storage Area Network : [[SAN]]—a network area composed of **storage devices**.

Wireless [[LAN]] : [[WLAN]]—a LAN in which the **connections are wireless** rather than wired. A WLAN uses radio waves to transmit data between wireless devices.

Wireless Mesh Network : [[WMN]]—uses multiple access points to extend the WLAN. The topology uses a wireless router. The two wireless APs will extend the reach of the WLAN within a home. Similarly, business and municipalities can use WMNs to quickly add new areas of coverage.

## Tools
For the CompTIA A+ exam, you should be able to evaluate a set of network requirements in a **given scenario** and select the best network tool for the job.

### Crimper
A crimper is used to **connect a connector to a cable**. It is not usually practical to use cables of a fixed length. It is also easier to run cable without the connectors on it. So, the cable is run and cut to the desired length, and then the connector is crimped on using a crimper. There are **different types** of crimpers for ethernet, coaxial, and fiber-optic cables.

### Cable Stripper
used to **remove the insulation** from the end of a cable before the connector is crimped onto it.

### Wi-Fi Analyzer
used to design, optimize, or troubleshoot a Wi-Fi network. This device is used to show strong and weak spots in wireless coverage. It is a way to **visualize Wi-Fi network** coverage.

### Toner Probe
These devices are used to **locate cables** in a wiring closet. The tone generator is typically placed at the user end, and a probe is waved around in the wiring closet to locate the connection. It will make a distinctive noise when it is near the correct cable.

### Punchdown Tool
used to **connect the exposed ends of a wire into a wiring harness**.

### Cable Tester
This device is used to certify that the cable meets the standards of the **wiring code** and to ensure it can be used for communication. It will identify broken wires or missing pin connections.

### Loopback Plug
a special cable that is wired to **transmit and receive on a single connector**. There are loopback plugs for different types of connectors, like USB or ethernet, for testing network interface cards (NICs).

### Network Test Access Port : [[TAP]]
a hardware device that creates a copy of **network traffic** for use by monitoring devices without interfering with network traffic. A network TAP can be easily moved from location to location to identify problems.

---
# Legacy Connections
In the 1990s, internet speeds were slow compared to today, which now has the bandwidth to transmit voice and video, as well as data. A dial-up connection requires either an internal modem installed in the computer or an external modem connected by USB. The modem dial-up port is connected to a phone socket using an RJ-11 connector. Once the modem is physically installed it must be connected to one of the computer’s software COM ports. The modem must also be configured with local dialing properties such as the prefix for an outside line and the area code
The Set Up a Connection or Network Wizard is used to configure a link to the ISP server. Connecting to the internet has evolved from analog telephone to broadband:

**Analog Telephone**
Analog telephone internet access can transmit data over standard voice telephone lines. This type of service uses an analog modem to place a telephone call to another modem at a remote site. This method of connection is known as dialup.

Integrated Services Digital Network : [[ISDN]]
uses multiple channels and can carry different types of services; therefore, it is considered a type of broadband. ISDN is a standard that uses multiple channels to send voice, video, and data over normal telephone wires. ISDN bandwidth is larger than traditional dialup.

## Hotspot and Tethering
Many cell phones provide the ability to connect other devices, as shown in the figure. This connection, known as tethering, can be made using Wi-Fi, Bluetooth, or by using a USB cable. Once a device is connected, it is able to use the phone’s cellular connection to access the Internet. When a cellular phone allows Wi-Fi devices to connect and use the mobile data network, it is called a mobile hotspot.


---
# Nav
< [[Mobile Devices|Previous]] < ^ [[Navigation|Home]] ^ > [[Virtualization and Cloud Computing|Next]] >
