---
tags: 
parent docs:
  - "[[Peripherals]]"
  - "[[Navigation]]"
sibling docs: 
child docs: 
media:
---
Computer technicians are often required to select, purchase, and install printers for the users. Technicians need to know how to configure, troubleshoot, and repair the most common types of printers. Most printers available today are usually either laser printers using imaging drums or inkjet printers using electrostatic spray technology. Dot matrix printers using impact technology are used in applications that require carbon copies. Thermal printers are commonly found in retail. Many are used to print receipts. 3D printers are used in design and manufacturing.

# Characteristics

**Speed and Quality**
Printer speed is a factor to consider when selecting a printer. The speed of a printer is measured in pages per minute (PPM). Printer speed varies between makes and models. Speed is also affected by the complexity of the image and the quality desired by the user. The quality of printing is measured in dots per inch (dpi). The larger the dpi number, the better the image resolution. When the resolution is higher, text and images are clearer. To produce the best high-resolution images, use high-quality ink or toner and high-quality paper.

**Color**
The color printing process uses the primary colors cyan, magenta, and yellow (CMY). For inkjet printing, the color black serves as the base or key color. Thus, the acronym CMYK refers to the inkjet color printing process. 


**Unboxing and Setup**
When installing a multi-function device or printer, read the **manufacturer’s instructions** first. The next step is to evaluate the **needs of the user**, the **demands** that will be placed on the device, and the most appropriate **location** for maximized efficiency. When **unboxing** the device, be sure to open the box on a stable flat surface. Avoid banging or dropping the device. Lift the device out in the proper orientation to avoid tipping the device, which is particularly important with printers that use toner cartridges.

## Reliability
A printer should be reliable. Because so many types of printers are on the market, research the specifications of several printers before selecting one. Here are some manufacturer options to consider:
- **Warranty** - Identify what is covered within the warranty.
- **Scheduled** **servicing** - Servicing is based on expected usage. Usage information is in the documentation or on the manufacturer’s website.
- **Mean time between failures (MTBF)** - The printer should work without failing for an average length of time. This information is in the documentation or on the manufacturer's website.

## Cost
When buying a printer, there is more than just the initial cost of the printer to consider. The total cost of ownership (TCO) includes a number of factors:

- Initial purchase price
- Cost of consumable supplies, such as paper and ink
- Pages per month
- Price per page
- Maintenance costs
- Warranty costs

When calculating the TCO, consider the amount of printing required and the expected lifetime of the printer.

##### Printer Control Language (PCL) vs. PostScript
Printer control language (PCL) and PostScript are two printer communication languages. **PostScript** is an older technology and is device independent, which allows for print jobs to result in the same output regardless of the printer used. **PCL** is a newer and more common printing language that is device dependent. This means that the printer itself is responsible for some of the printing data, which may result in slightly different outputs depending on the printer used.

### [[Cabling and Ports]]
A printer’s interface is the hardware and software that a printer uses to connect with devices or a network. The hardware interface used by a printer is commonly called the **port**. A printer can only be used with the correct interface.

#### USB
The USB connection is the **most common** wired connection method for printers. A USB port will allow for the connection of a physical USB cable to the appropriate device. When a USB device is added to a computer system that supports plug-and-play, the device is automatically detected and starts the driver installation process.

#### Ethernet
Printers that are designed to work on a network will have an **RJ-45 ethernet** connector. They connect to the network with an ethernet cable, just as a computer would. They are easily shared since they are connected directly to the network. Connecting a printer to the network requires cabling that is compatible with both the network and the network port installed in the printer.

#### Serial
A serial connection can be used for dot matrix printers because the printers do not require high-speed data transfer. A serial connection for a printer is often referred to as COM. Serial ports are generally found on legacy computer systems.

#### Parallel
The data transfer path is wider than the serial data transfer path, allowing data to move more quickly to or from the printer.

IEEE 1284 is the standard for parallel printer ports. Enhanced Parallel Port (EPP) and Enhanced Capabilities Port (ECP) are two modes of operation within the IEEE 1284 standard that allow bidirectional communication. A parallel connection for a printer is often referred to as LPT. Parallel ports are generally found on legacy computer systems.

#### FireWire
Also known as i.LINK or IEEE 1394, is a high-speed communication bus that is platform independent. FireWire connects digital devices such as printers, scanners, cameras, and hard drives.

#### Wireless
Many printers come with built-in wireless capability which enables them to be connected to a Wi-Fi network. Wireless connections to printers may be made via [[Bluetooth]], [[802.11]], or a direct ad hoc connection.

Wireless printers enable hosts to connect and print wirelessly using Bluetooth or a Wi-Fi connection. For wireless printers to use Bluetooth, both the printer and the host device must have Bluetooth capabilities and be paired. If necessary, you can add a Bluetooth adapter to the computer, usually in a USB port. Wireless Bluetooth printers also allow for printing from mobile devices.

Wireless printers that use Wi-Fi connect directly to a wireless router or access point. Setup is completed by connecting the printer to the computer with the supplied software or using the printer display panel to connect to the wireless router. The printer’s wireless adapter will support an 802.11 standard. The devices connecting to the printer must also support the same standard.

In wireless infrastructure mode, the printer is configured to connect to an access point. Client connections to the printer go through the access point. In wireless ad-hoc mode, client devices connect directly to the printer.

### Public/Shared Devices
Devices can be shared by multiple users over wired or wireless connections. Users can connect directly to a printer or through a **print server** or **cloud** printing service. Small office/home office (SOHO) devices can be made available and shared with anyone on a network. This is true for devices that are connected directly to the network or connected to a computer. If a printer is connected to a computer, then the operating system must be configured to make the printer available to users on the network.

#### Printer Share
Printer share is the process of providing access to a printer to other computers and devices on a network.

