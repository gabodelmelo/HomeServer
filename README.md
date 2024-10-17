# Home Server Project: Repurposing Old Hardware for Modern Needs

## Overview

In this project, I transformed an old PC and a Western Digital NAS into a fully functional home server. The goal was to centralize storage, manage media, automate downloads, handle backups, and enable secure remote access. Using **Ubuntu Server** and **Docker**, I deployed multiple applications to manage multimedia streaming, automate content downloads, and even provide password management, all while ensuring remote access security.
![imagen](https://github.com/user-attachments/assets/1d28f6ae-e401-4a1b-950e-0d22be02b3ba)

### Key Objectives:

- Repurpose existing hardware to create a cost-effective home server.
- Centralize file storage, media streaming, and backups with NAS and Docker applications.
- Automate downloads and backup processes directly to the NAS via network shares.
- Set up secure remote access to home network resources via VPN.

---

## Steps Taken

### Hardware and Initial Setup

- **PC Specs**: 24GB RAM, Intel i7, and a 250GB SSD for the operating system.
- **NAS**: Western Digital MyCloud EX2 with 8TB storage (two 4TB drives) for media storage and backups.
- **Operating System**: Installed **Ubuntu Server** on the SSD to ensure optimal performance and stability.

### Installing and Configuring CASAOS

I installed **CASAOS**, a web-based interface for managing Docker containers. This simplified the management of my server, transforming it into a flexible, NAS-like environment.

### Deployed Docker Applications

- **Jellyfin**: Set up as a media streaming server for seamless access to movies, music, and TV shows across all devices.
- **qBittorrent**: Automated content downloads, with all downloaded files stored directly on the NAS.
- **Ombi**: Configured for media request management, allowing users to request TV shows or movies, which are then automatically downloaded to the NAS.
- **VaultWarden**: Deployed a self-hosted password manager to store credentials locally, ensuring enhanced security without relying on third-party services.
- **Wireguard**: Set up a VPN to enable secure, remote access to files and media from anywhere.
- **Crafty**: Installed a private Minecraft server, managed through Crafty's web interface for easy control and monitoring.

### Automation of Downloads and Backups

- **Automated Downloads**: All media content downloaded via qBittorrent is saved directly to the NAS, ensuring centralized and organized storage.
- **Automated Backups**: Regular backups of critical server configurations and data are automatically transferred to the NAS for secure storage.

### Additional Custom Scripts

- Set up a **Telegram bot** to receive notifications on system status, alerts, and successful backup completions.
- Developed custom automation scripts to handle routine tasks, including file organization, backups, and updates.

---

## Outcome

The home server now efficiently manages automated downloads, file storage, media streaming, and backups. Through the integration of network shares between the server and the NAS, all downloads and backups are centralized, streamlining data management. Additionally, the system provides secure remote access via VPN, ensuring flexibility and maintaining high performance.

---

## Key Learnings

- Gained hands-on experience with **Docker** for application deployment and management.
- Enhanced skills in automating backups and file sharing over a network.
- Developed expertise in setting up **VPNs** for secure, remote access.
- Strengthened automation capabilities through custom scripts for system maintenance and monitoring.

---
