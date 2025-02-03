---
tags: 
parent docs:
  - "[[Navigation]]"
sibling docs: 
child docs: 
last updated: 2025-01-20T18:24:00
media:
---
# Nav
< [[Mobile Devices|Previous]] < ^ [[Navigation|Home]] ^ > [[Virtualization and Cloud Computing|Next]] >

---

Understanding all types of networks and their corresponding connections is vital if you are in an IT support position. You will need to know everything about TCP/IP, Wi-Fi, and SOHO connections. About 20% of the CompTIA A+ 1101 test concerns various aspects of networking. Around 25% of the questions concerning networking will begin with a scenario.

# Ports and Protocols
For this exam, you should know the following TCP/UDP port numbers, the protocols that run over those ports, and the **primary use** for each. A port is the unique identifier number for transmission control and direction. A protocol is a set of rules that govern communications.

For the CompTIA A+ exam, you must be able to **compare and contrast** TCP and UDP ports and protocols and their respective purposes. **Memorizing port numbers** is highly recommended for this section.

## The TCP/IP Model
The TCP/IP model consists of layers that perform functions necessary to prepare data for transmission over a network. TCP/IP stands for two important protocols in the model: Transmission Control Protocol (TCP) and Internet Protocol (IP). TCP is responsible for tracking all the network connections between a user’s device and multiple destinations. The Internet Protocol (IP) is responsible for adding addressing so that data can be routed to the intended destination. The two protocols that operate at the transport layer are TCP and User Datagram Protocol (UDP).

TCP is considered a reliable, full-featured transport layer protocol, which ensures that all of the data arrives at the destination. In contrast, UDP is a very simple transport layer protocol that does not provide for any reliability.

![[TCP-IP Model.canvas|TCP-IP Model]]
## Transmission Control Protocol (TCP) 
a transport protocol that is designed for reliability, with guaranteed delivery, and data assembled in the proper order, required a digital handshake.

TCP transport is analogous to sending packages that are tracked from source to destination. If a shipping order is broken up into several packages, a customer can check online to see the order of the delivery. TCP is a connection-oriented which establishes a set connection before data flow begins between two devices. 

With TCP, there are three basic operations of reliability:
- Numbering and tracking data segments transmitted to a specific device from a specific application
- Acknowledging received data
- Retransmitting any unacknowledged data after a certain period of time

| Port    | Protocol           | Application                                      | Description                                                                                                                                                                                                                                             |
| ------- | ------------------ | ------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 20/21   | File Transport     | File Transfer Protocol : [[FTP]]                 | used to manipulate files. FTP can copy files, list and manipulate directories, and view file contents. **Port 21** is mainly used for file management and **port 20** is used for data transfer. FTP is **not secure** and transmits in **plain text**. |
| 22      | Remote Access      | Secure Shell : [[SSH]]                           | connection-oriented protocol used to set up secure Telnet connections for remote logins. SSH is **secure**. SCP secure copy protocol, SFTP is SSH FTP                                                                                                   |
| 23      | Remote Access      | Telnet                                           | a terminal emulation program that allows for remote access to text on another computer. Telnet is **not secure** and transmits **plaintext**.                                                                                                           |
| 25      | Email and Identity | Simple Mail Transfer Protocol : [[SMTP]]         | used to send **email only** and is a **push protocol**. It may also be used to relay email messages from source to destination email servers.                                                                                                           |
| 80      | World Wide Web     | Hypertext Transfer Protocol : [[HTTP]]           | manages communications between a web server and a client to view internet content using a set of notation. HTTP is **not secure** and transmits in **plain text**.                                                                                      |
| 110/995 | Email and Identity | Post Office Protocol 3 : [[POP3]]                | used for **downloading email**.                                                                                                                                                                                                                         |
| 143/993 | Email and Identity | Internet Message Access Protocol : [[IMAP]]      | currently in its fourth version, or IMAP4, and is used for downloading email. IMAP4 is a **secure** port                                                                                                                                                |
| 389     | Email and Identity | Lightweight Directory Access Protocol : [[LDAP]] | used for **accessing information** stored in an information directory.                                                                                                                                                                                  |
| 548     | File Transfer      | Apple Filing Protocol : [[AFP]]                  | proprietary port for file transfer for Apple devices                                                                                                                                                                                                    |

## User Datagram Protocol : [[UDP]] Ports
a transport protocol that is designed for speed, transferring the data as quickly as possible, with some tolerance for data loss

UDP is similar to placing a regular, non-registered, letter in the mail. The sender of the letter is not aware of the availability of the receiver to receive the letter. Nor is the post office responsible for tracking the letter or informing the sender if the letter does not arrive at the final destination. UDP is a connectionless protocol which allow for data to flow without guaranteeing an established connection. This allows for faster data flow but does not guarantee reliable data flow. 

UDP provides the basic functions for delivering data segments between the appropriate applications, with very little overhead and data checking. UDP is known as a best-effort delivery protocol. In the context of networking, best-effort delivery is referred to as unreliable because there is no acknowledgment that the data is received at the destination.

| Port  | Protocol           | Application                                                           | Description                                                                                                                                                                                             |
| ----- | ------------------ | --------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 67/68 | Network Operations | Dynamic Host Configuration Protocol : [[DHCP]]                        | **assigns IP addresses** dynamically to network clients through a lease. DHCP uses **port 67** for the server and **port 68** for the client. need a default gateway, IP address, DNS, and subnet mask. |
| 69    | File Transfer      | Trivial File Transfer Protocol : [[TFTP]]                             | a **faster version of FTP** that **uses UDP** rather than TCP as its transport protocol.                                                                                                                |
| 161   | Network Operations | Simple Network Management Protocol : [[SNMP]]                         | used for network management. SNMP uses **port 161** for sending, receiving and monitoring requests and **port 162** for receiving transmissions from managed devices.                                   |
| 445   | File transport     | Server Message Block : [[SMB]]/Common Internet File System : [[CIFS]] | primarily a **Microsoft protocol** used for **shared file access**. Common Internet File System (CIFS) is an enhanced version of SMB.                                                                   |

## TCP vs. UDP
**Transmission Control Protocol (TCP)** is a connection-oriented protocol used to send and receive data over a network. Before data is sent, a connection is established with the receiving host. It is considered a **reliable protocol** because the receiving host acknowledges that it received the data and in the correct order. TCP is used in cases where receiving the proper data is more important than speed. 

**User Datagram Protocol (UDP)** is a **connectionless protocol**. Data is sent without any assurance that the receiving host is actually receiving the data. For that reason, it is considered an **unreliable protocol**. The advantage of UDP over TCP is that it is faster.

TCP and UDP use a source and destination port number to keep track of application conversations. The source port number is associated with the originating application on the local device. The destination port number is associated with the destination application on the remote device. These are not physical ports. They are numbers that are used by TCP and UDP to identify the applications that should handle the data.

The source port number is dynamically generated by the sending device. This process allows multiple conversations to occur at the same time for the same application. For example, when you use a web browser, you can have more than one tab open at a time. The destination port number is 80 for regular web traffic or 443 for secure web traffic. These are called well-known port numbers because they are consistently used by most webservers on the Internet. Source port numbers will be different for each tab opened. This is how your computer knows which browser tab to deliver the web content to. Similarly, other network applications like email and file transfer have their own assigned port numbers.

| Port    | Protocol           | Application                                                         | Description                                                                                                                                                                                                         |
| ------- | ------------------ | ------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 53      | World Wide Web     | Domain Name System : [[DNS]]                                        | used to resolve hostnames to IP addresses for Web, Email, and other Internet services. It uses UDP for request and information transfer between DNS servers. TCP will be used for DNS responses if required         |
| 137/139 | Network Operations | Network Basic Input/Output System : [[NetBIOS]] over TCP/IP (NetBT) | an API for **communication between computers** over a network. NetBIOS works over OSI layer 4 and needs to work with a layer 5 protocol, namely TCP/IP, to function properly. NetBIOS over TCP/IP is called NetBT.  |
| 427     | Network Operations | Service Location Protocol : [[SLP]]                                 | allows computers and other devices to locate services on a LAN without previous configuration. Usually uses UDP, but can use TCP.                                                                                   |
| 443     | World Wide Web     | Hypertext Transfer Protocol Secure : [[HTTPS]]                      | the **secure version of HTTP**. HTTPS used encryption and authenticates your connect with the webserver                                                                                                             |
| 3389    | Remote Access      | Remote Desktop Protocol : [[RDP]]                                   | allows for remote connection to computers. used mainly for logging onto servers. RDP sessions can not interact or observe each other                                                                                |
## Media Access Control
[MAC] : Your fingerprint and mailing address are two ways to identify you and locate you. Your fingerprint usually does not change. Your fingerprint can be used to uniquely identify you, wherever your location. Your mailing address is different. It is your location. Unlike your fingerprint, your mailing address can change.

