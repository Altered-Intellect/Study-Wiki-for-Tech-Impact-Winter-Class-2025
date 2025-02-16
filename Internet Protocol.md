---
tags: 
parent docs: 
sibling docs: 
child docs: 
media:
---

IP addressing is assigned by network administrators based on the location within the network. When a device moves from one network to another, its IP address will most likely change. An IP version 4 (IPv4) address is 32 bits and represented in dotted decimal notation. An IP version 6 (IPv6) address is 128 bits and is represented in hexadecimal format.

### Laptop Addressing Information

Today, your computer probably has an IPv4 and an IPv6 address, as shown for the laptop in the figure. In the early 1990s, there was a concern about running out of IPv4 network addresses. The Internet Engineering Task Force (IETF) began to look for a replacement. This led to the development of IPv6. Currently, IPv6 is operating alongside IPv4 and is beginning to replace it.

The Figure shows output for the command **ipconfig /all** on the laptop. The output is highlighted to show the MAC address and two IP addresses.

**Note**: Windows OS calls the NIC an Ethernet adapter and the MAC address a physical address.

````
C:\> ipconfig /all 

Windows IP Configuration  
Host Name . . . . . . . . . . . . : ITEuser 
Primary Dns Suffix  . . . . . . . : 
Node Type . . . . . . . . . . . . : Hybrid 
IP Routing Enabled. . . . . . . . : No 
WINS Proxy Enabled. . . . . . . . : No 

Ethernet adapter Local Area Connection:  
Connection-specific DNS Suffix  . : 
Description . . . . . . . . . . . : Intel(R) PRO/1000 MT Network Connection 
Physical Address. . . . . . . . . : 00-50-56-BE-D7-87 
DHCP Enabled. . . . . . . . . . . : No 
Autoconfiguration Enabled . . . . : Yes 
IPv6 Address. . . . . . . . . . . : 2001:db8:cafe:200::8(Preferred) 
Link-local IPv6 Address . . . . . : fe80::8cbf:a682:d2e0:98a%11(Preferred) 
IPv4 Address. . . . . . . . . . . : 192.168.200.8(Preferred) 
Subnet Mask . . . . . . . . . . . : 255.255.255.0 
Default Gateway . . . . . . . . . : 2001:db8:cafe:200::1     192.168.200.1 

C:\>
````

# IPv4
An IPv4 address is a **32-bit hierarchical address** that identifies a host on a network and is typically written in dotted-decimal notation. The 32-bit address is divided into 4 bytes, or octets, containing 8 bits each (ex: 192.168.10.55). Therefore, the 32-bit address 192.168.200.8 has four octets. IPv4 addresses are divided into designated classes, A, B, C, D, E, and F, based on the first 3 bits of the IP address. IPv4 addresses are **finite** and are running out.

**Private addresses**—A private IP address is **not routable** on the internet.
**Class A :** 10.0.0.0–10.255.255.255
**Class B :** 172.16.0.0–172.31.255.255
**Class C :** 192.168.0.0.–192.168.255.255

An IPv4 address is composed of two parts. The first part identifies the network. The second part identifies this device on the network. The subnet mask is used by the device to determine the network. For example, the computer in the figure uses the subnet mask 255.255.255.0 to determine that the IPv4 address 192.168.200.8 belongs to the 192.168.200.0 network. The .8 portion is this device’s unique host portion on the 192.168.200 network. Any other device with that same 192.168.200 prefix will be on the same network but have a different value for the host portion. Devices with a different prefix will be on a different network.

To see this at the binary level, you can convert the 32-bit IPv4 address and subnet mask to their binary equivalents, as shown in table below. A one bit in the subnet mask means that bit is part of the network portion. So, the first 24 bits of the 192.168.200.8 address are network bits. The last 8 bits are host bits.

| Decimal IP      | Network                    | Host       |
| --------------- | -------------------------- | ---------- |
| 192.168.200.008 | 11000000.10101000.11001000 | .000010000 |
| 255.255.255.0   | 11111111.11111111.11111111 | .000000000 |
| 192.168.200.0   | 11000000.10101000.11001000 | .000000000 |
determine whether to send data directly to the intended receiver or to a router. It will send it directly to the receiver if the receiver is on the same network. Otherwise, it will send the data to a router. A router then uses the network portion of the IP address to route traffic between different networks.

For example, if the Windows computer in figure above has data to send to a host at 192.168.200.25, it sends the data directly to that host because it has the same prefix of 192.168.200. If the destination’s IPv4 address is 192.168.201.25, then the Window’s computer will send the data to a router.

**Public addresses**—Public addresses are **routable on the internet**. Public addresses are purchased and **only one computer** can hold any given public address at a time.

