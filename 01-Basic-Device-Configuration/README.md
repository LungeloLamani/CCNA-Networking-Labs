CCNA Basic Device Configuration Lab

📚 Module

CCNA: Switching, Routing, and Wireless Essentials

🎯 Lab Objective

Configure and secure a Cisco switch using basic IOS commands and verify the configuration.

🖥️ Lab Environment

- Cisco Packet Tracer
- Cisco 2960 Switch
- PC connected to the switch
- Cisco IOS CLI

⚙️ Configuration Tasks

The lab covered:

- Entering privileged EXEC mode
- Entering global configuration mode
- Configuring the switch hostname
- Securing privileged EXEC access
- Configuring console access
- Configuring remote access using SSH
- Configuring the switch management interface
- Assigning an IP address
- Configuring the default gateway
- Saving the configuration
- Verifying the configuration

🔧 Important Commands

enable
configure terminal
hostname Switch1
show running-config
show interfaces
show ip interface brief
copy running-config startup-config

🔐 SSH Configuration

The lab also included configuring SSH for secure remote management.

ip domain-name example.com
username admin secret <password>
crypto key generate rsa
line vty 0 15
login local
transport input ssh

«Passwords and private credentials are not included in this repository.»

✅ Verification

The configuration was verified using Cisco IOS "show" commands, including:

show running-config
show ip interface brief
show interfaces

🎥 Video Demonstration

Basic Device Configuration Lab

Video demonstration will be linked here.

🧠 What I Learned

This lab provided practical experience with the initial configuration and securing of a Cisco switch. It also reinforced the use of Cisco IOS command modes, configuration commands, SSH, and verification commands.

📌 Next Lab

VLAN Configuration → Inter-VLAN Routing → Layer 3 Switching