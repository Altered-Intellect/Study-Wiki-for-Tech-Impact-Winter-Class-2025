---
tags: 
parent docs:
  - "[[Navigation]]"
sibling docs: 
child docs: 
media:
---
# Nav
< [[Networks|Previous]] < ^ [[Navigation|Home]] ^

---

The terms “virtualization” and “cloud computing” are often used interchangeably although they mean different things.

Virtualization enables a single computer to host multiple independent virtual computers that share the host computer hardware. Virtualization software separates the actual physical hardware from the virtual machine (VM) instances. VMs have their own operating systems and connect to hardware resources through software running on the host computer. An image of a VM can be saved as a file and then be re-started when required.

It is important to remember that all the VMs share the resources of the host computer. Therefore, the limiting factor on the number of VMs that can run at the same time is directly related to the amount of processing power, memory, and storage.

Cloud computing separates the applications from the hardware. It provides organizations with on-demand delivery of computing services over the network. Service providers such as Amazon Web Services (AWS) own and manage the cloud infrastructure that includes the networking devices, servers, and storage devices and is usually housed in a data center.

Virtualization is the foundation which supports cloud computing. Providers such as AWS offer cloud services using powerful servers that can dynamically provision virtual servers as required.

Without virtualization, cloud computing, as it is most-widely implemented, would not be possible.

# Cloud Computing
Cloud computing has only increased in use during the years since the last edition of the CompTIA A+ Core Series test. Even though only about 11% of the questions pertain to this field, it will be important to know the answers. You’ll need to be able to compare and contrast ideas in cloud computing and also be able to set up virtualization for the client. It is worth noting that _none_ of the questions in this area will begin with a scenario for you to evaluate when answering.

## Cloud-Computing Concepts
For this exam, it is important to understand cloud computing and the different types of cloud-computing offerings that exist. You should also be able to summarize entire processes. Before cloud computing, **scalability** was difficult, as users were always restricted by their local resources. A common example of cloud computing includes online file storage. **Online file storage** allows users to store documents, photos, and videos **in the cloud** without needing to take up storage on their local hard drive. However, cloud computing covers far more than just file storage. It’s now possible to move an entire organization’s **infrastructure** (everything from servers to networking equipment) to the cloud.

### Applications
#### Virtual application streaming / cloud-based applications
Organization are using cloud-based applications to provide on-demand software delivery. For example, Microsoft Office365 provides online versions of Microsoft Word, Excel, and PowerPoint. When a user requests an application, minimal application code is forwarded to client. The client pulls additional code from the cloud server as required. For offline use, the application may be saved locally on the host.

#### Cloud-based Email
Organizations are using cloud-based solutions for their email requirements. Examples of cloud based email applications include Office 365, Gmail, iCloud Mail, Outlook, Yahoo, and Exchange Online.

#### Cloud file storage solutions
Organizations are using cloud-based storage solutions for their corporate data. Examples of cloud storage solutions include Google Drive, OneDrive, iCloud Drive, Box, and Dropbox. Some of these solutions include synchronization applications that are either provided by the vendors or commercially available applications.

#### Virtual Desktop Infrastructure (VDI)
An organization can use this technology to deploy entire desktop environments from a server in a data center to clients. The virtual desktops are created by a VM controlled by a hypervisor. However, all computing on the VDI is done on servers. VDIs can be persistent which provides the user with a customizable image that is saved for future use or non-persistent which reverts the image back to its initial state when a user logs out.

#### Windows Virtual Desktop (WVD)
This is a virtual desktop enabled edition of Windows 10 that runs on modern or legacy computers or remotely on Azure virtual machines. It provides a virtualized Windows 10 experience that is always up to date and available on any device.

### Common Cloud Models
include the different types of cloud structures that can be used as well as service structures that can be offered within the cloud environment. Cloud services are often sold **as a service**.