#### Print Server
A print server sits on the network and handles printing requests from users. It can **spool** (temporarily store) requests for printers that are busy, allow prioritization of print jobs, and delete jobs after they’ve been sent. Print servers may be **separate devices or integrated** into the printer.

### Configuration Settings
The settings within a printer that can be optimized to best suit the needs of the users. Configuration settings can be accessible to all users or restricted to authorized users only.

#### Duplex
Enabling duplex mode causes the printer to **print on both sides** of the paper.

#### Orientation
There are two options for orientation: portrait or landscape. In **portrait mode**, the top of the page is the shorter dimension. This is how pages are typically printed. In **landscape mode**, the top of the page is the longer dimension. Spreadsheets and slides are often printed in landscape mode.

#### Tray Settings
The tray settings control how the printer manages the individual paper trays in the device.

#### Print Quality
**Print quality** settings control resolution and color. **Resolution** is expressed in **dots per inch (dpi)**. Higher resolutions provide better quality printouts. **Color settings** control how vivid the color output is.

### Security
Giving access to users over the network raises concerns over **data privacy**. Steps must be taken to ensure that users cannot read other users’ print jobs.

#### User Authentication
Users can be required to authenticate to print servers. They typically authenticate at one of **two security levels: user or administrator**. Users are limited to printing and managing their own print jobs. This prevents other users from seeing or interfering with other users’ print jobs. Administrators can manage all print jobs.

#### Badging
a function that can be used for the security of a printer. An attached badge scanner is used to access secure printing functions.

#### Audit Logs
Keep a record of all print jobs along with the originating location of the print jobs for later auditing.

#### Secured Prints
Printouts that **require authentication** at the physical printer before a print job commences. This ensures that the intended recipient of the print must be present to reduce the likelihood of another unauthorized user from grabbing or seeing a sensitive print.

### [[Networks]] Scan Services
Network scan services are hardware and software functions designed to input or scan documents. Scans taken on a printer or scanning device can be set to record the scanned information in a specified manner.

It is possible to configure the MFD as a device on the network, just like a networked printer to provide scanning and copying to network locations rather than simply copying to paper. There are three popular places to direct these scans:

#### Email
**Scan to email** occurs when a printer/scanner is instructed to send the scanned image or document to a specific email address or group of addresses, typically in a PDF file. The scan will be created as a file attachment in an email. The scanning prompts will ask for the hostname or IP address of the SMTP server and, often, the email account credentials.

#### SMB
**Scan to folder** is the process of sending a scanned document or image to a specified folder. The protocol used by the printer/scanner to send data to a network folder is secure message block (SMB). The scan is sent to a network folder on the LAN. The scanning prompts should ask for the path to the folder to which you wish the scan to be saved.

#### Cloud Services
**Scan to cloud** occurs when a printer/scanner is instructed to send a scanned image or document to a specified cloud location or service and is supported by popular cloud services, such as Google Drive, OneDrive, and Dropbox.

The scan is uploaded to a storage location in the cloud such as Google Drive or Apple iCloud. The MFD may have specific cloud locations that are preconfigured or allow you to configure your own. You log in using the scanning prompts either in the software or on the MFD screen if it has one.

### [[Automatic Document Feeder|ADF]]
There are two primary types of scanners. An **automatic document feeder (AFD)** is a scanning device that allows for multiple pages to be scanned automatically through the use of a feeder, eliminating the need to manually change the document being scanned. 

An automatic document feeder (ADF) can be found on some laser and inkjet printers which also have the capabilities of copy machines. These are called multi-function devices (MFDs). The ADF is a slot where an existing document can be placed. The machine is then set to make copies of this document.

When started, the ADF pulls one page of the document onto the glass surface of the platen, where it is scanned and copies are made. The page on the platen is then automatically removed and the next page in the original document is pulled onto the platen. This process continues until the entire original document in the feeder has been pulled through. Some machines can make multiple copies. Usually these machines can also collate these copies.

Depending on the capabilities of the machine, the original document may be placed face up in the feeder or face down. The machine may have a limit as to how many pages can be in the original document.

### Flatbed Scanner
A **flatbed scanner** is a scanning device that requires manual placement of a document to be scanned onto a flat scanning surface with a closable lid.

## Printer Consumables
Printer consumables are the components of a computer that require replacement. You must be able to install and replace printer consumables. These questions will be scenario based.

### Laser
Laser printers create **high-quality** printouts using a complex process. The component that actually “draws” the image is a laser. It works with other components to transfer that image to the paper.

Some advantages of a laser printer are low cost per page, high ppm, high capacity, and prints come out dry. Some disadvantages of a laser printer are high cost of startup, and that toner cartridges can be expensive.

#### Imaging Parts
Laser printers have the following specific imaging parts.

**Imaging drum**—The central part of the laser printer is its imaging drum. The drum is a metal cylinder that is coated with a light-sensitive insulating material. The laser draws the page image onto the imaging drum. When a beam of laser light strikes the drum, it becomes a conductor at the point where the light hits it. 
**Fuser assembly**—The fuser assembly applies pressure and heat to bond the toner to the paper.
**Transfer Belt**—Used in color laser printers, the transfer belt transfers the page image from the imaging drum to the paper.
**Transfer roller**—Used in black-and-white laser printers, the transfer roller transfers the page image from the imaging drum to the paper.
**Pickup rollers**—Rubber pickup rollers feed paper from the paper tray through the printer.
**Separation pads**—To ensure that only one page is fed at a time, separation pads separate the page being fed from the pages underneath it.
**Duplexing assembly**—To print on both sides of the paper, the duplexing assembly will flip the paper over.

#### Imaging Process
The imaging process of a laser printer specifies the process the printer follows to produce an image.

