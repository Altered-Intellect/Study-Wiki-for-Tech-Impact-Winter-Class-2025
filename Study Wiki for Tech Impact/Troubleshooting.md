---
tags: 
parent docs:
  - "[[Navigation]]"
sibling docs: 
child docs: 
last updated: 2025-01-14T23:28:00
media:
---
Troubleshooting requires an organized and logical approach to problems with computers and other components. Sometimes issues arise during preventive maintenance. At other times, a customer may contact you with a problem. A logical approach to troubleshooting allows you to eliminate variables and identify causes of problems in a systematic order. Asking the right questions, testing the right hardware, and examining the right data helps you understand the problem and form a proposed solution.

Troubleshooting is a skill that you refine over time. Each time you solve a problem, you increase your troubleshooting skills by gaining more experience. You learn how and when to combine steps, or skip steps, to reach a solution quickly. The troubleshooting process is a guideline that is modified to fit your needs.

This section presents an approach to problem-solving that you can apply to both hardware and software.

**Note**: The term customer, as used in this course, is any user that requires technical computer assistance.

Before you begin troubleshooting problems, always follow the necessary precautions to protect data on a computer. Some repairs, such as replacing a hard drive or reinstalling an operating system, might put the data on the computer at risk. Make sure you do everything possible to prevent data loss while attempting repairs. If your work results in data loss for the customer, you or your company could be held liable.

## Data Backup

A data backup is a copy of the data on a computer hard drive that is saved to another storage device or to cloud storage. Cloud storage is online storage that is accessed via the internet. In an organization, backups may be performed on a daily, weekly, or monthly basis.

If you are unsure that a backup has been done, do not attempt any troubleshooting activities until you check with the customer. Here is a list of items to verify with the customer that a backup has been performed:
- Date of the last backup
- Contents of the backup
- Data integrity of the backup
- Availability of all backup media for a data restore

If the customer does not have a current backup and you are not able to create one, ask the customer to sign a liability release form. A liability release form contains at least the following information:
- Permission to work on the computer without a current backup available
- Release from liability if data is lost or corrupted
- Description of the work to be performed


# Methodology
Best practice methodology refers to the use of basic structured principles that should be followed when approaching a troubleshooting situation. While individuals may approach troubleshooting differently, certain **basic principles remain constant**: create a backup, prioritize tasks, and document the process. _Note:_ Questions regarding this section of the exam will come in the form of scenarios.

## Corporate Policies, Procedures, and Impacts
Every corporate enterprise has differing policies and procedures. Always consider corporate policies, procedures, and potential impacts before you begin troubleshooting.

### 1. Identify the Problem
Observation is that first step of any action and is crucial for problem solving. Technical problems with computer systems generally occur in one (or more) of **four areas**: hardware, the operating system, software, and the user. It is vital to accurately identify the problem **before taking action**.
- **Gather information**—To properly identify a problem, begin by gathering information **from the user and the computer system** in question. When gathering information from the user, ask questions to clarify the problem. Clarifying the issue will give you a starting point for further investigation. After questioning the user, examine the device to determine what is working and what is not. Check for common issues such as power problems or issues resolved upon reboot. Look into systems logs or application logs for information. Is the issue a hardware problem or a software problem?
- **Inquire about changes**—Consider all the changes that could affect the user (e.g., network, computer, power issues, external connection, user account) and how those changes can be involved in the problem. As an example, let’s say the network team worked over the weekend performing an upgrade to the infrastructure (switch replacement) and neglected to plug all the cabling back into the switch (as simple as a cable falling behind the wiring channel and being missed). The user might have been the one missed and now they cannot authenticate to the network, access their files, print to the network printer, and, therefore, cannot perform common functions. These things happen daily and other teams can be conducting changes without regard to the effect on employees.
**Conversation Etiquette**
When you are talking to the customer, follow these guidelines:
- ask direct questions
- use common terms
- be polite, do not talk down or insult
- do not accuse the customer of causing the problem
Information to gather 

