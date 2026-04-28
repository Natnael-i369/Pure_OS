# PureOS Installation on VMware Workstation

## Project Title
Virtual OS Installation (PureOS)

## Author
Natnael Getachew  
Bahir Dar University  
Faculty of Computing  
Department of Software Engineering

## Description
This project demonstrates the installation of **PureOS** on a virtual machine using **VMware Workstation**. PureOS is a Debian-based Linux distribution focused on privacy, security, and free open-source software.

The purpose of this project is to gain practical experience with operating system installation, virtualization, and Linux environment management.

## Requirements

### Hardware Requirements
- Dual-core processor (Intel/AMD)
- Virtualization support enabled (VT-x / AMD-V)
- Minimum 4 GB RAM (8 GB recommended)
- At least 20 GB free storage
- Stable power supply
- Internet connection

### Software Requirements
- VMware Workstation / VirtualBox
- PureOS ISO file
- Host OS: Windows / Linux / macOS

## Installation Steps

### Step 1: Download Required Software
- Download and install VMware Workstation.
- Download PureOS ISO from the official website.

### Step 2: Create New Virtual Machine
- Open VMware Workstation.
- Select **Create a New Virtual Machine**.
- Choose **Typical (Recommended)**.

### Step 3: Select Installation Media
- Choose **Installer disc image file (ISO)**.
- Browse and select the PureOS ISO file.

### Step 4: Select Guest Operating System
- Guest OS: **Linux**
- Version: **Debian 10/11 (64-bit)**

### Step 5: Configure Virtual Machine
- Name: PureOS
- Disk Size: 20 GB minimum
- RAM: 2 GB minimum (4 GB recommended)
- CPU: 2 cores

### Step 6: Start Virtual Machine
- Power on the VM.
- Boot into PureOS installer.

### Step 7: Begin Installation
- Select language
- Select keyboard layout
- Continue with default settings

### Step 8: Disk Partitioning
- Select **Erase disk and install PureOS**  
(This only affects the virtual disk)

### Step 9: Create User Account
- Full Name: Natnael Getachew
- Username: Natnael
- Create password

### Step 10: Complete Installation
- Wait for file copying and setup.
- Restart VM after installation.
- Login using created credentials.

## Common Issues and Solutions

### Low Performance
Increase RAM and CPU allocation.

### ISO Boot Error
Re-download ISO and verify integrity.

### No Internet Connection
Use NAT network mode.

### Display Problems
Install VMware tools / guest additions.

## Advantages of Virtual Installation
- Safe testing environment
- No effect on host OS
- Easy reset and reinstallation
- Learn Linux practically
- Run multiple operating systems

## Conclusion
PureOS can be installed successfully using VMware Workstation through a simple structured process. Running it in a virtual machine is safe, flexible, and useful for learning operating system concepts.

## License
Educational Use# Pure_OS
Installation Process
