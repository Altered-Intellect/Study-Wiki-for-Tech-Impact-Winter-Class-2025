---
tags: 
parent docs:
  - "[[Hardware]]"
sibling docs: 
child docs: 
last updated: 2025-01-13T23:59:00
media:
---
# Nav
| < [[Power Supply]] < | ^ [[Hardware]] ^ | > [[Peripherals]] > |

---
## Components

### Central Processing Unit ([[CPU]])
This is considered the brain of the computer.
The central processing unit (CPU) is responsible for interpreting and executing commands. It handles instructions from the computer's other hardware, such as a keyboard, and software. The CPU interprets the instructions and outputs the information to the monitor or performs the requested tasks.

The CPU is a small microchip that resides within a CPU package. The CPU package is often referred to as the CPU. CPU packages come in different form factors, each style requiring a particular socket on the motherboard. Common CPU manufacturers include Intel and AMD.

The CPU socket is the connection between the motherboard and the processor. Modern CPU sockets and processor packages are built around the following architectures:

**Pin Grid Array (PGA)**
In PGA architecture, the pins are on the underside of the processor package and is inserted into the motherboard CPU socket using zero insertion force (ZIF). ZIF refers to the amount of force needed to install a CPU into the motherboard socket or slot.

**Land Grid Array (LGA)**
In an LGA architecture, the pins are in the socket instead of on the processor.

Various CPU manufacturers complement their CPU with performance-enhancing features. For instance, Intel incorporates Hyper-Threading to enhance the performance of some of their CPUs. With Hyper-Threading, multiple pieces of code (threads) are executed simultaneously in the CPU. To an operating system, a single CPU with Hyper-Threading performs as though there are two CPUs when multiple threads are being processed. AMD processors use HyperTransport to enhance CPU performance. HyperTransport is a high-speed connection between the CPU and the Northbridge chip.

The power of a CPU is measured by the speed and the amount of data that it can process. The speed of a CPU is rated in cycles per second, such as millions of cycles per second, called megahertz (MHz), or billions of cycles per second, called gigahertz (GHz). The amount of data that a CPU can process at one time depends on the size of the front side bus (FSB). This is also called the CPU bus or the processor data bus. Higher performance can be achieved when the width of the FSB increases, much like a roadway can carry more cars when it has many lanes. The width of the FSB is measured in bits. A bit is the smallest unit of data in a computer. Current processors use a 32-bit or 64-bit FSB.

### Cooling System
The flow of current between electronic components generates heat. Computer components perform better when kept cool. If the heat is not removed, the computer may run more slowly. If too much heat builds up, the computer could crash, or components can be damaged. Therefore, it is imperative that computers be kept cool.

Computers are kept cool using active and passive cooling solutions. Active solutions require power while passive solutions do not. Passive solutions for cooling usually involve reducing the speed at which a component is operating or adding heat sinks to computer chips. A case fan is considered as active cooling. The figure shows examples of passive and active cooling solutions.
**Heat Sink (Passive Cooling)**
**Case Fan (Active Cooling)**

### [[Computational Memory]]
A computer might use different types of memory chips. However, all memory chips store data in the form of bytes. A byte is a grouping of digital information and represents information such as letters, numbers, and symbols. Specifically, a byte is a block of eight bits stored as either 0 or 1 in the memory chip.

### **Expansion slots** 
These provide locations to connect additional components.
Computers have expansion slots on the motherboard to install adapter cards. The type of adapter card connector must match the expansion slot.

**[[PCI]]**
Peripheral Component Interconnect is a 32-bit or 64-bit expansion slot. It is currently found in few computers. PCI expansion slots have become mostly obsolete.

**[[Mini-PCI]]**
This is smaller version of PCI found in some laptops. Mini PCI has three different form factors; Type I, Type II, and Type III. Type I and II cards have 100 pins, while Type III has 124. Type II cards include RJ-45 connectors on the board, and the card must be housed at the edge of the laptop so the sockets reach the outside. Type I and III cards connect to external RJ-45 sockets by cables.