| type                   | description                                                   |
| ---------------------- | ------------------------------------------------------------- |
| Customer Info          | company, contact, address, phone number                       |
| Computer Configuration | manufacturer, model, OS, network environment, connection type |
| Problem Description    | open/close-ended questions                                    |
| Feedback               | error messages, beep sequences, LEDs, POST                    |
**Open-Ended and Closed-Ended Questions**
Open-ended questions allow customers to explain the details of the problem in their own words. Use open-ended questions to obtain general information.

Based on the information from the customer, you can proceed with closed-ended questions. Closed-ended questions generally require a yes or no answer.

**Documenting Responses**
Document the information from the customer in the work order, in the repair log, and in your repair journal. Write down anything that you think might be important for you or another technician. The small details often lead to the solution of a difficult or complicated problem.

**Beep Codes**
Each BIOS manufacturer has a unique beep sequence, a combination of long and short beeps, for hardware failures. When troubleshooting, power on the computer and listen. As the system proceeds through the POST, most computers emit one beep to indicate that the system is booting properly. If there is an error, you might hear multiple beeps. Document the beep code sequence, and research the code to determine the specific problem.

**BIOS Information**
If the computer boots and stops after the POST, investigate the BIOS settings. A device might not be detected or configured properly. Refer to the motherboard documentation to ensure that the BIOS settings are correct.

**Diagnostic Tools**
Conduct research to determine which software is available to help diagnose and solve problems. There are many programs to help you troubleshoot hardware. Manufacturers of system hardware usually provide diagnostic tools of their own. For instance, a hard drive manufacturer might provide a tool to boot the computer and diagnose why the hard drive does not start the operating system.

**Device Manager**
The Device Manager displays all the devices that are configured on a computer. The operating system flags the devices that are not operating correctly with an error icon. A yellow triangle with an exclamation point indicates that the device is in a problem state. A red X means that the device is disabled, removed, or Windows can't locate the device. An arrow down means the device has been disabled. A yellow question mark indicates that the system does not know which driver to install for the hardware.

**Task Manager**
The Task Manager displays the applications and background processes that are currently running. With the Task Manager, you can close applications that have stopped responding. You can also monitor the performance of the CPU and virtual memory, view all processes that are currently running, and view information about the network connections.

### 2. Create a Theory of Probable Cause
Keep it **simple**. Always question the obvious and don’t assume something isn’t relevant. You might think it is common sense to be plugged into the network, but the user might not know this. Using your questioning ability, develop a theory (or two) regarding what the problem might be. When developing a theory, remember to **eliminate possible theories** as well if they do not fit the scenario.
- **External or internal research**—Utilize research resources, which can include internal and external resources. Check previous service **documentation** within the company, refer back to the **device manual**, and check for potential theories using **online** forums and search engines. The internet, when utilized properly, can be extremely helpful for troubleshooting problems.
	- device is powered off
	- power switch for an outlet is turned off
	- surge protector is turned off
	- loose external cable connections
	- non-bootable disk in designated boot drive
	- incorrect boot order in BIOS setup

### 3. Test the Theory/Determine the Cause
When you have your theory developed, you need to test it. On a time-sensitive issue, or if you know 100% that the theory is valid, you can implement it based upon corporate policies and/or procedures. In a perfect world, you would be able to replicate the issue within a testing (or laboratory) environment for verification. This isn’t always the case and you should be ready to test your theory at a moment’s notice. When testing a theory, **begin with the most obvious** and simple theories first, such as checking the power supply or ensuring cables are properly seated, before moving onto more complicated theories.
- **If theory is confirmed, determine next steps**—Only **test one possible solution at a time** and only **make one change at a time**. Sounds like a lengthy process? It is, but if you implement multiple changes in one process, how do you know which one worked and which one didn’t? Remember, keep it simple. If your theory is confirmed, then you can skip to the plan of action to implement your theory. If not, then it’s back to testing again. No worries, proper troubleshooting is an art.
- **If theory is not confirmed, establish new theory or escalate**—You’ve tested your theory and the problem still exists. Step back and take a look at your theory to see what other avenues are available and develop a working theory regarding the next possible solution. If you have exhausted all your potential theories, it may be time to escalate the problem.

