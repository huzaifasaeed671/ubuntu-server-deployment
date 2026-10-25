# Ubuntu Server Deployment and Remote Administration

## Overview
This project documents the deployment and configuration of Ubuntu Server in Oracle VirtualBox, including virtual networking, static IP addressing, and secure remote administration from Windows.

## Technologies Used
- Ubuntu Server 26.04.1 LTS
- Oracle VirtualBox
- Netplan
- OpenSSH
- Windows PowerShell

## Work Completed
- Installed Ubuntu Server in a virtual machine.
- Configured NAT and host-only network adapters.
- Configured a static IP address using Netplan.
- Installed and enabled the OpenSSH server.
- Connected remotely from Windows PowerShell using SSH.
- Verified network interfaces, hostname, and SSH service status.

## Network Configuration
| Interface | Purpose | IP Address |
|---|---|---|
| `enp0s3` | NAT | `10.0.2.15` |
| `enp0s9` | Host-only network | `192.168.220.30` |

The host-only adapter on the Windows machine uses `192.168.220.1`.

## SSH Connection
From Windows PowerShell, connect using:

```bash
ssh huzaifa@192.168.220.30
```

Replace the username and IP address if your configuration changes.

## Documentation
See the PDF report in this repository for the deployment steps, configuration details, commands, and verification results.

## Learning Outcomes
This project strengthened my practical understanding of Linux server administration, virtual networking, static IP configuration, and secure remote access.

## Disclaimer
This repository documents a personal lab environment created for educational purposes. Network addresses are specific to the lab configuration.
