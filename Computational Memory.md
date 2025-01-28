---
tags: 
parent docs:
  - "[[Hardware]]"
sibling docs: 
child docs: 
last updated: 2025-01-08T21:32:00
media:
---
# Nav
| < [[Cabling and Ports]] < | ^ [[Hardware]] ^ | > [[Storage]] > |

---
# [[RAM]] - Random Access Memory
This is the memory bank for data currently in use by a computer or device. It is a temporary location to store data and applications.
RAM is the temporary working storage for data and programs that are being accessed by the CPU. Unlike ROM, RAM is volatile memory, which means that the contents are erased every time the computer is powered off.
Adding more RAM in a computer enhances the system performance. For instance, more RAM increases the memory capacity of the computer to hold and process programs and files. With less RAM, a computer must swap data between RAM and the much slower hard drive. The maximum amount of RAM that can be installed is limited by the form factor of the motherboard.
You must be able to identify and install different RAM types. These questions will be scenario based.
 
### Modules
Early computers had RAM installed on the motherboard as individual chips. The individual memory chips, called dual inline package (DIP) chips, were difficult to install and often became loose. To solve this problem, designers soldered the memory chips to a circuit board to create a memory module which would then be placed into a memory slot on the motherboard.

#### Dynamic RAM
DRAM gradually discharges energy so it must be constantly refreshed with pulses of electricity in order to maintain the stored data in the chip. it is an older type of RAM popular until the mid-1990s and was used as the main memory bank 

#### Static RAM
requires constant but lower power to function. used in the modern day for cache memory as it is faster but more expensive than DRAM
##### Cache Memory
The fastest memory is typically static RAM (SRAM) which is cache memory for storing the most recently used data and instructions by the CPU. SRAM provides the processor with faster access to the data than retrieving it from the slower dynamic RAM (DRAM), or main memory.
- **L1** : an internal cache that is integrated into the CPU. A CPU can have various models each with a different amount of L1 cache.
- **L2** : an external cache that was originally mounted on the motherboard near the CPU. L2 cache is now integrated into the CPU.
- **L3** : used on some high-end workstations and server CPUs.

#### Synchronous Dynamic RAM - (SDRAM)
DRAM that operates in synchronization with the memory bus. It is able to process overlapping instructions in parallel – e.g. It can process a read before a write has been completed. It has high transfer rates.

#### Double Data Rate Synchronous Dynamic RAM - (DDRSD) 
DDR-SDRAM transfers data twice as fast as SDRAM as it is able to support two writes and two reads per CPU clock cycle. The connector has 184 pins and a single notch and uses lower standard voltage (2.5 V)
##### Transfer Rates

| RAM Type | Speed                  | Peak Transfer Rate*                                                                     |
| -------- | ---------------------- | --------------------------------------------------------------------------------------- |
| DDR      | 266, 333, 400          | 2.1 GB/s, 2.7 GB/s, 3.2 GB/s                                                            |
| DDR2     | 533, 667, 800          | 4.27 GB/s, 5.33 GB/s, 6.4 GB/s                                                          |
| DDR3     | 1066, 1333, 1600, 1866 | 8.5 GB/s, 10.6 GB/s, 12.8 GB/s, 14.9 GB/s                                               |
| DDR4     | 2133, 2400, 2666, 3200 | 17 GB/s, 19.2 GB/s, 21.3 GB/s, 25.6 GB/s                                                |
| DDR5     |                        |                                                                                         |
|          |                        | Practical transfer rate is limited by the CPU and the specifications of the motherboard |


##### Double Data Rate 2 (DDR2) 
runs at higher clock speeds than DDR (553 MHz vs. DDR at 200 MHz) Improves performance by decreasing noise and crosstalk between signal wires. The connector has 240 pins and uses an even lower standard voltage (1.8 V)

##### Double Data Rate 3 (DDR3)
DDR3 is **faster than DDR2** and has 30% **less power consumption**. It comes in 240-pin DIMM and 204-pin SODIMM. Double data rate (DDR), as the name implies, doubles the transfer rate of memory. DDR2 further increases the speed by two. DDR and DDR2 are legacy technologies and no longer used in modern devices.
- expands memory bandwidth by doubling the clock rate of DDR2. It consumes less power than DDR2 (1.5 V), generates less heat, runs at higher clock speeds (up to 800 MHz) and has a connector with 240 pins

##### Double Data Rate 4 (DDR4)
DDR4 is **faster than DDR3** and has **less power consumption**. It comes in 288-pin DIMM and 260-pin SODIMM.
- quadruples DDR3 maximum storage capacity, consumes less power than DDR3 (1.2 V), runs at higher clock speeds (up to 1600 MHz), and has a connector with 288 pins. Available with advanced error correction features such as error-correcting code memory (ECC memory) to detect multiple bit errors.

##### Double Data Rate 5 (DDR5)
DDR5 **doubles the speed of DDR4** to 6.4 Gbps with improved power efficiency at 1.1 volts and is available in **up to 128 GB** modules.
- more than double the speed of the fastest DDR4 modules and quadruples its maximum storage capacity. Slightly lower power consumption than DDR4 (1.1 V). Has a maximum module size is 128 GB, and a connector with 288 pins but a different pattern than DDR4, so they are not compatible.

