# System Setup and Configuration Script

This Bash script automates the setup and configuration of a Linux system using `dialog` for interactive user input. It is designed to streamline initial system setup tasks such as updating packages, configuring the hostname, installing essential tools, and managing disk partitions.

## 📋 Features

- System update and upgrade
- Interactive hostname and domain configuration
- Package selection and installation via checklist
- Hostname and `/etc/hosts` configuration
- Optional disk partition resizing and filesystem extension
- Useful shell aliases added to `.bashrc`
- Summary display of all performed actions

## 🛠️ Prerequisites

- A Linux system with `dnf` package manager (e.g., Fedora, RHEL, CentOS)
- `dialog` installed (`sudo dnf install -y dialog`)
- Root privileges to execute system-level changes

## 🚀 Usage

1. **Make the script executable**:
   ```bash
   chmod +x setup.sh
   ```
