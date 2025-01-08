---
tags: 
parent docs:
  - "[[Hardware]]"
sibling docs: 
child docs: 
last updated: 2025-01-07T23:59:00
media:
---
# Nav
| < [[Computational Memory]] < | ^ [[Hardware]] ^ | > [[Cases]] > |

---
### Hard Drives
A hard drive is a **non-volatile storage device** designed for **quick access**. It is also known as a **hard disk drive (HDD)** or a **conventional drive** and uses a magnetic spinning internal platter to store memory.
HDDs are the traditional magnetic disk devices that have been used for years. Their storage capacity ranges from gigabytes (GBs) to terabytes (TBs). Their speed is measured in revolutions per minute (RPM). This indicates how fast the spindle turns the platters that hold the data. The faster the spindle speed, the faster a hard drive can find data on the platters. This can correspond to faster transfer speeds.

**Tape Drive**
Magnetic tapes are most often used for archiving data. At one time they were useful for backing up PCs, however as HDDs became cheaper, external HDD drives are now frequently used for this purpose. However, tape backups are still used in enterprise networks. Tape drives use a magnetic read/write head and removable tape cartridge, as shown in Figure 2. Although data retrieval using a tape drive can be fast, locating specific data is slow because the tape must be wound on a reel until the data is found. Common tape storage capacities vary between a few GBs to many TBs.
#### Speeds
The speed at which a HDD operates is measured by the number of **revolutions per minute (rpm)** that the platter of an HDD spins. Higher speeds use more energy and increase heat production. There are four HDD speeds: **5,400 rpm**, **7,200 rpm**, **10,000 rpm**, and **15,000rpm**.

#### Form Factor
The form factor refers to the **physical size of the hard drive**. Both form factors contain the same connectors.

**2.5”**—2.5” hard drives are typically used in **laptops**, can be mounted in a 3.5” form factor slot with the use of a converter kit.
**3.5”**—3.5” hard drives are typically used in **desktop** computers.

### Semiconductor Storage 
#### SSDs
A solid-state drive (SSD) is a semiconductor **flash memory technology** that contains no moving parts. Flash memory is a form of nonvolatile read/write memory. Nonvolatile memory **retains data when power is removed**. Flash **erases data in blocks**, rather than at the byte level. An SSD uses a series of NAND chips to store memory. SSDs can be made in smaller form factors than HDDs and are capable of much higher speeds.

#### Communications Interfaces
the method through which an SSD communicates with the motherboard and other components.

**NVMe**—**Non-volatile memory express** is an open-source standard used to optimize data transfer and can support speeds up to 3.5 GBps. This specification was developed specifically to allow computers to take greater advantage of the features of SSDs by providing a standard interface between SSDs, the PCIe bus, and operating systems. NVMe allows compliant SSD drives to attach to the PCIe bus without requiring special drivers, in much the same way that USB flash drives can be used in multiple computers without requiring installation on each.

**SSHDs—Solid State Hybrid Drives** are a compromise between a magnetic HDD and an SSD. They are faster than an HDD but less expensive than an SSD. They combine a magnetic HDD with onboard flash memory serving as a non-volatile cache. The SSHD drive automatically caches data that is frequently accessed, which can speed up certain operations such as operating system start up.

**SATA**—The **serial AT attachment** interface is the slowest of the SSD interfaces.

**PCIe**—**Peripheral component interconnect express** offers faster speeds than SATA but slower than NVMe.

#### Form Factors
The shape and size of the SSD.

**M.2**—M.2 is a form factor for SSDs. It is 22 mm wide and can vary in length, with the most common lengths being 80 mm and 60 mm. It is referred to as “gumstick memory” because its size is similar to a stick of gum. M.2 drives plug into an M.2 slot on a motherboard.

**mSATA**—**Mini-serial ATA** is a form factor for SSDs. mSATAs have a 30-mm wide, 52-pin connector and use the SATA interface for communication. mSATAs can be either 30 mm x 50.95 mm or 30 mm x 26.8 mm.

### Drive Configurations
Storage devices can be configured for high availability so that if one disk in an array of disks fails, data is not lost. The most common configuration is known as redundant array of independent (or inexpensive) disks (RAID).