##### Graphics DDR 
RAM designed for video graphics. Used in conjunction with a dedicated GPU, and processes massive amounts of data but not necessarily at the fastest speeds. Has a hardware family (GDDR2-5) with each family member improves performance and lowers power consumption.

#### Virtual RAM
Virtual RAM is space on a hard drive that can be allocated when additional memory is requested from an application. This space on the hard drive is also known as a **swap file** or a **paging file**.
#### Dual Inline Package (DIP)
an individual memory chip. A DIP has dual rows of pins used to attach it to the motherboard.

#### Single Inline Memory Module (SIMM)
 a small circuit board that holds several memory chips. SIMMs have 30-pin or 72-pin configurations.

#### Dual Inline Memory Module (DIMM) 
a circuit board that holds SDRAM, DDR SDRAM, DDR2 SDRAM, DDR3 SDRAM, and DDR4 SDRAM chips. There are 168-pin SDRAM DIMMs, 184-pin DDR DIMMs, 240-pin DDR2 and DDR3 DIMMs, and 288-pin DDR4 DIMMs.

#### Small Outline Dual Inline Memory Module (SODIMM)
Small outline dual inline memory modules are commonly found in laptops where space is at a premium and come in 100-, 144-, 200-, 204-, and 260-pin configurations. SODIMM defines the physical form factor of the module.
Small Outline DIMM has a 72-pin and 100-pin configurations for support of 32-bit transfers or a 144-pin, 200-pin, 204-pin, and 260-pin configurations for support of 64-bit transfers. This smaller, more condensed version of DIMM provides random access data storage that is ideal for use in laptops, printers, and other devices where conserving space is desirable.
#### Error-Correcting Code (ECC) RAM
Error-correcting code memory has **logic built in** to detect and correct single-bit memory errors. For each byte (eight bits) of memory, a parity bit is set that will allow the logic to detect and **correct an error in a single bit** of each byte. The logic would not correct an error in any byte with more than one bad bit.
Memory errors occur when the data is not stored correctly in the chips. The computer uses different methods to detect and correct data errors in memory.
- **Nonparity** : does not check for errors in memory. Nonparity RAM is the most common RAM used for home and business workstations.
- **Parity** : contains eight bits for data and one bit for error checking. The error-checking bit is called a parity bit.
- **ECC** : Error Correction Code memory can detect multiple bit errors in memory and correct single bit errors in memory. On servers used for financial or data analytics, ECC memory modules may be required.

### Multi-channel
Memory modules can be single-sided or double-sided. Single-sided memory modules contain RAM on only one side of the module. Double-sided memory modules contain RAM on both sides.

The speed of memory has a direct impact on how much data a processor can process in a given period of time. As processor speed increases, memory speed must also increase. Memory throughput has also been increased through multichannel technology. Standard RAM is single channel, meaning that all of the RAM slots are addressed at the same time. Dual channel RAM adds a second channel to be able to access a second module at the same time. 

Triple channel technology provides another channel so that three modules can be accessed at the same time. Quadruple channel adds another channel to the memory controller for even higher bandwidth. To use triple and quadruple channel memory controllers for the most bandwidth, the chipset architecture must support it and will only be able to use as many channels that have memory slots populated. In many cases, memory slots can only be populated in a certain order to ensure all memory channels are used.

#### Single-Channel
Single-channel memory transfers data in chunks the same size as the system bus’s bandwidth.

#### Dual-Channel
Dual-channel memory occurs when the memory controller **coordinates two memory banks** to work in conjunction with one another as a synchronized set when communicating with the CPU, doubling the size of the data transfer.

#### Triple-Channel
Triple-channel memory **coordinates three memory modules** for communication with the CPU.

#### Quad-Channel
Quad-channel memory **coordinates four memory modules** for communication with the CPU.

# [[ROM]] - Read Only Memory
An essential computer chip is the read-only memory (ROM) chip. ROM chips are located on the motherboard and other circuit boards and contain instructions that can be directly accessed by a CPU. The instructions stored in ROM include basic operation instructions such as booting the computer and loading the operating system.
ROM is nonvolatile which means that the contents are not erased when the computer is powered off.
Information is written to a ROM chip when it is manufactured. A ROM chip that cannot be erased or re-written is now obsolete. The term ROM still tends to be used generically for any read-only memory chip type.

**[[PROM]]**
Information on a programmable read-only memory chip is written after it is manufactured. PROMs are manufactured blank and then can be programmed by a PROM programmer when needed. Generally, these chips cannot be erased and can only be programmed once.

**[[EPROM]]**
Erasable programmable read-only memory is non-volatile but can be erased by exposing it to strong ultraviolet light. EPROMs usually have a transparent quartz window on the top of the chip. Constant erasing and reprogramming could ultimately render the chip useless.

**[[EEPROM]]**
Information is written to an electrically erasable programmable read-only memory chip after it is manufactured and without removing it from the device. EEPROM chips are also called Flash ROMs since its contents can be "flashed" for deletion. EEPROMs are often used to store a computer system's BIOS.