#### Private Cloud
A cloud model in which the virtualization resources purchased by the user are dedicated solely to the use of the user. This ensures the greatest level of security for the user but comes at an increased price as well as less flexibility for the resources. Think of a cloud as a physical file cabinet. With a private cloud, only the user is able to access or store their information in the file cabinet.
- used in the government and private companies 

#### Public Cloud
A virtualization resource in which the resource is **shared across the open internet**. This means that the same cloud server that contains a user’s data also contains the data of anyone else who uses that service. Imagine the physical file cabinet again. With a public cloud, you are able to store your data in a separate file within the file cabinet, but the files of thousands of other people are also stored in the same file cabinet. For this reason, a public cloud is not as secure as a private cloud. An example of a public cloud would be **Dropbox** or **iCloud**.
- provides a  

#### Hybrid Cloud
A **mixture** of the public cloud and the private cloud. A portion of the data is stored in a public cloud while other more sensitive data can be stored in a private cloud. A hybrid cloud offers the **security** of a private cloud for more sensitive data as well as the **flexibility** and **scalability** of a public cloud.
- often used to have half of the network on premises and the other in the cloud

#### Community Cloud
A cloud that is **shared between a specific set of users**. Imagine the file cabinet again. The file cabinet is shared between users, but only a specific set of users can store their data in the file cabinet, increasing security over a public cloud, which allows for anyone to store data in the file cabinet.
- the public of a specific field such as medical, police, fire, and other public services

### As a Service Models
![[As a Service.canvas|As a Service]]
#### Infrastructure as a Service (IaaS)
can be thought of as a **virtual data center**. As its name suggests, infrastructure as a service (IaaS) providers allow clients to build their entire infrastructure in the cloud. Infrastructure includes items such as servers, firewalls, routers, and switches. In an IaaS environment, clients are entirely responsible for managing, maintaining, and patching operating systems and applications.

The cloud provider manages the network and provides organizations access to network equipment, virtualized network services, storage, software, and supporting network infrastructure. There are many advantages for organizations to adopt IaaS. Organizations do not need to invest in capital equipment and only pay for usage on-demand. The provider network includes redundancy and eliminates a single point of failure in the provider network infrastructure. The network can also scale seamlessly based on current requirements. IaaS providers include Amazon Web Service, DigitalOcean, and Microsoft Azure.
- Includes network, computers (virtual or dedicated), and storage
- Typically used by organization infrastructure and network architects

Cloud service providers have extended the IaaS model to also provide IT as a service (ITaaS). ITaaS can extend the capability of IT without requiring investment in new infrastructure, training new personnel, or licensing new software. These services are available on demand and delivered economically to any device anywhere in the world without compromising security or function.

#### Metal as a Service (MaaS)


#### Containers as a Service (CaaS)


#### Platform as a Service (PaaS)
provides a platform for developers to **build their own applications**. PaaS providers will handle everything on the back end, including servers, operating systems, and development tools. This allows developers to focus on creating, building, and managing their applications.

The cloud provider provides access to operating systems, development tools, programming languages, and libraries used to develop, test, and deliver applications. This is useful to application developers. The cloud provider manages the underlying network, servers, and cloud infrastructure. PaaS providers include Amazon Web Service, Oracle Cloud, Google Cloud Platform and Microsoft Azure.
- Includes tools and services used to deliver the applications
- Includes OS and applications stack
- Typically requested by application and software developers

#### Function as a Service (FaaS)


#### Software as a Service (SaaS)
In recent years, there has been a major shift from locally installed software to **web-based software**. Software as a service (SaaS) has become a popular choice for organizations because it allows them to access their programs **anywhere an internet connection is available**. SaaS can be described as any program that is accessed via the web and not locally installed.

The cloud provider provides access to services, such as email, calendar, communication, and office tools over the Internet on a subscription basis. Users access the software using a browser. Advantages include minimal upfront costs for customers and immediate application availability. SaaS providers include Salesforce customer management relationship (CRM) software, Microsoft Office 365, MS SharePoint software, and Google G Suite.
- Software applications (e.g., email, office 365, ...) are provided over the network on a subscription basis
- Typically used by end users

