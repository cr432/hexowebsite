---
title: VirtualBox
date: 2024-10-16 13:12:01
tags:
---
## What is VirtualBox?

**VirtualBox** is a free and open-source software developed by Oracle that allows users to run multiple operating systems simultaneously on a single physical machine. Each operating system runs inside a **Virtual Machine (VM)**, which simulates a separate computer.

---

## Why Use VirtualBox?

VirtualBox is useful for:
- Testing new operating systems without affecting your main OS.
- Running legacy applications that only work on older operating systems.
- Setting up development environments with isolated software stacks.
- Learning and experimenting with multiple OS configurations without needing multiple physical machines.

---

## Installing VirtualBox

Follow these steps to install VirtualBox on your system:

1. **Download VirtualBox**:
   - Go to the [VirtualBox website](https://www.virtualbox.org/).
   - Choose the version that matches your operating system (Windows, macOS, Linux).

2. **Install VirtualBox**:
   - Run the installer and follow the prompts.
   - Accept the default settings unless you have specific requirements.
   - After installation, launch VirtualBox from your desktop or start menu.

---

## Setting Up Your First Virtual Machine

Once VirtualBox is installed, follow these steps to set up your first virtual machine.

### Step 1: Creating a New VM
1. Open VirtualBox.
2. Click the **New** button to create a new virtual machine.
3. Give your VM a name (e.g., "UbuntuTest").
4. Choose the type and version of the OS you want to install (e.g., Linux, Ubuntu (64-bit)).
5. Click **Next**.

### Step 2: Configuring VM Settings
1. **Memory (RAM)**: Select the amount of memory to allocate to the VM. For most modern OSes, 2GB (2048MB) is recommended. Click **Next**.
2. **Hard Disk**: Choose **Create a virtual hard disk now** and click **Create**.
3. **Disk File Type**: Choose **VDI (VirtualBox Disk Image)** and click **Next**.
4. **Storage**: Select **Dynamically allocated** for flexible disk space management. Click **Next**.
5. **Disk Size**: Set the virtual hard disk size (e.g., 20GB for Ubuntu). Click **Create**.

### Step 3: Installing the Guest OS
1. Select your newly created VM in the VirtualBox manager.
2. Click **Start** to boot the VM.
3. VirtualBox will prompt you to provide the installation media for the OS:
   - Select the **ISO file** for the operating system (e.g., Ubuntu ISO) and click **Start**.
4. Follow the installation steps inside the VM to install the OS as you would on a physical machine.

---

## Common VirtualBox Features

### 1. Snapshots
Snapshots allow you to save the current state of your VM and return to it later. This is useful for testing configurations or software without the risk of losing your setup.

- To create a snapshot:
  1. Select your VM.
  2. Go to **Machine > Take Snapshot**.

### 2. Shared Folders
Shared folders let you access files from your host machine inside your VM.

- To set up a shared folder:
  1. Right-click your VM in VirtualBox, choose **Settings > Shared Folders**.
  2. Add a folder from your host and mark it as **Auto-mount**.

### 3. Guest Additions
Guest Additions are a set of drivers and utilities that improve VM performance and enable features like shared clipboard, drag-and-drop, and better display resolution.

- To install Guest Additions:
  1. Start your VM.
  2. Go to **Devices > Insert Guest Additions CD Image** from the VirtualBox menu.
  3. Follow the prompts inside your VM to install it.

---

## Useful Tips and Troubleshooting

### 1. Enable Virtualization in BIOS
If your VM is slow or won’t start, ensure that hardware virtualization (Intel VT-x or AMD-V) is enabled in your system’s BIOS settings.

### 2. Adjust VM Settings
If your VM runs slowly, consider:
- Increasing the amount of RAM allocated to the VM.
- Allocating more CPU cores to the VM (**Settings > System > Processor**).

### 3. Networking Issues
If your VM can’t access the internet:
- Check that the **Network Adapter** is set to **NAT** under VM settings.

---

## Conclusion

**VirtualBox** is a powerful tool for running multiple operating systems on a single machine. Whether you're testing software, setting up development environments, or exploring new OS configurations, VirtualBox is an excellent choice for beginners. Once you've mastered the basics, you can explore more advanced features like networking between VMs, automation with **VBoxManage**, and integrating with cloud services.