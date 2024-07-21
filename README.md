### User Manual for the `setup-xrdp.sh` Script

This user manual provides step-by-step instructions for using the `setup-xrdp.sh` script to set up XRDP on various Debian-based desktop systems.

#### Repository: debian-xrdp-setup

---

### Table of Contents

- [Introduction](#introduction)
- [System Requirements](#system-requirements)
- [Pre-requisites](#pre-requisites)
- [Installation Steps](#installation-steps)
- [Usage Instructions](#usage-instructions)
- [Troubleshooting](#troubleshooting)
- [Additional Information](#additional-information)
---

### Introduction

The `setup-xrdp.sh` script automates the installation and configuration of XRDP on various Debian-based desktop systems. Supported distributions include:

- Ubuntu Desktop
- Kali Linux
- Debian
- Linux Mint
- Elementary OS
- Zorin OS
- MX Linux
- Parrot OS

### System Requirements

- A Debian-based desktop system (as listed above)
- Internet connection to download necessary packages
- Root or sudo privileges

### Pre-requisites

1. Ensure your system is up to date:

```shell
    sudo apt update && sudo apt upgrade -y
```
    
2. Install Git if it's not already installed:
    
```shell
    sudo apt install git -y
```
    

### Installation Steps

1. **Clone the Repository**
    
    Clone the `debian-xrdp-setup` repository to your local machine:
    
```shell
    git clone https://github.com/yourusername/debian-xrdp-setup.git
```
    
2. **Navigate to the Script Directory**
    
    Change to the directory where the script is located:
    
```shell
    cd debian-xrdp-setup
```
    
3. **Make the Script Executable**
    
    Ensure the script has executable permissions:
    
```shell
    chmod +x setup-xrdp.sh
```
    

### Usage Instructions

1. **Run the Script**
    
    Execute the script with sudo privileges:
    
```shell
    sudo ./setup-xrdp.sh
```
    
2. **Choose Your Distribution**
    
    When prompted, enter the number corresponding to your Debian-based distribution:
    
```markdown
Please enter the number corresponding to your Debian-based distribution: 

1. Ubuntu Desktop 
2. Kali Linux 
3. Debian 
4. Linux Mint 
5. Elementary OS 
6. Zorin OS 
7. MX Linux 
8. Parrot OS Enter your choice (1/2/3/4/5/6/7/8):       
```


3.  **Follow the On-Screen Instructions**
    
    The script will guide you through the installation process, displaying messages and statuses for each step. It will:
    
    - Update your system
    - Install XRDP
    - Install the appropriate desktop environment (XFCE)
    - Configure XRDP to use XFCE
    - Enable and start the XRDP service
    - Configure the firewall (if `ufw` or `firewalld` is installed)

### Troubleshooting

If you encounter any issues during the installation, refer to the following log files for troubleshooting:

- `/var/log/xrdp.log`
- `/var/log/xrdp-sesman.log`

### Additional Information

- **Connecting from Windows:** Use the "Remote Desktop Connection" application and enter the IP address of your Debian-based machine.
- **Connecting from Linux:** Use a Remote Desktop client like `Remmina` and select the RDP protocol.

---

By following this user manual, you should be able to easily set up XRDP on your Debian-based desktop system and remotely connect to it using an RDP client.