#### Security as a Service (SECaaS)


#### IT as a Service (ITaaS)


### Cloud Characteristics
**features available on the cloud**. You must be able to summarize these common features.

#### On-demand (self-service)
Individuals can provision or make changes to computing services as needed without requiring human interaction with the service provider.

#### Broad network access
Capabilities are available over the network and can be accessed using smartphones, tablets, laptops, and workstations.

#### Shared Resources
also known as **resource pooling**. The division of the resources of the provider among the clients of that provider. One physical host machine with a lot of resources (memory, storage capacity) can have its resources shared among multiple virtual machines. This resource sharing can occur both **internally and externally**.

#### Metered Utilization
refers to the concept of tracking a cloud user’s usage and **charging only for the number of services used**.

Cloud systems provide service performance measurements that can be used to automatically control and optimize resources using a metering mechanism. Metering can be used to set thresholds to ensure that a customer is always provided with satisfactory service levels. Measured and metered services also provide reports for both the provider and service consumer.

_Note:_ The terms “measured service” and “metered service” are commonly used interchangeably when referring to cloud computing. The National Institute of Standards and Technology publication, SP 800-145, “The NIST Definition of Cloud Computing,” characterizes a measured service as when “cloud systems automatically control and optimize resource use by leveraging a metering capability at some level of abstraction appropriate to the type of service (e.g., storage, processing, bandwidth, and active user accounts). Resource usage can be monitored, controlled, and reported, providing transparency for both the provider and consumer of the utilized service.”

