---
tags: 
parent docs:
  - "[[Navigation]]"
sibling docs: 
child docs:
---
# Malware
There are many types of threats created to disrupt computers and networks. The greatest and most common threat for computers and the data contained on them is malware.

Malware is software developed by cybercriminals to perform malicious acts. In fact, the word malware is an abbreviation of **mal**icious soft**ware**.

Malware is typically installed on a computer without user knowledge. Once a host is infected, the malware could:
- Change the computer configuration.
- Delete files or corrupt hard drives.
- Collect information stored on the computer without the user’s consent.
- Open extra windows on the computer or redirect the browser.

How does malware get on your computer? Cybercriminals use a variety of methods to infect hosts including one or more of the following:
- User visiting infected website
- User has outdated antivirus software
- Web Browser not patched for new vulnerability
- Downloading a "free" program
- Opening unsolicited email
- Exchanging files on file sharing sites
- Computer infected by another infected host
- Insert a USB stick that you found in a public area
- Opening attachments sent in instant messenger, social media, etc.

Depending on their goals, cybercriminals will use different types of malware. The choice of malware depends on the target and what they are after.

Non-compliant and legacy systems are especially vulnerable to software exploitations. A non-compliant system is one which has not been updated with operating system or application patches or missing antivirus and firewall security software. Legacy systems are those which the vendor no longer provides support or fixes for vulnerabilities.

## Adware
- Adware is usually distributed by downloading online software.
- Adware can display unsolicited advertising using pop-up web browser windows, new toolbars, or unexpectedly redirect a webpage to a different website.
- Pop-up windows may be difficult to control as new windows can pop-up faster than the user can close them.

## Ransomware
- Ransomware typically denies a user access to their files by encrypting the files and then displaying a message demanding a ransom for the decryption key.
- Users without up-to-date backups must pay the ransom to decrypt their files. Users without up-to-date backups must pay the ransom to decrypt their files.
- Payment is usually made using wire transfer or crypto currencies (e.g., Bitcoin).

## Rootkit
- Rootkits are used by cybercriminals to gain administrator-account level access to a computer.
- They are very difficult to detect because they can alter firewall, antivirus protection, system files, and even OS commands to conceal their presence.
- They can provide a backdoor to cybercriminals giving them access to the PC, and allowing them to upload files, and install new software to be used in a DDoS attack.
- Special rootkit removal tools must be used to remove them, or a complete system re-install may be required.

## Spyware
- Similar to adware but used to gather information about the user and send to cybercriminals without the user’s consent.
- Spyware can be a low threat, gathering browsing data, or it can be a high threat capturing personal and financial information.

## Scareware
- A scam software that uses social engineering to shock, cause anxiety, or cause, the perception of a threat. it is generally directed at an unsuspecting user

## Phishing
- malware that attempts to convince people to divulge sensitive information under the guise of a trusted source

## Worm
- A worm is a self-replicating program that propagates automatically without user actions by exploiting vulnerabilities in legitimate software.
- It uses the network to search for other victims with the same vulnerability.
- The intent of a worm is usually to slow or disrupt network operations.

## Viruses
The first and most common type of computer malware is a **virus**. Viruses require human action to propagate and infect other computers. For example, a virus can infect a computer when a victim opens an email attachment, opens a file on a USB drive, or downloads a file.

The virus hides by attaching itself to computer code, software, or documents on the computer. When opened, the virus executes and infects the computer.

**Viruses can:**
- Alter, corrupt, delete files, or erase entire computer drives.
- Cause computer booting issues, corrupt applications.
- Capture and send sensitive information to attackers.
- Access and use email accounts to spread.
- Lay dormant until summoned by the attacker.

### Types

| Type        | Description                                                         |
| ----------- | ------------------------------------------------------------------- |
| Boot sector | virus attacks the boot sector, file partition table, or file system |
| Firmware    | attacks the device firmware                                         |
| Macro       | uses the MS Office macro feature maliciously                        |
| Program     | inserts itself in another executable program                        |
| Script      | attacks the OS interpreter which is used to execute scripts         |

## Trojan Horses
A program that looks useful but also carries malicious code. Trojan horses are often provided with free online programs such as computer games. Unsuspecting users download and install the program, and install the Trojan horse with it.

### Types

| Types                      | Description                                                                                                                          |
| -------------------------- | ------------------------------------------------------------------------------------------------------------------------------------ |
| Remote-access              | enables unauthorized remote access                                                                                                   |
| Data-sending               | provides the attacker with sensitive data, such as passwords                                                                         |
| Destructive                | corrupts or deletes files                                                                                                            |
| Proxy                      | will use the victim's computer as the source device to launch attacks and perform other illegal or harmful activities                |
| FTP                        | enables unauthorized file transfer services on end devices                                                                           |
| Security software disabler | stops antivirus programs or firewalls from functioning                                                                               |
| [[Denial of Service\|DoS]] | slows or halts network activity                                                                                                      |
| Keylogger                  | actively attempts to steal confidential information, such as credit card numbers, by recording key strokes entered into the web-form |

## Fixes
To fix some issues caused by viruses, it may be necessary to boot the computer using the Windows product disk and then use the Windows Recovery Console, which replaces the recovery console from Windows 2000, to run commands from a “clean” command environment. The Recovery Console is able to perform functions such as repairing the boot file and writing a new master boot record or volume boot record.

## Anti-Malware Programs
Malware is designed to invade privacy, steal information, damage the operating system, or allow hackers to take control of a computer. It is important that you protect computers and mobile devices using reputable antivirus software.

This is the seven-step best practice procedure for malware-removal:
1. Identify and research malware symptoms
2. Quarantine the infected systems
3. Disable System Restore (in Windows)
4. Remediate infected systems
5. Schedule scans and run updates
6. Enable System Restore and create restore points (in Windows)
7. Educate the end user

Today, antivirus programs are commonly referred to as anti-malware programs because many of them can also detect and block Trojans, rootkits, ransomware, spyware, keyloggers, and adware programs, as shown in the figure.

![[568fb4f89dcbe676f0b42949b6004c9d885764d1.jpg]]

Anti-malware programs are the best line of defense against malware because they continuously look for known patterns against a database of known malware signatures. They can also use heuristic malware identification techniques which can detect specific behavior associated with some types of malware.

Anti-malware programs are started when a computer boots checking the system resources, drives, and memory for malware. It then runs continuously in the background scanning for malware signatures. When a virus is detected, the anti-malware software displays a warning similar as shown in the figure. It may automatically quarantine or delete the malware depending on software settings.

Anti-malware programs are available for Windows, Linux, and macOS by many reputable security organizations such as McAfee, Symantec (Norton), Kaspersky, Trend Micro, Bitdefender and more.

**Note**: Using two or more anti-malware solutions simultaneously can negatively impact computer performance.

he most common method of malware delivery is through email. Email filters are a line of defense against email threats, such as spam, viruses, and other malware, by filtering email messages before they reach the user’s inbox. File attachments can also be scanned before they are opened.

Email filtering is available on most email applications or it can be installed at the organization’s email gateway. In addition to detecting and filtering out spam messages, email filters also allow the user to create blacklists of known spammer domains and to whitelist known trusted or safe domains.

Malware can also be delivered through applications that are installed. Installation of software from untrusted sources can lead to the spread of malware such as Trojans. To mitigate this risk vendors implement various methods to restrict the ability of users to install untrusted software. Windows uses the system of Administrator and Standard user accounts along with User Account Control.(UAC) and system policies to help prevent installation of untrusted software.

When faced with a warning window that is suspect, never click inside the warning window. Close the tab or the browser to see if the warning window goes away. If the tab or browser does not close, press ALT+F4 to close the window or use the task manager to end the program. If the warning window does not go away, scan the computer using a known, good antivirus or adware protection program to ensure that the computer is not infected.

