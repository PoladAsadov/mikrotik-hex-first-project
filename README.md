# mikrotik-hex-first-project
Backup configuration file of my MikroTik hEX router for my first paid networking project. I made this setup for the Restoraunt network. This backup includes interface setup, IP addresses, DHCP settings, and basic firewall rules.
# MikroTik First Project – RouterOS Backup

This repository contains the full binary backup of my MikroTik hEX router, exported as part of my network configuration learning process.

## 📁 File

- `Backup_FirstProject.backup`:  
  A complete RouterOS binary backup created using Winbox. This file includes:
  - Interface setup
  - IP address assignments
  - DHCP client/server settings
  - Bridge and VLAN (if configured)
  - User credentials (encrypted)
  - Firewall and NAT rules
  - System identity and DNS settings

## 💡 Notes

- This is a `.backup` file, which can be **restored only** on the same or very similar MikroTik device.
- For a readable version of the configuration, use:
  ```shell
  /export file=config
