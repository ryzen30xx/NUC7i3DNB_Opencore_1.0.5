# Project Title

Brief description of your project.

## Table of Contents
- [Description](#description)
- [Folders](#folders)
- [Warning](#warning)
- [SMBIOS Configuration](#smbios-configuration)
- [Quick Start](#quick-start)
- [License](#license)
- [Contribution](#contribution)

## Description

Provide a brief overview of your Hackintosh configuration and its purpose.

## Folders

- **EFI Backup (0.7.5)**: This folder contains the EFI configuration for **macOS Big Sur**.
- **EFI (1.0.5)**: This folder contains the EFI configuration for **macOS Ventura and newer**.

## Warning

**IMPORTANT:** Please select the correct EFI folder based on your macOS version. Using the wrong EFI configuration may lead to boot issues or instability.

- For **macOS Big Sur**, use the `EFI Backup (0.7.5)` folder.
- For **macOS Ventura or newer**, use the `EFI (1.0.5)` folder.

## SMBIOS Configuration

To ensure compatible system properties, you should set your SMBIOS to **Macmini7,1** for better stability and performance.

## Quick Start

1. **Backup Your Current EFI**: Make sure to back up your existing EFI configuration before making any changes.
   
2. **Choose the Correct EFI**:
   - Navigate to either the `EFI Backup (0.7.5)` or `EFI (1.0.5)` folder based on your macOS version.
   - Copy the contents of the chosen folder.

3. **Replace the Existing EFI Files**:
   - Open your mounted EFI partition (generally available at `/Volumes/EFI` on macOS).
   - Replace the current contents in the `EFI` folder with your copied files.

4. **Reboot Your System**: After replacing the files, reboot to apply your new EFI configuration.
