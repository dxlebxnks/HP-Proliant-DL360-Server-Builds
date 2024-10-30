# HP ProLiant DL360 Server Build with Windows Server 2022

## Project Overview

This project documents the setup and configuration of an HP ProLiant DL360 server, including RAID 1 configuration and installation of Windows Server 2022. This setup provides a fault-tolerant environment with data redundancy.

## Objectives

- Configure RAID 1 for data mirroring and reliability.
- Install and update Windows Server 2022.
- Ensure proper driver and firmware compatibility for optimal performance.

## Table of Contents

1. [Project Overview](#project-overview)
2. [Objectives](#objectives)
3. [Requirements](#requirements)
4. [Server Configuration](#server-configuration)
5. [Windows Server Installation](#windows-server-installation)
6. [Testing and Validation](#testing-and-validation)
7. [Additional Documentation](#additional-documentation)

## Requirements

- **Hardware**: HP ProLiant DL360 server
- **Operating System**: Windows Server 2022
- **Tools**: HP Smart Array Utility, RAID configuration utilities

## Server Configuration

### Step 1: Access HP Smart Array Utility
1. Boot the server and enter the HP Smart Array configuration.
2. Select two identical drives and configure RAID 1 for data mirroring.

### Step 2: Configure RAID Array
1. In the HP Smart Array utility, select drives for RAID 1.
2. Apply necessary settings for redundancy.

## Windows Server Installation

1. Boot the server from a Windows Server 2022 installation media.
2. Follow the installation prompts to install Windows Server on the RAID-configured drives.
3. After installation, update the OS to the latest version and apply patches.

## Testing and Validation

- Verify the RAID 1 setup by simulating drive failure.
- Test the OS installation, ensuring stability and performance.

## Additional Documentation

- [Detailed RAID Configuration](docs/RAID-Configuration.md)
- [Windows Server Update and Patch Process](docs/Update-Patching.md)
