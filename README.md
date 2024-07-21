# Debian-XRDP-setup ⚡️ [![GitHub](https://img.shields.io/github/license/kusal-tharindu/debian-xrdp-setup?color=blue)](https://github.com/kusal-tharindu/debian-xrdp-setup/blob/main/LICENSE) ![GitHub stars](https://img.shields.io/github/stars/kusal-tharindu/debian-xrdp-setup) ![GitHub forks](https://img.shields.io/github/forks/kusal-tharindu/debian-xrdp-setup) 

<h2 align="center">
  <img src="/readme-img/readme.png" alt="Debian-XRDP-setup" width="600px" />
  <br>
</h2>

### User Manual for the `setup-xrdp.sh` Script

The `setup-xrdp.sh` script is designed to automate the installation and configuration of XRDP on various Debian-based desktop systems. XRDP is an open-source implementation of the Microsoft Remote Desktop Protocol (RDP), which allows you to access your desktop environment remotely from another computer.

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

---
## Authors ✍

- **`Kusal Tharindu`**
- <img src="https://kusal.dtk2globle.com/assets/images/logo/last.png" height="20"/>&nbsp; [- **Kusal Tharindu**]([https://github.com/sasinduKKarunarathna](https://github.com/kusal-tharindu)) 

- [![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/kusal-tharindu) [![Twitter](https://img.shields.io/badge/Twitter-%231DA1F2.svg?logo=Twitter&logoColor=white)](https://twitter.com/tharindu_kusal) [![GitHub](https://img.shields.io/badge/github-%231DA1F2.svg?logo=github&logoColor=black)](https://github.com/kusal-tharindu)

## Wanna read my articles?

* <img src="https://kusal.dtk2globle.com/assets/images/logo/last.png" height="20"/>&nbsp; [Portfolio](https://kusal.dtk2globle.com/)
* <img src="https://1.bp.blogspot.com/-FAZt0e1ahsk/YJVuGsoDC1I/AAAAAAAAAI8/KNj3GmSpX6AI-tsXnBHWjRqaycmM8PH4gCK4BGAYYCw/s1600/DTK%2B%25281%2529.png" height="20"/>&nbsp; [Personal Blog](https://blog.dtk2globle.com/)

---

## License 📄

This project is licensed under the MIT License.

Find out more details: [LICENSE.md](https://github.com/kusal-tharindu/debian-xrdp-setup/blob/main/LICENSE)

---
## Fair Use Act Disclaimer 🛑 

This project is for educational purposes only.

Fair Use
Copyright Disclaimer under section 107 of the Copyright Act of 1976, allowance is made for “fair use” for purposes such as criticism, comment, news reporting, teaching, scholarship, education and research. Fair use is a use permitted by copyright statute that might otherwise be infringing.

Find out more details: [Disclaimer.md](https://github.com/kusal-tharindu/debian-xrdp-setup/blob/main/Disclaimer.md)

---
## Acknowledgments 🎁

I was motivated to create this project because I wanted to contribute on something useful for the dev community.

Many thanks to all my contributors who helped make this project a reality.

---
## You can help me by Donating 💰

  <a href="https://www.buymeacoffee.com/kusal26" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" height="45px" ></a>
   
---
## Contact Me 📞
If you have any questions about this Privacy Policy, You can contact us:
- By email: contact@dtk2globle.com