You can determine an exact cause by testing your theories of probable causes one at a time, starting with the quickest and easiest. The table below identifies some common steps to determine the cause of the problem. Once the theory is confirmed, you then determine the steps to resolve the problem. As you become more experienced at troubleshooting computers, you will work through the steps in the process faster. For now, practice each step to better understand the troubleshooting process.
Common steps to determine a cause 
- ensure the device is powered on
- power switch for an outlet is turned on
- surge protector is turned on
- external cable connections are secure
- the designated boot drive is bootable
- verify the boot order in the BIOS setup

If you cannot determine the exact cause of the problem after testing all your theories, establish a new theory of probable cause and test it. If necessary, escalate the problem to a technician with more experience. Before you escalate, document each test that you tried, as shown in the work order below.

### 4. Create and Execute a Plan of Action
Always remember: Your **company’s policies and procedures take precedence** and should be in the forefront prior to acting on any plan. The conclusion that you make might affect the whole company, but that might also be needed depending on the breath of the issue. Does correcting the issue require downtime for the company or just a single computer? Can that be scheduled around the users’ workday? Does it need to happen immediately? These are all questions that should be included in your plan of action.
- **Vendor instructions**—When creating a plan of action, remember to take into account vendor instructions. Vendors often provide **documented fixes** to identified issues, which should be considered.

Divide larger problems into smaller problems than can be analyzed and solved individually. Prioritize solutions starting with the easiest and the fastest to implement. Create a list of possible  silutions and implement them one at a time. If you implement a possible solution and it does not correct the problem, reverse the action and try another solution. Continue this process until you have found the appropriate solution
If no solution is achieved in the previous step, further research is needed to implement the solution
- help desk repair logs
- other technicians
- manufacturer FAQ sites
- new groups
- computer manuals
- device manuals
- online forums
- internet search
### 5. Verify System Functionality
Once the issues have been resolved or appear to be resolved, verify full functionality of the problem system. Remember to verify **full system functionality** and do not focus strictly on the problem system. A fix to one system or component may cause issues with another system or component. Verifying full system functionality confirms that you have solved the original problem while repairing the computer. Whenever possible, have the customer verify the solution and system functionality.
- reboot the computer
- ensure multiple applications work properly
- verify network and internet connections
- print a document from one application 
- ensure all attached devices work properly
- ensure no error messages are received

### 6. Document Findings, Actions, and Outcomes
We can’t express how important it is for issues to be fully documented. **Everything that you have done** from the moment the user contacted you to the moment the user was back online, such as indications, findings, actions, outcomes, scenarios, etc., must be documented. Your **company should have a repository** to keep this information safe. It should also be possible to share among your peers in the event the same type of issue arises in the future. 

If the customer is available, demonstrate how the solution has corrected the computer problem. have the customer relay the solution and try to reproduce the problem. When the customer can verify that the problem has been resolved, you can complete the documentation for the repair in the work order and in your journal. 
Include the following information in the documentation:
- description of the problem, including precautions and complications
- steps to resolve the problem, from description to testing
- components and tools used in the repair

# Common PC Problems
Computer problems can be attributed to hardware, software, networks, or some combination of the three. You will resolve some types of problems more often than others.

These are some common hardware problems:
- **Storage Device** - Storage device problems are often related to loose, or incorrect cable connections, incorrect drive and media formats, and incorrect jumper and BIOS settings.
- **Motherboard and Internal Components** - These problems are often caused by incorrect or loose cables, failed components, incorrect drivers, and corrupted updates.
- **Power Supply** - Power problems are often caused by a faulty power supply, loose connections, and inadequate wattage.
- **CPU and Memory** - Processor and memory problems are often caused by faulty installations, incorrect BIOS settings, inadequate cooling and ventilation, and compatibility issues.
- **Displays** - Display problems are often caused by incorrect settings, loose connections, and incorrect or corrupted drivers.