**Processing**—Before any actual printing is done, the image of the full page is placed into memory. The data from the source must be converted into a printable form. The printer converts data from common languages, such as Adobe PostScript (PS) or HP Printer Command Language (PCL), to a bitmap image stored in the printer’s memory. Some laser printers have built-in Graphical Device Interface (GDI) support. GDI is used by Windows applications to display printed images on a monitor so there is no need to convert the output to another format such as PS or PCL.
**Charging**—A high negative charge is applied to the imaging drum. The image on the drum is removed and the drum is conditioned for the new image. A wire, grid, or roller receives a charge of approximately -600 volts DC uniformly across the surface of the drum. The charged wire or grid is called the primary corona. The roller is called a conditioning roller.
**Exposing**—The laser draws the image of the page onto the imaging drum by exposing it to the laser light. The tightly focused laser light removes the negative charge from the imaging drum (neutralizing it), leaving the rest of the drum negatively charged. Every portion of the drum that is scanned with the light has the surface charge reduced to about -100 volts DC. As the drum turns, an invisible image is created on the drum.
**Developing**—The negatively charged toner is transferred to the imaging drum. A control blade holds the toner at a microscopic distance from the drum. Since the drum is also negatively charged, the toner will only stick to the areas that have been neutralized by the laser. 
**Transferring**—The toner, attached to the image, is transferred to the paper. The corona wire places a positive charge on the paper. Because the drum was charged negatively, the toner on the drum is now attracted to the paper. The image is now on the paper and is held in place by the positive charge. Because color printers have three cartridges of toner, a colored image must go through multiple transfers to be complete. To ensure precise images, some color printers write multiple times onto a transfer belt that transfers the complete image to paper.
**Fusing**—A fusing roller uses heat and pressure to bond the toner to the paper. The printing paper is rolled between a heated roller and a pressure roller. As the paper moves through the rollers, the loose toner is melted and fused with the fibers in the paper. The paper is then moved to the output tray as a printed page. Laser printers with duplex assemblies can print on both sides of a sheet of paper.
**Cleaning**—When an image has been deposited on the paper and the drum has separated from the paper, the remaining toner must be removed from the drum. A printer might have a blade that scrapes the excess toner. Some printers use an AC voltage on a wire that removes the charge from the drum surface and allows the excess toner to fall away from the drum. The excess toner is stored in a used toner container that is either emptied or discarded.

#### Maintenance
Laser printers tend to be expensive, so regular maintenance must be done to keep them running well for a long time. Manufacturers make this fairly easy for common maintenance tasks like replacing toner. Other tasks require more knowledge and skill.

**Replace toner**—Toner is used for each print job, so it must periodically be replaced. Toner comes in a **toner cartridge** that is easily replaced by the user.
**Maintenance kit**—Printer manufacturers recommend replacing certain parts periodically. They provide these parts in maintenance kits. They may include the fuser assembly, transfer belt, transfer roller, pickup rollers, and/or separate pads.
**Calibrate**—Calibration is done to keep the page image sharp and accurate. This may be done on a periodic basis and when parts are replaced. Each printer will have its own calibration process.
**Clean**—Toner is a fine powder that will leave residue in the printer. Keeping the inside of the printer clean will keep it running well and prevent loose toner from showing up on printouts.

### Inkjet
Inkjet printers create **high-quality** printouts, though the **resolution can be less** than that of laser printers. They are also much **less expensive**. They create the page image by spraying ink dots onto precise points on the paper. Several components work together to transfer the page image to the paper.

Some advantages of an inkjet printer are initial low cost, high resolution, and they are quick to warm up. Some disadvantages of an inkjet printer are that the nozzles are prone to clogging, ink cartridges can be expensive, and the ink is wet for a few seconds after printing.

#### Imaging Parts
Inkjet printers have the following specific imaging parts.

**Ink cartridge**—Ink is stored in ink cartridges that supply ink to the print heads. There may be a **separate cartridge** for each of the standard colors used—cyan, magenta, yellow, and black. Some inkjet printers use a **combined color cartridge** with cyan, magenta, and yellow ink, plus a black ink cartridge. Ink cartridges are designed for specific makes and models of inkjet printers.
**Print head**—The print head draws the ink from the cartridge and ejects it onto the paper. Inkjet printers use ink cartridges that spray ink onto a page through tiny holes. The tiny holes are called nozzles and are located in the print head. Some printers combine the ink cartridge and the print head into a single unit. There are two types of inkjet nozzles:
	**Thermal** - A pulse of electrical current is applied to heating chambers around the nozzles. The heat creates a bubble of steam in the chamber. The steam forces ink out through the nozzle and onto the paper.
	**Piezoelectric** - Piezoelectric crystals are located in the ink reservoir at the back of each nozzle. A charge is applied to the crystal, causing it to vibrate. This vibration of the crystal controls the flow of ink onto the paper.
**Roller**—Paper is fed through the printer by the roller from the feeder.
**Feeder**—Paper may be fed from either a simple paper tray or a feeder. Most feeders have adjustments to allow you to feed papers of varied sizes. The feeder may hold blank paper in a tray or cassette. Some inkjet printers are also copiers. They may have an Automatic Document Feeder (ADF). The ADF holds documents which are fed page by page onto the scanner bed for copying.
**Duplexing assembly**—The duplexing assembly flips the paper over so that you can print on both sides. It is not found in all inkjet printers.
**Carriage belt**—The carriage holds the print heads and gets moved into position so the print heads can eject the ink onto the proper spot on the paper. The belt moves the carriage into position so the print heads can eject the ink onto the proper spot on the paper.

#### Calibration
Calibration is done to keep the page image sharp and accurate. This may be done on a periodic basis and when parts are replaced. The printer should be calibrated whenever a print head or ink cartridge is replaced. Each printer will have its own calibration process.