#### Redundant Array of Independent/Inexpensive Disks (RAID) 0, 1, 5, 10
There are different RAID configurations, known as RAID 0, 1, 5, 10, that provide different levels of data protection. **Striping** is a method of storing part of the data on each drive in an array. **Mirroring** is keeping a full copy of a disk on another disk.

RAID 0: offers striping of data only; no redundancy; good performance
RAID 1: offers mirroring of data only; requires more storage space to store full copies of data
RAID 5: offers striping with parity; minimum of three drives; ability to calculate missing data and rebuild
RAID 10: offers striping and mirroring for full redundancy; minimum of four drives

### Removable Storage
Removable storage devices are not contained internally but externally and can be relocated.

#### Flash Drives
Flash drives are removable storage devices that are capable of containing a large quantity of information in a **non-volatile, small, and portable** form. Flash memory devices include SD cards, USB flash drives, and optical cards.

#### Memory Cards
A memory card is a **flash memory** device that can **store data in a non-volatile state**. Common memory card form factors include SD, CF, micro-SD, mini-SD, and xD.

#### Optical Cards
**flash storage** devices that store data through the use of **lasers** on spinning discs. Examples of optical cards include CDs, DVDs, and BDs. Optical drives are a type of removable media storage device that use lasers to read and write data on optical media. They were developed to overcome the storage capacity limitations of removable magnetic media such as floppy discs and magnetic storage cartridges.

##### Types of Optical Media
**Compact Disc (CD)** - audio and data
**Digital Versatile Disc (DVD)** - digital video and data
**Blu-ray Disc (BD)** - HD digital video and data

CD,DVD, and BD media can be pre-recorded (read only), recordable (write once), or re-recordable (read and write multiple times). DVD and BD media can also be single layer (SL) or dual layer (DL). Dual layer media roughly doubles the capacity of a single disc. 
The table describes the various types of optical media and their approximate storage capacities.

| Optical Media | Description                                                          | Storage Capacity         |
| ------------- | -------------------------------------------------------------------- | ------------------------ |
| CD-ROM        | memory media, pre-recorded (read only)                               | 700 MB                   |
| CD-R          | memory media, recordable (write once)                                | 700 MB                   |
| CD-RW         | memory media, re-recordable (read and write multiple times)          | 700 MB                   |
| DVD-ROM       | memory media, pre-recorded (read only)                               | 4.7 GB (SL), 8.5 GB (DL) |
| DVD-RAM       | memory media, re-recordable (read and write multiple times)          | 4.7 GB (SL), 8.5 GB (DL) |
| DVD+/-R       | memory media, recordable (write once)                                | 4.7 GB (SL), 8.5 GB (DL) |
| DVD+/-RW      | memory media, re-recordable (read and write multiple times)          | 4.7 GB (SL), 8.5 GB (DL) |
| BD-ROM        | various media (games, movies, or software), pre-recorded (read only) | 25 GB (SL), 50 GB (DL)   |
| BD-R          | memory media, recordable (write once)                                | 25 GB (SL), 50 GB (DL)   |
| BD-RE         | memory media, re-recordable (read and write multiple times)          | 25 GB (SL), 50 GB (DL)   |
#### Media Reader
Many digital devices such as cameras, smart phones, and tablets use media cards to store information, music, pictures, videos, data, and more.

Several media card formats have been developed over the years including:

- **Secure digital (SD)** - SD cards were designed for use in portable devices such as cameras, MP3 players, and laptops. SD cards can hold as much as 2 TB of data.
- **MicroSD** – This is a much smaller version of SD, commonly used in smartphones and tablets.
- **MiniSD** – A version of SD between the size of an SD card and a microSD card. The format was developed for mobile phones.
- **CompactFlash** - CompactFlash is an older format, but still in wide use because of its high speed and high capacity (up to 128 GB is common). CompactFlash is often used as storage for video cameras.
- **Memory** **Stick** – Created by Sony Corporation, Memory Stick is a proprietary flash memory used in cameras, MP3 players, hand-held video game systems, mobile phones, cameras, and other portable electronics.
- **xD** – Also known as Picture Card, it was used in some digital cameras.