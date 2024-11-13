# task-8
![image](https://user-images.githubusercontent.com/70103173/122405784-f6102380-cf9d-11eb-8bd4-600d9aa8a934.png)
Here's a detailed GitHub description for your project, including a brief summary, setup instructions, and an explanation of each menu option:

---

# Project Title: **Automated Management Tool for AWS, Docker, LVM, and Hadoop**

## Description

This project is a Text User Interface (TUI) script in Python that enables easy and efficient management of cloud and storage technologies, including AWS (Amazon Web Services), Docker, Logical Volume Management (LVM), and Hadoop. Users can select options to perform various management tasks related to instances, containers, logical volumes, and Hadoop nodes from within the TUI interface. This tool aims to streamline administrative tasks across multiple platforms, allowing users to focus on essential operations without needing to manually configure each technology.

### Features

- **AWS Management:** Allows users to interact with AWS services for EC2 instance and volume management, including launching, starting, stopping, and configuring instances.
- **Docker Management:** Provides options for container management, such as starting Docker, running containers, pulling images, and stopping services.
- **Logical Volume Management (LVM):** Automates logical volume management, including creating, resizing, and removing volume groups and logical volumes.
- **Hadoop Management:** Includes options for configuring and managing Hadoop nodes, such as setting up the Hadoop file system, starting/stopping nodes, and handling data files.

## Prerequisites

- Python 3.x
- [AWS CLI](https://aws.amazon.com/cli/) installed and configured with the required permissions
- Docker installed on the system
- Hadoop installation for Hadoop-related operations
- Python libraries: `getpass`, `os`, and `subprocess`

## Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/automated-management-tool.git
   ```
2. Ensure the required dependencies and libraries are installed.
3. Run the script using:
   ```bash
   python3 management_tool.py
   ```

## Usage

The TUI provides an interactive experience with five primary options:

### Main Menu Options

1. **AWS Management** - Interact with AWS services:
   - Log in, launch instances, start/stop instances, describe instances, manage volumes, configure web servers, and mount volumes.
   
2. **Docker Management** - Manage Docker containers:
   - Start Docker, view images, run containers, pull images, stop/delete containers, and stop Docker services.
   
3. **Logical Volume Management (LVM)** - Automate LVM tasks:
   - Manage volume groups: create, display, extend, merge, reduce, rename, remove, and add volumes.
   - Manage logical volumes: create, format, mount, unmount, extend, reduce, remove, and display logical volumes.
   
4. **Hadoop Management** - Handle Hadoop node configurations:
   - Check installation, install Hadoop, create directories, configure `hdfs-site.xml` and `core-site.xml`, format name nodes, start/stop services, upload/remove files, and check cluster reports.

5. **Exit** - Exit the management tool.

## Detailed Module Descriptions

### 1. AWS Management Module

Provides options to manage EC2 instances and volumes on AWS:
   - Login, launch, start/stop instances, create/attach volumes, partition and format disks, and mount volumes as web servers.

### 2. Docker Management Module

Enables Docker container management with options to:
   - Start Docker, list images, run containers, pull images, and control Docker services.

### 3. Logical Volume Management (LVM) Module

Automates LVM management, including creating and resizing volume groups and logical volumes:
   - Manage Volume Groups (create, display, extend, reduce, etc.)
   - Manage Logical Volumes (create, format, mount, unmount, extend, reduce, etc.)

### 4. Hadoop Management Module

Facilitates managing Hadoop nodes and configuring `hdfs-site.xml` and `core-site.xml` files for different nodes:
   - Install Hadoop, configure and format nodes, upload/remove files, and display cluster reports.

---