## [[Storage]]
Computer does not recognize a storage device.

| Probable Cause              | Possible Solutions                   |
| --------------------------- | ------------------------------------ |
| loose power or data cable   | secure cable                         |
| jumpers are set incorrectly | reset jumpers                        |
| storage device failed       | replace storage device               |
| incorrect BIOS setting      | reset storage device setting in BIOS |
Computer does not recognize an optical disc.

| Probable Cause                                    | Possible Solutions                                       |
| ------------------------------------------------- | -------------------------------------------------------- |
| the disc is inserted upside-down                  | invert disc                                              |
| there is more than one disc inserted in the drive | ensure that there is only one disc inserted in the drive |
| a disc is damaged                                 | replace disc                                             |
| a disc is in the wrong format                     | use the correct disc type                                |
| the optical drive is faulty                       | replace the optical disc                                 |
The computer will not eject the optical disc

| Probable Cause                                | Possible Solutions                                                   |
| --------------------------------------------- | -------------------------------------------------------------------- |
| the optical drive is jammed                   | insert a pin in the small hole next to the eject button on the drive |
| the optical drive has been locked by software | reboot the computer                                                  |
| the optical drive is faulty                   | replace the optical drive                                            |
The computer does not recognize a removable, external drive

| Probable Cause                                       | Possible Solutions                    |
| ---------------------------------------------------- | ------------------------------------- |
| the removeable external drive is not seated properly | remove and reseat the drive           |
| the external ports are disabled in the BIOS settings | enable the ports in the BIOS settings |
| the removable external drive is faulty               | replace the removable external drive  |
A media reader can not read a memory card that works properly

| Probable Cause                                                   | Possible Solutions                                             |
| ---------------------------------------------------------------- | -------------------------------------------------------------- |
| the media reader does not support the memory card type           | use a different memory card type                               |
| the media reader is not connected correctly                      | ensure the media reader is connected correctly in the computer |
| the media reader is not configured properly in the BIOS settings | reconfigure the media reader in the BIOS settings              |
| the media reader is faulty                                       | install a known good media reader                              |
Retrieving or saving data from the USB flash drive is slow.

| Probable Cause                                     | Possible Solutions                                                                         |
| -------------------------------------------------- | ------------------------------------------------------------------------------------------ |
| the motherboard does not support USB 3.0           | replace the motherboard with a USB 3.0 capable motherboard or add a USB 3.0 expansion card |
| the port is set to full speed in the BIOS settings | set the port speed in the BIOS settings to high speed                                      |
The computer does not recognize a removable external drive

| Probable Cause                                                            | Possible Solutions                                                    |
| ------------------------------------------------------------------------- | --------------------------------------------------------------------- |
| the OS does not have the correct drivers for the removable external drive | download the correct drivers for the external drive                   |
| the USB port has too many attached devices to supply power                | attach external power to the device or remove some of the USB devices |
"Can not read from source disk" error is displayed when a use tries to open or save a file.

| Probable Cause | Possible Solutions |
| -------------- | ------------------ |
| failing drive  | replace disk       |

### [[RAID]]
RAID can not be found or stops working

| Probable Cause                                      | Possible Solutions                                                                       |
| --------------------------------------------------- | ---------------------------------------------------------------------------------------- |
| the external RAID controller is not receiving power | check the power connections to the RAID conntroller                                      |
| the BIOS settings are incorrect                     | reconfigure the BIOS settings for the RAID controller                                    |
| the RAID controller has failed                      | replace the RAID controller                                                              |
| missing driver for RAID controller                  | check the drivers are installed and use the RAID configurations utility to verify status |

## [[Motherboards]]
The clock on the computer is no longer keeping the correct time or the BIOS setting are changing when the computer is rebooted.