**[[PCI-X]]**
PCI eXtended is an updated version of the standard PCI. It uses a 32-bit bus with higher bandwidth than the PCI bus. PCI-X can operate up to four times faster than PCI. PCI-X expansion slots have become mostly obsolete.

**[[PCIe]]**
PCI Express is a 64-bit parallel interface that is backward compatible with 32-bit PCI devices. PCIe is a serial point-to-point connection with a different physical interface that was designed to supersede both PCI and PCI-X. There are four sizes (lengths): PCI Express x1, PCI Express x4, PCI Express x8, and PCI Express x16.'PCIe x4' connections have four data lanes. 'PCIe x8' connections have eight data lanes. 'PCIe x16' connections have sixteen data lanes. PCIe can supply up to 25 watts of power to each slot. For a graphics card, it can supply up to 75 watts. For very powerful graphics cards, an additional 75 watts can be supplied by a PCIe power connector from the power supply.
- **Versions** : Every version of PCIe is backward-compatible with all other versions, for example, if you have a motherboard that supports version 4, you can still use version 3 PCIe components. The speed of the bus will be determined by the lowest version component installed. 

| Version | GB/s single | GB/s for x8 |
| ------- | ----------- | ----------- |
| 2       | .5          | 8           |
| 3       | .985        | 8           |
| 4       | 1.969       | 31.508      |
| 5       | 3.938       | 63.015      |

**[[Riser Card]]**
added to a computer to provide additional expansion slots for more expansion cards.

**[[AGP]]**
Accelerated Graphics Port (AGP) was a high speed slot for attaching an AGP video card. The AGP has been superceeded by PCI. Few motherboards still use this technology today.

#### Adapter Cards
increase the functionality of a computer by adding controllers for specific devices or by replacing malfunctioning ports.
There are a variety of adapter cards available that are used to expand and customize the capability of a computer.

- **Sound Adapter** : provide audio capability.
- **Video adapter** : provide video capability.
- **Network Interface Card (NIC)** : connects a computer to a network using a network cable.
- **eSATA card** : Adds additional internal and external SATA ports to a computer through a single PCI Express slot.
- **Wireless NIC** : A wireless NIC connects a computer to a network using radio frequencies.
- **Capture card** : Capture cards send a video signal to a computer so that the signal can be recorded to a storage drive with video capture software.
- **TV tuner card** : These provide the ability to watch and record television signals on a PC by connecting a cable television, satellite, or antenna to the installed tuner card.
- **Universal Serial Bus (USB) controller card** : Provides additional USB ports to connect the computer to peripheral devices. USB is a standard interface that connects peripheral devices to a computer. USB devices are hot-swappable, which means that users can connect and disconnect the devices while the computer is powered on.

It should be noted that some of these adapter cards can be integrated on the motherboard.
**Note**: Older computers may also have a modem adapter, Accelerated Graphics Port (AGP), a Small Computer System Interface (SCSI) adapter, and more.

### **Chipset** 
This consists of the integrated circuits on the motherboard that control how system hardware interacts with the CPU and motherboard. It also establishes how much memory can be added to a motherboard and the type of connectors on the motherboard.
Most chipsets consist of the following two types:
- **Northbridge** – Controls high speed access to the RAM and video card. It also controls the speed at which the CPU communicates with all of the other components in the computer. Video capability is sometimes integrated into the Northbridge.
- **Southbridge** – Allows the CPU to communicate with slower speed devices including hard drives, Universal Serial Bus (USB) ports, and expansion slots

**Basic input/output system (BIOS) chip and Unified Extensible Firmware Interface (UEFI) chip** - BIOS is used to help boot the computer and manage the flow of data between the hard drive, video card, keyboard, mouse, and more. In modern computers BIOS has been replaced by UEFI. UEFI specifies a different firmware for boot and runtime services. Firmware is programming that allows a computer operating system to control the hardware.