#### Maintenance
Inkjet printers require **minimal** maintenance, which is easily done using features available through the printer’s menus or software. To determine if maintenance is needed, test pages specifically designed to point out flaws can be printed from the printer’s menus or software.

**Clean heads**—Printer heads can get clogged over time. Cleaning the heads can be done by selecting a menu option or through the printer’s software. When initiated, the printer will run through a head-cleaning process.
**Replace cartridges**—When the ink in a cartridge has been used up, the cartridge must be replaced. A calibration should be done after replacing a cartridge.
**Calibrate**—Calibration is done to keep the page image sharp and accurate. This may be done on a periodic basis and when parts are replaced. The printer should be calibrated whenever a print head or ink cartridge is replaced. Each printer will have its own calibration process.
**Clear jams**—Paper may get jammed in the printer as it is fed through. It may be cleared manually by simply pulling it out. Some printers provide a way to run just the feeder, either manually by turning a wheel or by running the feed motor.

### Thermal Printers
use **chemically treated thermal paper** that changes color when heated. It is the heat, rather than ink, that transfers the image to the paper. Thermal printers are simple and **inexpensive**. Common uses are for receipts and shipping labels. The image printed is sensitive to light and heat, so it **will fade over time**.

Many retail cash registers and some older fax machines contain thermal printers. Thermal paper is chemically treated and has a waxy quality. Thermal paper becomes black when heated. After a roll of thermal paper is loaded, the feed assembly moves the paper through the printer. Electrical current is sent to the heating element in the print head to generate heat. The heated areas of the print head make the image on the paper.

Some advantages of thermal printers are that they last a long time because there are few moving parts, their operation is quiet and there is no cost for ink or toner. However, thermal paper is expensive, it must be stored at room temperature and can degrade over time. Thermal printer images are poor quality, and color printing is not available.

#### Imaging Parts
Thermal printers have the following specific imaging parts.

**Feed assembly**—The feed assembly feeds the thermal paper through the printer.
**Heating element**—The heating element heats specific areas of the thermal paper as it scrolls by. The heated areas darken to create the image.

#### Special Paper and Heat Sensitivity
Thermal paper is chemically treated paper that changes color when heated. This makes the print out vulnerable to damage or degradation when exposed to heat.

#### Maintenance
thermal printers are simpler than other types of printers. There are fewer moving parts and **no ink**.

**Replace paper**—Thermal paper comes in **rolls** of various sizes. Replacing the paper is a simple matter of removing the empty roll and inserting the new roll. There is a button or wheel that can be used to feed the paper into the printer after the new roll is inserted.
**Clean heating element**—The heating element should be cleaned periodically to ensure proper heat transfer to the paper. Isopropyl alcohol is typically used as the cleaning agent. Some printers come with a pen or pad to make it easier to access the heating element for cleaning.
**Remove debris**—Paper fragments and dust will accumulate in the printer over time. This debris should be removed as needed. A commonly used method is to blow out the debris with **compressed air**.

### Impact printers
use a **matrix of pins** to strike an ink ribbon to transfer ink to the paper. The most common type is the **dot-matrix** printers. A unique feature of impact printers, as compared to other printers, is that they can **print multiple copies simultaneously** using carbonless or no carbon required (NCR) paper.

An advantage of impact printers is that the ribbon is less expensive than inkjet cartridges or laser printer toner cartridges. They can use continuous feed or normal sheets of paper and can print carbon copies. Disadvantages include the fact that they are noisy, the graphics are low-resolution, and they have limited color-printing capabilities.

A dot matrix printer has a print head containing pins that are surrounded by electromagnets. When energized, the pins push forward onto the ink ribbon, creating a character on the paper. The number of pins on a print head, 9 or 24, determines the quality of the print. The highest quality of print that is produced by the dot matrix printer is referred to as near letter quality (NLQ).

Most dot matrix printers use continuous-feed paper, also known as tractor feed. The paper has perforations between each sheet, and perforated strips on the side are used to feed the paper and to prevent skewing or shifting. Sheet feeders that print one page at a time are available for some higher quality printers. A large roller, called the platen, applies pressure to keep the paper from slipping. If a multiple-copy paper is used, you can adjust the platen gap to the thickness of the paper.

#### Imaging Parts
Impact printers have the following specific imaging parts.

**Print head**—The print head is a row or rectangular matrix of metal pins. The pins that strike the ink ribbon form the character to be printed.
**Ribbon**—The ribbon holds the ink that is transferred to the paper by the print head during printing.
**Tractor feed**—The tractor feed feeds the paper through the printer.

#### Impact Paper
is simply paper made for impact printers. It may come on a roll or as fanfold paper in single-ply, duplicate, or triplicate. Duplicate and triplicate paper transfers the image through to all copies simultaneously.

#### Maintenance
There is little maintenance required on impact printers. In most printers, these items can all be replaced by the user.

**Replace ribbon**—Ribbon replacement is usually a simple task. The new ribbon should be taut, leaving no slack.
**Replace print head**—The pins in a print head can get bent or broken, so the print head will eventually need to be replaced. The print head does get hot due to the friction of rapidly moving parts, so care must be taken to ensure it **cools down** before touching it. It is held in by a lever that must be released to remove the old print head.
**Replace paper**—Paper replacement requires a bit more effort than in other types of printers. The paper has holes along the side that are placed into the tractor feed. These must be aligned so that the paper feeds properly. Also, since the paper is continuous, as opposed to separate sheets, the top of the page must be lined up properly.

