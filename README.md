# Hackintosh EFI Configuration

This repository contains configurations for Hackintosh EFI partitions tailored for different versions of macOS. Please make sure to carefully choose the correct EFI folder for your specific macOS version to ensure successful booting.

## Table of Contents
- [Description](#description)
- [Folders](#folders)
- [Warning](#warning)
- [SMBIOS Configuration](#smbios-configuration)
- [PC Specifications](#pc-specifications)
- [Compatibility Table](#compatibility-table)
- [Quick Start](#quick-start)
- [License](#license)
- [Contribution](#contribution)

## Description

Provide a brief overview of your Hackintosh configuration and its purpose. This configuration is designed specifically for compatibility with **NUC7i3DNB** hardware.

## Folders

- **EFI Backup (0.7.5)**: This folder contains the EFI configuration for **macOS Big Sur**.
- **EFI (1.0.5)**: This folder contains the EFI configuration for **macOS Ventura and newer**.

## Warning

**IMPORTANT:** 
- Please select the correct EFI folder based on your macOS version. Using the wrong EFI configuration may lead to boot issues or instability.
- **Note:** `EFI (1.0.5)` has known issues with Power Management, which may affect system performance and battery life. Use with caution.

### Functionality Notes:
- For **macOS Big Sur**, use the `EFI Backup (0.7.5)` folder.
- For **macOS Ventura or newer**, use the `EFI (1.0.5)` folder, understanding the potential Power Management issues.

## SMBIOS Configuration

To ensure compatible system properties, you should set your SMBIOS to **Macmini7,1** for better stability and performance.

## PC Specifications

This EFI configuration is compatible with the following hardware:

- **Model**: NUC7i3DNB
- **Processor**: Intel Core i3-7100U
- **Graphics**: Intel HD Graphics 620
- **RAM**: 8GB DDR4
- **Storage**: M.2 SSD

## Compatibility Table

| Features              | EFI Backup (0.7.5) | EFI (1.0.5)              |
|-----------------------|---------------------|---------------------------|
| Sleep/Wake            | Work                | Work                      |
| Airdrop/Handoff       | Work                | Work                      |
| Power Management       | Works correctly     | Known issues              |

## Quick Start

1. **Backup Your Current EFI**: Make sure to back up your existing EFI configuration before making any changes.
   
2. **Choose the Correct EFI**:
   - Navigate to either the `EFI Backup (0.7.5)` or `EFI (1.0.5)` folder based on your macOS version.
   - Copy the contents of the chosen folder.

3. **Replace the Existing EFI Files**:
   - Open your mounted EFI partition (generally available at `/Volumes/EFI` on macOS).
   - Replace the current contents in the `EFI` folder with your copied files.

4. **Reboot Your System**: After replacing the files, reboot to apply your new EFI configuration.

## Contribution

Contributions and enhancements are welcome! If you have improvements, please feel free to submit a Pull Request.

---

If you have any questions or require assistance, please don't hesitate to reach out!