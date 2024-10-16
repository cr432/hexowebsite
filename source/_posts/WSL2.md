---
title: WSL2
date: 2024-10-16 13:08:32
tags:
---
## Windows Subsystem for Linux 2 (WSL2)

**Windows Subsystem for Linux 2 (WSL2)** is a feature in Windows that allows users to run a full Linux kernel on their Windows system. It offers better performance and full compatibility with Linux software compared to WSL1. WSL2 uses a lightweight virtual machine (VM), providing improved file system performance. It’s an excellent tool for developers who need both Windows and Linux environments.

---

### Benefits of WSL2

- **Full Linux Kernel**: Includes a complete Linux kernel built by Microsoft, supporting system calls and better compatibility with Linux applications.
- **Improved File I/O Performance**: Offers faster file system performance, especially for workloads involving heavy I/O.
- **Better Docker Integration**: Runs Docker natively without needing Docker Desktop, providing a seamless developer experience.
- **Low Resource Usage**: Though it uses a VM, WSL2 is lightweight and consumes fewer system resources compared to traditional virtual machines.
- **Seamless Windows Integration**: Allows easy access to Windows files from the Linux environment, enabling fluid work across both systems.

---

### Key Features

- **Native Linux Kernel**: Enhances compatibility with Linux tools and services.
- **Virtualized Environment**: Runs a Linux kernel using lightweight virtualization.
- **File System Support**: Provides a fast and efficient file system for developers.
- **Memory Management**: Dynamically allocates system resources based on workload needs.

---

### System Requirements

- Windows 10 Version 1903 or higher (Build 18362 or higher)
- Windows 11 fully supports WSL2
- Windows Hyper-V and Virtual Machine Platform must be enabled