Devices that are attached to a network have two addresses that are similar to your fingerprint and mailing address. These two types of addresses are the MAC address and the Internet Protocol (IP) address.

The MAC address is hard-coded onto the Ethernet or wireless network interface card : [[Motherboards#NIC|NIC]] by the manufacturer. The address stays with the device regardless of what network the device is connected to. A MAC address is 48 bits and can be represented in one of the three hexadecimal formats shown in the table below.

| Address Format    | Description                          |
| ----------------- | ------------------------------------ |
| 00-50-56-BE-D7-87 | two hexadecimal digits with hyphens  |
| 00:50:56:BE:D7:87 | two hexadecimal digits with colons   |
| 0050.56BE.D787    | four hexadecimal digits with periods |
The figure below shows a topology with two local area networks (LANs). This topology demonstrates that MAC addresses do not change when a device is moved. But IP addresses do change. The laptop was moved to LAN 2. Notice that the laptop’s MAC address did not change, but its IP addresses did change.

**Note**: Converting between decimal, binary, and hexadecimal numbering systems is beyond the scope of this course. Search the internet to learn more about these numbering systems.
![[MAC Address Change.canvas|MAC Address Change]]
### Filtering
MAC address filtering specifies exactly which device MAC addresses are allowed to or blocked from sending data on your network. Many wireless routers only give you the option of allowing or blocking MAC addresses, but not both. Technicians will typically configure allowed MAC addresses. The MAC address for your Windows computer can be found with the **ipconfig /all** command, as shown in the figure.

You may need to search the internet for where to find the MAC address on a specific device. Finding the MAC address is not always straight forward because not all devices call it a MAC address. Windows calls it a “Physical Address”, as shown below.
```
C:\> ipconfig /all 

Windows IP Configuration  
Host Name . . . . . . . . . . . . : ITEuser 
Primary Dns Suffix  . . . . . . . : 
Node Type . . . . . . . . . . . . : Hybrid 
IP Routing Enabled. . . . . . . . : No 
WINS Proxy Enabled. . . . . . . . : No 

Ethernet adapter Local Area Connection:  
Connection-specific DNS Suffix  . : 
Description . . . . . . . . . . . : Intel(R) PRO/1000 MT
Network Connection Physical Address. . . . . . . . . : 00-50-56-BE-D7-87 
DHCP Enabled. . . . . . . . . . . : No 
Autoconfiguration Enabled . . . . : Yes 
IPv6 Address. . . . . . . . . . . : 2001:db8:cafe:200::8(Preferred) 
Link-local IPv6 Address . . . . . : fe80::8cbf:a682:d2e0:98a%11(Preferred) 
IPv4 Address. . . . . . . . . . . : 192.168.200.8(Preferred) 
Subnet Mask . . . . . . . . . . . : 255.255.255.0 
Default Gateway . . . . . . . . . : 2001:db8:cafe:200::1     192.168.200.1 

C:\>
```


On an iPhone it is called the “Wi-Fi Address” and on an Android it is called “Wi-Fi MAC address”. Additionally, your device may have two or more MAC addresses. For example, the PlayStation 4 in the figure has two MAC addresses: one for wired networks and one for wireless networks. Similarly, a Windows PC might have multiple MAC addresses. The PC below has three MAC addresses: wired, wireless, and virtual.

**Note**: The last six hexadecimal numbers are replaced with an **X** in the figure for security reasons.

```
C:\> ipconfig /all 

Windows IP Configuration
<output omitted> 

Ethernet adapter Ethernet: 
<output omitted> 
Physical Address. . . . . . . . . : 44-A8-42-XX-XX-XX 
DHCP Enabled. . . . . . . . . . . : Yes 
Autoconfiguration Enabled . . . . : Yes 

Ethernet adapter VirtualBox Host-Only Network: 

Connection-specific DNS Suffix  . : 
Description . . . . . . . . . . . : VirtualBox Host-Only 
Ethernet Adapter 
Physical Address. . . . . . . . . : 0A-00-27-XX-XX-XX
<output omitted> 

Wireless LAN adapter Wi-Fi:  
Connection-specific DNS Suffix  . : lan 
Description . . . . . . . . . . . : Intel(R) Dual Band
Wireless-AC 3165 
Physical Address. . . . . . . . . : E0-94-67-XX-XX-XX
<output omitted> 

C:\>
```

Finally, consider the fact that new devices might be added to the network at any time. You can see how the technician responsible for manually configuring all these MAC addresses might be overwhelmed. Imagine having to manually enter and maintain dozens of MAC addresses in an interface such as the one shown below.

However, MAC address filtering may be your only option. Better solutions, such as port security, require purchasing a more expensive router or a separate firewall device, and are beyond the scope of this course.

# Design
As a computer technician, you must be able to support the networking needs of your customers. Therefore, you must be familiar with:
- **Network components** – Includes wired and wireless network interface cards (NIC) and network devices such as switches, wireless access points (APs), routers, multipurpose devices, and more.
- **Network design** – Involves knowing how networks are interconnected to support the needs of a business. For instance, the needs of a small business will differ greatly from the needs of a large business.

Consider a small business with 10 employees. The business has contracted you to connect their users. As shown in the figure, a home or small office wireless router could be used for such a small number of users. These routers are multiple purpose and typically provide router, switch, firewall, and access point capabilities. In addition, these wireless routers often provide a variety of other services including DHCP.

If the business was much larger, then you would not use a wireless router. Instead, you would consult with a network architect to design a network of dedicated switches, access points (AP), firewall appliances, and routers.

Regardless of network design, you must know how to install network cards, connect wired and wireless devices, and configure basic network equipment.

**Note**: This document will focus on connecting and configuring a small office or home wireless router. The configurations will be demonstrated using Packet Tracer. However, the same functionality and similar graphical user interface (GUI) elements exist in all wireless routers. You can purchase a variety of low-cost wireless routers online and from consumer electronic stores. Search the internet for “wireless router reviews” to research current recommendations.

## Logging into a Router
Most home and small office wireless routers are ready for service out of the box. They preconfigured to be connected to the network and provide services. For example, the wireless router uses DHCP to automatically provide addressing information to connected devices. However, wireless router default IP addresses, usernames, and passwords can easily be found on the internet. Just enter the search phrase “default wireless router IP address” or “default wireless router passwords” to see a listing of many websites that provide this information. Therefore, your first priority should be to change these defaults for security reasons.

To gain access to the wireless router’s configuration GUI, open a web browser. In the address field, enter the default IP address for your wireless router. The default IP address can be found in the documentation that came with the wireless router or you can search the internet. The figure shows the IPv4 address 192.168.0.1, which is a common default for many manufacturers. A security window prompts for authorization to access the router GUI. The word admin is commonly used as the default username and password. Again, check your wireless router’s documentation or search the internet.

## Basic Setup

### Step 1: Log in to the router from a web browser
After logging in, a GUI opens. The GUI will have tabs or menus to help you navigate to various router configuration tasks. It is often necessary to save the settings changed in one window before proceeding to another window. At this point, it is a best practice to make changes to the default settings.

### Step 2: Change the default admin password
To change the default login password, find the administration portion of the router’s GUI. In this example, the Administration tab was selected. This is where the router password can be changed. On some devices, such as the one in the example, you can only change the password. The username remains admin or whatever the default username is for the router you are configuring.

### Step 3: Log in with the new admin password
After you save the new password, the wireless router will request authorization again. Enter the username and new password, as shown in the example.

### Step 4: Change the default [[#Dynamic Host Protocol DHCP|DHCP]] [[IP#IPv4|IPv4]] address
You can change the default router IPv4 address. It is a best practice to use private IPv4 addressing inside your network. The IPv4 address 10.10.10.1 is used in the example but it could be any private IPv4 address you choose.

Search the internet for “private ip addressing” to learn more.

### Step 5: Renew the [[IP]] Address
When you click save, you will temporarily lose access to the wireless router. Open a command window and renew your IP address with the ipconfig /renew command, as shown in the example.

### Step 6: Log in to the [[#Router]] with the new [[IP]] address
Enter the router’s new IP address to regain access to the router configuration GUI, as shown in the example. You are now ready to continue configuring the router for wireless access.

## Basic Wireless Settings

### Step 1: View the [[#Wireless LAN WLAN|WLAN]] defaults
Out of the box, a wireless router provides wireless access to devices using a default wireless network name and password. The network name is called the Service Set Identified : [[SSID]]. Locate the basic wireless settings for your router to change these defaults.

### Step 2: Change the network mode
Some wireless routers allow you to select which 802.11 standard to implement. The example shows that “Mixed” has been selected. This means wireless devices connecting to the wireless router can have a variety of wireless NICs installed. Today’s wireless routers configured for mixed mode most likely support 802.11a, 802.11n, and 802.11ac NICs.

### Step 3: Configure the [[SSID]]
Assign an SSID to the wireless LAN (WLAN). OfficeNet is used in the example. The wireless router announces its presence by sending broadcasts advertising its SSID. This allows wireless hosts to automatically discover the name of the wireless network. If the SSID broadcast is disabled, you must manually enter the SSID on each wireless device that connects to the WLAN.

### Step 4: Configure the channel
Devices configured with the same channel within the 2.4GHz band may overlap and cause distortion, slowing down the wireless performance and potentially break network connections. The solution to avoid interference is to configure non-overlapping channels on the wireless routers and access points that are near to each other. Specifically, channels 1, 6, and 11 are non-overlapping. In the example, the wireless router is configured to use channel 6.

### Step 5: Configure the security mode
Out of the box, a wireless router may have no WLAN security configured. In the example, the personal version of Wi-Fi Protected Access version 2 (WPA2 Personal) is selected. WPA2 with Advanced Encryption Standard (AES) encryption is currently the strongest security mode.

### Step 6: Configure the passphrase
WPA2 personal uses a passphrase to authenticate wireless clients. WPA2 personal is easier to use in a small office or home environment because it does not require an authentication server. Larger organizations implement WPA2 enterprise and require wireless clients to authenticate with a username and password.

### Whitelisting and Blacklisting
Whitelisting and blacklisting specify which IP addresses are allowed or denied on your network. Similar to MAC address filtering, you can manually configure specific IP addresses to allow or deny into your network. On a wireless router, this is typically done using an access list or access policy, as shown in the figure. Refer to your wireless router’s documentation for specific steps or search the internet for a tutorial.

Whitelisting is a good tool for allowing your users, such as children or employees, access to those IP addresses you approve. You can also blacklist or explicitly block known sites. However, similar to MAC address filtering, this can become burdensome. Better solutions exist. Search the internet for “parental control software” and “content filters”.

## Configure a [[#Wireless Mesh Network WMN|WMN]]
In a small office or home network, one wireless router may suffice to provide wireless access to all the clients. However, if you want to extend the range beyond approximately 45 meters indoors and 90 meters outdoors, you can add wireless access points. As shown in the wireless mesh network in the figure, two access points are configured with the same WLAN settings from our previous example. Notice that the channels selected are 1 and 11 so that the access points do not interfere with channel 6 configured previously on the wireless router.

Extending a WLAN in a small office or home has become increasingly easier. Manufacturers have made creating a wireless mesh network (WMN) simple through smartphone apps. You buy the system, disperse the access points, plug them in, download the app, and configure your WMN in a few steps. Search the internet for “best wi-fi mesh network system” to find reviews of current offerings.

## Quality of Service
[QoS]
Many home and small office routers have an option for configuring Quality of Service (QoS). By configuring QoS, you can guarantee that certain traffic types, such as voice and video, are prioritized over traffic that is not as time-sensitive, such as email and web browsing. On some wireless routers, traffic can also be prioritized on specific ports.

The figure is a simplified mockup of a QoS interface based on a Netgear GUI. You will usually find the QoS settings in the advanced menus. If you have a wireless router available, investigate the QoS settings. Sometimes, these might be listed under “bandwidth control” or something similar. Consult the wireless router’s documentation or search the internet for “qos settings” for your router’s make and model.

## Universal Plug and Play
[UPnP]
A protocol that enables devices to dynamically add themselves to a network without the need for user intervention or configuration. Although convenient, UPnP is not secure. The UPnP protocol has no method for authenticating devices. Therefore, it considers every device trustworthy. In addition, the UPnP protocol has numerous security vulnerabilities. For example, malware can use the UPnP protocol to redirect traffic to different IP addresses outside your network, potentially sending sensitive information to a hacker.

Many home and small office wireless routers have UPnP enabled by default. Therefore, check this configuration and disable it, as shown in the figure.

Search the internet for “vulnerability profiling tools” to determine if your wireless router is exposed to UPnP vulnerabilities.

## DeMilitarized Zone
[DMZ] or Screened Subnet
A network that provides services to an untrusted network. An email, web, or FTP server is often placed into the DMZ so that the traffic using the server does not come inside the local network. This protects the internal network from attacks by this traffic but does not protect the servers in the DMZ in any way. It is common for a firewall to manage traffic to and from the DMZ. For example, the Web Server in the figure below is in the DMZ and is statically assigned the IPv4 address 10.10.10.50.

On a wireless router, you can create a DMZ for one device by forwarding all traffic ports from the internet to a specific IP address or MAC address. A server, game machine, or web camera can be in the DMZ so that the device can be accessed by anyone. A typical configuration of a DMZ has any traffic sources from the internet will be redirected to the Web Server’s IPv4 address 10.10.10.50. However, the Web Server is exposed to attacks from hackers on the internet and should have firewall software installed.

## Port Forwarding
Hardware firewalls can be used to block TCP and UDP ports to prevent unauthorized access in and out of a LAN. However, there are situations when specific ports must be opened so that certain programs and applications can communicate with devices on different networks. Port forwarding is a rule-based method of directing traffic between devices on separate networks.

When traffic reaches the router, the router determines if the traffic should be forwarded to a certain device based on the port number found with the traffic. Port numbers are associated with specific services, such as [FTP], [HTTP], [HTTPS], and [POP3]. The rules determine which traffic is sent on to the LAN. For example, a router might be configured to forward port 80, which is associated with HTTP. When the router receives a packet with the destination port of 80, the router forwards the traffic to the server inside the network that serves web pages. Port forwarding is enabled for port 80 and is associated with the web server at IPv4 address 10.10.10.50.

### Port triggering 
allows the router to temporarily forward data through inbound ports to a specific device. You can use port triggering to forward data to a computer only when a designated port range is used to make an outbound request. For example, a video game might use ports 27000 to 27100 for connecting with other players. These are the trigger ports. A chat client might use port 56 for connecting the same players so that they can interact with each other. In this instance, if there is gaming traffic on an outbound port within the triggered port range, inbound chat traffic on port 56 is forwarded to the computer that is being used to play the video game and chat with friends. When the game is over and the triggered ports are no longer in use, port 56 is no longer allowed to send traffic of any type to this computer.

# Common Networking Hardware
Networking hardware includes the physical components used to achieve network connectivity. You must be able to **compare and contrast** common networking hardware.

## Icons
Networks are systems that are formed by links. Computer networks connect devices and users to one another. A variety of networking icons are used to represent different parts of a computer network.

**Host Devices**
The network devices that people are most familiar with are called end devices or host devices. They are called end devices because they are at the end or edge of a network. They are also called host devices because they typically host network applications, such as web browsers and email clients, that use the network to provide services to the user.

**Intermediary Devices**
Computer networks contain many devices that exist in between the host devices. These intermediary devices ensure that data flows from one host device to another host device. The most common intermediary devices :
- **Switch** - connects multiple devices to the network.
- **Router** - forwards traffic between networks.
- **Wireless** **router** - connects multiple wireless devices to the network and may include a switch to connect wired hosts.
- **Access point (AP)** - connects to a wireless router and is used to extend the reach of a wireless network.
- **Modem** - connects a home or small office to the Internet.

**Network Media**
Communication across a network is carried on a medium. The medium provides the channel over which the message travels from source to destination. The plural for medium is media. The icons in the next figure represent different types of network media. [[#Local Are Network LAN]], wide area networks (WANs), and wireless networks are discussed further in this topic. The cloud is typically used in network topologies to represent connections to the internet. The internet is often the medium for communications between one network and another network.

## Router
A router is a device that connects multiple network devices and determines the best path for reaching a specified device using routing tables. Routers are **OSI Layer 3** devices and make decisions based on logical addresses. Key functions of a router include **connecting multiple network devices** to one another, breaking up broadcast domains, and connecting one LAN to another LAN on a WAN.

Routers can have all the functionality of a switch or a wireless AP. Switches use [[MAC]] addresses to forward traffic within a single network. Routers use IP addresses to forward traffic to other networks.

For some networks, it is more convenient to purchase and configure one device that serves all your needs than to purchase a separate device for each function. This is especially true for the home or small office. Multipurpose devices may also include a modem for connecting to the internet.

## Switches
A switch is a device that works at **OSI Layer 2**, examines the header of incoming packets for the [[MAC]] address, and forwards the packet to the correct location. 

[[#Bridges]] and [[#Hub]](s) are now considered legacy devices because of the benefits and low cost of switches. A switch microsegments a LAN. Micro-segmenting means that switches filter and segment network traffic by sending data only to the device to which it is sent. This provides higher dedicated bandwidth to each device on the network. When PC-A sends a job to the printer, only the printer receives the traffic. Both switches and legacy bridges perform micro-segmentation, however, switches perform this filtering and forwarding operation in hardware, and also include additional features.

### Operation
Every device on a network has a unique [[#MAC Media Access Control|MAC]] address. This address is hardcoded by the manufacturer of the NIC. As devices send data, switches enter the device’s MAC address into a switching table that records the MAC address for each device connected to the switch, and records which switch port can be used to reach a device with a given MAC address. When traffic arrives that is destined for a particular MAC address, the switch uses the switching table to determine which port to use to reach the MAC address. The traffic is forwarded out the port to the destination. By sending traffic out of only one port to the destination, other ports are not affected.

### Managed
A managed switch is one that **allows for port configuration**, traffic management, and traffic monitoring. Managed switches offer quality of service (QoS), redundancy, port mirroring, and VLANs. usually used for office and 

### Unmanaged
An unmanaged switch does _not_ allow for configuration and passes on all data for a MAC address to its ports. usually use for home, or public applications

## Access Points
An access point is technically any device to which a host can connect in order to access a network. Wired access points include **hubs** and **switches**. However, the term usually refers to a wireless access point (WAP) that allows Wi-Fi devices to connect to a network.
### Wireless
provide network access to wireless devices, such as laptops and tablets. The wireless AP uses radio waves to communicate with the wireless NIC in the devices and other wireless access points. An access point has a limited range of coverage. Large networks require several access points to provide adequate wireless coverage. A wireless access point provides connectivity only to the network, while a wireless router provides additional features.

## Patch Panel
A dumb device that is essentially a large rack-mounted HUB whose sole purpose is to **connect cables** together. A **dumb device** is a device that broadcasts all data coming in through the input port out over all output ports. A dumb device, like a patch panel, makes no logical decisions and simply serves as a connection and relay point.

A patch panel can be unpowered or powered. A powered patch panel can regenerate weak signals before sending them on to the next device.

For safety, ensure that all cables are secured using cable ties or cable management products and are not crossing walkways or running under desks where they can be kicked.

## Firewall
A firewall is a **security appliance**, either hardware or software, that filters network traffic based on a preconfigured set of rules. Firewalls protect data and equipment on a network from unauthorized access. A firewall resides between two or more networks. It does not use the resources of the computers it is protecting, so there is no impact on processing performance. Basic firewalls track source and destination ports and the IP of the packets.

Firewalls use various techniques for determining what is permitted or denied access to a network segment, such as an Access Control List [ACL]. This list is a file that the router uses which contains rules about data traffic between networks.

**Note**: On a secure network, if computer performance is not an issue, enable the internal operating system firewall for additional security. For example, in Windows 10 the firewall is called Windows Defender Firewall. Some applications might not operate properly unless the firewall is configured correctly for them.

### Intrusion Detection/Prevention Systems
[[ID.PSs]] : IDS passively monitor traffic on the network. Stand-alone IDS systems have largely disappeared in favor of Intrusion Prevention Systems (IPSs). But the detection feature of an IDS is still part of any IPS implementation. The figure shows that an IDS-enabled device copies the traffic stream and analyzes the copied traffic rather than the actual forwarded packets. Working offline, it compares the captured traffic stream with known malicious signatures, similar to software that checks for viruses.

An IPS builds upon IDS technology. However, an IPS device is implemented in inline mode. This means that all inbound and outbound traffic must flow through it for processing. As shown in the next figure, an IPS does not allow packets to enter the target system without first being analyzed.

The biggest difference between IDS and IPS is that an IPS responds immediately and does not allow any malicious traffic to pass, whereas an IDS allows malicious traffic to pass before it is addressed. However, a poorly configured IPS can negatively affect the flow of traffic in the network.

## Power over Ethernet
[PoE] : A technology that delivers power to devices over data lines, such as an ethernet cable, rather than having a separate power cord.

For example, a PoE switch transfers small amounts of DC current over an Ethernet cable, along with the data, to power PoE devices. Low voltage devices that support PoE, such as wireless access points, surveillance video devices, and IP phones, can be powered from remote locations. Devices that support PoE can receive power over an Ethernet connection at distances up to 330 ft (100 m) away.

PoE devices like PoE switches, PoE injectors, IP cameras, Voice over IP (VoIP) phones, and wireless access points (WAPs) are the top five most popular devices. Power can also be inserted in the middle of a cable run using a PoE injector.

### Injectors
An injector is a **midspan device** that sits between the switch and the access point and supplies power via an ethernet connection.

### Switch
A switch sits in front of the midspan injector device and provides **power to the ethernet cable**.

#### PoE Standards
PoE standards are the **IEEE 802.3 standards** that define PoE specifications.

- **PoE- 802.3af-15.4 W**—WAPs, static surveillance cameras, VoIP phones
- **PoE+- 802.3at-30W**—alarm systems, PTZ cameras, video IP phones
- **PoE++- 802.3bt (Type 3)-60 W**—multi-radio WAPs, video conferencing equipment
- **PoE++- 802.3bt (Type 4)-100 W**—laptops, flat-screen monitors

#### Ethernet of Power
More commonly called powerline networking, uses existing electrical wiring to connect devices, as shown in the next figure. The concept of “no new wires” means the ability to connect a device to the network wherever there is an electrical outlet. This saves the cost of installing data cables and without any additional cost to the electrical bill. Using the same wiring that delivers electricity, powerline networking sends information by sending data on certain frequencies. A powerline networking adapter can plugged into an electrical outlet to send data over the existing power grid. 

### Repeater
Regenerating weak signals is the primary purpose of a repeater. Repeaters are also called extenders because they extend the distance a signal can travel. In today’s networks, repeaters are most often used to regenerate signals in fiber-optic cables. Also, every networking device that receives and sends data regenerates the signal.

### Hub
A HUB is a dumb **Layer 1** device that sends all incoming data to all connected devices as a broadcast. Hubs are also known as **multiport repeaters**. These extend the reach of a network because it regenerates the electrical signal. Hubs can also connect to another networking device, such as a switch or router, which connects to other sections of the network.

Hubs are legacy devices and should not be used in today’s networks. Hubs do not segment network traffic. When one device sends traffic, the hub floods that traffic to all other devices connected to the hub. The devices are sharing the bandwidth.

### Bridges 
Were introduced to divide LANs into segments. Bridges keep a record of all the devices on each segment. A bridge can then filter network traffic between LAN segments. This helps reduce the amount of traffic between devices. For example, in the next figure, if PC-A needs to send a job to the printer, the traffic will not be forward to Segment 2. However, the server will also receive this print job traffic.

### Cable Modem
A cable modem is a device that connects to a cable line to provide **connectivity**. A cable modem is technically no longer a modem, however, since it does not modulate and demodulate analog signals.

### Digital Subscriber Line
[DSL] : A digital subscriber line (DSL) modem provides connectivity **via a telephone line**.
DSL is an always-on service, which means that there is no need to dial up each time you want to connect to the internet. Voice and data signals are carried on different frequencies on the copper telephone wires. A filter prevents DSL signals from interfering with phone signals.

Very high-speed DSL (VDSL) attains much higher bit rates than DSL. A symmetric link can carry as much as 26 Mbps in both directions while an asymmetric link can carry as much as 52 Mbps download and 6 Mbps upload. VDSL2 can carry as much as 100 Mbps in both directions.

### Optical Network Terminal
[ONT] : An optical network terminal (ONT) modem is one that provides connectivity **via a fiber-optic line**.

### Network Interface Card
[NIC] : A network interface card (NIC), also known as a **network adapter card**, is used to provide the physical interface between a computer and the cabling used for connectivity. 

There are different types of NICs. Ethernet NICs are used to connect to Ethernet networks and wireless NICs are used to connect to 802.11 wireless networks. Most NICs in desktop computers are integrated into the motherboard or connected to an expansion slot. NICs are also available in a USB form factor.

A NIC also performs the important function of addressing data with the NIC’s media access control [[MAC]] address and sending the data out as bits on the network. NICs found on most computers today are gigabit Ethernet (1000 Mbps) capable.

**Note**: Today’s computers and motherboards typically have NICs built in including wireless capability. Refer to the manufacturer’s specifications for more information.

### Software-Defined Networking
[SDN] : sets up a network virtually via the cloud. It replaces the functionality of the router in a network.

## Cloud-based Network Controller
A cloud-based network controller is a device in the cloud that allows network administrators to manage network devices. For example, a medium sized company with multiple locations might have hundreds of wireless APs. Managing these devices can be cumbersome without using some type of controller.

For example, Cisco Meraki provides cloud-based networking that centralizes the management, visibility, and control of all Meraki devices into one dashboard interface, as shown in the figure. The network administrator is able to manage the wireless devices in multiple locations with the click of a mouse button.

---

# Protocols for Wireless Networking
You must be able to **compare and contrast** wireless networking protocols and what they have in common and where they differ.

## Frequencies
The frequency of a wireless protocol refers to the audio range in which the technology broadcasts. The **two operating frequencies for Wi-Fi** are 2.4 GHz and 5 GHz. The frequency has an impact on transmission range and data throughput.

**2.4 GHz**—This relatively low frequency (compared with 5 GHz) has a **greater transmission range** because it passes through objects such as walls and floors better. On the negative side, **throughput is slower** and it is an open frequency range that other devices use. Devices like cordless phones and microwave ovens can **interfere** with it.

**5 GHz**—At this higher frequency, **throughput is faster**. On the negative side, the **transmission range is shorter** as the signal is attenuated by objects such as walls and floors.

## Channels
Channels are different frequencies that are used for communications between the end-user device and the wireless access point. The **2.4 GHz range** has 14 channels, but the top three cannot be used in **North America**, so the U.S. has **11 available channels**. Devices will automatically select a channel, but if there seems to be interference, we can manually select another channel. The **5 GHz range** also has channels, but there is more room in the RF spectrum at that range, so we never have to set those channels.

### Regulations
The Federal Communications Commission (FCC) has defined 14 different 22 MHz communications channels but only allows for the use of the first 11 channels.

### 2.4 GHz vs. 5 GHz
There are 25 defined 20 MHz channels at 5 GHz, 24 of which can be used for Wi-Fi communications, while 2.4 GHz only has 14 defined channels, 11 of which can be used.

## Bluetooth
Bluetooth allows devices to communicate over short distances (10 meters) in a personal area network (PAN). It is typically used to **connect peripherals**, such as headphones, to a laptop or smartphone. It is the IEEE 802.15.1 standard.

## [[802.11]]
The Wi-Fi specification 802.11 is part of the IEEE 802 wireless networking standards. It is used for Wi-Fi communications. They all use the ethernet protocol and carrier sense multiple access with collision avoidance (CSMA/CA) media access method. The main characteristics that differentiate them are their operating frequencies, theoretical maximum data speed, and throughput.

## Long-Range Fixed Wireless
A long-ranged fixed wireless connection is a point-to-point wireless technology that employs the use of directional antennas to send and receive network signals usually from **10 to 20 km**.

### Licensed
Licensed frequencies are frequencies whose use is granted by the **FCC** in the US.

### Unlicensed
Unlicensed frequencies are frequencies that can be used by anyone, such as 2.4 and 5 GHz. The common use of these frequencies, however, often causes **interference** and can create susceptibility to **eavesdropping**.

### Power
Power can be transmitted via long-range fixed wireless and is commonly known as wireless power transfer (WPT). Power is generated by the transmitting station and sent via microwave or laser light to the receiver who turns the transmission back into electricity.

### Regulatory Requirements for Wireless Power
WPT technology is regulated by the FCC in the US.

## Near-Field Communication
[NFC] : has a **very short range** of a few inches. It is used for contactless communications between devices that are right next to one another. The most common use today is for contactless payment systems. 
NFC uses frequency 13.56 MHz and is a subset of the RFID standards. NFC is designed to be a secure method to complete transactions. For example, a consumer pays for good or services by waving the phone near the payment system, as shown in the figure. Based on a unique ID, the payment is charged directly against a pre-paid account or bank account. NFC is also used in mass-transportation services, the public parking sector, and many more consumer areas.

## Radio-Frequency Identification 
[RFID] : uses a **radio signal** to send information from an RFID tag with identifying information. This is commonly used to streamline the inventory of tracking applications.
RFID uses the frequencies within the 125 MHz to 960 MHz range to uniquely identify items, such as in a shipping department as shown in the figure. Active RFID tags that contain a battery can broadcast their ID up to 100 meters. Passive RFID tags rely on the RFID reader to use radio waves to activate and read the tag. Passive RFID tags are typically used for close scanning but have a range of up to 25 meters.

## Zigbee
uses low-power digital radios based on the IEEE 802.15.4 wireless standard for low-rate wireless personal area networks (LR-WPANs) that is meant to be used by low-cost, low-speed devices. Zigbee operates within frequencies from 868 MHz to 2.4 GHz and is limited to 10 to 20 meters. Zigbee has a data rate from 40-250 kb/s and can support approximately 65,000 devices.

The ZigBee specification relies on a main device called a ZigBee Coordinator. Tasked with managing all ZigBee client devices, the ZigBee Coordinator is responsible for the creation and maintenance of the ZigBee network.

Although Zigbee is an open standard, software developers must be a paid member of the Zigbee Alliance to use and contribute to the standard.

## Z-Wave
a proprietary standard that is now owned by Silicon Labs. However, a public version of the interoperability layer of Z-Wave was open sourced in 2016. These open source Z-Wave standards include Z-Wave's S2 security, Z/IP for transporting Z-Wave signals over IP networks, and Z-Ware middleware.

Z-Wave operates within a variety of frequencies based on the country from 865.2 MHz in India to 922 - 926 MHz in Japan. Z-Wave operates at 908.42 MHz in the North America. Z-Wave can transmit data up to 100 meters but has a slower data rate than Zigbee at 9.6-100 kb/s. Z-Wave can support up to 232 devices in one wireless mesh network.

# Networked Host Services
You need to have a working understanding of the properties and purpose of network-delivered services in a client-server environment and know how to **summarize** them. Know the difference between a **client application** and a **server application**. Client applications request services from a server application.

## Server Roles
All computers connected to a network that participate directly in network communication are classified as hosts. Hosts are also called end devices. Hosts on networks perform a certain role. Some of these hosts perform security tasks, while others provide web services. There are also many legacy or embedded systems that perform specific tasks such as file or print services. Hosts that provide services are called servers. Hosts that use these services are called clients.

Each service requires separate server software. For example, a server requires web server software in order to provide web services to the network. A computer with server software can provide services simultaneously to one or many clients. Additionally, a single computer can run multiple types of server software. In a home or small business, it may be necessary for one computer to act as a file server, a web server, and an email server.

You are expected to have a working understanding of the following network services. A server is not necessarily a stand-alone piece of hardware. A server is usually a **process running in memory** on a networked system that responds to requests from a remote client system.
- **File Client and Server** - The File Server stores corporate and user files in a central location. The client devices access these files with client software such as Windows Explorer.
- **Web Client and Server** - The Web Server runs web server software and clients use their browser software, such as Chrome or FireFox, to access web pages on the server.
- **Email Client and Server** - The Email Server runs email server software and clients use their mail client software, such as Microsoft Outlook, to access email on the server.
- **Cloud Storage** - 

### DNS
DNS servers resolve hostnames to IP addresses. On the internet, domain names, such as http://www.cisco.com, are much easier for people to remember than 198.133.219.25, which is the actual numeric IP address for this server. If Cisco decides to change the numeric IP address of www.cisco.com, it is transparent to the user because the domain name remains the same. The new address is simply linked to the existing domain name and connectivity is maintained.

Two public DNS servers are needed for an enterprise to host a website, with one DNS server acting as redundancy. Records of hostname IP address sets are held in a zone file. If the DNS address is not located in the zone file, it requests the information from a higher-level DNS server called the **root server**.
1. Client uses domain name
2. The DNS server matches the domain name with the numeric address
3. The DNS server accepts and returns the DNS Query response with the numeric address
4. The domain name is resolved to its numeric network device address by the DNS protocol

#### Records
When a client does not know the IP address of a web domain or email domain name, it sends a DNS query to the DNS server identified in its IP configuration
The DNS query may ask the DNS server:
- What is the IPv4 or IPv6 address for this domain name?
- What is the IP address for emails forwarded to this domain name?
- Do you have additional information about this email domain name?

To answer these types of questions, a DNS server keeps a list of domain names and IP addressed information in the **resource records (RRs)**. This list or RRs is stored on a DNS server in a DNS zone database.

When the server receives a DNS name query, it looks in its zone database for a matching RR to resolve the query. If it finds a match, it replies to the requesting host with the RR information. If there is no match, then it queries a higher-level DNS server.

### [[#Dynamic Host Protocol DHCP|DHCP]]
A Dynamic Host Configuration Protocol (DHCP) server provides **IP configuration information**, such as an IP address, subnet mask, default gateway, and DNS server address, automatically to clients. The scope of a DHCP server is the information that is permitted to be shared with a client, including the IP address, subnet mask, default gateway, Domain name, and any other information the DHCP server may hold. DHCP is the service used by ISPs, network administrators, and wireless routers to automatically assign IP addressing information to hosts.

#### Operation
Dynamic Host Configuration Protocol (DHCP) works in a client/server mode, where DHCP clients request available IP configurations from a DHCP server. A DHCP server is configured with a scope (i.e., a pool or a range) of addresses that it can lease to requesting DHCP clients.

**Note**: The DHCP server can be a dedicated server or a router configured to provide DHCP services. The DHCP scope should not include manually assigned or reserved IP addresses such as the default gateway address, switch management address, printer address, and more.

As shown in the figure, when the DHCP client boots (or otherwise wants to join a network), it initiates the following four-step process to obtain a lease.

#### Reservations
a section of the DHCP scope that is reserved for things like printers and servers on a network to ensure that the devices are always able to be accessed from the same IP address

#### 4-step Lease
The client must contact the DHCP server periodically to extend the lease. This lease mechanism ensures that moved or power-off clients do not keep addresses that they no longer need. When a lease expires, the DHCP server returns the address to the pool where it can be reallocated as necessary.
1. Discover : The DHCP client broadcasts a DHCPDISCOVER message to request an IP configuration from a DHCP server.
2. Offer : The DHCP server chooses an available IP configuration from its configured scope, and sends a DHCPOFFER unicast message to the client [[MAC]] address. The IP configuration can contain the IP address, subnet mask, default gateway, DNS servers, and the period of time (i.e., the lease) that the host can use the IP configuration.
3. Request : The client then officially requests the IP configuration by sending a broadcast DHCPREQUEST message to the DHCP Server.
4. Acknowledge : The server removes the IP configuration from its pool of available IP configurations and sends a unicast acknowledgement (DHCPACK) to the DHCP client to confirm that it can use the address until the lease expires.

**Note**: DHCP messages are sent using UDP ports 67 (server) and UDP port 68 (clients). DHCP servers listen for client messages on UDP port 67 and DHCP clients listen for messages from servers on UDP port 68. 

#### Process via Wireshark
Once a client receives the DHCPACK from the server, it send out an ARP message to the provided IP address to make sure it is not already assigned on the network. ARP (address resolution protocol) is a network protocol to discover the [[MAC]] address of a device using an IP address. If there is no response to the ARP request, then the host can use the IP configuration. If the host receives an ARP reply, then it restarts the DHCP process to obtain a different IP configuration.

#### Address Renewal
**DHCP Reservations**  
It is also possible to ensure that some hosts, such as servers and printers, are always assigned the same IP address when they connect. To do so, a DHCP server is configured with a reserved list of IP addresses based on the requesting DHCP client’s [[MAC]] address.

Therefore, when a host sends a DHCPDISCOVER message, the DHCP server looks in its DHCP reserved address list for a matching MAC address. If it finds a match, then it sends a DHCPOFFER with the reserved IP address.

### Fileshare
A fileshare or file server is a **central repository** for the storage, management, and access of network files. A network can also use [[NAS]] for a file server.

The File Transfer Protocol (FTP) provides the ability to transfer files between a client and a server. An FTP client is an application that runs on a computer that is used to push and pull files from a server running FTP as a service.

As the figure illustrates, to successfully transfer files, FTP requires two connections between the client and the server, one for commands and replies, the other for the actual file transfer.

FTP has many security weaknesses. Therefore, a more secure file transfer services should be used, such as one of the following:
- **File Transfer Protocol Secure (FTPS)** - An FTP client can request the file transfer session be encrypted. The file server can accept or deny the request.
- **SSH File Transfer Protocol (SFTP)** - As an extension to Secure Shell (SSH) protocol, SFTP can be used to establish a secure file transfer session.
- **Secure Copy (SCP)** - SCP also uses SSH to secure file transfers.

Replaced by cloud services like OneDrive in most applications with the exception of data security.

### [[Printers]]
A print server is a server that manages print requests and connects printers to a network.
Print servers enable multiple computer users to access a single printer. A print server has three functions:
- Provide client access to print resources.
- Administer print jobs by storing them in a queue until the print device is ready for them and then feeding or spooling the print information to the printer.
- Provide feedback to users.

### Mail
A mail server is responsible for sending, receiving, and managing emails. A mail server must be running a **specialized server package**, such as Microsoft Exchange, Sendmail, Postfix, or Exim, to be considered a mail server.

Email is a store-and-forward method of sending, storing, and retrieving electronic messages across a network. Email messages are stored in databases on mail servers.

Email clients communicate with mail servers to send and receive email. Mail servers communicate with other mail servers to transport messages from one domain to another. An email client does not communicate directly with another email client when sending email. Instead, both clients rely on the mail server to transport messages.

Email supports three separate protocols for operation: Simple Mail Transfer Protocol (SMTP), Post Office Protocol (POP), and Internet Message Access Protocol (IMAP). The application layer process that sends mail uses SMTP. A client retrieves email using one of the two application layer protocols: POP or IMAP.

### Syslog
The syslog server in a client-server model is responsible for **collecting information** obtained through system monitoring, such as **login events or errors**. Messages compiled in a syslog server include the facility code, the severity level, and a textual description of the logged events. Syslog servers are composed of **three primary components**: the listener, the database, and the management and filtering software.

The syslog logging service provides three primary functions:
- gather logging information for monitoring and troubleshooting
- select the type of logging information that is captured
- specify the destinations of captured syslog messages

### Web Servers
A web server listens for incoming requests. The requests are executed by the web server and provide the requested content, including text, images, videos, and the running of scripts. Common web server platforms include Microsoft’s Internet Information Services (IIS) and Apache.

Web resources are provided by a web server. The host accesses the web resources using the Hypertext Transfer Protocol (HTTP) or the secure HTTP (HTTPS). HTTP is a set of rules for exchanging text, graphic images, sound, and video on the World Wide Web. HTTPS adds encryption and authentication services using Secure Sockets Layer (SSL) protocol or the newer Transport Layer Security (TLS) protocol. HTTP operates on port 80. HTTPS operates on port 443.

To better understand how the web browser and web server interact, we can examine how a web page is opened in a browser. For this example, use the http://www.cisco.com/index.html URL.

First, the browser interprets the three parts of the URL:
1. **http** (the protocol or scheme)
2. www.cisco.com (the server name)
3. **index.html** (the specific filename requested)

#### [[HTTP]] Protocol
1. The browser then checks with a Domain Name Server (DNS) to convert www.cisco.com into a numeric address, which it uses to connect to the server. Using HTTP requirements, the browser sends a GET request to the server and asks for the index.html file, as shown in the next figure.
2. The server sends the HTML code for this web page back to the client’s browser, as shown in the next figure.
3. the browser interprets the HTML code and formats the page for the browser window.

### Proxy
A proxy server **makes requests for resources** on behalf of a client. The proxy server acts as an intermediary between the client and the target server.

A popular use for proxy servers is to act as storage or cache for web pages that are frequently accessed by devices on the internal network. For example, the proxy server in the figure is storing the web pages for www.cisco.com. When any internal host sends an HTTP GET request to www.cisco.com, the proxy server completes the following steps:
1. It intercepts the requests.
2. It checks to see if the website content has changed.
3. If not, the proxy server responds to host with the web page.

In addition, a proxy server can effectively hide the IP addresses of internal hosts because all requests going out to the internet are sourced from the proxy server’s IP address.

### Authentication, Authorization, and Accounting : [[AAA]]
An authentication, authorization, and accounting (triple A or AAA) server is an access control server that acts as a gatekeeper for critical network components. AAA servers are also known as domain controllers. Examples of AAA servers include remote access service (RAS), Remote Authentication Dial-In User Service : [[RADIUS]], Terminal Access Controller Access-Control System Plus : [[TACACS+]], and Kerberos.
The remote client goes through a four-step process to authenticate with a AAA server and gain access to the network.
1. The client establishes a connection with the router
2. The AAA router prompts the user for a username and password
3. The router authenticates the username and password using a remote AAA server
4. The user is provided access to the network based on the information in the remote AAA server.

### Endpoint Management
An endpoint management server is typically responsible for monitoring all the end devices in your network including desktops, laptops, servers, tablets, and any device connected to your network. An endpoint management server can restrict an end device’s connection to the network if the device does not meet certain predetermined requirements. For example, it can verify the devices has the latest operating system and anti-virus updates. Cisco’s Digital Network Architecture (DNA) Center is an example of a solution that provides endpoint management.

## Internet Appliances
An internet appliance is a device that aids in internet access and helps users access the internet safely.

### Spam Gateways
A spam gateway, also known as an **antispam gateway**, is an internet appliance whose purpose is to **block malicious emails** from accessing the network.

### Unified Threat Management : [[UTM]]
Unified threat management (UTM) acts to **centralize security management** on a network. UTM typically provides packeting filtering and inspection, IPS, gateway antimalware, spam blocking, malicious website blocking, and application control.

It is a generic name for an all-in-one security appliance. UTMs include all the functionality of an IDS/IPS as well as stateful firewall services. Stateful firewalls provide stateful packet filtering by using connection information maintained in a state table. A stateful firewall tracks each connection by logging the source and destination addresses, as well as source and destination port numbers.

In addition to IDS/IPS and stateful firewall services, UTMs also typically provide additional security services such as:
- Zero Day protection
- Denial of Service (DoS) and Distributed Denial of Service (DDoS) protection
- Proxy filtering of applications
- Email filtering for spam and phishing attacks
- Antispyware
- Network access control
- VPN services

These features can vary significantly, depending on the UTM vendor. In the firewall market today, UTMs are now typically called next-generation firewalls. 

#### VPN Concentrator 

### Load Balancers
A load balancer is responsible for **evenly distributing** requests over servers to balance the system. Common load balancing configurations include identical, cross-region, and content-based load balancing. 

Some examples include streaming media servers, web servers, and email servers. Often, multiple servers are providing one service in order to provide timely content. A load balancer can be used distribute the demand of requests. It is placed in front of the servers to ensure each server is being used as much as the others. This prevents things like network timeouts and slow responses. Some load balancers are able to track which servers are busy and able to send requests to servers that are not. 

## Embedded Systems
**Embedded systems** are devices other than computers that have computer technology running within. Like legacy systems, these may not be able to stay updated.

Embedded systems are related to legacy systems in that many legacy systems have embedded microchips. These embedded microchips are typically programmed to provide dedicated input and output instructions to a specialized device. Examples of embedded systems in the home are things such as a thermostat, refrigerator, cooking range, dishwasher, washing machine, video game consoles, and smart TVs. Embedded systems are increasingly becoming connected to the internet. Security should be top of mind when the technician recommends and installs embedded systems.

## Legacy
**Legacy systems** are older systems that for one reason or another have not been updated. It is usually due to essential applications that will not run on the updated platform. 

Legacy systems range from industrial control systems : [[ICS]] to computer mainframe systems, and a wide variety of networking devices such as hubs and bridges. Legacy systems are inherently vulnerable to security breaches because they cannot be upgraded or patched. One solution to alleviate some of the security risk is to air gap these systems. Air gapping is the process of physically isolating legacy systems from other networks and particularly the internet.

### Supervisory Control and Data Acquisition : [[SCADA]]
Supervisory control and data acquisition : [[SCADA]] is an example of a **critical legacy system category**. A SCADA system is a high-level management system used in an industrial control system : [[ICS]] to control manufacturing machines and processes, manage large-scale infrastructure settings, and run building components.

This type of system provides automation for critical services such as national security, water treatment plants, or power suppliers. SCADA software runs on a computer to gather data from the devices used by the ICS. The SCADA manages the devices remotely typically through the use of satellite or cellular communications.

### Internet of Things : [[IoT]] Devices
An internet of things (IoT) device connects to the network through a central controller or coordinating device. Common examples of IoT devices include **smart devices** such as thermostats and home automation and security devices.

The internet of today is significantly different than the internet of past decades. The internet of today is more than email, web pages, and file transfers between computers. The evolving internet is becoming an Internet of Things (IoT). No longer will the only devices accessing the internet be computers, tablets, and smartphones. The sensor-equipped, internet-ready devices of tomorrow will include everything from automobiles and biomedical devices, to household appliances and natural ecosystems.

You may already have some IoT devices in your home. You can buy all kinds of connected devices including thermostats, light switches, security cameras, door locks, and voice-enabled digital assistants (such as Amazon Alexis and Google Home). These devices can all be connected to your network. In addition, many of them can be directly managed from a smartphone app.

#### Devices in Packet Tracer
At this point in its infancy, the IoT market has not yet agreed upon a set of standards for IoT device installation and configuration. Configuring IoT devices is very much device specific. Consult the manufacturer’s documentation or website for configuration guides.

In this course, you will use Packet Tracer to explore a basic IoT device configuration. The figure shows all the IoT devices in Packet Tracer. Packet Tracer also includes a number of sensors and actuators.

---

## Basic Wired/Wireless Small Office/Home Office : [[SOHO]] Networks
When setting up a [[SOHO]] network, keep the following steps in mind:
- Understand relevant regulations.
- Make a map.
- Locate the server(s).
- Identify client computer locations.
- Locate network resources.
- Determine user connectivity type.
- Designate additional connectivity options if needed.

You must be able to install and configure basic wired and wireless SOHO networks. On the CompTIA A+ exam, these concepts will be addressed in scenario-based questions.

## Internet Protocol : [[IP]] Addressing
Internet protocol (IP) addressing is the assignment of a unique device identifier on a local network or the internet. The IP address is responsible for managing logical network addresses.

## Configurations
You must be able to **compare and contrast** common network configuration concepts for the CompTIA A+ exam.
### DNS
The domain name system : [[DNS]] has only one function: to **resolve hostnames to IP addresses**. DNS settings are usually given out via DHCP along with IP address information, but this can be done manually as well. This allows the user (client) to resolve domain names to IP addresses in order to perform searches or lookups. These are usually given out in a primary and secondary fashion for redundancy purposes.

#### Address
contained on the DNS server in **zone files**. The zone file maintains records of hostname-to-IP address mappings and contains information such as the name of the server or computer, internet protocol address, record type, computer address, and comments.

#### A
a common DNS record type and RR that signifies that the host record is an **IPv4** address.

#### AAAA
, pronounced “quad A”, is a common DNS record type and RR that signifies the host record is an **IPv6** address.

#### Mail Exchanger : [[MX]]
A mail exchanger (MX) record is a common DNS record type that signifies that the host record is the name or address of an email server. MX records include a priority value (lowest integer is preferred) when multiple email servers are available for redundancy.

#### Text : [[TXT]]
A text (TXT) record is a common DNS record type that signifies that the host record is a text record for human-readable or machine-readable data. Useful for identifying legitimate email servers from spam generating servers.

##### Spam Management
the process of determining if data is spam or valid.

The DNS service is commonly abused by threat actors to assist in their spam email campaigns. For this reason, DNS servers now implement the following anti-spam security features using TXT resource records.

###### DKIM
DomainKeys Identified Mail : [[DKIM]] is a type of spam management that authenticates using **encryption** through a public-private key pair.
- Is more advanced than SPF because it leverages cryptographic authentication using digital signatures instead of a list of authorized SMTP servers. 
- The TXT RR contains the public encryption key of the sending domain that external email servers use to validate the authenticity of the sending email server.
- DKIM can replace or be used with SPF

###### SPF
Sender Policy Framework : [[SPF]] is a spam management that authenticates an email server **based on its IP address**.
- It is a resource record that identifies SMTP email servers authorized to send emails for an organization.
- The RR includes the IP address and email server domain name that receiving servers use to determine legitimacy of emails. 
- There can only be one SPF RR per domain.
- The SPF can also indicate how to process unknown servers including rejecting them, flagging them, or accepting them.

###### DMARC
Domain-based Message Authentication, Reporting and Conformance (DMARC) is a type of spam management that **combines DKIM and SPF** in one framework and offers **more control** over what the user can do with spam email. It specifies additional policy information for non-compliant SPF and DKIM DNS queries. 

### Dynamic Host Protocol
[DHCP]
DHCP automatically assigns all of the settings needed to access resources on your LAN or the internet. It can provide IP address, subnet, gateway, and DNS information. If you want to ensure that a device gets a specific IP address, you can configure a DHCP reservation in the DHCP server.

#### Leases
A lease is a temporary IP configuration assigned by the DHCP server to a client. A lease typically includes an IP address, subnet mask, default gateway, and DNS server address.

#### Reservations
A reservation is the reserving of an IP address for a specific client based on the client’s [[#MAC Media Access Control|MAC]] address and is primarily used for devices that require a static IP address.

#### Scope
The scope is information provided outside the IP address and the subnet mask issued by the DHCP server, such as the default gateway, DNS server address, or domain name.

### Virtual [[#Local Area Network]]

A virtual local area network (VLAN) is a **logical subnet**, typically configured on a switch, that acts as a separate subnet. They allow an administrator to segment the ports on a single switch as if it were multiple switches. This provides more efficient forwarding of data by isolating traffic to only those ports where it is required. 

VLANs also allow end devices to be grouped together for administrative purposes. Without VLANs, every device connected to a switch would be on the same subnet. By configuring VLANs on the switch, you can have devices on that one switch in different subnets or VLANs.

VLANs provide segmentation and organizational flexibility in a switched network. A group of devices within a VLAN communicate as if each device was attached to the same switch. VLANs are based on logical connections, instead of physical connections. An administrator can segment VLANs based on factors such as function, team, or application, without regard for the physical location of the users or devices.

By default, all switch ports are assigned to VLAN 1. However, you can assign the PCs to different VLANs by configuring their interconnecting port.

Once the VLAN information is configured on the other switches, the faculty member using PC1 would be able to communicate with PC4 because they are on the same VLANs. If the faculty member wanted to send something to PC5 which is assigned to VLAN 30, then the services of a router would be required.

VLANs help reduce excessive broadcast traffic and implement access and security policies between groups of users.
![[VLAN.canvas|VLAN]]

### Virtual Private Network : [[VPN]]
A virtual private network (VPN) is an **encrypted connection** between two networks or between a host and a network. When a host connects to a network over a VPN, it is assigned a separate IP address that is in the network’s address range.
The most common type of VPN is used by teleworkers to access a corporate private network. Teleworkers are network users that are offsite or remote. In the figure, the fat links between Teleworker 1 and the router at the Company Headquarters represent a VPN connection.
![[VPN.canvas|VPN]]

## Types
For this exam, you should understand the specific networks and internet connections listed below and **understand the differences** between them.

### Internet Connection
Internet connection types are methods, either wired or wireless, through which a device can connect to the internet.

#### Satellite
A satellite connection is a wireless connection type that employs the use of satellites to achieve connectivity. Satellite connections are typically slower than wired broadband connections and require a satellite dish. Weather and misalignment can affect connectivity.

#### Fiber
A fiber connection is a type of wired connection that uses a fiber-optic cable made of thin flexible glass or plastic fiber surrounded by a rubberized outer sheath to send data via light signals. Fiber offers fast data transmission. There are **two types** of fiber varieties: **single-mode fiber (SMF)** and **multimode fiber (MMF)**. 

#### Cable
A cable connection is a type of wired connection that uses a cable, either **[[Copper Wiring#Coaxial|Coaxial]]** or [[Copper Wiring#Twisted Copper Pair|Twisted Pair]], for data transmission. Coax and twisted pair cables use different connector types and cable specifications. 
A cable internet connection does not use telephone lines. Cable uses coaxial cable lines originally designed to carry cable television. A cable modem connects your computer to the cable company. You can plug your computer directly into the cable modem. However, connecting a routing device to the modem allows multiple computers to share the connection to the internet.

#### [[DSL]]
A digital subscriber line : [[DSL]] is a type of **wired connection** that uses existing phone lines paired with a DSL modem to provide internet service.

#### Cellular
A cellular connection is a type of wireless connection type that uses a **provider’s cellular network** for connectivity.
It relies on cell towers distributed throughout the user’s coverage area to provide seamless access to cell phone services and the internet. With the advent of the third-generation (3G) of cellular technology, smartphones could access the internet. Download and upload speeds continue to improve with each iteration of cell phone technology.

In some regions of the world, smartphones are the only way users access the internet. In the United States, users are increasingly relying on smartphones for internet access. According to the Pew Research Center, in 2018 20% of adults in the United States do not use broadband at home (28% for adults 18-29). Instead, they use a smartphone for personal internet access. 

Performance will be limited by the capabilities of the phone and the cell tower to which it is connected. Cellular technology has evolved through multiple generations (the “G” in abbreviation).

##### 1G/2G
- The first generation (1G) of cell phones were analog voice calls only.
- introduced digital voice, conference calls, and caller ID.
- Speed: less than 9.6 Kb/s.
##### 2.5G
- supports web browsing, short audio and video clips, games, and downloads of applications and ring tones.
- Speed: 9.6 Kb/s to 237 Kb/s.
##### 3G
- supports full-motion video, streaming music, 3D gaming, and faster web browsing.
- Speed: 144 Kb/s to 2 Mb/s.
##### 3.5G
- supports high-quality streaming video, high-quality video conferencing, and Voice over IP (VoIP).
- VoIP is a technology that applies internet addressing to voice data.
- Speed: 400 Kb/s to 16 Mb/s.
##### 4G
- supports IP-based voice, gaming services, high-quality streamed multimedia, and Internet Protocol version 6 (IPv6). IPv6 is the newest version of internet addressing.
- No cell phone carriers could meet the 4G speed standards when first announced in 2008.
- Speed: 5.8 Mb/s to 672 Mb/s.
##### LTE
- Long Term Evolution (LTE) is a designation for a 4G technology that meets the 4G speed standards.
- An advanced version of LTE significantly improves the speeds while the user is moving at high speeds, such as in a car on the highway.
- Speed: 50 Mb/s to 100 Mb/s when mobile, and up to 1 Gb/s when stationary.
##### 5G
- The standard was ratified in June 2018 and is currently being implemented in select markets.
- supports a wide variety of applications including augmented reality (AR), virtual reality (VR), smart homes, smart cars, and any scenario where data transfer occurs between devices.
- Speed: 400 Mb/s to 3 Gb/s download; 500 Mb/s to 1.5 Gb/s upload.
##### 6G
- currently in development. As of late 2022, no standard yet exists. 
- will support even faster speeds required for AR/VR applications, artificial intelligence (AI) applications, and instantaneous communications.
- potential replacement for COX services

#### Wireless Internet Service Provider
[WISP] : A wireless connection type in which an internet service provider (ISP) offers connectivity using wireless technology. WISP connections are **fixed point-to-point connections**.

#### Broadband
uses different frequencies to send multiple signals over the same medium. For example, the coaxial cables used to bring cable television to your home can carry computer network transmissions at the same time as hundreds of TV channels. Your cell phone can receive voice calls while also using a web browser.
Some common broadband network connections include cable, [[#Digital Subscriber Line]], ISDN, [[#Satellite]], and [[#Cellular]].
### Topology
Network types define the general area that is covered by a network.

#### Local Area Network
[LAN] : a collection of devices connected to one another in **one physical area**, such as an office building, and can be small or large. The distinguishing characteristic for LANs today is that they are typically owned by an individual, such as in a home or small business, or wholly managed by an IT department, such as in a school or corporation.
![[LAN.canvas|LAN]]

#### Wide Area Network
[WAN] : a network that covers a **large geographical area** and is composed of multiple LANs. Individuals and organizations contract for WAN access from a service provider. The internet is the largest WAN.
![[WAN.canvas|WAN]]

#### Personal Area Network
[PAN] : composed of primarily **Bluetooth-connected devices**.
![[PAN.canvas|PAN]]

#### Metropolitan Area Network
[MAN] : a network larger than a LAN but smaller than a WAN and **limited to a smaller geographical area**, such as a city or a campus. The network consists of various buildings connected through wireless or fiber optic media.
![[MAN.canvas|MAN]]

#### Storage Area Network
[SAN] : a network area composed of **storage devices**.

#### Wireless [[#Local Area Network]]
[WLAN] : a LAN in which the **connections are wireless** rather than wired. A WLAN uses radio waves to transmit data between wireless devices.
![[WLAN.canvas|WLAN]]

#### Wireless Mesh Network
[WMN] : uses multiple access points to extend the WLAN. The topology uses a wireless router. The two wireless APs will extend the reach of the WLAN within a home. Similarly, business and municipalities can use WMNs to quickly add new areas of coverage.
![[WMN.canvas|WMN]]

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

### Punch-down Tool
used to **connect the exposed ends of a wire into a wiring harness**.

### Cable Tester
This device is used to certify that the cable meets the standards of the **wiring code** and to ensure it can be used for communication. It will identify broken wires or missing pin connections.

### Loopback Plug
a special cable that is wired to **transmit and receive on a single connector**. There are loopback plugs for different types of connectors, like USB or ethernet, for testing network interface cards (NICs).

### Network Test Access Port 
[Net TAP] : a hardware device that creates a copy of **network traffic** for use by monitoring devices without interfering with network traffic. A network TAP can be easily moved from location to location to identify problems.

---
# Legacy Connections
In the 1990s, internet speeds were slow compared to today, which now has the bandwidth to transmit voice and video, as well as data. A dial-up connection requires either an internal modem installed in the computer or an external modem connected by USB. The modem dial-up port is connected to a phone socket using an RJ-11 connector. Once the modem is physically installed it must be connected to one of the computer’s software COM ports. The modem must also be configured with local dialing properties such as the prefix for an outside line and the area code
The Set Up a Connection or Network Wizard is used to configure a link to the ISP server. Connecting to the internet has evolved from analog telephone to broadband:

**Analog Telephone**
Analog telephone internet access can transmit data over standard voice telephone lines. This type of service uses an analog modem to place a telephone call to another modem at a remote site. This method of connection is known as dialup.

Integrated Services Digital Network
[ISDN] : uses multiple channels and can carry different types of services; therefore, it is considered a type of broadband. ISDN is a standard that uses multiple channels to send voice, video, and data over normal telephone wires. ISDN bandwidth is larger than traditional dialup.

## Hotspot and Tethering
Many cell phones provide the ability to connect other devices, as shown in the figure. This connection, known as tethering, can be made using Wi-Fi, Bluetooth, or by using a USB cable. Once a device is connected, it is able to use the phone’s cellular connection to access the Internet. When a cellular phone allows Wi-Fi devices to connect and use the mobile data network, it is called a mobile hotspot.


---
# Nav
< [[Mobile Devices|Previous]] < ^ [[Navigation|Home]] ^ > [[Virtualization and Cloud Computing|Next]] >
