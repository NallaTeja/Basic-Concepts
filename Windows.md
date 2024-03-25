Fundamentals of Windows
- Operating System (OS) *OS Architecture *Bit&byte *Types of Disk & Filesystem 
- Users & group
- Device Management
- Disk Management
- Task Schduler
- Powershell & Command promt

When you power on your PC, the operating system (OS) starts through a multi-step process known as booting.The services are up and running listed below:

1. **Power-On**: You press the power button, and the computer begins to power up.

2. **BIOS/UEFI Initialization**: The Basic Input/Output System (BIOS) or Unified Extensible Firmware Interface (UEFI) takes control. It's a firmware stored on a chip on the motherboard⁴.

3. **POST**: The BIOS/UEFI performs a Power-On Self-Test (POST) to check the hardware's functionality⁵.

4. **Bootloader**: The BIOS/UEFI then looks for a bootable device (like a hard drive or SSD) and loads the Master Boot Record (MBR) or GUID Partition Table (GPT) into RAM. From there, it runs the bootloader⁴.

5. **Kernel Loading**: The bootloader loads the kernel of the OS into memory. The kernel is the core of the OS and manages the CPU, memory, and peripheral devices⁴.

6. **System Initialization**: The kernel initializes the system's hardware and mounts the filesystem. It then starts system processes and loads drivers⁴.

7. **User Space**: After the system processes are up, the kernel hands over control to the user space. This is where application software and user interfaces run⁴.

8. **Login**: Finally, the OS displays a login prompt or graphical login screen, allowing you to access your system⁴.


Difference b/w bit and byte?
Bit: The smallest unit of data in a computer. It can be represented by either a 0 or a 1. Bits are fundamental for data transmission between components like the CPU, RAM, and storage devices. 
For example, network speeds are often measured in bits per second (e.g., 2 Mbps or 1 Gbps).
Byte: A byte consists of 8 bits. It is commonly used to express storage sizes. In computing, bytes represent 256 different values. For instance, when you see file sizes or system storage capacities, such as Kilobytes (KB), megabytes (MB), gigabytes (GB), and terabytes (TB) are all examples of byte-based measurements.
8 bit is equal to 1 byte. 8 bits can represent 256 different values (0 to 255). 
255: This is the maximum value you can represent with 8 bits using binary notation (11111111 in binary).
256: This is the total number of different values you can represent with 8 bits, starting from 0 up to 255.
Note: 10 MBps (Megabytes per second) is greater than 10 Mbps (Megabits per second) because 10 MegaBytes consist of 10 × 8 = 80 Mbps. Data speed (internet) is measured in kilobits, megabits, and gigabits, while storage capacity (computer files) is expressed in kilobytes, megabytes, and gigabytes

Comparison between HDD (Hard Disk Drive) and SSD (Solid State Drive):

- **Storage Mechanism**:
  - **HDD**: Uses magnetic storage to store and retrieve data using one or more rotating disks.
  - **SSD**: Uses flash memory, which is faster and has no moving parts.

- **Speed**:
  - **HDD**: Generally slower due to the mechanical movement of the read/write head.
  - **SSD**: Faster data access and boot times because it accesses data electronically.

- **Durability**:
  - **HDD**: More prone to damage from drops or movement because of its mechanical parts.
  - **SSD**: More resistant to physical shock and are less likely to lose data due to no moving parts.

- **Noise**:
  - **HDD**: Can produce audible noise and vibration when in use.
  - **SSD**: Operates silently as it has no moving parts.

- **Energy Efficiency**:
  - **HDD**: Consumes more power, which can reduce the battery life of laptops.
  - **SSD**: More energy-efficient, leading to longer battery life in portable devices.

- **Cost**:
  - **HDD**: Less expensive per gigabyte of storage.
  - **SSD**: More expensive, but prices have been decreasing over time.

- **Capacity**:
  - **HDD**: Available in larger capacities, suitable for bulk storage.
  - **SSD**: Typically offers less capacity but is sufficient for most users' needs.

- **Lifespan**:
  - **HDD**: The lifespan can be affected by wear and tear of mechanical parts.
  - **SSD**: Generally has a longer lifespan due to the lack of mechanical parts, but its write cycles are finite.

In summary, SSDs offer faster performance, durability, and energy efficiency, while HDDs are more cost-effective for larger storage capacities.

![image](https://github.com/NallaTeja/Basic-Concepts/assets/145950340/a661d49b-f8f6-498e-8a56-3b73c4f11dba)