| Probable Cause                  | Possible Solutions |
| ------------------------------- | ------------------ |
| the CMOS batter may be loose    | secure battery     |
| the CMOS battery may be drained | replace battery    |
After updating the BIOS firmware, the computer will not start.

| Probable Cause                                     | Possible Solutions                                                                                                                          |
| -------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------- |
| the BIOS firmware update did not install correctly | contact the motherboard manufacturer to obtain the new BIOS chip. (if the motherboard has two BIOS chips, the second BIOS chip can be used) |
The computer displays the incorrect CPU information when the computer boots.

| Probable Cause                                                 | Possible Solutions                                   |
| -------------------------------------------------------------- | ---------------------------------------------------- |
| the CPU settings are not correct in the advanced BIOS settings | set the advanced BIOS settings correctly for the CPU |
| BIOS does not properly recognize the CPU                       | update the BIOS                                      |
The hard drive LED on the front of the computer does not turn on.

| Probable Cause                                        | Possible Solutions                                                                         |
| ----------------------------------------------------- | ------------------------------------------------------------------------------------------ |
| the hard drive LED cable is not connected or is loose | reconnect the LED cable to the motherboard                                                 |
| the hard drive LED cable is incorrectly oriented      | correctly orient the hard drive LED cable to the front case panel connection and reconnect |
The built-in NIC has stopped working

| Probable Cause              | Possible Solutions                            |
| --------------------------- | --------------------------------------------- |
| the NIC hardware has failed | install a new NIC into an open expansion slot |
The computer does not display any video after installing a new PCIe video card

| Probable Cause                                             | Possible Solutions                                      |
| ---------------------------------------------------------- | ------------------------------------------------------- |
| BIOS settings are set to use the built-in video            | disable the built-in video in the BIOS settings         |
| the monitor cable is still connected to the built-in video | connect the monitor cable to the new video card         |
| the new video card needs auxiliary power                   | connect any required power connectors to the video card |
| the new video card is faulty                               | install a good video card                               |
The new sound card does not work

| Probable Cause                                         | Possible Solutions                                     |
| ------------------------------------------------------ | ------------------------------------------------------ |
| the speaker are not connected to the correct jack      | connect the speakers the correct jack                  |
| the audio is muted                                     | unmute the audio                                       |
| the sound card is faulty                               | install a good sound card                              |
| BIOS settings are set to use the on-board sound device | disable the on-board audio device in the BIOS settings |
System attempts to boot to an incorrect device

| Probable Cause                           | Possible Solutions                                                                              |
| ---------------------------------------- | ----------------------------------------------------------------------------------------------- |
| media was left on a removable drive      | check that the removeable drives do not contain media that is interfering with the boot process |
| the boot order is configured incorrectly | check that the boot order is configured correctly                                               |
User can hear fans spinning but the computer does not start and there are no beeps from the speaker.

| Probable Cause                  | Possible Solutions                                                            |
| ------------------------------- | ----------------------------------------------------------------------------- |
| POST procedure is not executing | faulty cabling, damaged or mis-seated CPU, or the other motherboard component |
Motherboard capacitors are distended, swollen, emitting residue, or bulging.

| Probable Cause                  | Possible Solutions  |
| ------------------------------- | ------------------- |
| heat, ESP, power surge or spike | replace motherboard |
After updating the BOIS firmware, the computer will not start

| Probable Cause                                     | Possible Solutions                                                                                                                                                                                    |
| -------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| the BIOS firmware update did not install correctly | restore the original firmware from the onboard backup if it is available, if the motherboard has two BIOS chips use the second one, or contact the motherboard manufacturer to obtain a new BIOS chip |

### CPU and memory
The computer will not boot or it locks up

| Probable Cause                | Possible Solutions                                              |
| ----------------------------- | --------------------------------------------------------------- |
| the CPU has over heated       | reinstall the CPU, replace the CPU fan, or add fans to the case |
| the CPU or CPU fan has failed | replace the CPU or CPU fan                                      |
The CPU fan is making an unusual noise