Click [here](https://zvelo.com/introduction-to-rogue-anti-virus/) to read a blog about rogue antivirus malware.

In Linux, users are prompted if they attempt to install untrusted software. The software is signed with a cryptographic private key and requires the public key for the repository to install the software.

Mobile OS vendors use the walled garden model to prevent installation of untrusted software. Under this model, apps are distributed from an approved store, such as the App Store for Apple or the Windows Store for Microsoft.

### Signature File Updates
ew malware is always being developed therefore anti-malware software must be updated regularly. This process is often enabled by default. However, a technician should know how to manually update anti-malware software signatures.

To update the signature file manually follow the suggested steps in the list.

**Step 1**. Create a **Windows Restore Point** in case the file you load is corrupt. Setting a restore point allows you to go back to the way things were.
**Step 2**. Open the anti-malware program. If the program is set to execute or obtain updates automatically, you may need to turn the automatic feature off to perform these steps manually.
**Step 3**. Click the **update** button.
**Step 4**. After the program is updated, use it to scan the computer and then check the report for viruses or other problems.
**Step 5**. Set the anti-malware program to automatically update its signature file and scan your computer on a regular basis.

Always download the signature files from the manufacturer’s website to make sure the update is authentic and not corrupted by malware. This can put great demand on the manufacturer’s website, especially when new malware is released. To avoid creating too much traffic at a single website, some manufacturers distribute their signature files for download to multiple download sites. These download sites are called mirrors.

**CAUTION**: When downloading signature files from a mirror, ensure that the mirror site is a legitimate site. Always link to the mirror site from the manufacturer’s website.

# Curing Infected Systems
When a malware protection program detects that a computer is infected, it removes or quarantines the threat. However, the computer is most likely still at risk.

When malware is discovered on a home computer, you should update your anti-malware software and perform full scans of all your media. Many anti-malware programs can be set to run on system start before loading Windows. This allows the program to access all areas of the disk without being affected by the operating system or any malware.

When malware is discovered on a business computer, you should remove the computer from the network to prevent other computers from becoming infected. Unplug all network cables from the computer and disable all wireless connections. Next, follow the incident response policy that is in place. This may include notifying IT personnel, saving log files to removable media, or turning off the computer.

Removing malware may require that the computer be rebooted into Safe Mode. This prevents most drivers from loading. Some malware may require that a special tool from the anti-malware vendor be used. Be sure that you download these tools from a legitimate site.

For really stubborn malware, it may be necessary to contact a specialist to ensure that the computer has been completely cleaned. Otherwise, the computer may need to be reformatted, the operating system reinstalled, and recover your data from the most recent backups.

The OS system restore service may include infected files in a restore point. Therefore, once a computer has been cleaned of any malware, the system restore files should be deleted, as shown in the figure.

![[c429025fa2d7d1a8ceeb0b1e501eeb9f541e862b.jpg]]

After remediation, you may need to fix some issues caused by viruses, it may be necessary to boot the computer using the Windows product disk and then use the Windows Recovery Console, which replaces the recovery console from Windows 2000, to run commands from a “clean” command environment. The Recovery Console can perform functions such as repairing the boot file and writing a new master boot record or volume boot record.

-  perform an information query of a target
	Attacker is looking for network information about a target using various tools including Google search, organizations website, whois, and more.
-  initiate a ping sweep of the target network
	Attacker initiates a ping sweep of the discovered target’s public network address to determine which IP addresses are active.
-  initiate a port scan of active IP addresses
	Attacker determines which services are available on the active ports using tools such as Nmap, SuperScan, and more.
-  run vulnerability scanners
	Attacker runs vulnerability scanner to discover the type and version of the application and operating system running on the target host using tools such as Nipper, Secuna PSI, and more.
-  run exploitation tools
	Attacker attempts to discover vulnerable services that can be exploited using tools such as Metasploit, Core Impact, and more.

## Types of TCP/IP attacks

- [[Denial of Service|DoS]]
	- In a DoS attack, the attacker completely overwhelms a target device with false requests to create a denial of service for legitimate users.
	- An attacker could also cut or unplug a network cable to a critical network device to cause a network outage.
	- DoS attacks may be caused for malicious reasons or used in conjunction with another attack.
- [[Distributed DoS|DDoS]]
	- A DDoS attack is an amplified DoS attack using many infected hosts called zombies to overwhelm a target.
	- Attackers control zombies using a handler computer and botnet is an army of compromised hosts.
	- Botnets remain dormant until instructed by the handler.
	- Botnets can be also be used for SPAM and phishing attacks.
- [[DNS]] Poisoning
	- In a DNS poisoning attack, the attacker has successfully infected a host to accept false DNS records pointing to malicious servers.
	- Subsequently, traffic is diverted to these malicious servers to capture confidential information.
	- An attacker can then retrieve the data from that location.
- [[Man-in-the-Middle|MitM]] or On-Path-Attack
	- In a TCP/IP MitM attack, an attacker intercepts communications between two hosts.
	- If successful, the attacker could capture packets and view their content, manipulate packets, and more.
	- MitM attacks can be created using an ARP poisoning spoofing attack.
- Replay
	- A replay attack is a type of spoofing attack, where the attacker has:
		- Captured an authenticated packet.
		- Altered the packet’s contents.
		- Sent it to its original destination.
	- The goal is to have the target host accept the altered packet as authentic.
- Spoofing
	- In a TCP/IP spoofing attack, the attacker forges IP addresses.
- For example, an attacker has spoofed the IP address of a trusted host to gain access to resources.
- SYN Flood
	- A SYN flood attack is a type of DoS attack that exploits the TCP three-way handshake. 
	- The attacker sends continuous false SYN requests to the target. 
	- The target is eventually overwhelmed and unable to establish valid SYN requests creating a DoS attack.

## Zero-Day
The following two terms are commonly used to describe when a threat is detected:
- **Zero-day** – Sometimes also referred to as zero-day attacks, zero-day threat, or zero-day exploit. This is the day that an unknown vulnerability has been discovered by the vendor. The term is a reference to the amount of time that a vendor has had to address the vulnerability.
- **Zero-hour** – This is the moment when the exploit is discovered.

A network remains vulnerable between the zero-day and the time it takes a vendor to develop a solution.

In the example in the list, a software vendor has learned of a new vulnerability. The software can be exploited until a patch that addresses the vulnerability is made available. Notice that in the example, it took several days and a few software patch updates to mitigate the threat.

Vendor software  vulnerability discovered by vendor.
- Zero-day: 09/14/20xx
- Zero-hour: 8:37 am.
Day 16  
First patch released.

Day 17  
Second patch released.

Day 18  
Third patch released.

Security advisory issued by vendor

Patched Vendor software

How can networks be protected against all of the threats and zero-day attacks?

# Network Attacks
Many network attacks are fast moving, therefore, network security professionals must adopt a more sophisticated view of the network architecture. There is no one solution to protect against all TCP/IP or zero-day attacks.

One solution is to use a defense-in-depth approach also known as a layered approach to security. This requires a combination of networking devices and services working together in tandem.

Consider the network in the figure. There are several security devices and services implemented to protect its users and assets against TCP/IP threats. These include the following:
- **VPN** - A router is used to provide secure VPN services with corporate sites and remote access support for remote users using secure encrypted tunnels.
- **ASA Firewall** - This dedicated device provides stateful firewall services. It ensures that internal traffic can go out and come back, but external traffic cannot initiate connections to inside hosts.
- **IPS** - An Intrusion Prevention System (IPS) monitors incoming and outgoing traffic looking for malware, network attack signatures, and more. If it recognizes a threat, it can immediately stop it
- **AAA Server** - This server contains a secure database of who is authorized to access and manage network devices. Network devices authenticate administrative users using this database.
- **ESA/WSA** - The email security appliance (ESA) filters spam and suspicious emails. The web security appliance (WSA) filters known and suspicious Internet malware sites.

All network devices including the router and switches are also hardened as indicated by the combination locks on their respective icons. This indicates that they have been secured to prevent attackers from tampering with the devices.

# Social Engineering Attacks
To secure networks and hosts, organizations often deploy the network security solutions and latest anti-malware solutions for their hosts. However, they still have not addressed the weakest link … the users.

Social engineering is likely the single most serious threat to a well-configured and well-secured network.

Cybercriminals use social engineering techniques to deceive and trick unsuspecting targets to reveal confidential information or violate security gain information. Social engineering is an access attack that attempts to manipulate individuals into performing actions or divulging confidential information.

Social engineers prey on people’s weaknesses and often rely on human nature and people’s willingness to be helpful.

**Note**: Social engineering is often used in conjunction with other network attacks.

## Techniques
There are many different ways to use social engineering techniques. Some social engineering techniques are used in-person while others may use the telephone or Internet.

For example, a hacker could call an authorized employee with an urgent problem that requires immediate network access. The hacker could appeal to the employee’s vanity, invoke authority using name-dropping techniques, or appeal to the employee’s greed.

### Baiting
An attacker leaves a malware infected flash drive in a public location (e.g., a corporate washroom). A victim finds the drive and unsuspectingly inserts it into their laptop, unintentionally installing the malware.

### Impersonation
This type of attack is where an attacker pretends to be someone they are not (e.g., new employee, fellow employee, a vendor or partner company employee, etc.) to gain the trust of a victim.
### Tailgating
This is an in-person type of attack where an attacker quickly follows an authorized person into a secure location to gain access to a secure area.
### Shoulder Surfing
This is an in-person type of attack where an attacker inconspicuously looks over someone’s shoulder to steal their passwords or other information.
### Dumpster Diving
This is an in-person type of attack where an attacker rummages through trash bins to discover confidential documents.
### Pretexting
An attacker pretends to need personal or financial data in order to confirm the identity of the recipient.
### Phishing
An attacker sends fraudulent email disguised as being from a legitimate, trusted source to trick the recipient into installing malware on their device, or to share personal or financial information (e.g., bank account number and access code).
### Spear Phishing
An attacker creates a targeted phishing attack tailored specifically for an individual or organization.
### Spam
Also known as junk mail, this is unsolicited email which often contains harmful links, malware, or deceptive content
### Something for Something
Sometimes called “Quid pro quo”, this is when an attacker requests personal information from a party in exchange for something such as a free gift.

## Protection
Enterprises must train and educate their users about the risks of social engineering, and develop strategies to validate identities over the phone, via email, or in person.

Below is a list of recommended practices that should be followed by all users:
- Always destroy confidential information according to the organization policy.
- Never give your username / password credentials to anyone.
- Never leave your username / password credentials where they can easily be found.
- Never open emails from untrusted sources.
- Never release work related information on social media sites.
- Never re-use work related passwords.
- Always lock or sign out of your computer when unattended.
- Always report suspicious individuals.

# Security Policy
etwork, the data, and the computers in an organization. The security policy is a constantly evolving document based on changes in technology, business, and employee requirements.

The security policy is usually created by a committee with members consisting of management and IT staff. Together they create and manage a document that should answer the questions listed in the figure.

A security policy typically addresses the items described in the figure. This list is not exhaustive and would include other items related specifically to the operation of an organization.

It is up to the IT staff to implement security policy specifications in the network. For example, to implement recommendations on a Windows host, IT staff could use the Local Security Policy feature.

## Policy Identifies
- Which assets require protection
- What are the possible threats?
- What to do in the event of a security breach?
- What training will be in place to educate the end users?

## Security Policy
- Password Policies
- Acceptable Use Policies
- Remote Access Policies
- Network Maintenance Policies
- Incident Handling Policies

## Categories
Identification and Authentication
Specifies authorized persons that can have access to network resources and outlines verification procedures.

Password Policies
Ensures passwords meet minimum requirements and are changed regularly.

[[Acceptable Use Policies|AUP]]
Identifies network resources and usages that are acceptable to the organization. It may also identify ramifications if this policy is violated.

Remote Access Policies
Identifies how remote users can access a network and what is accessible via remote connectivity.

Network Maintenance Policies
Specifies network device operating systems and end-user application update procedures.

Incident Handling Policies
Describes how security incidents are handled.

# Securing Devices and Data
The goal of the security policy is to ensure a safe network environment and to protect assets. As shown in the figure, an organization’s assets include their data, employees, and physical devices such as computers and network equipment.

The security policy should identify hardware and equipment that can be used to prevent theft, vandalism, and data loss.

## Physical Security
Physical security is as important as data security. For example, if a computer is taken from an organization, the data is also stolen or worse, lost.

Physical security involves securing:
- Access to an organization’s premise
- Access to restricted areas
- The computing and network infrastructure

The level of physical security implemented depends on the organization as some have higher physical security requirements than others.

For example, consider how data centers, airports, or even military installations are secured. These organizations use perimeter security including fences, gates, and checkpoints posted with security guards.

Entrance to a building premise and restricted areas is secured using one or more locking mechanism. Building doors typically use self-closing and self-locking mechanisms. The type of locking mechanism required varies based on the level of security required.

A visitor accessing a secure building may have to pass through a security checkpoint manned by security guards. They may scan you and your belongings, and have you sign in an entry control roster when you enter the building and sign out when you leave.

Higher security organizations have all employees wear identification badges with photographs. These badges could be smart cards containing the user information and security clearance to access restricted areas. For additional security requirements, RFID badges can also be used with proximity badge readers to monitor the location of an individual.

## Types of Secure Locks
**Conventional lock**
Unlocked by entering the required key into the door handle mechanism.

**Deadbolt lock**
Unlocked by entering the required key into a lock separate from the door handle mechanism.

**Electronic lock**
Unlocked by entering a secret combination code or PIN into the keypad.

**Token-based lock**
Unlocked by swiping a secure card or by using a near proximity reader to detect a smart card or wireless key fob.

**Biometric lock**
Unlocked using a biometric scanner such as a thumbprint reader. Other biometric scanners include voice print or a retina scanner.

**Multifactor lock**
A lock that uses a combination of mechanisms. For example, a user must enter a PIN code and then scan their thumb.

## Mantraps
In high-security environments, mantraps are often used to limit access to restricted areas and to prevent tailgating. A mantrap is a small room with two doors, one of which must be closed before the other can be opened.

Typically, a person enters the mantrap by unlocking one door. Once inside the mantrap, the first door closes and then the user must unlock the second door to enter the restricted area.

In the figure, the person must enter the building using a smart card to open the locked door to the mantrap. Once the person successfully enters the mantrap, the first door locks and they must now unlock the next door using the biometric reader. The person must have their thumbprint scanned to unlock the locked door to the secure internal area.

**Insecure (public) Area**
Entrance -> Locked door -> Smart card scanner

**Mantrap**
Biometric scanner -> Locked door

**Secure Internal Area**
Exit

## Securing Computers and Network Hardware
Organizations must protect their computing and network infrastructure. This includes cabling, telecommunication equipment, and network devices.

There are several methods of physically protecting computer and networking equipment as listed in the figure.

Network equipment should only be installed in secured areas. As well, all cabling should be enclosed within conduits or routed inside walls to prevent unauthorized access or tampering. Conduit is a casing that protects the infrastructure media from damage and unauthorized access.

Access to physical switch ports and switch hardware should be restricted to authorized personnel by using a secure server room and locking hardware cabinets. To prevent the attachment of rogue or unauthorized client devices, switch ports should be disabled through the switch management software.

Factors that determine the most effective security equipment to use to secure equipment and data include:
- How the equipment is used
- Where the computer equipment is located
- What type of user access to data is required

For instance, a computer in a busy public place, such as a library, requires additional protection from theft and vandalism. In a busy call center, a server may need to be secured in a locked equipment room. Server locks can provide physical chassis security by preventing access to power switches, removable drives, and USB ports. Where it is necessary to use a laptop computer in a public place, a security dongle and key fob ensure that the computer locks if the user and laptop are separated. Another tool for physical security is the USB lock which is locked into place in a USB port and requires a key to be removed.

Security policies can be applied to mobile devices in a corporate network through enterprise mobility management (EMM) software. Mobile device management (MDM) software can manage corporate-owned devices and Bring Your Own Device (BYOD). The software logs use of devices on the network and determines if it should be allowed to connect, known as onboarding, based on administrative policies. MDM software sets policies for connectivity, authentication, and the use of features such as the microphone and camera on the device. Mobile application management (MAM) sets policies for the applications that are allowed to be used on a device. It keeps corporate data secure and away from applications that are not allowed to process it.

**Securing the Computing and Network Infrastructure**
- Use webcams with motion-detection and surveillance software.
- Install physical alarms triggered by motion-detection sensors.
- Label and install RFID sensors on equipment.
- Use locking cabinets or security cages around equipment.
- Fit equipment with security screws.
- Keep telecommunication rooms locked.
- Use cable locks with equipment.

# Protecting Data
Data is likely to be an organization’s most valuable assets. Organizational data can include research and development data, sales data, financial data, human resource and legal data, employee data, contractor data, and customer data.

Data can be lost or damaged in circumstances such as theft, equipment failure, or a disaster. Data loss or data exfiltration are terms used to describe when data is intentionally or unintentionally lost, stolen, or leaked to the outside world.

Data loss can negatively affect an organization in multiple ways. Losing data regardless of circumstances can be detrimental or even catastrophic to an organization. Data loss can result in:

- Brand damage / Loss of reputation
- Loss of competitive advantage
- Loss of customers
- Loss of revenue
- Legal action resulting in fines and civil penalties
- Significant cost and effort to notify affected parties
- Significant cost and effort to recover from the breach

Data can be protected from data loss using methods, such as data backups, file and folder permissions, and file and folder encryption.

Data loss prevention (DLP) is preventing data loss or leakage. DLP software uses a dictionary database or algorithm to identify confidential data and block the transfer of that data to removable media or email if it does not conform to predefined policy.

## Backups
Backing up data is one of the most effective ways of protecting against data loss. A data backup stores a copy of the informaiton in a computer to removable backup media that can be kept in a safe place. If the computer hardware fails, the data can be restored from the backup to functional hardware.

Data backup should be performed on a regular basis as identified in the security policy. Data backups are usually stored offsite to protect the backup media if anything happens the main facility. Windows hosts have a backup and restore utility. This is useful for users to backup their data to another drive or to a cloud-based storage provider. The macOS includes the **Time Machine** utility to perform backup and restore functions. 

|            | Data Backup Considerations                                                                                                                                                                                  |
| ---------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Frequency  | perform backups on a regular basis as identified in the security policy, full backup can be time-consuming, therefore perform monthly or weekly full backups with frequent partial backups of changed files |
| Security   | backups should be protected using strong passwords, the password is required to restore data                                                                                                                |
| Validation | always backups to ensure the integrity of the data and validate the file restoration procedures                                                                                                             |
| Storage    | backups should be transported to an approved offsite storage location on a daily, weekly, or monthly rotation, as required by the security policy                                                           |


### Magnetic Media
Protecting data also includes removing files from storage devices when they are no longer needed. Simply deleting files or reformatting the drive may not be enough to ensure your privacy.

For example, deleting files from a magnetic hard disk drive does not remove them completely. The operating system removes the file reference in the file allocation table but the actual data remains on the drive. This deleted data is only overwritten when the hard drive stores new data in the same location.

Software tools can be used to recover folders, files, and even entire partitions. This could be a blessing if the erasure was accidental. But it could also be disastrous if the data is recovered by a malicious user.

For this reason, storage media should be fully erased using one or more of the methods listed in the figure.

Data wiping software
- Also known as secure erase.
- Software tools specifically designed to overwrite existing data multiple times, rendering the data unreadable.
Degaussing wand
- Consists of a wand with very powerful magnets which is held over exposed hard drive platters to disrupt or eliminate the magnetic field on a hard drive.
- Hard drive platters must be exposed to the wand for approximately 2 minutes.
Electromagnetic degaussing device
- Useful for erasing multiple drives.
- Consists of a magnet with an electrical current applied to it to create a very strong magnetic field that disrupts or eliminates the magnetic field on a hard drive.
- Very expensive but fast (erases a drive in seconds).

**Note**: Data wiping and degaussing techniques are irreversible, and the data can never be recovered.

#### Destruction
Companies with sensitive data should always establish clear policies for storage media disposal. There are two choices available when a storage media is no longer needed.
- Recycled : Hard drives that have been wiped can be reused in other computers. The drive can be reformatted , and a new operating system can be installed. Two types of formatting can be performed as described in the table.
- Destroyed : Destroying the hard drive fully ensures that data cannot be recovered from a hard drive. Specifically designed devices such as hard drive crushers, shredders, and incinerators, can be used to dispose of large volumes of drives. Otherwise physically damaging that drive with a hammer is effective

| Low-level                                                                                                                                                                                       | Standard                                                                                                                                                                  |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| The surface is the dist is marked with sector markers identifying tracks where the data will be physically stored on the disk, most often performed at the factory after the drive is assembled | also called high-level formatting, a process creates a boot sector and a file system, a standard format can only be performed after a low-level format has been completed |

A company may choose an outside contractor to destroy their storage media. These contractors are typically bonded and follow strict governmental regulations. They may also offer a certificate of destruction to provide evidence that the media has been completely destroyed.
### SSDs
SSDs are comprised of flash memory instead of magnetic platters. Common techniques used for erasing data such as degaussing are not effective with flash memory. Perform a secure erase to fully ensure that data cannot be recovered from an SSD and hybrid SSD.

Other storage media and documents (e.g., optical disks, eMMC, USB sticks) must also be destroyed. Use a shredding machine or incinerator that is designed to destroy documents and each type of media. For sensitive documents that must be kept, such as those with classified information or passwords, always keep them locked in a secure location.

When thinking about what devices must be wiped or destroyed, remember that devices besides computers and mobile devices store data. Printers and multifunction devices may also contain a hard drive that caches printed or scanned documents. This caching feature can be turned off in some instances, or the device needs to be wiped on a regular basis to ensure data privacy. It is a good security practice to set up user authentication on the device, if possible, to prevent an unauthorized person from changing any settings that concern privacy.

## File and Folder Permissions
Permissions are rules you configure to limit folder or file access for an individual or for a group of users. The figure lists the permissions that are available for files and folders.

To configure file- or folder-level permissions in all versions of Windows, right-click the file or folder and select **Properties > Security > Edit…**

Users should be limited to only the resources they need in a computer or on a network. For example, they should not be able to access all files on a server if they only need access to a single folder. It may be easier to provide users access to the entire drive, but it is more secure to limit access to only the folder that is needed to perform their job. This is known as the principle of least privilege. Limiting access to resources also prevents malicious programs from accessing those resources if the user’s computer becomes infected.

Folder redirection allows a user with administrative privileges to redirect the path of a local folder to a folder on a network share. This makes the folder’s data available to the user when they log into any computer on the network where the network share is located. With user data redirected from local to network storage, administrators can back up the user data when the network data folders are backed up.

File and network share permissions can be granted to individuals or through membership within a group. These share permissions are much different than file and folder level NTFS permissions. If an individual or a group is denied permissions to a network share, this denial overrides any other permissions given. For example, if you deny someone permission to a network share, the user cannot access that share, even if the user is the administrator or part of the administrator group. The local security policy must outline which resources and the type of access allowed for each user and group.

When the permissions of a folder are changed, you are given the option to apply the same permissions to all sub-folders. This is known as permission propagation. Permission propagation is an easy way to apply permissions to many files and folders quickly. After parent folder permissions have been set, folders and files that are created inside the parent folder inherit the permissions of the parent folder.

Also, the location of the data and the action performed on the data determine how the permissions are propagated:
- **Data is moved to the same volume** – It will keep the original permissions
- **Data is copied to the same volume** – It will inherit new permissions
- **Data is moved to a different volume** – It will inherit new permissions
- **Data is copied to a different volume** – It will inherit new permissions

Full Control
- See the content of a file or folder
- Change and delete existing files and folders
- Create new files and folders
- Run programs in a folder

Modify
- Change and delete existing files and folders
- Users cannot create new files or folders

Read and Execute
- See the contents of existing files or folders
- Run programs in a folder

Read
- See the contents of a folder and open files and folders

Write
- Create new files and folders
- Make changes to existing files and folders

### File and Folder Encryption
Encryption is often used to protect data. Encryption is where data is transformed using a complicated algorithm to make it unreadable. A special key must be used to return the unreadable information back into readable data. Software programs are used to encrypt files, folders, and even entire drives.

Encrypting File System (EFS) is a Windows feature that can encrypt data. EFS is directly linked to a specific user account. Only the user that encrypted the data will be able to access it after it has been encrypted using EFS. To encrypt data using EFS in all Windows versions, follow these steps:

1. Select one or more files or folders.
2. Right-click the selected data **> Properties**.
3. Click **Advanced…**
4. Select the **Encrypt contents to secure data** check box and click **OK**. Windows will display an informational message stating that it is applying attributes.
5. Files and folders that have been encrypted with EFS are displayed in green, as shown in the figure. This option can be enabled in the View tab of the File Explorer Options.

# Bitlocker
You can also choose to encrypt an entire hard drive using a feature called BitLocker. To use BitLocker, at least two volumes must be present on a hard disk. A system volume is left unencrypted and must be at least 100 MB. This volume holds the files required by Windows to boot.

**Note**: BitLocker is built into all Windows 11 editions and Windows 10 Pro, Enterprise, and Education editions. Windows 11 Home edition uses a limited version of BitLocker.

Before using BitLocker, the Trusted Platform Module (TPM) must be enabled in BIOS. The TPM is a specialized chip installed on the motherboard. The TPM stores information specific to the host computer, such as encryption keys, digital certificates, and passwords. Applications, like BitLocker, that use encryption can make use of the TPM chip. For example, the steps to enable TPM on a Lenovo laptop are listed below.
1. Start the computer, and enter the BIOS configuration.
2. Look for the TPM option within the BIOS configuration screens. Consult the manual for your motherboard to locate the correct screen.
3. Choose **Enable** or **Activate** the security chip.
4. Save the changes to the BIOS configuration.
5. Reboot the computer.

To turn on BitLocker full disk encryption in all versions of Windows, follow the steps listed below:
1. Click **Control Panel** > **BitLocker Drive Encryption**.
2. On the **BitLocker Drive Encryption** page, click **Turn On BitLocker** on the operating system volume. (If TPM is not initialized, follow the instructions provided by the wizard to initialize the TPM).
3. The **save the recovery password** page enables you to save the password to a USB drive, to a network drive or other location, or print the password. After saving the recovery password, click **Next**.
4. On the **Encrypt the selected disk volume** page, select the **Run BitLocker System Check** check box and click **Continue**.
5. Click **Restart Now**.

When the steps are completed, the **Encryption in Progress** status bar is displayed. After the computer reboots, you can verify BitLocker is active as shown in the figure below.

![[add94d315a4b13568de1ab240ca58132e24aa469.png]]

You can click **TPM Administration** to view the TPM details, as shown below.

BitLocker encryption can also be used with removable drives by using **BitLocker To Go**. **BitLocker To Go** does not use a TPM chip, but still provides encryption for the data and requires a password.

# Workstations
Computers and workstations should always be secured from theft in any environment to protect data and computing resources. This is a standard practice in a company as computers are typically secured in locked rooms.

To prevent unauthorized users from stealing or accessing local computers, and network resources, lock you workstation, laptop, or server when staff are not present. This includes physical security as well as password security. 

If you must leave a computer in an open public area, cable locks should be used to deter theft. Data displayed on your computer screen should also be protected. This is especially true when using a laptop in a public location such as an airport coffee house, or customer site. Use a privacy screen to protect the information displays on your laptop screen from prying eyes. A privacy screen is a clear plastic panel attached to the computer screen that only permits the user in the front of the screen to see the information displayed.

Access to your computer must also be protected. There are three levels of password protection that can be used on a computer as described in the table.

Three types of Password Protection

|         |                                                                      |
| ------- | -------------------------------------------------------------------- |
| BIOS    | Prevent the operating system form booting and changing BIOS settings |
| Login   | Prevents unauthorized access to the local computer.                  |
| Network | Prevents access to network resources by unauthorized personnel       |

#### Securing BIOS
A Windows, Linux, or Mac login password can be bypassed. Your computer may be booted from a CD or flash drive with a different operating system. After it is booted, the malicious user could access or erase your files.

Setting a BIOS or UEFI password can prevent someone from booting the computer. It also prevents someone from altering the configured settings. In the figure, for example, a user would have to enter the configured BIOS password to access the BIOS configuration.

All users, regardless of user account, share BIOS passwords. UEFI passwords can be set on a per-user basis. However, an authentication server is required.

**Caution**: A BIOS or UEFI password is relatively difficult to reset, therefore be sure you remember it.

### Securing Windows Login
The most common type of password protection is the computer login. This is typically where you enter a password and sometimes a username as shown in figure.

Depending on your computer system, Windows 10 may also support other sign-in options. Specifically, Windows 10 supports the following sign-in options:
- **Windows Hello** – Feature that enables Window you to use facial recognition or use your fingerprint to access Windows.
- **PIN** – Enter a pre-configured PIN number to access Windows.
- **Picture password** - You choose a picture and gestures to use with the picture to create a unique password.
- **Dynamic lock** – Feature makes Windows lock when a pre-paired device such as a cell phone goes out of range of the PC.

#### Windows Sign-in Options
**PIN**
The figure displays a sample PIN authentication screen instead of the password login option. In this example, a user could change the sign-in option to either password, fingerprint, or facial recognition.

**Laptop Fingerprint Reader**
If a user chose to authenticate using their fingerprint, they would then scan their finger.

To change sign-in options on a Windows 10 computer, use **Start > Settings > Accounts > Sign-in options** as shown below. In this window, you could also change your password, set a PIN number, enable picture password, and dynamic lock.

#### Local Password Management
Password management for stand-alone Windows computers can be set locally using the Windows **User Accounts** tool. To create, remove, or modify a password in Windows, use **Control Panel > User Accounts** as shown.

![[ac1e2a5af84a84f8926f8fa76f0e449d23f36c1d.jpg]]

It is also important to make sure that computers are secure when users are away. A security policy should contain a rule about requiring a computer to lock when the screensaver starts. This will ensure that after a short time away from the computer, the screen saver will start and then the computer cannot be used until the user logs in.

In all versions of Windows except 10, use **Control Panel > Personalization > Screen Saver** as shown below. In Windows 10, use **Settings > Personalization > Lock screen > Screen saver settings.** Choose a screen saver and a wait time, and then select the **On resume, display logon screen** option.

#### Usernames and Passwords
The system administrators usually defines a naming convention for usernames when creating network logins. A common example of a username is the first letter of the person's first name and then the entire last name. Keep the naming convention simple so that people do not have a hard time remembering it. Usernames, like passwords, are an important piece for information and should not be revealed.

Password guidelines are an important component of a security policy. Any user that must log on to a computer or connect to a network resource should be required to have a password. Password help prevent theft of data and malicious acts. Passwords also help to confirm that the logging of events is valid by ensuring that the user is the correct person.

Strong Password Guidelines

|                |                                                                                                              |
| -------------- | ------------------------------------------------------------------------------------------------------------ |
| Minimum length | make password of at least eight characters, but no more than 64                                              |
| Complexity     | no common, easily guessed passwords, such as password, abc123, all printing character and spaces are allowed |
| Variety        | use a different password for each site or computer that you use, never use the same password twice           |
| Expiration     | no periodical or arbitrary password expiration                                                               |

### Local Security Policy
In most networks that use Windows computers, Active Directory is configured with Domains on a Windows Server. Windows computers are members of a domain. The administrator configures a Domain Security Policy that applies to all computers that join. Account policies are automatically set when a user logs in to Windows.

For stand-alone computers that are not part of an Active Directory domain, the Windows Local Security Policy can be used to enforce security settings.

To access Local Security Policy, use **Search > secpol.msc** and then click **secpol**.

### Account Policies Security Settings
The security policy will identify the password policies required. The Windows local security policy could be used to set implement the password policies. When assigning passwords, the level of password control should match the level of protection required.

**Enforce password history**
Use **Account Policies > Password Policy** to enforce password requirements as shown. Review the currently configured Password Policy settings.
- the user may reuse a password after a configuration number of passwords have been saved
Maximum password age
- the user must change the password after a configurable number of days
Minimum password age
- the user must wait a configurable amount of time before changing a password again, this helps re-enforce password history by preventing a user form entering a different password a specified number of times in order to use a previous password again
Minimum password length
- the password must be at least a specified number of characters
Complexity requirements
- the password must not contain specific items such as the user's account name or parts of the user's full name that exceed two consecutive characters
- the password must contain specific items such as three of the following four categories: uppercase letters, lowercase letters, numbers, and symbols
Store passwords using reversible encryption
- essentially the same as storing plaintext versions of the passwords, for this reason, this policy should never be enabled unless application requirements outweigh the need to protect password information

**Note**: Use strong passwords whenever possible.

### Local Policies Security Settings
The Local Policy in the Local Security Policy is used to configure audit policies, user rights policies, and security policies.

It is useful to log successful and unsuccessful login attempts. Use the **Local Policies > Audit Policy** to enable auditing. In this example, the **Audit account login events** auditing is being enabled for all logon events.

The **User Rights Assignment** and **Security Options** provide a wide variety of security options beyond the scope of this course. However, some settings will be explored in the lab.

### Exporting the Local Security Policy
An administrator may need to implement an extensive local policy for user rights and security options. This policy most likely would need to be replicated on each system. To help simplify this process, the **Local Security Policy** can be exported and copied to other Windows hosts.

The steps to replicate a Local Security Policy on other computers are:
1. Use the **Action > Export List…** feature to export the policy of a secure host.
2. Save the policy with a name, such as **workstation.inf**. to external media.
3. Then import the Local Security Policy file to other stand-alone computers.

## Managing User Groups

### Accounts
Employees in an organization often require different levels of access to data. For example, a manager and an accountant might be the only employees in an organization with access to the payroll files.

Employees can be grouped by job requirements and given access to files according to group permissions. This process helps manage employee access to the network. Temporary accounts can be set up for employees who need short-term access. Close management of network access can help to limit areas of vulnerability that might allow a virus or malicious software to enter the network.

There are several tasks associated with managing users and groups.

Terminating Employee Access
- When an employee leaves an organization, immediately disable the account or change the login credentials to the account.
Guest Access
- Temporary employees and guests may need limited access to the network using a guest account.
- Special guest account with additional privileges can be created and disabled as required.
Track Login Times
- Employees may only be allowed to login during specific hours, such as 7 a.m. to 6 p.m.
- Logins would be blocked during other times of the day. This is known as logon time restrictions. The authenticating server periodically checks if a user has privileges to continue using the network. If the user does not, then an automatic logout procedure is activated.
Log Failed Login Attempts
- Configure a threshold for the number of times a user is allowed to attempt a login.
- By default, in Windows the number of failed login attempts is set to zero therefore a user will never be locked out until this setting is changed.
Idle Timeout and Screen Lock
- Configure an idle timer that will automatically log the user out and lock the screen after a specified period of time.
- The user must log back in to unlock the screen.
Change default admin user credentials
- Rename default accounts, such as the default admin user account, so that attackers cannot use the known account names to access the computer.
- Windows disables this account by default and replaces it with a named account which is created during the operating system setup process.
- Some devices ship with a default password such as “admin” or “password”. These should be changed during initial device setup.

### Tools and Tasks
A regular maintenance task for administrators is to create and remove users from the network, change account passwords, or change user permissions. You must have admin privileges to manage users.

To accomplish these tasks, you can use either [[User Account Control|UAC]] or Local Users and Group Manager. 

#### Local Users and Group Manager 
- **Control Panel > Administrative Tools > Computer Management > Local Users and Groups**
- can be used to create and manage users and groups that are stored locally on a computer

The Local Users and Groups tool can limit the ability of users and groups to perform certain actions by assigning rights and permissions. 
- **Rights** - A right authorizes a user to perform certain actions on a computer. Examples include backing up files and folders or shutting down a computer.
- **Permissions** - A permission is a rule that is associated with an object (usually a file, folder, or printer). It regulates which users can have access to the object and in what manner.

To configure all of the users and groups on a computer using the **Local Users and Groups Manager** tools type **lusrmgr.msc** in the Search box, or Run Line utility.

The **Local Users and Groups > Users** window displays current user accounts on the computer. It includes the built-in administrator and built-in guest accounts.

The built-in accounts have the following rights and permissions:

**Administrator**
- Account has full control of the computer and is a member of the Administrators group.
- Account can assign user rights and access control permissions.
- Account can be renamed or disabled but never be deleted or removed from the Administrators group.
- Account is disabled by default.

**Guest**
- Account is used by users who do not have an assigned account on the computer.
- It is a member of the default Guests group, which allows a user to log on to a computer.
- By default, the account does not require a password.
- Account is disabled by default.

Double-clicking a user or right-clicking and choosing **Properties** opens the user properties window, as shown in the next figure. This window allows you to change the user options defined when the user was created. Additionally, it permits you to lock an account. The window also lets you assign a user to a group using the **Member of** tab, or controlling which folders the user has access to using the **Profile** tab.

To add a user, click the **Action** menu and select **New User**. This opens the New User window. From here you can assign a username, full name, description, and account options.

**Note**: Some versions of Windows also include the built-in Power User account which possesses most of the power of an administrator but for security reasons, lacks some of the privileges of an administrator.

## Managing Groups
Users can be assigned to groups for easier management. Tasks used to manage local groups include the following:
- Create a Local Group
- Add members to the group
- Identify members in the local group
- Delete group
- Create a local user account
- Managing Local Groups

The **Local Users and Groups Manager** tool is used to manage local groups on a Windows computer. Use **Control Panel > Administrative Tools > Computer Management > Local Users and Groups** to open the Local Users and Groups Manager. From the **Local Users and Groups** window, double-click **Groups** to list all of the local groups on the computer. There are many built-in groups available.

The three most commonly used groups are described the following:

**Administrator**
- Group members have full control of the computer and can assign user rights and access control permissions.
- Administrator account is a default member of the group.
- Use caution when you add users to this group.

**Guest**
- Members of this group have a temporary profile created at logon, and when the member logs off, the profile is deleted.
- The Guest account (which is disabled by default) is also a default member of this group.

**Users**
- Members of this group can perform common tasks, such as running applications, using local and network printers, and locking the computer.
- Members cannot share directories or create local printers.

It is important to note that running your computer as a member of the Administrators group makes the system vulnerable to Trojan horses and other security risks. It is recommended that you add your domain user account only to the Users group (and not to the Administrators group) to perform routine tasks, including running programs and visiting internet sites. When it becomes necessary to perform administrative tasks on the local computer, use **Run as Administrator** to start a program using administrative credentials. 

Double click a group to view its properties. To create a new group, click the **Action > New Group** to open the **New Group** window. From here you can create new groups and assign users to them.

## Active Directory Users and Computers
While local accounts are stored in the in the Local Security Accounts database of a local machine, domains accounts are stored in the Active Directory on a Windows Server Domain Controller (DC) and are accessible from any computer joined to the domain. Only domain administrators can create domain accounts on a Domain Controller.

The Active Directory is a database of all computers, users, and services in an Active Directory domain. The Active Directory Users and Computers console on Windows server is used to manage Active Directory users, groups, and Organizational Units (OUs). Organizational units provide a way to subdivide a domain into smaller administrative units. The Active Directory Users and Computers, an administrator can create more OUs in which to place accounts or add accounts to existing OUs.

To create a new user account, right-click the container or OU which will contain the account and choose **New User**. Enter the user’s information such as name, last name and logon name, then click **Next**, and then set an initial password for the user. By default, the option to force the user to reset their password on first sign in is selected. If a user should lock themselves out of their account with too many password attempts, the administrator can open Active Directory Users and Computers, right-click on the user object, select **Properties**, and check **Unlock account**.

To delete a user account simply right-click the user object and select **Delete**. Note however that once an account is deleted it may not be retrievable. Another option is to disable an account rather than to delete it. Once an account is disabled, the user is denied access to the network until the administrator re-enables the account.

To create a new group account in active directory is similar to creating a new user. Open Active directory Users and Computers select the container that will house the group, click **Action**, click **New** and then click **Group**. Fill in the group details and click **OK**.

# Windows Firewall
A firewall protects computers and networks by preventing undesirable traffic from entering internal networks. For instance, the top topologies in the figure illustrates how the firewall enables traffic from an internal network host to exit the network and return to the inside network. The topology illustrates how traffic initiated by the outside network (i.e., the internet) is denied access to the internal network.

Firewall permits traffic from users in the inside network to exit and return.
	Firewall <> Inside <> Internet

Firewall denies outside traffic access to the inside network.
	Inside <> Firewall <\X> Internet

## DMZ Server
A firewall could allow outside users controlled access to specific services. For instance, servers accessible to outside users are usually located on a special network referred to as the demilitarized zone (DMZ). The DMZ zone enables a network administrator to apply specific policies for hosts connected to that network.

For example, select play in the figure below to see how the DMZ server provides web, FTP, and email services (i.e, SMTP and IMAP) to external users. Notice how the firewall only permits access to those server services and denies all other outside requests.

A firewall protects computers and networks by preventing undesirable traffic from entering internal networks. For instance, the top topologies in the figure illustrates how the firewall enables traffic from an internal network host to exit the network and return to the inside network. The list illustrates how traffic initiated by the outside network (i.e., the internet) is denied access to the internal network.
Allows
- traffic from any external address to the web server
- traffic to the FTP, SMTP, and internal IMAP server 
Disallows
- all inbound traffic with network addresses matching internal-registered IP addresses
- all inbound traffic to server from external addresses
- all inbound ICMP echo request traffic
- all inbound MS Active Directory queries
- all inbound traffic to MS SQL server queries
- all MS Domain Local Broadcasts

Firewall services can be provided as follows:
- **Host-based firewall** – Using software such as Windows Defender Firewall.
- **Small office home office (SOHO)** – Network-based solution using a home or small office wireless router. These devices not only provide routing and WI-FI services, but they also provide NAT, DHCP, and firewall services. Many routers also provide settings listed in Figure 4.
- **Small to medium-sized organization** - Network-based solution using a dedicated device such as a Cisco Adaptive Security Appliance (ASA) or enabled on a Cisco Integrated Services Router (ISR). These devices use access control lists (ACLs) and advanced features to filter packets based on their header information including source and destination IP address, protocol, source and destination TCP/UDP ports, and more.

Although the focus of this section is on the host-based firewall solution using Windows Firewall, the table below shows the firewall settings provided by many SOHO routers.

A DMZ is a subnetwork that provides services to untrusted networks. Email, web, and FTP servers are often placed into the DMZ so that the traffic using the server does not come inside the local network. This protects the internal network from attacks by this traffic, but does not protect the servers in the DMZ in any way. It is common for a firewall or proxy to manage traffic to and from the DMZ.

The topology below shows a router diagram that features a DMZ.

![[0aae787fc6dd439b64339ede581a8fc09896fdd5.png]]

## Typical SOHO Router Firewall Settings
Port Address Translation
- a version of [[Network Address Protocol|NAT]] that overloads the router assigned public IP address
- enable internal host with a private IP address to use the public address of the router to traverse the Internet
- return traffic to the router is retranslated to the internal private IP address
Pert Forwarding
- also called destination [[Network Address Protocol|NAT]] 
- adds an Internet accesible host on a small router
- Internet traffic is forwarded to a specific host/port number
Disable Ports
- selectively enable or disable access to specific TCP/UDP ports
MAC Address Filtering
- add known MAC addresses to a whitelist
- permit only whitelist MAC addresses to connect
Whitelist/Blacklists URLs
- blacklists are used to block malicious/disreputable sites based on domain name and IP address
- whitelist can be used to identify permitted sites

### Software Firewalls
A software firewall is a program that provides firewall services on a computer to allow or deny traffic to the computer. The software firewall applies a set of rules to data transmissions through inspection and filtering of data packets.

Windows Firewall is an example of a software firewall that helps prevent cybercriminals and malware from gaining access to your computer. It is installed by default when the Windows OS is installed.

**Note**: In Windows 10 the Windows Firewall was renamed to Windows Defender Firewall. In this section, Windows Firewall includes Windows Defender Firewall.

Windows Firewall settings are configured using the Windows Firewall window. To change Windows Firewall settings, you must have administrator privileges to open the Windows Firewall window.

To open the Windows Firewall window, use **Control Panel > Windows Firewall**. To disable or re-enable Windows Firewall or change notifications for a network, click on either **Change notifications settings** or **Turn Windows Defender Firewall on or off** to open the Customize Settings window shown below.

Software firewall features are applied to a network connection. Software firewalls have a standard set of inbound and outbound rules that are enabled depending on the location of the connected network.

In the figure below, firewall rules are enabled for a private network, a guest or public network, or a corporate domain network. The window displays the settings for the private network as it is the currently connected network. To display the settings for the domain or guest networks, click on the drop-down arrow beside the **Not connected** label.

From this Windows Firewall window, you can enable or disable Windows Firewall, change notification settings, allow apps through the firewall, configure advanced settings, or restore firewall defaults.

If you wish to use a different software firewall, you will need to disable Windows Firewall. To disable the Windows Firewall, follow the steps listed:

1. **Control Panel** > **Windows Defender Firewall** > **Turn Windows Defender Firewall on or off**
2. Click **Turn off Windows Defender Firewall (not recommended)** for the desired network

**Note**: Windows Firewall is enabled by default. Do not disable Windows Firewall on a Windows host unless another firewall software is enabled.

### Configure Exceptions
You can allow or deny access to specific programs or ports from the Windows Firewall window. To configure exceptions and allow or block applications or ports, click on **Allow an app or feature through the Windows Firewall** to open the Allowed apps window.

From this window, you can add, change, or remove the allowed programs and ports on the different networks. The steps required to add programs through the Windows Firewall is listed below:
1. **Control Panel** > **Windows Defender Firewall** > **Allow a app or feature through the Windows Firewall**
2. Click **Change settings** if not greyed out.
3. Check the boxes for listed applications or use **Allow another app** if a program is not listed
4. Click OK

### Advanced Security
Another Windows tool that is available to provide even greater access control with Windows Firewall policies is the Windows Firewall with Advanced Security. It is called Windows Defender Firewall with Advanced Security in Windows 10.

To open it, from the Windows Firewall window, click on **Advanced settings** to open it as shown in the figure.

**Note**: Alternatively, you can enter **wf.msc** in the search box and press enter.

Windows Defender Firewall with Advanced Security provides these features:
- **Inbound and Outbound Rules** – You can configure inbound rules that are applied to incoming internet traffic and outbound rules which are applied to traffic leaving your computer going to the network. These rules can specify ports, protocols, programs, services, users, or computers.
- **Connection Security Rules** - Connection security rules secure traffic between two computers. It requires that both computers have the same rules defined and enabled.
- **Monitoring** – You can display the firewall inbound or outbound active rules or any active connection security rules.

# Web Security
Web browsers are not only used for web browsing, they are also now used to run other applications including Microsoft 365, Google docs, interface for remote access SSL users, and more. To help support these additional features, browsers use plug-ins to support other content. However, some of these plug-ins may also introduce security problems.

Browsers are targets and should be secured, and some examples of web browser security features are:
- InPrivate Browsing
- Pop-up Blocker
- SmartScreen Filter
- ActiveX Filtering

When browsing, many websites and services require the use of authentication for access. Recently, it has become common to require multifactor authentication over a traditional username and password. Multifactor authentication involves using a combination of different technologies, such as a password, a smart card, and biometrics, to authentication a user. For example, two-factor authentication combines something a user has, such as a smart card with something they know like a password or pin. Three-factor authentication combines all three, something a user knows, something they have, and some type of biometric component like a thumb or eye retina scan.

Recently, authenticator applications have become a popular method for multifactor authentication. For example, the service may require both a password and a registered phone or email address. To access the service an authenticator application sends a code called a one-time password (OTP) to the registered phone or email address. The user must supply their account username and password plus the OTP code to authenticate.

Once authenticated, the system may grant a software token to the application or device which was used to authenticate with. The software token allows the user to perform actions on the system without the need to repeatedly authenticate. If the token system is not secure, a third party may be able to capture it and act as the user. This is known as a replay attack. The token should be designed to prevent replay attacks, being time limited or being used only once.

## Extensions and Plugins
There are many types of browser add-ons that add functionality and features. These are the main types of add-ons:
- **Plug-ins** - These are generally related to multimedia objects on a web page such as a video format or content created using Flash. They are generally limited in interaction compared to an extension because it is only supposed to interact with just the media object. Plug-ins have had many vulnerabilities and are now rarely used. Now, HTML version 5 is the preferred method to serve this type of role.
- **Extensions** - An extension changes the features of a browser through the use of an application programming interface (API). For example, an extension may block pop-ups, prevent sites from using your computing power to crypto-mine, or simply change a menu option within the browser. By default, you must provide the extension permission to perform the intended action. The scripts that the extension executes could be malicious and compromise your browser's security. It is extremely important to only install legitimate extensions from trusted sources.
- **Themes** - The theme is the look and feel of the browser. They change the colors and provide custom images for the browser. There is the risk that the theme could inject malicious code into the browser using an image created by a threat actor.
- **Apps** - Apps allow you to edit documents within the browser. This could be a cloud application that performs the same function as a spreadsheet, word processor, or image editor.
- **Default search provider** - There are many sites that provide search capabilities. You can specify which site you would like to use by default. Specifying a malicious site could redirect you to a site that is spoofed, compromising your browser's security.

Always make sure that you are installing browsers, extensions, and plug-ins from a trusted source. Always keep your software up to date. There have been instances of malicious software served from trusted stores, so keeping them up to date reduces the risk that they are malicious.

**Browser Settings**
Browsers maintain settings and allow you to change them. These can be accessed through the browser's menu, or through an internal URL like about:preferences or chrome://settings. There are also internal URLs like about:config or chrome://flags for adjusting advanced settings.

Another feature of the modern browser is the ability for the user to sign in and synchronize browser settings with other devices from the same user. History, passwords, bookmarks, and other data can be saved and synchronized across multiple devices.

**Password Manager**
It can be overwhelming trying to remember the myriad of passwords to all the web sites that require log ins. Especially since most sites are requiring more complicated passwords than ever. Using the same password is a big security risk, so a password manager can be used locally on the device to secure passwords and not have to worry about them being compromised. Once you are signed into the browser, the password manager can populate the password in the credential area. This does not always work, and if not, you should be able to copy the password from the manager and paste it into the credential area.

## Secure Connections and Valid Certificates
In order to provide a secure connection, the internet often uses Transport Layer Security (TLS) and digital certificates. This ensures that the identity of the host running a web site is valid and makes sure that the data is encrypted between the server and your browser. Certificate authorities (CAs) issue certificates to domains that contain a public key so that the CA that issued the certificate can validate it because they signed it. The browser can provide the information associated with the certificate when a site is using HTTPS. 

There have been stolen certificates from CAs because of a weak key being used in the certificate. Only install or update root certificates that you an verify are safe and legitimate. A root certificate must be trusted, so if a fake certificate is installed a threat actor could compromise the encryption between your browser and the web server. Microsoft Edge uses the Windows certificate store, but other browsers have a separate store for them. To use internal sites and a third-party browser, ensure that the internal CA root certificate is added direct to the browser. The certificate manager can be found in the browser settings, as shown in the following figure.

## Browser Privacy Settings
Many companies are trying to create profiles of the habits of people online. This includes their search and browse habits. Privacy controls can watch the use of tracking tools like cookies that are used to track online activity. A cookie is simply a text file that stores data from a browser session. This data could simply be where you were on a web page, or who you are. Third-party cookies are often used to provide information to a different website without your knowledge.

Privacy settings can be used to enable cookies, block them, or just not allow cookies from third parties. The following features can be used to block other methods of tracking:
- **Ad blocker** - This is an extension that can be used to block the display of unwanted ads. These extensions use rules and algorithms to block items that are not part of the site's main content. It is important to understand that there are some sites that detect ad blockers and prevent the user from viewing the website while an ad blocker is in use.
- **Pop-up blocker** - This is  code that prevents a website from creating any windows that are not requested by the user.

The browser also stores data about the user and their activity. This can be configured in two ways:
- **Private browser** - This method disables the caching of information by the browser such as history, form information, or cookies so that when the browser is closed, all of the data is erased. This does not make the user anonymous because the web sites can still see IP addresses and other information not blocked by the private session.
- **Clearing cache** - This will delete all browsing history. Any files that have been cached as a method to speed up the user experience will also be deleted. To stay safe, it is a good practice to delete your cache after every session. This can be done manually or automatically after each session.

### In-Private Browsing
Web browsers retain information about the web pages that you visit, the searches that you perform, and other identifiable information including usernames, passwords, and more. Although convenient on a personal computer, this is a concern when using a public computer such as a computer in a library, hotel business center, or an internet café. The information retained by web browsers can be recovered and exploited to steal your identity, your money, or change your passwords on important accounts.

To improve security when using a public computer, always:
- Clear your browsing history
- Use the InPrivate mode

**Clear your browsing history**

All web browser have a way to clear their browsing history, cookies, files, and more. The steps to clear the browsing history in Microsoft Edge are listed below.

**Clearing Browsing History in MS Edge**
1. Click on More actions three dotted icon (…) on the top right hand side of MS Edge.
2. Select **Settings**, and then click Privacy, search, and services.
3. Under the **Clear browsing data** subheading, click **Choose what to clear** to open the **Clear browsing data** menu.
4. Choose a **Time range**, select what to clear, and then click **Clear now**.

Use the InPrivate mode
All web browsers provide the ability to browse the web anonymously without retaining information. Using an InPrivate browser temporarily stores files and cookies and deletes them when the InPrivate session is ended.

**Opening an InPrivate Window in MS Edge**
Steps to open an InPrivate window in Microsoft Edge is listed below.
1. Click on More actions three dotted icon (…) on the top right hand side of MS Edge.
2. Select **New InPrivate** windows to open a new InPrivate browser window.

### Pop-up Blocker
A pop-up is a web browser window that opens on top of another web browser window. Some pop-ups are initiated while browsing, such as a link on a page that opens a pop-up to deliver additional information or a close-up of a picture. Other pop-ups are initiated by a website or advertiser and are often unwanted or annoying, especially when multiple pop-ups are opened at the same time on a web page.

Most web browsers offer the ability to block pop-up windows. This enables a user to limit or block most of the pop-ups that occur while browsing the web.

**Steps to Block Pop-ups in MS Edge**
1. Click the **Settings and more** three dotted icon (…) on the top right hand side of MS Edge.
2. Select **Settings**.
3. Select **Cookies and site permissions**, and then click **Pop-ups and redirects**.
4. Ensure the **Block** slider is **On**.

### Smart-Screen Filter
Web browsers may also offer additional web filtering capabilities. For instance, Microsoft Edge provides the SmartScreen Filter feature. This feature detects phishing websites, analyzes websites for suspicious items, and checks downloads against a list that contains sites and files that are known to be malicious.

The steps to enable SmartScreen filter in Microsoft Edge are as follows:
1. Click on More actions three dotted icon (…) on the top right hand side of MS Edge.
2. Select **Settings**.
3. Select **Privacy, search, and services**.
4. Scroll to the Security section and ensure **Microsoft Defender SmartScreen** is **On**.

### ActiveX Filtering
Some web browsers may require you to install an ActiveX control. The problem is that ActiveX controls can be used for malicious reasons.

ActiveX filtering allows for web browsing without running ActiveX controls. After an ActiveX control has been installed for a website, the control runs on other websites as well. This may degrade performance or introduce security risks. When ActiveX filtering is enabled, you can choose which websites are allowed to run ActiveX controls. Sites that are not approved cannot run these controls, and the browser does not show notifications for you to install or enable them.

To enable ActiveX filtering in Internet Explorer 11, use **Tools > ActiveX Filtering**. The example in the figure displays that ActiveX filtering is enabled. Clicking the **ActiveX Filtering** again would disable ActiveX.

To view a website that contains ActiveX content when ActiveX filtering is enabled, click the blue **ActiveX Filtering** icon in the address bar, and click **Turn off ActiveX Filtering**.

After viewing the content, you can turn ActiveX filtering for the website back on by following the same steps.

**Note**: Microsoft Edge does not support ActiveX filtering.

## Security Maintenance

### Restrictive Settings
Devices often come with security features that are not enabled or the security features left to their defaults. For example, many home users leave the wireless router with default passwords and open wireless authentication because it is "easier".

Permissive settings
Some devices are shipped with permissive settings. This enables access through all ports, exept those explicitly denied. The problem is that the default permissive setting leave many devices exposed to attackers. 
- easier to implement
- less secure and easier to hack

Restrictive settings
Many devices now ship with restrictive settings. They must be configured to enable access. Any packet not explicitly permitted is denied.
- harder to implement
- more secure and difficult to hack

It is your responsibility to secures devices and configure restrictive settings whenever possible

### Disable Auto-play
Older Windows hosts used AutoRun to simplify the user experience. When new media (e.g., flash drive, CD, or DVD drive) is inserted into the computer, AutoRun would automatically look for a special file called **autorun.inf** and execute it. Malicious users have taken advantage of this feature to quickly infect hosts.

Newer Windows hosts now use a similar feature called AutoPlay. With AutoPlay, you can determine which media will run automatically. AutoPlay provides additional controls and can prompt the user to choose an action based on the content of the new media.

Use the **Control Panel > AutoPlay** window, shown in figure below, to open the AutoPlay window and configure the actions associated with specific media. However, you are still just one click away from unknowingly running malware through the AutoPlay dialog.

Therefore, the most secure solution is to turn off AutoPlay. The steps to disable AutoPlay are listed below:
1. **Control Panel** > **AutoPlay**.
2. Uncheck the Use AutoPlay for all media and devices checkbox as shown.
3. Click **Save**.

# [[Operating System]] Service Packs and Patches
Patches are code updates that manufacturers provide to prevent a newly discovered virus or worm from making a successful attack. From time to time, manufacturers combine patches and upgrades into a comprehensive update application called a service pack.

It is critical to apply security patches and OS updates whenever possible. Many devastating virus attacks could have been much less severe if more users had downloaded and installed the latest service pack.

Windows routinely checks the Windows Update website for high-priority updates that can help protect a computer from the latest security threats. These updates include security updates, critical updates, and service packs. Depending on the setting you choose, Windows automatically downloads and installs any high-priority updates that your computer needs or notifies you as these updates become available.

# Wireless Security
## Hash Encoding
Hash encoding, or hashing, ensures the integrity of the message. This means that the message is not corrupted, nor has it been tampered with during transmission. Hashing uses a mathematical function to create a numeric value, called a message digest that is unique to the data. If even one character is changed, the function output will not be the same. The function can only be used one way. Knowing only the message digest does not allow an attacker to recreate the original message, because a changed message would have a completely different hash output. The most popular hashing algorithm is now Secure Hash Algorithm (SHA) which is replacing the older Message Digest 5 (MD5) algorithm.

## Symmetric Encryption
Symmetric encryption ensures the confidentiality of the message. If an encrypted message is intercepted, it cannot be understood. It can only be decrypted using the password, known as the key, that it was encrypted with. Symmetric encryption requires both sides of an encrypted conversation to use an encryption key to encode and decode the data. The sender and receiver must use identical keys. Advanced Encryption Standard (AES) and the older Triple Data Encryption Algorithm (3DES) are examples of symmetric encryption.

## Asymmetric Encryption
Asymmetric encryption requires a private key and a public key. The public key can be widely distributed, including emailing in plain text or posting on the web. The private key is kept by an individual and must not be disclosed to any other party:
- Public key encryption is used when an organization needs to receive encrypted text from many sources. The public key can be distributed and used to encrypt the messages. The intended recipient is the only party to have the private key, which is used to decrypt the messages.
- In the case of digital signatures, a private key is required for encrypting a message, and a public key is needed to decode the message. This approach allows the receiver to be confident about the source of the message because only a message encrypted using the originator’s private key could be decrypted by the public key. RSA is the most popular example of asymmetric encryption.

Smart cards also use asymmetric encryption. A digital certificate is stored with a private key on a smart card hardware token. To perform authentication, the card provides the certificate  to an authentication server which checks that it is valid and trusted. The server then uses the public key in the certificate to issue an encrypted challenge to the user. The smart card decrypts the challenge with  the private key and sends an appropriate response to the server.

## Wi-Fi Configuration Best Practices
Radio waves used to transmit data in wireless networks make it easy for attackers to monitor and collect data without physically connecting to a network. Attackers gain access to an unprotected wireless network simply by being within range of it. A technician needs to configure access points and wireless NICs with an appropriate level of security.

A robust wireless network with sufficient coverage for users in all locations requires the proper placement of antenna and access points. If placing the access point in proximity of the provider’s cabling does not provide enough coverage, then extenders and repeaters can be used to boost the wireless signals to locations where it is weak. A site survey can also be performed to identify signal dead zones.

Reducing the power output on an Access Point may help to prevent war driving, however it may also result in insufficient wireless coverage for legitimate users.

Increasing the power output of an Access Point can increase coverage, however it can also increase the chance of signal bouncing and interference. There may also be legal restrictions on wireless power levels. Because of these potential issues it is usually best to set power levels to auto negotiate.

When installing wireless services, apply wireless security techniques immediately to prevent unwanted access to the network. Wireless access points should be configured with basic security settings that are compatible with the existing network security. When setting up the access point on a Wi-Fi network, the management software will prompt for a new administrator password. There may also be an option to change the default username of the administrator account, which is slightly more secure that using the default name configured. Also, on smaller networks, you can assign IP addresses statically instead of using DHCP. This prevents any computer from connecting to the access point unless it is configured with the correct IP address.

Additional security, such as parental controls or content filtering are services that may be available in a wireless router. Internet access times can be limited to certain hours or days, specific IP addresses can be blocked, and key words can be blocked. The location and depth of these features varies depending on the manufacturer and model of the router.

One way to provide a level of security on Wi-Fi networks is to change the default Service Set ID (SSID) and to disable broadcast of the SSID. Access point vendors use a default SSIDs for their devices based on the devices brand and model. These should be changed to something users will recognize and will not get confused with other nearby networks. Most access points broadcast the SSID by default. A level of privacy can be gained by disabling the broadcast of the SSID. This will prevent wireless network adapters form finding the network unless they are specifically configured with the name of the network SSID. Disabling the SSID broadcast provides very little security. Someone who knows the SSID of that network can simply enter it manually. A wireless network will also broadcast the SSID during a computer scan. The SSID can be easily intercepted in transit.

## Authentication Methods
There are a variety of authentication methods from unsecured to the most secure, as shown in the figure below. The details of these authentication methods are as follows:
- **Open** - Any wireless device can connect to the wireless network. This should only be used in situations where security is of no concern.
- **Shared Key** - Provides mechanisms to authenticate and encrypt data between a wireless client and AP or wireless router.
- **WEP** - WEP stands for Wired Equivalent Privacy. This was the original 802.11 specification securing WLANs, however the encryption key never changes when exchanging packets, making it easy to crack.
- **WPA** - WPA stands for Wi-Fi Protected Access. This standard uses WEP, but secures the data with the much stronger Temporal Key Integrity Protocol (TKIP) encryption algorithm. TKIP changes the key for each packet, making it much more difficult to crack.
- **WPS** - Many routers offer Wi-Fi Protected Setup (WPS). With WPS, both the router and the wireless device will have a button that, when both are pressed, automatically configures Wi-Fi security between the devices. A software solution using a PIN is also common. It is important to know that WPS is not entirely secure. It is vulnerable to brute-force attack. WPS should be turned off as a security best practice.
- **WPA2/WPA3** - WPA2 is now the industry standard for securing WLANs. WPA2 uses the Advanced Encryption Standard (AES) for encryption. AES is currently considered the strongest encryption protocol. Since 2006, any device that bears the Wi-Fi Certified logo is WPA2 certified. WPA3 has been ratified since 2018 and is mandatory Wi-Fi certified devices. WPA3 includes a variety of security over WPA2. However, the currently large install base of WPA2 devices including Internet of Things (IoT) devices will probably not be updated. In addition, many users do not understand the new protocol or know how to implement it. Therefore, as of 2022, adoption of WPA3 has been very slow. Use a wireless encryption system to encode the information being sent to prevent unwanted capture and use of data. Most wireless access points support several different security modes As discussed in a previous chapter, always implement the strongest security mode (WPA2) possible.

## Firmware Updates
Most wireless routers offer upgradable firmware. Firmware releases may contain fixes for common problems reported by customers as well as security vulnerabilities. You should periodically check the manufacturer’s website for updated firmware. After it is downloaded, you can use the GUI to upload the firmware to the wireless router, as shown in the figure. Users will be disconnected from the WLAN and the Internet until the upgrade finishes. The wireless router may need to reboot several times before normal network operations are restored.

## Firewalls
A hardware firewall is a physical filtering component that inspects data packets from the network before they reach computers and other devices on a network. A hardware firewall is a freestanding unit that does not use the resources of the computers it is protecting, so there is no impact on processing performance. The firewall can be configured to block multiple individual ports, a range of ports, or even traffic specific to an application. Most wireless routers also include an integrated hardware firewall.

A hardware firewall passes two different types of traffic into your network:
- Responses to traffic that originates from inside your network
- Traffic destined for a port that you have intentionally left open
- dedicated hardware component
- initial cost for hardware and software updates can be expensive
- multiple computers can be protected
- no impact on computer performance

Software Firewall
- available as third party, cost varies
- free version included with Windows operating systems
- typically protects only the computer on which it is installed
- uses computer resources, having a potential impact on performance 

Hardware and software firewalls protect data and equipment on a network from unauthorized access. A firewall should be used in addition to security software. The figure below shows the wireless router browser-based interface with SPI Firewall protection enabled.

#### Configuration
Packet Filter
- Packets cannot pass through the firewall, unless they match the established rule set configured in the firewall. Traffic can be filtered based on different attributes, suck as sourch IP address, source port or destination IP address or port. Traffic can also be filtered based on destination services or protocols such as WWW or FTP.
[[Stateful Packet Inspection|SPI]] 
- This is a firewall that keeps track of the state of network connections travelling through the firewall. Packets that are not part of a known connection are dropped. 
Application Layer
- All packets travelling to or from an application are intercepted. All un
Proxy
- This is a firewall installed on a proxy server that inspects all traffic and allows or denies packets based on configured rule. A proxy server is a relay between a client and a destination server on the internet.

## Port Forwarding/Triggering
Hardware firewalls can be used to block ports to prevent unauthorized access in and out of a LAN. However, there are situations when specific ports must be opened so that certain programs and applications can communicate with devices on different networks. Port forwarding is a rule-based method of directing traffic between devices on separate networks.

When traffic reaches the router, the router determines if the traffic should be forwarded to a certain device based on the port number found with the traffic. Port numbers are associated with specific services, such as FTP, HTTP, HTTPS, and POP3. The rules determine which traffic is sent on to the LAN. For example, a router might be configured to forward port 80, which is associated with HTTP. When the router receives a packet with the destination port of 80, the router forwards the traffic to the server inside the network that serves web pages. In the figure, port forwarding is enabled for port 80 and is associated with the web server at IP address 192.168.1.254.

Port triggering allows the router to temporarily forward data through inbound ports to a specific device. You can use port triggering to forward data to a computer only when a designated port range is used to make an outbound request. For example, a video game might use ports 27000 to 27100 for connecting with other players. These are the trigger ports. A chat client might use port 56 for connecting the same players so that they can interact with each other. In this instance, if there is gaming traffic on an outbound port within the triggered port range, inbound chat traffic on port 56 is forwarded to the computer that is being used to play the video game and chat with friends. When the game is over and the triggered ports are no longer in use, port 56 is no longer allowed to send traffic of any type to this computer.

## [[Universal Plug and Play]]
A protocol that enables devices to dynamically forward traffic through network ports without the need for user intervention or configuration. Port forwarding is often used for streaming media, hosting games, or providing services from home and small business computers to the internet.

Although convenient, UPnP is not secure. The UPnP protocol has no method for authenticating devices. Therefore, it considers every device trustworthy. In addition, the UPnP protocol has numerous security vulnerabilities. For example, malware can use the UPnP protocol to redirect traffic to different IP addresses outside your network, potentially sending sensitive information to a hacker.

Many websites host a variety of free browser-based vulnerability profiling tools. Search the internet for “UPnP router test” and scan your router to determine if yours is exposed to UPnP vulnerabilities.

Many home and small office wireless routers have UPnP enabled by default.

# Common Problems
A security alert is displayed.

| Probable Causes                   | Possible Solutions          |
| --------------------------------- | --------------------------- |
| the windows firewall is disabled  | enable the Windows Firewall |
| virus definitions are out-of-date | update virus definitions    |
| malware has been detected         | scan for malware            |
A user is receiving hundreds or thousands of junk emails each day.

| Probable Causes                                                                | Possible Solutions                                           |
| ------------------------------------------------------------------------------ | ------------------------------------------------------------ |
| the network is not providing detection or SPAM protection for the email server | install/update antivirus software or email antispam software |
An unauthorized wireless access point is discovered on the network

| Probable Causes                                  | Possible Solutions                                                                                                                                      |
| ------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------- |
| a user added a wireless access point to increase | disconnect and confiscate the unauthorized device, enforce the security policy by taking actions against the person responsible for the security breach |
An unknown printer repair person is observed looking under keyboard and on desktops

| Probable Causes                                                                            | Possible Solutions                                                                                                                                      |
| ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------- |
| a user added a wireless access point to increase the wireless range of the company network | disconnect and confiscate that unauthorized device, enforce the security policy by taking action against the person responsible for the security breach |
an unknown printer repair person is observed looking under keyboards and on desktops

| Probable Causes                                                                                     | Possible Solutions                                                                        |
| --------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------- |
| visitor are not being monitored properly or user credentials have been stolen to enter the building | contact security or police, educate users to never to hide passwords near their work area |
System files have been renamed, application crash, files are disappearing, or file permissions have changed

| Probable Causes          | Possible Solutions                                                            |
| ------------------------ | ----------------------------------------------------------------------------- |
| the computer has a virus | remove the virus using antivirus software, restore the computer from a backup |
Users with flash drives are infecting computers on the network with viruses

| Probable Causes                                                                            | Possible Solutions                                                       |
| ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------ |
| flash drives are not scanned by the antivirus software when a network computer accesses it | set the antivirus software to scan removable media when data is accessed |
Your email contacts report spam comin from you

| Probable Causes            | Possible Solutions                                                                   |
| -------------------------- | ----------------------------------------------------------------------------------- |
| your email has been hacked change your email password, contact the email service support and reset the account d  |
Your wireless network is compromised even though 128-vitWEP encryption is used

| Probable Causes                                             | Possible Solutions                                                               |
| ----------------------------------------------------------- | -------------------------------------------------------------------------------- |
| WEP can be decrypted using commonly available hacking tools | upgrade WPA encryption, and use MAC address filtering for older wireless clients |
User receives Access Denied errors when attempting to open files

| Probable Causes                              | Possible Solutions                                     |
| -------------------------------------------- | ------------------------------------------------------ |
| malware has changed the permissions of files | quarantine the infected system and investigate closely |
Browser opens page other than what the user is attempting to access.

| Probable Causes | Possible Solutions                                                                                      |
| --------------- | ------------------------------------------------------------------------------------------------------- |
| spyware         | check host file for malicious entries, verify that the DNS servers that the client is using are correct |
Users are being redirected to malicious websites

| Probable Causes                                   | Possible Solutions                                                                                                                                                                                                                                                |
| ------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| compromised domain name resolution - DNS spoofing | flush local DNS cache with ipconfig/ flushdns to clear malicious entries, check the HOSTS file for spoofed entries, check the priority order for name resolution service, validate the DNS resolvers set as primary and secondary in the clients IP configuration |