### Connectors
**[[SATA]]**
Serial Advanced Technology Attachment (ATA), is a disk drive interface used for connecting optical drives, hard drives, and solid-state drives to the motherboard. SATA supports hot swapping, which is the ability to replace devices without powering off the computer.

**[[IDE]]**
Integrated Drive Electronics (IDE) is an older standard interface for connecting disk drives to the motherboard. IDE uses a 40-pin connector. Each IDE interface supports a maximum of two devices.

**Internal USB**
A 19-pin connector is used to connect the external USB 3 ports on the computer case to the motherboard. USB 1.1 and USB 2 connectors have 9 pins.

## Form Factor
The form factor describes the physical characteristics of the motherboard.

### Advanced Technology eXtended (ATX)
Older Advanced Technology eXtended variants contain a **20-pin Molex power connection**, while newer models contain the **24-pin Molex power connection**. Standard ATX motherboards measure 12” x 9.6” (30.5cm x 24.4cm). 
Micro-ATX is a little bit smaller than the ATX and does not have as much expansion ability. It is designed for small devices such as thin clients and set-top boxes. Measure 9.6"^2 (24.4cm^2).

### Information Technology eXtended (ITX)
Information Technology eXtended is a series of significantly smaller form factor boards that were created by VIA Technologies™. 
**ITX** is the largest of the ITX form factors, with a size of 8.5" x 7.5"
**Mini-ITX** measures 6.7” x 6.7”.
**Nano-ITX** measures 4.7” x 4.7”. 
**Pico-ITX** measures 3.9” x 2.8”.
**mobile-ITX** measures 2.4” x 2.4”.

## Motherboard Connector Types
Motherboards have a variety of connectors that determine what can be connected to them.

**PCI**—**Peripheral Component Interconnect** was introduced by Intel™ in the 1990s. This replaced older 8- and 16-bit expansion slots with a 32-bit slot.
**PCIe**—**PCI express** sends data in a serial stream at higher speeds than conventional PCI. It has superseded PCI.
**Power connectors**—The power connector of a motherboard is a special **24-pin** connection point through which a motherboard receives electrical power.
**[[SATA]]**—The **serial ATA connector** is used to connect a hard drive or optical drive.
**eSATA**—An **external SATA** is a connection type that allows for external devices to connect directly to the motherboard using a SATA connection.
**Headers**—A header is a motherboard connection type that allows for external components, such as lights and buttons, to connect directly to the motherboard. Examples of components connected to headers are the power button and light, the reset button, drive activity lights, audio jacks, and USB ports.
**M.2**—M.2 (pronounced M dot 2) is not technically a connection or bus type but rather a form factor. M.2 supports SATA, USB, and PCIe buses.

## Motherboard Compatibility
Motherboards only work with compatible components. Components dependent upon motherboard compatibility include bus architecture, chipsets, expansion slots, memory slots, CPUs, power connectors, non-volatile storage, firmware, CMOS batteries, and front panel connectors and headers.

### [[CPU]] Sockets
the space on the motherboard designed to hold the CPU that contains a specific pin grid array dependent upon the motherboard.

#### [[Advanced Micro Devices, Inc.™ (AMD)]]
Specific AMD CPUs must run with specific AMD chipsets. The motherboard manufacturers may vary.

#### [[Intel™]]
Specific Intel CPUs must run with specific Intel chipsets. The motherboard manufacturers may vary.

### [[Server]]
Server motherboards are typically capable of **housing multiple processors** with expanded memory and networking capabilities. Most server motherboards are **ATX sized** and specifically designed to fit within the server chassis.

### Multi-socket
A multi-socket motherboard is a motherboard that has **more than one CPU socket**.

### Desktop
A desktop motherboard can be either **ATX or ITX** and typically contains **one CPU socket**.

### Mobile
A mobile motherboard can be a standard small form factor motherboard but are more commonly specifically designed to fit the needs of the manufacturer with the CPU soldered into the motherboard.