| Probable Cause         | Possible Solutions  |
| ---------------------- | ------------------- |
| the CPU fan is failing | replace the CPU fan |
The computer reboots without warning, locks up, displays error messages or the BSOD

| Probable Cause                                | Possible Solutions                                                                              |
| --------------------------------------------- | ----------------------------------------------------------------------------------------------- |
| the front-side bus is set too high            | reset to the factory default settings for the motherboard, or lower the front-side bus settings |
| the CPU multiplier or voltage is set too high | lower the multiplier or voltage settings                                                        |
| RAM is failing                                | test each RAM module to determine if they are operating correctly                               |
After upgrading from a single core CPU to a dual core CPU, the computer runs more slowly and only show on CPU graph in the Task Manager

| Probable Cause                                 | Possible Solutions                                        |
| ---------------------------------------------- | --------------------------------------------------------- |
| the BIOS does not recognized the dual core CPU | update the BIOS firmware to the support the dual core CPU |
A CPU will not install onto the motherboard

| Probable Cause                | Possible Solutions                                                    |
| ----------------------------- | --------------------------------------------------------------------- |
| the CPU is the incorrect tpye | replace the CPU with the CPU that matches the motherboard socket type |
The computer does not recognize the RAM that was added

| Probable Cause                          | Possible Solutions                |
| --------------------------------------- | --------------------------------- |
| the RAM is faulty                       | replace the RAM                   |
| the incorrect type of RAM was installed | install the correct type of RAM   |
| the new RAM is loose in the memory slot | secure the RAM in the memory slot |
After Upgrading Windows, the computer runs very slowly

| Probable Cause                             | Possible Solutions                           |
| ------------------------------------------ | -------------------------------------------- |
| the computer does not have enough RAM      | install additional RAM, or revert the update |
| the video card does not have enough memory | install a video card that has more memory    |
the computer exhibits slow performance

| Probable Cause                        | Possible Solutions                        |
| ------------------------------------- | ----------------------------------------- |
| the computer does not have enough RAM | install additional RAM                    |
| the computer is overheating           | clean the fans or install additional fans |

## [[Peripherals]]

### Displays
Display has power but no image on the screen

| Probable Cause                                                     | Possible Solutions                                                               |
| ------------------------------------------------------------------ | -------------------------------------------------------------------------------- |
| video cable is loose or damaged                                    | reconnect or replace the video cable                                             |
| the computer is not sending a video signal to the external display | use the Fn key along with the multipurpose key to toggle to the external display |
The display is flickering

| Probable Cause                                      | Possible Solutions                                    |
| --------------------------------------------------- | ----------------------------------------------------- |
| images on the screen are not refreshing fast enough | adjust the screen refresh rate                        |
| the display inverter is damaged or malfunctioning   | disassemble the display unit and replace the inverter |
The image on the display looks dim

| Probable Cause                             | Possible Solutions                                                                                                  |
| ------------------------------------------ | ------------------------------------------------------------------------------------------------------------------- |
| the LCD backlight is not properly adjusted | check the repair manual for the instructions about calibrating the LCD backlight. adjust the LCD backlight properly |
Pixels on the screen are dead, or not generating color

| Probable Cause                       | Possible Solutions      |
| ------------------------------------ | ----------------------- |
| power to the pixels has been cut off | contact the maufacturer |
The image on the screen appears to flash lines or patterns of different color and size (artifacts), the images on a display screen are distorted, or the color patterns on a screen are incorrect

| Probable Cause                        | Possible Solutions                                            |
| ------------------------------------- | ------------------------------------------------------------- |
| the display is not properly connected | disassemble the display to check the connections              |
| the GPU is overheating                | disassemble and clean the computer, check for dust and debris |
| the GPU is faulty or malfunctioning   | replace the GPU                                               |
| display setting have been changed     | restore display settings to the original factory settings     |
The display has a 'ghost' image