## NAT : Network Address Translation
On a wireless router, if you look for a page like the Status tab, you will find the IPv4 addressing information that the router uses to send data to the internet. Notice that the IPv4 address is 209.165.201.11 is a different network than the 10.10.10.1 address assigned to the router’s LAN interface. All the devices on the router’s LAN will get assigned addresses with the 10.10.10 prefix.

The 209.165.201.11 IPv4 address is publicly routable on the internet. Any address with the 10 in the first octet is a private IPv4 address and cannot be routed on the internet. Therefore, the router will use a process called Network Address Translation (NAT) to convert private IPv4 addresses to Internet-routable IPv4 addresses. With NAT, a private (local) source IPv4 address is translated to a public (global) address. The process is reversed for incoming packets. The router is able to translate many internal IPv4 addresses into public addresses, by using NAT.

Some ISPs use private addressing to connect to customer devices. However, eventually, your traffic will leave the provider’s network and be routed on the internet. To see the IP addresses for your devices, search the internet for “what is my IP address.” Do this for other devices on the same network and you will see that they all share the same public IPv4 address. NAT makes this possible by tracking the source port numbers for every session established by a device. If your ISP has IPv6 enabled, you will see a unique IPv6 address for each device.

# IPv6
IPv6 addresses are **128-bit addresses** expressed in **hexadecimal notation** and are composed of eight 16-bit fields separated by colons (ex: 2001:0db8:3c4d:0012:0000:0000:1234:56ab, which can be reduced to 2001:db8:3c4d:12::1234:56ab)

determine whether to send data directly to the intended receiver or to a router. It will send it directly to the receiver if the receiver is on the same network. Otherwise, it will send the data to a router. A router then uses the network portion of the IP address to route traffic between different networks.

For example, if the Windows computer in figure above has data to send to a host at 192.168.200.25, it sends the data directly to that host because it has the same prefix of 192.168.200. If the destination’s IPv4 address is 192.168.201.25, then the Window’s computer will send the data to a router.

## Compression
**Rule 1 - Omit Leading 0s**
The first rule to help reduce the notation of IPv6 addresses is to omit any leading 0s (zeros) in any 16-bit section. For example, in the example above:
- **0db8** can be represented as **db8**, in the first IPv6 address
- **0123** can be represented as **123**, in the second IPv6 address
- **0001** can be represented as **1**, in the third IPv6 address

**Note**: IPv6 addresses must be represented in lowercase letters, but you may often see them as uppercase.

**Rule 2 – Omit All 0 Segments**
The second rule to help reduce the notation of IPv6 addresses is that a double colon (::) can replace any group of consecutive zeros. The double colon (::) can only be used once within an address, otherwise there would be more than one possible resulting address.

The following table show examples of how to use the two rules to compress the IPv6 addresses shown in the example above.

| ---            | IPv6                                                            | ---                                                     | ---                                                                 |
| -------------- | --------------------------------------------------------------- | ------------------------------------------------------- | ------------------------------------------------------------------- |
| Fully Expanded | 2001:**0**DB8:**000**0:1111:**000**0:**000**0:**000**0:**0**200 | fe80:**000**0:**000**0:**000**0:**0**123:4567:89ab:cdef | ff02:**000**0:**000**0:**000**0:**000**0:**000**0:**000**0:**000**1 |
| No Leading 0s  | 2001: DB8:   0:1111:   0:   0:   0: 200                         | fe80:   0:   0:   0: 123:4567:89ab:cdef                 | ff02:   0:   0:   0:   0:   0:   0:   1                             |
| Compressed     | 2001:DB8:0:1111::200                                            | fe80::123:4567:89ab:cdef                                | ff02::1                                                             |

# [[Automatic Private IP Addressing|APIPA]]
Assigns an IP address to a device that was not assigned a static or dynamic IP address. The address will be **in the 169.254.0.0 network**. This is generally not useful, other than being an indication that the device failed to get an IP address through normal means. These addresses are also referred to as link-local addresses.

### Link-local IPv4 and IPv6 Addresses
Link-local addresses for IPv4 and IPv6 are used by a device to communicate with other computers connected to the same network within the same IP address range. The major difference between IPv4 and IPv6 is the following:
- An IPv4 device uses the link-local address if the device cannot obtain an IPv4 address.
- An IPv6 device must always be dynamically or manually configured with a link-local IPv6 address.

**IPv4 Link-Local Address**
If your Windows computer cannot communicate with a DHCP server to obtain an IPv4 address, then Windows automatically assigns an [[Automatic Private IP Addressing]] (APIPA) address. This link-local address is in the range of 169.254.0.0 to 169.254.255.255.