### Complementary Metal-Oxide-Semiconductor (CMOS) battery
a small, coin-shaped battery found on a computer’s [motherboard](https://www.hp.com/us-en/shop/tech-takes/what-does-a-motherboard-do). It provides power to the CMOS chip, which stores important system information such as the date, time, and hardware settings in the CMOS memory.

The CMOS battery serves several crucial functions in your computer:
1. **Maintains System Time and Date**: It keeps the real-time clock (RTC) running even when the computer is powered off, ensuring the correct date and time are maintained.
2. **Preserves BIOS Settings**: It ensures that your BIOS (Basic Input/Output System) settings are retained between restarts, preventing the system from reverting to default settings.
3. **Enables Quick Startups**: By maintaining BIOS settings, it allows for faster boot times and ensures the operating system loads correctly.
4. **Supports Power Management**: It helps manage low-power states when the computer is in sleep or hibernation mode.

## Key Facts About CMOS Batteries:

- Typically a CR2032 lithium coin cell battery
- Lasts between 2 to 10 years, depending on usage
- Provides power to maintain BIOS settings when the computer is turned off
- Found in both desktop computers and laptops

For those looking to stock up on replacement batteries, consider getting a CR2032 lithium battery pack.

## Basic Input/Output System (BIOS)
The **basic input/output system (BIOS)** is, arguably, one of the most important aspects of a computer. You need to have a good understanding of system BIOS and how to modify the settings. Understand the importance of selecting the proper **boot sequence** and how BIOS provides low-level drivers that allow the operating system to interact with various hardware components. Comprehend the various stages in the boot sequence, the **system POST**, and the role BIOS plays in loading the operating system. The CompTIA A+ questions about BIOS require that you assess a scenario to choose the best answer.

## Unified Extensible Firmware Interface (UEFI) settings
The Unified Extensible Firmware Interface (UEFI) is an updated booting program which connects the firmware of a computer to the operating system. UEFI is faster than BIOS, but it is not widely available on all computer devices. UEFI forgoes the self-test process, which increases its speed. UEFI is capable of handling drives larger than 2TB and more than four primary partitions. However, most devices still use the BIOS system.

### Boot Options
You can set the sequence of devices to boot from in the boot option settings. You usually boot from the **hard drive**, but you may want to boot from an **optical drive** or **flash drive**. The boot sequence tells the BIOS where to look to load the operating system. It will proceed down the list in the order configured until it finds an operating system to load.

### USB Permissions
can be set in the BIOS and specify the permissions that USB devices have on a device.

### Trusted Platform Module (TPM) Security Features
TPM is a dedicated security coprocessor or cryptoprocessor that can be configured for **booting authentication**.

### Fan Considerations
Fans provide airflow within a computer to keep components cool during operation. Fan considerations include fan location, front or rear, and fan dedication, such as power supply exhaust, CPU, chipset, video card, or memory module fans.

### Secure Boot
ensures that the operating system and drivers are **authorized** versions without malicious code before loading them.

### Boot Password
The **supervisor or admin password**, if enabled, requires a password to view and set all BIOS settings. The **user or system password** allows minor changes such as time and date or boot options to be set.

## Encryption
An encryption key can be set to access an encrypted hard drive. If set, that key must be used for decryption, even if the drive is moved to another computer.

### TPM
The Trusted Platform Module is a **security chip** that stores cryptographic keys used by the BIOS or UEFI in booting authentication.

### Hardware Security Module (HSM)
A hardware security module (HSM) is a security device that can create, manage, and store encryption keys.

## CPU Architecture
CPU architecture is the sequence of stored instructions by which a CPU communicates with other components. A CPU executes these instructions by following a specific instruction set.

There are two distinct types of instruction sets that CPUs may use:
- **Reduced Instruction Set Computer (RISC)** - This architecture uses a relatively small set of instructions. RISC chips are designed to execute these instructions very rapidly. Some well-known CPUs using RISC are PowerPC and ARM.
- **Complex Instruction Set Computer (CISC**) - This architecture uses a broad set of instructions, resulting in fewer steps per operation. Intel x86 and Motorola 68k are some well-known CPUs using CISC.

While the CPU is executing one step of the program, the remaining instructions and the data are stored nearby in a special, high-speed memory, called cache.

Execute Disable Bit - a bit that labels parts of the operating system unusable 

#### x64/x86
The x64/x86 platform uses **CISC technology** (CISC is an instruction set architecture [ISA]) that is designed to work with **either 64 or 32 bits** of data at a time. Working with 64 bits is referred to as x64 while working with 32 bits is referred to as x86.

#### Over-Clocking
a technique used to make a processor work at a faster speed than its original specification. Overclocking is not a recommended way to improve computer performance and can result in damage to the CPU. The opposite of overclocking is CPU throttling. CPU throttling is a technique used when the processor runs at less than the rated speed to conserve power or produce less heat. Throttling is commonly used on laptops and other mobile devices.

#### Advanced RISC Machine (ARM)
An advanced RISC machine (ARM) processor uses RISC ISA (RISC stands for **reduced instruction set computer**). ARM is also known as an **Acorn RISC** machine and is in direct competition with Intel and AMD x64-based CPUs.

### Processing
The latest processor technology has resulted in CPU manufacturers finding ways to incorporate more than one CPU  core into a single chip. Multicore processors have two or more processors on the same integrated circuit. In some  architectures, the cores have separate L2 and L3 cache resources, while in other architectures cache is shared  among the different cores for better performance and resource allocation. 
Integrating the processors on the same chip creates a very fast connection between them. Multicore processors execute instructions more quickly than single-core processors. Instructions can be distributed to all the processors  at the same time. RAM is shared between the processors because the cores reside on the same chip. A multicore processor is recommended for applieations such as video editing, gaming, and photo manipulation.

High-power consumption creates more heat in the computer case. Multicore processors conserve power and  produce less heat than multiple single-core processors, thus increasing performance and efficiency.  

Another feature found in some CPUs is an integrated graphics processing unit or GPU. The GPU is a chip that  performs the rapid mathematical calculations required to render graphics. A GPU can be integrated or dedicated.  Integrated GPUs are often directly embedded on the CPU and is dependent on system RAM while the dedicated  GPU is a separate chip with its own video memory dedicated exclusively for graphical processing. 

The benefit of integrated GPUs is cost and less heat dissipation. This allows for cheaper computers and smaller form factors. The  trade off is performance. Integrated GPUs are good at less complex tasks like watching videos and processing  graphical documents but are not best suited for intense gaming applications.  

CPUs have also been enhanced using the NX bit, also called the execute disable bit. This feature, when supported  and enabled n the operating system, can protect areas of memory that contain operating system files from  malicious attacks by malware  

#### Single-core
A core is the part of the CPU that reads and executes instructions. As the name implies, a single-core CPU has one core.A motherboard may have sockets for more than one processor, providing the ability to build a powerful multi-processor computer. Most of today’s CPUs have multiple cores.

#### Multicore
A core is the part of the CPU that reads and executes instructions. Multicore CPUs have more than one core. This allows different threads of instructions to be run simultaneously, with each core running one thread, resulting in faster performance. A **dual-core** processor will run faster than a single core, but not quite twice as fast. There are also **triple-core** (which is a quad-core with one of the cores disabled), **quad-core**, **hexa-core**, and **Octa-core** CPUs

#### Multithreading
Multithreading occurs when a CPU is able to run multiple threads at once. A thread is the string of instructions that the CPU runs. Hyper-threading technology (HTT) is a form of simultaneous multithreading marketed by Intel.
Hyper-Transport - a high speed connection between the CPU and the northbridge chip

#### Virtualization Support
CPU virtualization is a hardware feature supported by AMD and Intel CPUs that enables a single processor to act as multiple processors. AMD refers to virtualization support in their products as AMD-V, while Intel refers to virtualization support as Virtualization Technology (VT). This hardware virtualization technology allows the operating system to support virtualization more effectively and efficiently than is possible through software emulation. With CPU virtualization multiple operating systems can run in parallel on their own virtual machines as if they were running on completely independent computers. CPU virtualization is sometimes disabled by default in the BIOS and will need to be enabled.

screen subnet
DMZ
### Expansion Cards
An expansion card can be attached to a motherboard through **expansion slots**. An expansion slot can be used to expand the capabilities of a computer. You must use expansion cards that are compatible with the expansion slots available.

#### Sound Card
Add-on sound cards are used to **improve the sound capabilities** beyond the motherboard’s sound capabilities. A musician, composer, or audiophile may choose to upgrade their computer’s sound with an add-on card.

#### Video Card
**control the graphics** that are displayed. This function may be provided by an add-on card or it may be on-board, meaning built into the motherboard.

**On-board**—On-board video cards typically provide good graphics features and specifications. It serves the purpose for most users, but some users, like gamers or graphic designers, may need better graphics.
**Add-on card**—Add-on video cards have their own **graphics processing unit (GPU)**. They are used to improve the graphics capabilities beyond what the on-board video provides.

#### Capture Card
A capture card is an expansion device that **converts video signals to digital signals** that can then be uploaded to the internet.

#### NIC
A network interface card (NIC) is a device that provides a device with the capability to **connect to a network**, typically the internet. A NIC can be either an **on-board or add-on** card and may be either **wired or wireless** connections.

### Cooling
Components on motherboards and add-on cards generate heat, especially CPUs and GPUs. There are several types of cooling mechanisms to remove heat from a computer.

The speed of a modern processor is measured in GHz. A maximum speed rating refers to the maximum speed at which a processor can function without errors. Two primary factors can limit the speed of a processor:

- **Transmission Delay** - The processor chip is a collection of transistors interconnected by wires. Transmitting data through the transistors and wires creates delays.
- **Heat Generation** - As the transistors change state from on to off or off to on, a small amount of heat is generated. The amount of heat generated increases as the speed of the processor increases. When the processor becomes too hot, it begins to produce errors.

The front-side bus (FSB) is the path between the CPU and the [[Northbridge]]. It is used to connect various components, such as the chipset, expansion cards, and RAM. Data can travel in both directions across the FSB. The frequency of the bus is measured in MHz. The frequency at which a CPU operates is determined by applying a clock multiplier to the FSB speed. For example, a processor running at 3200 MHz might be using a 400 MHz FSB. 3200 MHz divided by 400 MHz is 8, so the CPU is eight times faster than the FSB.

Processors are further classified as 32-bit and 64-bit. The primary difference is the number of instructions that can be handled by the processor at one time. A 64-bit processor processes more instructions per clock cycle than a 32-bit processor. A 64-bit processor can also support more memory. To utilize the 64-bit processor capabilities, ensure that the operating system and applications installed support a 64-bit processor.

The CPU is one of the most expensive and sensitive components in the computer case. The CPU can become very hot; therefore most CPUs require an air-cooled or liquid cooled heat sink, combined with a fan for cooling.

#### Types
##### Fans
are used to **move air** through a computer to remove heat. Fans are positioned in the case to allow air to pass between the inside of the case and the outside. Fans are also used on individual components to provide extra cooling. They are sometimes integrated with a heat sink.

**Case Fan**
An active cooling solution uses fans inside of a computer case to blow out hot air. For increased air flow, some cases have multiple fans with cool air being brought in while another fan is blowing out hot air.

**CPU Fan**
CPUs that are overclocked or running multiple cores tend to generate excessive heat. It is a very common practice to install a fan on top of the heat sink. The fan moves heat away from the metal fins of the heatsink. This is known as active cooling.

##### Heat Sink
devices that conduct heat and have the effect of increasing the surface area of a component. The heat sink has a large surface area with metal fins to dissipate heat into the surrounding air. This is known as passive cooling. Between the heat sink and the CPU is a special thermal compound. The thermal compound increases the efficiency of heat transfer from the CPU to the heat sink by filling any tiny gaps between the two. This **removes heat** from the component more quickly than fans alone. Some heat sinks have fans built into them. Used in CPUs, M.2 SSDs, and GPUs

##### Thermal Paste/Pads
The quality of contact between a component to be cooled and the heat sink used to cool it will impact how effectively it is cooled. Thermal paste and thermal pads conduct heat and are used between the component and heat sink to **make the best thermal-conductive connection**.

##### Liquid
For high-performance computers, air cooling may not be enough. Liquid cooling is more effective at **transferring heat** away from components. **Distilled water** is the most commonly used liquid. Liquid cooling systems include a tank for the liquid, a radiator, a water pump, and a cooling block that attaches to the component being cooled. These components may be in the computer or outside in a separate unit that connects to the computer. CPU fans make noise and can be annoying at high speeds so liquid cooling used in silent computers

#### Selection

| **Factors**            |                                                                                                      |
| ---------------------- | ---------------------------------------------------------------------------------------------------- |
| Socket type            | The heat sink or fan type must match the socket type of the motherboard                              |
| Motherboard dimensions | The heat sink or fan must not interfere with any components attached to the motherboard              |
| Case size              | The heat sink and fan must fit within the case                                                       |
| Physical environment   | The heat sink and fan must be able to disperse enough heat to keep the CPU cool in warm environments |

# Installation

1. Install the [[CPU]]
2. Install the [[RAM]]
3. Install motherboard in the case

## Upgrade 
Computers need periodic upgrades for various reasons:
- User requirements change
- Upgraded software packages require new hardware
- New hardware offers enhanced performance

Changes to the computer may cause you to upgrade or replace components and peripherals. Research the effectiveness and cost of both upgrading and replacing.

If you upgrade or replace a motherboard, consider that you might have to replace other components including the CPU, heat sink and fan assembly, and RAM. A new motherboard must also fit into the old computer case and the power supply must support it.

When upgrading the motherboard, begin the upgrade by moving the CPU and the heat sink and fan assembly to the new motherboard if they will be reused. These items are much easier to work with when they are outside of the case. Work on an antistatic mat, and wear antistatic gloves or an antistatic wrist strap to avoid damaging the CPU. If the new motherboard requires a different CPU and RAM, install them at this time. Clean the thermal compound from the CPU and heat sink. Remember to re-apply thermal compound between the CPU and the heat sink.

Before beginning an upgrade, ensure that you know where and how everything is connected. Always make notes in a journal to record how the current computer is set up. A quick way is to use a cell phone and take pictures of important items such as how components connect to the motherboard. These pictures may prove to be surprisingly helpful when re-assembling.

To upgrade a motherboard from a computer case, follow these steps:

- **Step 1.** Record how the power supply, case fans, case LEDs, and case buttons attach to the old motherboard.
- **Step 2.** Disconnect the cables from the old motherboard.
- **Step 3.** Disconnect the expansion cards from the case. Remove each expansion card and place them in antistatic bags, or on an antistatic mat.
- **Step 4.** Carefully record how the old motherboard is secured to the case. Some mounting screws provide support while some may provide an important grounding connection between the motherboard and chassis. In particular, pay attention to screws and standoffs that are non-metallic, because these may be insulators. Replacing insulating screws and supports with metal hardware that conducts electricity might damage electrical components.
- **Step 5.** Remove the old motherboard from the case.
- **Step 6.** Examine the new motherboard and identify where all of the connectors are such as power, SATA, fan, USB, audio, front panel connector, and any others.
- **Step 7.** Examine the I/O shield located at the back of the computer case. Replace the old I/O shield with the I/O shield that comes with the new motherboard.

**Step 8.** Insert and secure the motherboard into the case. Be sure to consult the case and motherboard manufacturer user guides. Use the proper types of screws. Do not swap threaded screws with self-tapping metal screws, because they will damage the threaded screw holes and might not be secure. Make sure that the threaded screws are the correct length and have the same number of threads per inch. If the thread is correct, they fit easily. If you force a screw to fit, you can damage the threaded hole, and it will not hold the motherboard securely. Using the wrong screw can also produce metal shavings that can cause short circuits.

**Step 9.** Next, connect the power supply, case fans, case LEDs, front panel, and any other required cables. If the ATX power connectors are not the same size (some have more pins than others), you might need to use an adapter. Refer to the motherboard documentation for the layout of these connections.

**Step 10.** After the new motherboard is in place and the cables are connected, install and secure the expansion cards.

It is now time to check your work. Make sure that there are no loose parts or unconnected cables. Connect the keyboard, mouse, monitor, and power. If a problem is detected, shut the power supply off immediately.

### CPU Upgrade
One way to increase the power of a computer is to increase the processing speed. You can do this by upgrading the CPU. However, the CPU must meet the requirements listed in the figure.

The new CPU might require a different heat sink and fan assembly. The assembly must physically fit the CPU and be compatible with the CPU socket. It must also be adequate to remove the heat of the faster CPU.

**CAUTION**: You must apply thermal compound between the new CPU and the heat sink and fan assembly.

**Requirements**
- The new CPU must fit into the existing CPU socket.
- The new CPU must be compatible with the motherboard chipset.
- The new CPU must operate with the existing motherboard and power supply.

View thermal settings in the BIOS to determine if there are any problems with the CPU and the heat sink and fan assembly. Third-party software applications can also report CPU temperature information in an easy-to-read format. Refer to the motherboard or CPU user documentation to determine if the chip is operating in the correct temperature range.

To install additional fans in the case to help cool the computer, follow these steps:

**Step 1.** Align the fan so that it faces the correct direction to either draw air in or blow air out.

**Step 2.** Mount the fan using the predrilled holes in the case. It is common to mount fans near the top of the case to blow hot air out, and near the bottom of the case to bring air in. Avoid mounting two fans close together that are moving air in opposite directions.

**Step 3.** Connect the fan to the power supply or the motherboard, depending on the case fan plug type.

### Storage Upgrade
Instead of purchasing a new computer to get faster speed and more storage space, you might consider adding another hard drive. There are several reasons for installing an additional drive as listed in the figure.

After selecting the appropriate hard drive for the computer, follow these general guidelines during installation:

**Step 1.** Place the hard drive in an empty drive bay, and tighten the screws to secure the hard drive.

**Step 2.** Connect the drive to the motherboard using the correct cable.

**Step 3.** Attach the power cable to the drive.

**Reasons for New Drive**
- Increase storage space
- Increase hard drive speed
- Install a second operating system
- Store the system swap file
- Provide fault tolerance
- Back up the original hard drive

### Peripheral Upgrades
Peripheral devices periodically need to be upgraded. For example, if the device stops operating or if you wish to improve performance and productivity, an upgrade might be necessary.

These are a few reasons for upgrading a keyboard and/or a mouse:
- Change the keyboard and mouse to an ergonomic design such as those shown in the figure below. Ergonomic devices are made to be more comfortable to use and to help prevent repetitive motion injuries.
- Reconfigure the keyboard to accommodate a special task, such as typing in a second language with additional characters.
- To accommodate users with disabilities.

However, sometimes it is not possible to perform an upgrade using the existing expansion slots or sockets. In this case, you may be able to accomplish the upgrade using a USB connection. If the computer does not have an extra USB connection, you must install a USB adapter card or purchase a USB hub.

### Power Supply Upgrade
Upgrading your computer hardware will most likely also change its power needs. If so, you may need to upgrade your power supply. You can find calculators on the internet to help you determine if you need to upgrade the power supply. Search for “power supply wattage calculator”.

In addition to upgrading for additional power, a computer may be capable of having two power supplies. One acts as a redundant power supply in case of failure. A special motherboard must be used to take advantage of this configuration. This configuration is not often found with desktop computers. It is more commonly used in servers. This allows both power supplies to be hot-swappable. The faulty power supply can be replaced without losing power to the computer.