| Probable Cause                      | Possible Solutions                                                                                                                      |
| ----------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------- |
| the display is experiencing burn-in | power off the display and unplug it from the power source for a few hours, replace the battery, or use the degauss feature if it exists |
The images on the display have distorted geometry, or the monitor had oversized images and icons.

| Probable Cause                     | Possible Solutions                                 |
| ---------------------------------- | -------------------------------------------------- |
| the driver has become corrupted    | update or reinstall the driver in safe mode        |
| the display settings are incorrect | use the display's settings to correct the geometry |
The projector overheats and shuts down

| Probable Cause                   | Possible Solutions                                |
| -------------------------------- | ------------------------------------------------- |
| the fan has failed               | replace the fan                                   |
| the vents are clogged            | clean the vent and remove debris                  |
| the projector is in an enclosure | remove the enclosure or ensure proper ventilation |
In a muti-monitor setup, the displays are not aligned or are incorrectly oriented

| Probable Cause                                     | Possible Solutions                                                                           |
| -------------------------------------------------- | -------------------------------------------------------------------------------------------- |
| the settings for the multi-monitor are not correct | use the display control panel to identify each display and set the alignment and orientation |
| the driver had become corrupted                    | update or reinstall the driver in safe mode                                                  |
The display is in VGA mode

| Probable Cause                  | Possible Solutions                          |
| ------------------------------- | ------------------------------------------- |
| the computer is in safe mode    | reboot the computer                         |
| the driver had become corrupted | update or reinstall the driver in safe mode |


## [[Power Supply]]
The computer will not turn on

| Probable Cause                                                           | Possible Solutions                                                                |
| ------------------------------------------------------------------------ | --------------------------------------------------------------------------------- |
| the computer is not plugged in to the AC outlet or it is faulty          | plug the computer into a good AC outlet                                           |
| the power cord is faulty                                                 | use a good power cord                                                             |
| the power supply switch is not turned on                                 | turn on the power supply                                                          |
| the power supply switch is set to the incorrect voltage                  | set the power supply to the correct voltage                                       |
| the power button is not connected correctly to the front panel connector | correctly orient the power button to the front case panel connector and reconnect |
| the power supply has failed                                              | install a good power supply                                                       |
The computer reboots, turns off unexpectedly; or there is smoke or the smell of burning electronics

| Probable Cause                       | Possible Solutions       |
| ------------------------------------ | ------------------------ |
| the power supply is starting to fail | replace the power supply |

# Reference Tools
Good customer service includes providing the customer with a detailed description of the problem and the solution. It is important that a technician document all services and repairs and that this documentation is available to all other technicians. The documentation can then be used as reference material for similar problems.

## Personal
Personal reference tools include troubleshooting guides, manufacturer manuals, quick reference guides, and repair journals. In addition to an invoice, a technician keeps a journal of upgrades and repairs:
- **Notes** - Make notes as you go through the troubleshooting and repair process. Refer to these notes to avoid repeating steps and to determine what needs to be done next.
- **Journal** - Include descriptions of the problem, possible solutions that have been tried to correct the problem, and the steps taken to repair the problem. Note any configuration changes made to the equipment and any replacement parts used in the repair. Your journal, along with your notes, can be valuable when you encounter similar situations in the future.
- **History of repairs** - Make a detailed list of problems and repairs, including the date, replacement parts, and customer information. The history allows a technician to determine what work has been performed on a specific computer in the past.

## Online
The internet is an excellent source of information about specific hardware problems and possible solutions:
- Internet search engines
- News groups
- Manufacturer FAQs
- Online computer manuals
- Online forums and chat
- Technical websites

# Maintenance
Preventive maintenance is something that is often overlooked, but good IT professionals understand the importance of regular and systematic inspection, cleaning, and replacement of worn parts, materials, and systems. Effective preventive maintenance reduces part, material, and system faults, and keeps hardware and software in good working condition.