### 3-D Printer
is not technically a printer but a **fabrication machine** through a process called additive manufacturing. A three-dimensional object is created by adding layers of filament or liquid resin on top of one another to produce a specified output. These objects are first designed using a computer. A variety of media is now available to create these objects. But for beginners, 3D printers that use plastic filament are the most commonly used. The plastic filament is added in layers to create the object that was programmed on the computer.

Traditionally, machines cut or drilled pieces out of raw material (e.g., stone, metal, wood) to create an object. This is known as subtractive manufacturing. 3D printers add the material used to create objects in layers or even small bits; therefore, they are known as additive manufacturing machines.

#### Filament
is a **plastic** substance used by 3D printers to create an object. A 3D filament printer’s components include the frame, the printing plate or print bed, the extruder, the cooling fan, the printed circuit board (PCB), and the filament. Filament comes on a **spool**. The main three things to consider when choosing a filament type are the size, type, and color.

Common types of filament are plastic-based: ABS, PLA, and PVA. There are even filaments made of nylon, metal, or wood. Check your 3D printer's manual to determine which type(s) of filament to use.

#### Feeder
The feeder takes filament from a feed tube that is placed into the extruder. The feeder pulls it down to be heated and exits through the hot-end nozzle.

#### Hot-end nozzle
When the filament is heated to the correct temperature, it is extruded from this nozzle.

#### Axis
An axis is one of several bars on which the hotend nozzle travels to dispense filament. Axis are vertical or horizontal so that the hotend nozzle can be located within a specified location in a 3D environment to "print" the object.

#### Resin
is a **liquid** substance contained in a reservoir used to build a specified object. The resin is hardened by a UV light layer by layer to create the object. 3D resin printers are also referred to as stereolithography/digital light processing printers (SLA/DLP).

#### Print Bed
is the **plate** on which the object will be printed. In a filament printer, the print bed is located at the bottom of the printer with the printer creating the object from the bottom up. The print bed on a resin printer is often located at the top of the printer with the printer creating the object from the top down, appearing to rise from the printer.

# Servers

## Wireless Methods
### Virtual 
Virtual printing does not send a print job to a printer within your local network. Instead, the print software either sends the job to a file or transmits the information to a remote destination in the cloud for printing.

Typical methods for sending a print job to a file include the following:
- **Print to file** - Originally, print to file saved your data in a file with the .prn extension. The .prn file then could be quickly printed at any time without opening the original document. Print to file can now save in other formats, as shown in the figure.
- **Print to PDF** - Adobe’s Portable Document Format (PDF) was released as an open standard in 2008.
- **Print to XPS** - Introduced by Microsoft in Windows Vista, the XML Paper Specification (XPS) format was meant to be an alternative to PDF.
- **Print to image** - To prevent others from easily copying the content in a document, you can choose to print to an image file format, such as JPG or TIFF.

### Cloud
Cloud printing is sending a print job to a remote printer. The printer could be at any location within your organization’s network. Some printing companies provide software that you can install and then send print jobs to their closest location for processing.

Another cloud printing example is Google Cloud Print, which allows you to connect your printer to the web. After it is connected, you can send print jobs to your printer from anywhere that has internet access.

## Servers
Some printers require a separate print server to enable network connectivity because these printers do not have built-in network interfaces. Print servers let multiple computer users, regardless of device or operating system, to access a single printer. A print server has three functions:
- Provide client access to print resources.
- Administrate print jobs by storing them in a queue until the print device is ready for them and then feeding or spooling the print information to the printer.
- Provide feedback to users about the state of the printer.

Sharing a printer from a computer also has disadvantages. The computer sharing the printer uses its own resources to manage the print jobs coming to the printer. If the computer user on the desktop is working at the same time as a user on the network is printing, the desktop computer user might notice a performance slowdown. In addition, the printer is not available if the user reboots or powers off the computer with a shared printer.

### Software
In some instances, the computer sharing the printer is running an operating system that is not Windows, such as Mac OS. In this case, you can use print server software.

One example is Apple’s free Bonjour Printer Server, which is a built-in service in Mac OS. It is automatically installed on a Windows computer if you install the Apple Safari Browser. You can also download the Bonjour Printer Server for Windows, as shown in the figure, for free from the Apple website.

When it is downloaded and installed, the Bonjour Printer Server operates in the background, automatically detecting any compatible printers connected to the network.

### [[Hardware]]
A hardware print server is a simple device with a network card and memory. It connects to the network and communicates with the printer to enable print sharing. The print server in the figure is connected to the printer by a USB cable. A hardware print server may be integrated with another device, such as a wireless router. In this case, the printer would connect directly to the wireless router, most likely through a USB cable.

Apple’s AirPort Extreme is a hardware print server. Through the AirPrint service, the AirPort Extreme can share a printer with any device on the network.

A hardware print server can manage network printing through either wired or wireless connections. An advantage of using a hardware print server is that the server accepts incoming print jobs from devices, thereby freeing the computers for other tasks. A hardware print server is always available to users, unlike a printer shared from a user's computer.

### Dedicated
For larger networking environments with multiple LANs and many users, a dedicated print server is needed to manage printing services, as shown in the figure. A dedicated print server is more powerful than a hardware print server. It handles client print jobs in the most efficient manner and can manage more than one printer at a time. A dedicated print server must have the following resources to meet the requests of print clients:
- **Powerful processor** - Because the dedicated print server uses its processor to manage and route printing information, it must be fast enough to handle all incoming requests.
- **Adequate storage space** - A dedicated print server captures print jobs from clients, places them in a print queue, and sends them to the printer in a timely manner. This process requires the computer to have enough storage space to hold these jobs until completed.
- **Adequate memory** - The processor and RAM handle sending print jobs to a printer. If there is not enough memory to handle an entire print job, the document is stored on the drive in the print server and printed from there. This is generally is slower than printing directly from memory.

