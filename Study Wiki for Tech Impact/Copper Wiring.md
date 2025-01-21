---
tags: 
parent docs:
  - "[[Cabling and Ports]]"
sibling docs: 
child docs: 
last updated: 2025-01-13T00:29:00
media:
---
# Cat Cabling 

## **Coaxial**
A **coaxial cable** is a single copper-cored cable contained in an inner insulation layer. This inner layer is further contained in a wire mesh conductor. The entire cable is then further protected in an outer insulation layer. Coaxial cables are not as commonly used in modern networks, but some usage may still be seen with cable and satellite devices. Coaxial cables are specified by the **Radio Guide (RG) system**. For the purpose of the test, you need to be familiar with **RG-6**, which is made of a solid copper core used with satellite/cable modems, and **RG-59**, which is made of a solid copper core and used for cable television. used for broadband networks, and long distances.

Coaxial cable (or coax) carries data in the form of electrical signals. It provides improved shielding compared to unshielded twisted-pair (UTP), so it has a higher signal-to-noise ratio allowing it to carry more data. However, twisted-pair cabling has replaced coax in LANs because, when compared to UTP, coax is physically harder to install, more expensive, and harder to troubleshoot.

**Coax Cable Construction** Coax cable with the outer jacket pulled back to reveal the braided shielding and copper core conductor.

**RG-6** RG-6 cable is heavy gauge and has insulation and shielding tuned for high-bandwidth, high-frequency applications such as Internet, Cable TV, and Satellite TV signals. RG-6 commonly uses an F-Type connector, as shown in the figure.

**RG-59** RG-59 cable is thinner than RG-6 and has less shielding. RG-59 is recommended in low bandwidth and lower frequency applications such as analog video and CCTV applications. RG-59 commonly uses a BNC connector as shown in the next figure.

**British Naval (BNC)** BNC connectors connect coaxial cables to devices using a quarter-turn connection scheme. BNC is used with digital or analog audio, or video.

## Twisted Copper Pair
Twisted-pair is a type of copper cabling used for telephone communications and most Ethernet networks. The cable consists of pairs of individual wires twisted into pairs that are then twisted together, which is twisted to provide protection against [[crosstalk]] The cable is contained within an insulated jacket. **Ethernet cables** are twisted pairs. 

There are two types of twisted copper pairs: shielded twisted pair (STP) and unshielded twisted pair (UTP), with UTP being the most common. The twisting of wire pairs helps reduce crosstalk and electromagnetic induction. Both UTP and STP cables are terminated with an RJ-45 connector and plug into RJ-45 sockets, as shown in the next figure. Compared to UTP cable, STP cable is significantly more expensive and difficult to install. To gain the full benefit of the shielding, STP cables are terminated with special shielded STP RJ-45 data connectors (not shown). If the cable is improperly grounded, the shield may act as an antenna and pick up unwanted signals.

**RJ-11 Connector** Older telephone networks used a four-wire UTP cable with two wire pairs terminated with a 6-pin RJ-11 connector. The RJ-11 connector looks very similar to the RJ-45 connector but is smaller.

**RJ-45 Connector** Each end of a UTP cable must be terminated with a connector. In the case of Ethernet networks, it is an RJ-45 connector that terminates the cable and is plugged into an Ethernet port.

### Unshielded Twisted Pair
An unshielded twisted pair (UTP) is made of two to four pairs of twisted wires. The pairs of wires in UTP cables are twisted in direct contact with one another. Each wire in twisted pairs is contained within an insulating layer, preventing copper from directly touching copper. UTP does not protect against electromagnetic interference : [[EMI]] or radio frequency interference : [[RFI]]. [[EMI]] and RFI can be caused by a variety of sources including electric motors and fluorescent lights.

### Shielded Twisted Pair
A shielded twisted pair (STP) is made of two to four pairs of twisted wires. Each pair is contained in a layer of braided foil sheathing before being twisted with the other pairs in the cable. This reduces electrical interference. STP is used in Cat 7 and Cat 8 cables.


**Direct burial**
the practice of burying cables underground. Direct burial cables should be STP cables with an extra waterproof sheathing. It is recommended that direct burial be between six and eight inches underground in a protective PVC pipe and placed away from any other lines that contain electrical current.

#### Plenum
Plenum is a **Teflon-type covering** used to cover all types of network cables. Plenum is used in cables that may be exposed to extreme heat or have the possibility of releasing gasses into a ventilation system, such as in ceilings.

### Category Ratings
New or renovated office building often have some type of UTP cabling that connects every office. The distance limitation of UTP cabling used for data is 100m or 330ft. 

Each category also comes in [[#Plenum]] rated versions, which are inside plenum areas of buildings. A plenum is any area that is used for ventilation, such as the area between ceiling a drop-ceiling. 

| Type  | Speed                                | Features                                                                                                                                                                                                                                                                                                                                                  | Distance          |
| ----- | ------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------- |
| Cat5  | 100 Mb/s at 100 MHz                  | first widely adopted 4 pair UTP that replaced Cat3 UTP in Ethernet LANs, manufactured with higher standard that Cat3 to allow for higher data transfer rates                                                                                                                                                                                              | 100m              |
| Cat5e | 1 Gb/s at 100 MHz                    | manufactured with higher standard that Cat5 to allow for higher data transfer rates, more twists per foot that Cat5 to better prevent [[EMI]] and [[RFI]] from outside sources                                                                                                                                                                            | 100m              |
| Cat6  | 1 Gb/s at 250 MHz (Cat6a at 500 MHz) | manufactured with higher standard that Cat5e to allow for higher data transfer rates, more twists per foot that Cat5e to better prevent [[EMI]] and [[RFI]] from outside sources, good choice for customers using applications that require large amounts of bandwidth, such as video-conferencing or gaming, better insulation and performance than Cat6 | 55m (Cat6a  100m) |
## Wiring Schemes
Twisted pair wires are **color coded** for proper referencing. T568A and T568B are the two standards used for RJ-45 wiring connectors.  Each wiring scheme defines the pinout, or order of wire connections, on the end of the cable. Only the orange pair and green pair are reversed between T568A and T568B.

Compare the pinouts for the green and orange pairs in the following figures. On a network installation, one of the two wiring schemes (T568A or T568B) should be chosen and followed. It is important that the same wiring scheme is used for every termination in that project. If working on an existing network, use the wiring scheme that already exists.

### T568A 
1. White/Green
2. Green
3. White/Orange
4. Blue
5. White/Blue
6. Orange
7. White/Brown
8. Brown

### T568B
1. White/Orange
2. Orange
3. White/Green
4. Blue
5. White/Blue
6. Green
7. White/Brown
8. Brown

## Building and Testing
1. Cut cable to desired length
2. strip back sheathing 1 1/4in to expose wires
4. untwist and straighten wire pairings and cut pull string
5. organize wires by either T568A/B wiring schemes
6. cut any extra wire
7. slide on RJ45 connector and ensure it reaches the end
8. crimp wires using crimper
9. test wire for continuity 