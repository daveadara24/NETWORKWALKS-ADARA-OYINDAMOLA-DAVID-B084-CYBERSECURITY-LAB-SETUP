# NETWORKWALKS-ADARA-OYINDAMOLA-DAVID-B084-WK1-CYBERSECURITY-LAB-SETUP


# Kali Linux Installation on Oracle VirtualBox

![Kali Linux](https://img.shields.io/badge/OS-Kali%20Linux-blue?logo=kalilinux)
![Virtualization](https://img.shields.io/badge/Platform-VirtualBox-183A61?logo=virtualbox)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)

## Overview

This project documents my experience installing and configuring Kali Linux as a virtual machine using Oracle VirtualBox.

The goal was to build a safe, isolated environment for learning Linux fundamentals, networking, and practical cybersecurity.

This project is part of my journey toward developing hands-on cybersecurity skills.

## Objectives

- Understand virtualization and virtual machines.
- Install Kali Linux in Oracle VirtualBox.
- Configure the virtual machine's hardware resources.
- Verify that Kali Linux boots and operates correctly.
- Prepare a lab environment for future cybersecurity exercises.

## Tools and Technologies

| Tool | Purpose |
|---|---|
| Kali Linux | Linux distribution for cybersecurity learning |
| Oracle VirtualBox | Runs the virtual machine |
| Windows host | Main operating system running VirtualBox |

## System Requirements

- A computer with VirtualBox installed.
- A compatible Kali Linux installer image.
- Sufficient RAM and disk space.
- An internet connection for downloading the required software and updates.

## Installation Process

### Step 1: Download Kali Linux

I obtained the Kali Linux installer image from the official Kali Linux website.

Official download page: https://www.kali.org/get-kali/

### Step 2: Install Oracle VirtualBox

I installed Oracle VirtualBox on my host computer to create and manage the virtual machine.

Official website: https://www.virtualbox.org/

### Step 3: Create the Virtual Machine

I created a new virtual machine in VirtualBox and configured its operating system type, memory allocation, processors, and virtual hard disk.

### Step 4: Attach the Kali Linux Image

I selected the Kali Linux installer ISO as the virtual machine's installation media and started the machine.

### Step 5: Install Kali Linux

I followed the installer instructions, selected the required installation options, and completed the operating system installation.

### Step 6: Verify the Installation

After installation, I booted into Kali Linux and checked that the operating system was working.

I also began checking the network connection and virtual machine configuration.


<img width="1365" height="720" alt="Screenshot 2026-10-29 003952" src="https://github.com/user-attachments/assets/4369ffb5-354b-4c50-ade8-c1f1fd9a51be" />

<img width="1364" height="724" alt="Screenshot 2026-10-29 010555" src="https://github.com/user-attachments/assets/701312a1-2a98-48d1-b7e0-f57b53427006" />

## Challenges Encountered
The challenges i encountered were not so problematic but here are some things to note down
- check the ISO file to make sure to not install the wrong OS
- make sure to use the right storage partion to be able to install kali properly and to avoid it starting over
- the process may take some time, so do note that patience is advised
- finally, enjoy the process.


## What I Learned

- The fundamentals of virtualization.
- How to install a Linux operating system in a virtual machine.
- How virtual machine resources are allocated.
- The importance of documenting technical work.
- How to prepare a lab for future cybersecurity practice.

## Future Improvements

- Configure shared folders between the host and virtual machine.
- Enable clipboard integration and drag-and-drop where supported.
- Troubleshoot and verify internet connectivity.
- Practice Linux commands and permissions.
- Conduct authorized network analysis and defensive security exercises.

## Safety and Disclaimer

This virtual machine is intended for educational purposes and authorized cybersecurity practice. Any security testing will be performed in a controlled environment with appropriate permission.

## References

- Kali Linux: https://www.kali.org/
- VirtualBox: https://www.virtualbox.org/
- Kali Linux Documentation: https://www.kali.org/docs/