_Above information retrieved from [NIST SP 800-145, “The NIST Definition of Cloud Computing”]{https://nvlpubs.nist.gov/nistpubs/legacy/sp/nistspecialpublication800-145.pdf}{:target=”_blank”}._

#### Rapid Elasticity
It’s not always clear how much of a particular resource you are going to need when setting up a new environment. It’s entirely possible (and quite common) for your resource needs to grow as the organization grows. An organization that started with five servers might triple its server needs in several years. Virtualization makes it possible to quickly add new servers as you need them without the hassle of purchasing new hardware each time. This is known as rapid elasticity.

#### Resource pooling
The provider’s computing resources are pooled to serve multiple consumers using a multi-tenant model. Each model, each tenant (i.e., customer) shares the different physical and virtual resources dynamically assigned and reassigned according to consumer demand.  Examples of resources that can be pooled and shared include storage, processing, memory, and network bandwidth.

#### High Availability
the concept of a cloud service being **uninterrupted and responsive** the majority of the time. Service-level availability or **uptime** is measured in **nines**. For example, a provider with three nines of availability has 99.9% uptime while a provider with five nines of availability guarantees 99.999% uptime.

#### File Synchronization
the ability to provide the **most recent copy** of data on both the cloud and local devices through the synchronization process.

## Fog Computing 
wireless cloud computing used in modern [[Networks#Wireless Local Area Network|WLAN]], often uses [[IoT]]

## Software Defined Networking
To achieve efficient elasticity in the cloud, services must be provisioned and deprovisioned rapidly. This is done using scripting. Software-defined networking (SDN) is often used to perform these operations. In the SDN model, there are three layers, the application layer at the top, the control layer in the center, and the infrastructure layer at the bottom.  

### Application Layer
The application layer uses logic to decide how traffic is prioritized and where to switch it. The infrastructure layer is the physical and virtual devices that perform the routing and switching of traffic. The SDN controller in the center and controls the application and infrastructure layers. 

### Control Layer 

### Infrastructure Layer

### Application Programming Interface : [API]
The control of the layers is performed by scripts through an application programming interface (API). The API between the SDN controller and the application layer is called the northbound API and the API between the SDN controller and the infrastructure layer is called the southbound API.

An API is put in between a web application and an end user to determine what data the end user has access to.

### Software Defined [WAN] : SD-WAN
SD-WAN technologies make it possible to simplify an organization's network architecture, reducing it to a single orchestrated layer rather than a mixture of connected and integrated physical solutions. By virtualizing network architecture, organizations can better monitor and maintain their network organization, and can even offload a significant amount of work through automated processes. SD-WAN solutions include built-in firewalls, artificially intelligent security solutions, and integrated security features such as encryption, sandboxing, and IPS. Businesses are operating increasingly outside brick-and-mortar locations, SD-WAN technology can help reduce their costs. Through SD-WAN technology, companies can better improve their consistency and their reliability.

## Domain Controller

### Active Directory
# Virtualization
## Server Deployment
To fully appreciate virtualization, it is first necessary to understand how servers are used in an organization.

Traditionally, organizations delivered applications and services to their users using powerful dedicated servers as shown in the figure. These Windows and Linux servers are high-end computers with large amounts of RAM, powerful processors, and multiple large storage devices. New servers are added if more users or new services are required.

Problems with the traditional server deployment approach include:
- **Wasted resources** – This occurs when dedicated servers sit idle for long periods waiting until they are needed to deliver their specific service. Meanwhile, these servers waste energy.
- **Single-point of failure** – This occurs when a dedicated server fails or goes offline. There are no backup servers to handle the failure.
- **Server sprawl** – This occurs when an organization does not have adequate space to physically house underutilized servers. The servers take up more space than is warranted by the services that they provide.

Virtualizing servers to use resources more efficiently addresses these problems.

## Server Virtualization
takes advantage of idle resources to reduce the number of servers required to provide services to users.

A special program called the hypervisor is used to manage the computer resources and various VMs. It provides VMs access to all of the hardware of the physical machine such as CPUs, memory, disk controllers, and NICs. Each of these VMs runs a complete and separate operating system.

With virtualization, enterprises can now consolidate the number of servers. For example, it is not uncommon for 100 physical servers to be consolidated as virtual machines on top of 10 physical servers using hypervisors. In the figure, the previous eight dedicated servers have been consolidated into two servers using hypervisors to support multiple virtual instances of the operating systems.

### Better use of resources
Virtualization reduces the number of physical servers, networking devices, supporting infrastructure, and maintenance costs.

### Less space required
Server consolidation with virtualization reduces the overall footprint of the data center. Fewer servers, network devices, and racks reduce the amount of required floor space.
### Less energy consumed
Consolidating servers lowers the monthly power and cooling costs. Reduced consumption helps enterprises to achieve a smaller carbon footprint.

### Reduced cost
Cost savings because less equipment is required, less energy is consumed, and less space is required.

### Faster server provisioning
Creating a virtual server is far faster than provisioning a physical server.

### Maximized server uptime
Most server virtualization platforms now offer advanced redundant fault tolerance features, such as live migration, storage migration, high availability, and distributed resource scheduling. They also support the ability to move a virtual machine from one server to another.

### Improved disaster recovery
Virtualization offers advanced solutions to keep business continuing during a disaster. VMs can be copied to other hardware platforms that may even be in a different data center.

### Support for legacy systems
Virtualization offers advanced solutions to keep business continuing during a disaster. VMs can be copied to other hardware platforms that may even be in a different data center.

## Desktop Virtualization
Thanks to virtualization, it’s possible to have multiple virtual desktops running on one physical machine. These machines operate similarly to a physical desktop, but all the **hardware is virtualized**. You must be able to summarize these concepts.

#### Virtual Desktop Infrastructure (VDI) on Premises
A virtual desktop infrastructure (VDI) is a means by which to manage virtual desktops. With a VDI on premises, the virtual machine running the virtual desktops is located on the physical premises of the entity using it. A VDI removes the physical hardware of a network, such as switches, cables, and NICs, and replaces them with **virtual hardware contained on a single machine** located at the site.

#### VDI in the Cloud
VDI in the cloud removes the virtual **machine** from the physical premises and places it in the cloud environment **run through cloud providers**. This eliminates the responsibility of the user for the physical hardware running the VDI.

## Client-Side Virtualization
the process of running the virtual environment on a device physically located on the premises. The virtualization software is run on the client machine rather than through the cloud. The client device hosts the hypervisor and is responsible for accommodating the necessary requirements to run the virtual machine. Considerations for client-side virtualization include **CPU**, **RAM**, **hard drive space**, and **network capabilities**. 

Many organizations use server virtualization to optimize network resources and reduce equipment and maintenance costs. Organizations are also using client-side virtualization to enable users with specific needs to run VMs on their local computer.

Client-side virtualization is beneficial for IT staff, IT support people, software developers and testers, and for educational reasons. It provides users with resources to test new operating systems, software, or to run older software. It can also be used to sandbox and create a secure isolated environment to open or run a suspicious file.

Some terms that are used when discussing client-side virtualization include:
- **Host computer** – This is the physical computer controlled by a user. VMs use the system resources of the host machine to boot and run an OS.
- **Host operating system (host OS)** - This is the operating system of the host computer. Users can use a virtualization emulator such as VirtualBox on the host OS to create and manage VMs.
- **Guest operating system (guest OS)** - This is the operating system that is running in the VM. Drivers are required to run the different OS version.

The guest OS is independent of the host OS. For example, the host OS could be Windows 10 and the VM could have Windows 7 installed. This guest of the VM would be Windows 7. In this example, the guest OS (Windows 7) does not interfere with the host OS (Windows 10) on the host computer.

Host and guest operating systems do not need to be of the same family. For example, the host OS could be Windows 10, while the guest OS is Linux. This is of benefit for users that need to increase the functionality of their host computer by running multiple operating systems at the same time.

To do well on questions about this, you must be able to summarize the following content.

## Hypervisors
The hypervisor, also called the Virtual Machine Manager (VMM), is the brain of virtualization. The hypervisor is the software used on the host computer to create and manage VMs.

The hypervisor allocates the physical system resources, such as CPU, RAM, and storage, to each VM as needed. This ensures that the operation of one virtual machine does not interfere with another.

There are two types of hypervisors.
### Type 1
**(native) hypervisor** – Also called bare-metal hypervisor and typically used with server virtualization. It runs directly on the hardware of a host and manages the allocation of system resources to virtual operating systems.

Type 1 hypervisors are common in data centers and in cloud computing. Examples of Type 1 hypervisors include VMware vSphere / ESXi, Xen, and Oracle VM Server.

Type 1 implementation, VMware vSphere runs directly on the server hardware with no operating system. VMware vSphere has been used to create a Windows Server VM and a Linux Server VM.

### Type 2
**(hosted) hypervisor** – This is hosted by an OS and is commonly used with client-side virtualization. Virtualization software such as VirtualBox and VMware Workstation are examples of a Type 2 hypervisor.

Type 2 hypervisors such as VMware Workstation work with the host computer to create and use multiple VMs.

In the Type 2 implementation, the host OS on the computer is Windows 10. VirtualBox has been used to create and manage the Windows 7 VM and a Linux VM.

Client-side emulators can run software meant for a different guest OS or an OS meant for different hardware. For example, if the host OS was Linux and we are creating a VM using Windows 7 to run an application that only runs in Windows 7. The Linux host computer will pretend to be a Windows 7 computer.

### The Purpose of Virtual Machines
A virtual machine is designed to remove the one-to-one hardware and software barrier and **maximize available resources**. Virtual machines can be used to run multiple OSs on a single device or can pool resources from multiple servers into a single powerful system. Virtual machines can also be used to **protect the host system** by separating the virtual machines from one another.

#### Network Sandbox
a **temporary, isolated virtual environment** that can be used for testing or quarantining. A sandbox creates a safe environment separated virtually from the host machine to eliminate the potential contamination of the host machine. Data in the sandbox is only in the sandbox and does not save to the host. When the sandbox is terminated, all data associated with the sandbox is also removed.

#### Test Development
Virtual machines can be used for test development by creating virtual environments and OSs that can be used for application testing or development.

#### Application Virtualization
The virtualization of applications. Application virtualization is often used with legacy software or legacy OS to offer the functionality of the legacy application. Application virtualization is also used for cross-platform functionality. For example, an application designed for a macOS can be used on a Windows machine by creating a virtual macOS on the Windows machine.

##### Legacy Software/OS
**outdated** software and operating systems that are not compatible with modern systems.

##### Cross-Platform Virtualization
the process of creating a virtual OS of one platform on a different platform, such as a macOS on a Windows OS.

### Resource Requirements
Not all virtual machines are created equal. The individual that is building the virtual machine determines what resources to provide to the virtual machine. This means determining the amount of **hard drive space** and the amount of **memory** that your local machine can afford to give the virtual machine. If your physical machine doesn’t have a lot of **RAM**, then you will not be able to provide enough RAM for your virtual machine to run smoothly.

All virtual machines share the following basic system requirements:
- **Processor support** : Processors, such as Intel VT and AMD-V, were specifically designed to support virtualization. The virtualization feature on these processors may need to be enabled. Processors with multiple cores are also recommenced as the additional cores increase speed and responsiveness when running multiple VMs.
- **Memory support** : Consider that you need memory for you host OS and will now need enough RAM to meet the requirements of each VM and their guest OS.
- **Storage** : Each VM creates very large files to store operating systems, applications, and all of the VM data. You must also factor in that an active VM will require a few GB of storage space. Therefore, large and fast drives are recommended.
- **Network Requirements** : Network connection requirements depend on the type of VM. Some VMs do not require outside connections while others do. VMs can be configured in a bridged, NAT, host-only, or a special network to connect only to other VMs. To connect to the Internet, a VM uses a virtual network adapter that simulates the real host adapter. The virtual network adapter than connects through the physical NIC to establish a connection to the Internet.

The minimum system requirements for Windows Hyper-V for Windows 10 and Windows 11, are shown in the tables below.

Like a physical computer, VMs are susceptible to the same threats and malicious attacks. Although VMs are isolated from the host, they can share resources (e.g., NIC, folders, and files). Users should exercise the same security considerations as the host and install security software, enable firewall feature, install patches, and update the operating system and programs. It is also important to keep the virtualization software updated. 

#### Windows Hyper-V Requirements for Windows 10

| Host OS         | Windows 10 Pro or Windows Server (2012 and 2016)                |
| --------------- | --------------------------------------------------------------- |
| Processor       | 64-bit processor with Second Level Address Translation (SLAT)   |
| BIOS            | CPU support for VM Monitor Mode Extension (VT-c on Intel CPU's) |
| Memory          | Minimum 4 Gb system RAM                                         |
| Hard Disk Space | At least 15 Gb per VM                                           |
#### Windows Hyper-V Requirements for Windows 11

| Host OS         | Windows 11 Home or Pro                                                                            |
| --------------- | ------------------------------------------------------------------------------------------------- |
| Processor       | 1 GHz or faster and 64-bit compatible processor or System on a Chip (SoC) with two or more cores, |
| BIOS            | UEFI, Secure Boot capable, and support for Trusted Platform Module (TPM)                          |
| Memory          | Minimum 4 Gb system RAM                                                                           |
| Hard Disk Space | At least 10 Gb per Virtual OS                                                                     |
| Graphics        | DircX 12 compatible or later with support for WDDM 2.0 driver and a display that supports 720p HQ |

### Security Requirements
Just as security is vital in physical computing, it’s also important to consider security when working with virtual machines. This means implementing the **same types of security controls** on your virtual desktops as you would on your physical ones, such as strong passwords, account lockout policies, and even multi-factor authentication.

---
# Nav
< [[Networks|Previous]] < ^ [[Navigation|Home]] ^