# Maintenance
A good preventive maintenance program helps to ensure good quality prints and uninterrupted operation. The printer documentation contains information on how to maintain and clean the equipment.

Read the information manuals that come with every new piece of equipment. Follow the recommended maintenance instructions. Use the supplies listed by the manufacturer. Less expensive supplies can save money, but may produce poor results, damage the equipment, or void the warranty.

As shown in the figure, most manufacturers sell maintenance kits for their printers. If you do not know how to maintain printing equipment, consult with a manufacturer-certified technician. When servicing toner kits and cartridges, wear air filter masks to avoid breathing in harmful particles

## Inkjet
Always consult the manual before performing maintenance tasks. The manual gives instructions that are specific to your inkjet printer.

The type and quality of paper and ink used can affect the life of the printer. The printer manufacturer might recommend which type of paper to use for best results. Some paper, especially photo paper, transparencies, and multilayered carbon paper, have a right and wrong side. Load the paper according to the manufacturer's instructions.

The manufacturer recommends the brand and type of ink to use. If the wrong type of ink is installed, the printer might not work or the print quality might deteriorate. Avoid refilling ink cartridges because the ink can leak.

When an inkjet printer produces blank pages, the ink cartridges might be empty. Some inkjet printers may not print any pages if one of the ink cartridges is empty. You can set the printer software to draft quality to reduce the amount of ink that the printer uses. These settings also reduce the print quality and the time it takes to print a document.

Over time, the parts collect dust, dirt, and other debris. If not cleaned regularly, the printer may not work well or could stop working completely. On inkjet printers, clean the paper-handling machinery with a damp cloth.

## Laser
Laser printers do not usually require much maintenance unless they are in a dusty area or are very old. When cleaning a laser printer, use only a vacuum cleaner with High Efficiency Particulate Air (HEPA) filtration. HEPA filtration catches microscopic particles within the filters.

Always consult the manual before performing maintenance tasks. The manual gives instructions that are specific to your laser printer. For some maintenance tasks done on a laser printer, you will need to disconnect the printer from its power source. Consult your manual for specific information. If you do not know how to maintain printing equipment, consult a manufacturer-certified technician.

Most manufacturers sell maintenance kits for their printers. For laser printers, the kit might contain replacement parts that often break or wear out such as the fuser assembly, transfer rollers and pickup rollers.

When you install new parts or replace toners and cartridges, visually inspect all internal components, remove bits of paper and dust, clean spilled ink or toner, and look for worn gears, cracked plastic, or broken parts.

Laser printers do not produce blank pages. Instead, they begin to print poor quality prints. Some printers have LCD message screens or LED lights that warn users when toner supplies are low. Some types of prints use more toner than others do. For example, a photograph uses more toner than a letter. You can set the printer software to toner save or draft quality to reduce the amount of toner that the printer uses. These settings also reduce the quality of laser prints.

When maintenance is completed, reset the counters to allow the next maintenance to be completed at the correct time. On many types of printers, the page count is viewed through the LCD display or a counter located inside the main cover.

## Thermal
Always consult the manual before performing maintenance tasks. The manual gives instructions that are specific to your thermal printer on how to replace the paper roll.

Thermal printers use heat to create an image on special paper. To extend the life of the printer, dampen a cotton swab with isopropyl alcohol to clean the heating element. Do this on a regular basis. The heating element is located near the slot where the printed paper emerges, as shown in the next figure. While the printer is open, use compressed air or a lint-free cloth to remove any debris.

## Impact 
Always consult the manual before performing maintenance tasks. The manual gives instructions that are specific to your impact printer.

An impact printer is similar to a typewriter because the print head strikes an inked ribbon to transfer ink to the paper. When the impact printer produces faded or light characters, the ribbon shown in the figure is worn out and needs to be replaced. Consult your manual for instructions on how to replace the ribbon.

If a consistent flaw is produced in all characters the print head is stuck or broken and needs to be cleaned or even replaced. Search for procedures on dot matrix printhead cleaning to learn about this.

# Installation
When you purchase a printer, the installation and configuration information is usually found on the manufacturer’s website. Before you install a printer, remove all packing material. Remove anything that prevents moving parts from shifting during shipping. Keep the original packing material in case you need to return the printer to the manufacturer for warranty service.

**Note**: Before connecting the printer to the computer, read the installation instructions. In some cases, the printer driver needs to be installed first before the printer is connected.

If the printer has a USB, FireWire, or parallel port, connect the corresponding cable to the printer port. Connect the other end of the data cable to the corresponding port on the back of the computer. If you are installing a network printer, connect the network cable to the network port.

After the data cable has been properly connected, attach the power cable to the printer. Connect the other end of the power cable to an available electrical outlet. When you turn on the power to the device, the computer determines the correct device driver to install.

# Optimization

## [[Software]]
With printers, most optimization is completed through the software that comes with the drivers.
The following tools optimize performance:
- **Print spool settings** - Cancel or pause current print jobs in the printer queue.
- **Color** **calibration** - Adjust settings to match the colors on the screen to the colors on the printed sheet.
- **Paper** **orientation** - Select landscape or portrait image layout.

Printers are calibrated using the printer driver software. Calibration makes sure that the print heads are aligned and that they can print on different kinds of media, such as cardstock, photographic paper, and optical discs. Some inkjet print heads are fitted to the ink cartridge, so you might have to recalibrate the printer each time you change a cartridge.

## [[Hardware]]
Some printers can be upgraded to print faster and to accommodate more print jobs by adding hardware. The hardware may include additional paper trays, sheet feeders, network cards, and expansion memory.

### Firmware
The procedure to upgrade firmware is similar to installing printer drivers. Because firmware updates do not take place automatically, visit the home page of the printer manufacturer to check the availability of new firmware.

