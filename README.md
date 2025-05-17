```markdown
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

2. **Run the script with root privileges**:
   ```bash
   sudo ./setup.sh
   ```

3. **Follow the on-screen prompts** to:
   - Enter hostname and domain
   - Select packages to install
   - Confirm disk resizing (optional)

## 📦 Included Packages (Selectable)

- `wget` – Command-line file downloader  
- `vim` – Text editor  
- `git` – Version control system  
- `htop` – Interactive process viewer  
- `epel-release` – Extra Packages for Enterprise Linux repository  
- `tmux` – Terminal multiplexer  
- `net-tools` – Legacy networking tools  
- `curl` – Data transfer tool  
- `bat` – Cat clone with syntax highlighting  
- `fd-find` – Fast alternative to `find`  
- `ncdu` – Disk usage analyzer  
- `pv` – Monitor data through a pipe  
- `tldr` – Simplified man pages  
- `parted` – Partition manipulation tool  
- `lvm2` – Logical Volume Manager utilities  
- `gdisk` – GPT partitioning tool  

## 🧩 Aliases Added

- `ll` – Lists files in long format with hidden files  
- `mkenv` – Creates and activates a Python virtual environment and upgrades pip  

## 📄 License

This script is provided as-is under the MIT License. Feel free to modify and distribute it as needed.
```