**IPv6 Link-Local Address**
Like IPv4, the IPv6 link-local address enables your device to communicate with other IPv6-enabled devices on the same network and only on that network. Unlike IPv4, every IPv6 enabled device is required to have a link-local address. IPv6 link-local addresses are in the range of fe80:: to febf::. For example, even though the links to other networks are down (not connected), all the devices on the LAN can still use link-local IPv6 addresses to communicate with each other.

**Note**: Unlike IPv4 link-local addresses, IPv6 link-local addresses are used in a variety of processes including network discovery protocols and routing protocols.

## Static
A static address is one that is **set manually** by a user or administrator. A device that is assigned a static address will keep that address until someone changes the configuration.

In a small network, you can manually configure each device with proper IP addressing. You would assign a unique IP address to each host within the same network. This is known as static IP addressing.

On a Windows computer, you can assign the following IPv4 address configuration information to a host:
- **IP address** - identifies this device on the network
- **Subnet mask** - is used to identify the network on which this device is connected
- **Default gateway** - identifies the router that this device uses to access the internet or another network
- **Optional values** - such as the preferred Domain Name System (DNS) server address and the alternate DNS server address

## Dynamic
A dynamic address is one that is **automatically assigned**, typically by a router or DHCP server. The next time a device that was dynamically assigned an IP address joins the network, it may be assigned a different IP address.

Rather than manually configure every device, you can take advantage of implementing a Dynamic Host Configuration Protocol (DHCP) server. A DHCP server automatically assigns IP addresses, which simplifies the addressing process. Automatically configuring some of the IP addressing parameters also reduces the possibility of assigning duplicate or invalid IP addresses.

By default, most host devices are configured to request IP addressing from a DHCP server. The default setting for a Windows computer is shown in the figure. When a computer is set to obtain an IP address automatically, all other IP addressing configuration boxes are not available. This process is the same for a wired or wireless NIC.

A DHCP server can automatically assign the following IPv4 address configuration information to a host:
- IPv4 address
- Subnet mask
- Default gateway
- Optional values, such as a DNS server address

DHCP is also available for automatically assigning IPv6 addressing information.

**Note**: The steps to configure a Windows computer is beyond the scope of this topic.

## Gateway
A gateway is a **router that connects your network** to another network, typically the Internet. When configuring a device on the network, you specify the internal IP address of the gateway as a default destination to send traffic.

## Subnet Mask
Separated into a network and host section, used to differentiate network class

|     |     | Network | Host |             |
| --- | --- | ------- | ---- | ----------- |
| 192 | 168 | 0       | 1    | IP 1        |
| 255 | 255 | 0       | 0    | Subnet mask |
| 192 | 168 | 15      | 0    | IP 2        |

## Public 

Ranges
- 1.0.0.0 - 9.255.255.255
- 11.0.0.0 - 126.255.255.255
- 129.0.0.0 - 169.253.255.255
- 169.255.0.0 - 172.15.255.255
- 172.32.0.0 - 191.0.1.255
- 192.0.3.0 - 192.88.98.255
- 192.88.100.0 - 192.167.255.255
- 192.169.0.0 - 198.17.255.255
- 198.20.0.0 - 223.255.255.255

172.16.x.x - 172.31.x.x  and 172.10.x.x.x are Private
## Private
- 10.0.0.0 - 10.255.255.255
- 127.0.0.0 - 128.255.255.255
- 169.254.0.0 - 169.254.255.255
- 172.16.0.0 - 172.31.255.255
- 191.0.2.0 - 191.0.2.255
- 
## [[Binary]]
0,1

| Decimal | 128 | 64  | 32  | 16  | 8   | 4   | 2   | 1   |
| ------- | --- | --- | --- | --- | --- | --- | --- | --- |
| 54      | 0   | 0   | 1   | 1   | 1   | 0   | 0   | 0   |
| 255     | 1   | 1   | 1   | 1   | 1   | 1   | 1   | 1   |
| 190     | 1   | 0   | 1   | 1   | 1   | 1   | 1   | 0   |
| 15      | 0   | 0   | 0   | 0   | 1   | 1   | 1   | 1   |

## [[Hexadecimal]] 
0,2,3,4,5,6,7,8,9,A,B,C,D,E,F

| Decimal | Binary   | 4,096 | 256 | 16  | 1   |
| ------- | -------- | ----- | --- | --- | --- |
| 100     | 11000010 | 0     | 0   | 6   | 4   |
| 255     | 11111111 | 0     | 0   | F   | F   |
| 175     | 10101111 | 0     | 0   | A   | F   |