### Printer [[Computational Memory|Memory]]
All printers have RAM, such as the chips shown in the figure. Printers usually arrive from the factory with enough memory to handle jobs that involve text. However, print jobs involving graphics, and especially photographs, run more efficiently if the printer memory is adequate to store the entire job before it starts. Upgrading the printer memory increases the printing speed and enhances complex print job performance.

Print job buffering is when a print job is captured in the internal printer memory. Buffering is a common feature in laser printers and plotters, as well as in advanced inkjet and dot matrix printers.

If you receive low memory errors, this can indicate that the printer is out of memory or has a memory overload. In this instance, you may need more memory.

# Sharing 
Windows allows computer users to share their printers with other users on the network.

Users who cannot connect to the shared printer might not have the required drivers installed. They might also be using different operating systems than the computer that is hosting the shared printer. Windows can automatically download the correct drivers to these users. Click the Additional Drivers button to select operating systems that the other users are using. When you close that dialog box by clicking OK, Windows will ask to obtain those additional drivers. If the other users are also using the same Windows OS, you do not need to click the Additional Drivers button.

There are potential data privacy and security issues when sharing printers:
- **Hard drive caching** - Cached print files pose a privacy and security risk because someone with access to the device could recover this files and have access to confidential or personal information.
- **User authentication** - To prevent unauthorized use of a network or cloud-based printer, permissions and user authentication methods can be used to control access to the printer.
- **Data privacy** - Print jobs sent over a network could be intercepted and read, copied, or modified.
# Test Functions
The installation of any device is not complete until you have successfully tested all its functions. Depending on the printer you have, functions might include:
- Print double-sided documents.
- Use different paper trays for different paper sizes.
- Change the settings of a color printer so that it prints in black and white or grayscale.
- Print in draft mode.
- Use an optical character recognition (OCR) application.
- Print a collated document.

**Note**: Collated printing is ideal when you need to print several copies of a multiple page document. The Collate setting will print each set, in turn, as shown in the figure. Some printers will even staple each printed set.

## Configuration Options
Each printer may have different configurations and default options. Check the printer documentation for specific information about its configuration and default settings. The table shows some common configuration options available for printers.

| Config            | Details                                                        |
| ----------------- | -------------------------------------------------------------- |
| Paper type        | standard, draft, gloss, or photo                               |
| Print quality     | draft, normal, or photo                                        |
| Color printing    | multiple color, grayscale black and white                      |
| Paper size        | standard (A1-4), envelopes, business cards                     |
| Paper orientation | landscape or portrait                                          |
| Print layout      | normal, banner, booklet, or poster                             |
| Duplex            | two-sided printing                                             |
| Collate           | print sets of a document with multiple pages arranged in order |

## Media Control
Common printer options that the user can configure include media control and printer output. The following media control options are specific to paper.
- Input paper tray selection
- Output path selection
- Media size and orientation
- Paper weight selection

## Printer Output Options
manage how the ink or toner goes on the media and include:
- Color management
- Print speed

# Multi-Function Printer/Device : [MFP/D]
Functions for an all-in-one printer include the following:
- Fax to another known working fax.
- Create a copy of a document.
- Scan a document.
- Print a document.

# Problems and Solutions
Printer problems can be attributed to hardware, software, networks, or some combination of the three. You will resolve some types of problems more often than others.
## An application document does not print

| Causes                                 | Solutions                                                                            |
| -------------------------------------- | ------------------------------------------------------------------------------------ |
| there is a document error in the queue | manage the print jobs by canceling the document from the print queue and print again |
## Printer can not be added or there is a print spooler error

| Causes                                                 | Solutions                                                     |
| ------------------------------------------------------ | ------------------------------------------------------------- |
| the pirnter service is stopped or not working properly | start the print spooler and if necessary, reboot the computer |
## Printer jobs are sent to the print queue

| Causes                                          | Solutions                                                            |
| ----------------------------------------------- | -------------------------------------------------------------------- |
| the printer ha been installed on the wrong port | use the printer properties and setting to configure the printer port |
## Print queue is functioning properly, but the printer does not print 

| Causes                                                                                   | Solutions                                                                                                    |
| ---------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------ |
| there is a bad cable connection                                                          | check for bent pins on the printer cable and check the printer cable connections to the printer and computer |
| the printer is in standby mode                                                           | manually resume the printer from standby, or power cycle the printer                                         |
| the printer has an error such as being out of paper, out of toner, or having a paper jam | check the printer status and correct any errors                                                              |
## Printer is printing unknown characters or does not print a test page

| Causes                                        | Solutions                                                               |
| --------------------------------------------- | ----------------------------------------------------------------------- |
| wrong or outdated printer driver is installed | uninstall the current print driver and install the correct print driver |
## Printer prints unknown character or does not print anything

| Causes                           | Solutions                                                         |
| -------------------------------- | ----------------------------------------------------------------- |
| printer may plugged into a UPS   | plug the printer directly into a wall outlet or a surge protector |
| incorrect print driver installed | uninstall incorrect print driver and install correct driver       |
| printer cables are loose         | secure cables                                                     |
## Paper jams when printing 

| Causes                                      | Solutions                                                        |
| ------------------------------------------- | ---------------------------------------------------------------- |
| printer is dirty                            | clean the printer                                                |
| the wrong paper is being used               | replace the paper with the manufacturer's recommended paper type |
| humidity causes the paper to stick together | insert new paper in the paper tray                               |
## Print jobs are faded or toner is not fusing to the paper

| Causes                                     | Solutions               |
| ------------------------------------------ | ----------------------- |
| toner cartridge is empty, low or defective | replace toner cartridge |
| paper is incompatible with the printer     | replace the paper       |
| the fuser is defective                     | replace the fuser       |
## Paper is creased after printing or is not being fed into the printer