Preventive maintenance doesn't just apply to hardware. Performing basic tasks like checking what programs run on start-up, scanning for malware, and removing unused programs helps a computer function more efficiently, and can keep it from slowing down. Good IT professionals also understand the importance of troubleshooting which requires an organized and logical approach to problems with computers and other components.

These guidelines are a starting point to help you develop your preventive maintenance and troubleshooting skills. You will also learn the importance of maintaining an optimal operating environment for computer systems that are clean, free of potential contaminants, and within the temperature and humidity range specified by the manufacturer.

## Benefits
Preventive maintenance plans are developed based on at least two factors:
- **Computer location or environment** - Dusty environments, such as construction sites, requires more attention than an office environment.
- **Computer use** - High-traffic networks, such as a school network, might require additional scanning and removal of malicious software and unwanted files.

Regular preventive maintenance:
- Reduces potential hardware and software problems, computer downtime, repair costs, and the number of equipment failures.
- Improves data protection, equipment life and stability, and saves money.

## Dust
The following are considerations to keep dust from damaging computer components:

- Clean/replace building air filters regularly to reduce the amount of dust in the air.
- Use a cloth or a duster to clean the outside of the computer case. If using a cleaning product, put a small amount onto a cleaning cloth and then wipe the outside of the case.
- Dust on the outside of a computer can travel through cooling fans to the inside.
- Accumulated dust prevents the flow of air and reduces the cooling of components.
- Hot computer components are more likely to break down.
- Remove dust from the inside of a computer using a combination of compressed air, a low-air-flow ESD vacuum cleaner, and a small lint-free cloth.
- Keep the can of compressed air upright to prevent the fluid from leaking onto computer components.
- Keep the compressed air can a safe distance from sensitive devices and components.
- Use the lint-free cloth to remove any dust left behind on the component.

**CAUTION**: When you clean a fan with compressed air, hold the fan blades in place. This prevents overspinning the rotor or moving the fan in the wrong direction.

## Internal Components
This is a basic checklist of components to inspect for dust and damage:
- **CPU heat sink and fan assembly** – The fan should spin freely, the fan power cable should be secure, and the fan should turn when the power is on.
- **RAM modules** – The modules must be seated securely in the RAM slots. Ensure that the retaining clips are not loose.
- **Storage devices** - All cables should be firmly connected. Check for loose, missing, or incorrectly set jumpers. A drive should not produce rattling, knocking, or grinding sounds.
- **Screws** - A loose screw in the case can cause a short circuit.
- **Adapter cards** – Ensure that they are seated properly and secured with the retaining screws in their expansion slots. Loose cards can cause short circuits. Missing expansion slot covers can let dust, dirt, or living pests inside the computer.
- **Cables** - Examine all cable connections. Ensure that pins are not broken and bent and that cables are not crimped, pinched, or severely bent. Retaining screws should be finger-tight.
- **Power devices** - Inspect power strips, surge suppressors (surge protectors), and UPS devices. Make sure that the devices work properly and that there is clear ventilation.
- **Keyboard and mouse** - Use compressed air to clean the keyboard, mouse, and mouse sensor.

## Environmental Concerns
An optimal operating environment for a computer is clean, free of potential contaminants, and within the temperature and humidity range specified by the manufacturer.

These guidelines help ensure optimal computer operating performance:
- Do not obstruct vents or airflow to the internal components.
- Keep the room temperature between 45 to 90 degrees Fahrenheit (7.2 to 32.2 degrees Celsius).
- Keep the humidity level between 10 and 80 percent.
- Temperature and humidity recommendations vary by computer manufacturer. Research the recommended values for computers used in extreme conditions.

## [[Software]]
Verify that installed software is current.
- Follow the policies of the organization when installing security updates, operating system, and program updates.

Create a software maintenance schedule to:
- Review and install the appropriate security, software, and driver updates.
- Update the virus definition files and scan for viruses and spyware.
- Remove unwanted or unused programs.
- Scan hard drives for errors and defragment hard drives.