| Causes                                                | Solutions                                                             |
| ----------------------------------------------------- | --------------------------------------------------------------------- |
| paper is defective or wrinkled                        | remove the paper, check for wrinkles, and replace the defective paper |
| paper is loaded incorrectly                           | remove, realign, and replace the paper as needed                      |
| the pick up rollers are obstructed, damaged, or dirty | clean or replace the pickup rollers                                   |
## User receives a "Document failed to print" message

| Causes                           | Solutions                                             |
| -------------------------------- | ----------------------------------------------------- |
| a cable is loose or disconnected | check and reconnect the Parallel, USB, or power cable |
| a printer is no longer shared    | configure the printer for sharing                     |
## User receives an "Access Denied" message when trying to install a printer

| Causes                                                     | Solutions                                    |
| ---------------------------------------------------------- | -------------------------------------------- |
| user does not have administrative or power user privileges | log out and log in as an admin or power user |
## Printer is printing incorrect colors

| Causes                                                      | Solutions                                                   |
| ----------------------------------------------------------- | ----------------------------------------------------------- |
| print cartridge is empty, defective or installed incorectly | replace the printer cartridge                               |
| print heads need to be cleaned and calibrated               | clean and calibrate the printer using the supplied software |
## Printer is printing blank pages

| Causes                               | Solutions                          |
| ------------------------------------ | ---------------------------------- |
| printer is out of ink or toner       | replace the ink or toner cartridge |
| print head is clogged                | replace the ink cartridge          |
| corona wire has failed               | replace the corona wire            |
| high voltage power supply has failed | replace the power supply           |
## Printer display has no image

| Causes                                | Solutions                    |
| ------------------------------------- | ---------------------------- |
| printer is not turned on              | turn on printer              |
| contrast of the screen is set too low | increase the screen contrast |
| the display is broken or damaged      | replace the display          |
## Printer will not print large or complex images

| Causes                                              | Solutions                                          |
| --------------------------------------------------- | -------------------------------------------------- |
| printer or print server does not have enough memory | ass more memory to the printer or the print server |
## Laser printer prints vertical lines or streak on every page

| Causes                                           | Solutions                                                             |
| ------------------------------------------------ | --------------------------------------------------------------------- |
| imaging drum is damaged, scratched, or dirty     | replace the imaging drum or toner cartridge when it contains the drum |
| toner is not evenly distributed in the cartridge | remove and shake the toner cartridge horizontally                     |
## Printed pages show ghost images

| Causes                                                                   | Solutions                                                             |
| ------------------------------------------------------------------------ | --------------------------------------------------------------------- |
| imaging drum is, scratched, or dirty or the drum wiper blade is worn out | replace the imaging drum or toner cartridge when it contains the drum |
## Each time a network printer is restarted, users receive a "Document failed to print" message

| Causes                                                                                                               | Solutions                                 |
| -------------------------------------------------------------------------------------------------------------------- | ----------------------------------------- |
| printer's IP configuration is set for DHCP or a device on the network has the same IP address as the network printer | assign a static IP address to the printer |
## There are multiple failed jobs in the printer logs

| Causes                  | Solutions                             |
| ----------------------- | ------------------------------------- |
| the printer is off      | turn the printer on                   |
| printer is out of paper | add paper to the printer              |
| printer is out of toner | replace the toner or ink cartridge(s) |
| print job is corrupt    | restart or delete the print job       |





https://www.explainthatstuff.com/laserprinters.html

## How a laser printer works

When you print something, your computer sends a vast stream of electronic data (typically a few megabytes or million characters) to your laser printer. An electronic circuit in the printer figures out what all this data means and what it needs to look like on the page. It makes a laser beam scan back and forth across a drum inside the printer, building up a pattern of static electricity. The static electricity attracts onto the page a kind of powdered ink called toner. Finally, as in a photocopier, a fuser unit bonds the toner to the paper.

1. Raster image processing : Millions of bytes (characters) of data stream into the printer from your computer. An electronic circuit in the printer (effectively, a small computer in its own right) figures out how to print this data so it looks correct on the page.
2. The electronic circuit activates the corona wire. This is a high-voltage wire that gives a static electric charge to anything nearby.
3. The corona wire charges up the photoreceptor drum so the drum gains a positive charge spread uniformly across its surface.
4. At the same time, the circuit activates the laser to make it draw the image of the page onto the drum. The laser beam doesn't actually move: it bounces off a moving [mirror](https://www.explainthatstuff.com/howmirrorswork.html) that scans it over the drum. Where the laser beam hits the drum, it erases the positive charge that was there and creates an area of negative charge instead. Gradually, an image of the entire page builds up on the drum: where the page should be white, there are areas with a positive charge; where the page should be black, there are areas of negative charge.
5. An ink roller touching the photoreceptor drum coats it with tiny particles of powdered ink (toner). The toner has been given a positive electrical charge, so it sticks to the parts of the photoreceptor drum that have a negative charge (remember that opposite electrical charges attract in the same way that opposite poles of a magnet attract). No ink is attracted to the parts of the drum that have a positive charge. An inked image of the page builds up on the drum.
6. A sheet of paper from a hopper on the other side of the printer feeds up toward the drum. As it moves along, the paper is given a strong negative electrical charge by another corona wire.
7. When the paper moves near the drum, its negative charge attracts the positively charged toner particles away from the drum. The image is transferred from the drum onto the paper but, for the moment, the toner particles are just resting lightly on the paper's surface.
8. Fusing : The inked paper passes through two hot rollers (the fuser unit). The heat and pressure from the rollers fuse the toner particles permanently into the fibers of the paper.
9. The printout emerges from the side of the copier. Thanks to the fuser unit, the paper is still warm. It's literally hot off the press!