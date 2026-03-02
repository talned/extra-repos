# Extra Repositories Manager

This repository provides utility scripts to set up and use the Chaotic AUR repository and CachyOS setup scripts for your Linux system. Follow the instructions below to get started.

---

## Table of Contents
- [Getting Started](#getting-started)
- [Chaotic AUR Installation](#chaotic-aur-installation)
- [CachyOS Setup](#cachyos-setup)
- [License](#license)

---

## Getting Started

Before using the scripts, ensure you have the necessary permissions and a compatible Linux distribution (e.g., Arch-based distros).

### Prerequisites

- A terminal application
- `bash` shell installed
- Internet access

---

### Steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/talned/extra-repos.git
   cd extra-repos
   ```

#### Chaotic AUR Installation

The `chaotic-setup` script automatically installs the Chaotic AUR repository on your system.

2. Run the script:
   ```bash
   bash chaotic-setup
   ```

This script will configure your system to use the Chaotic AUR repository for package management.

#### CachyOS Setup

The `cachyos-setup` script is designed for setting up CachyOS.

3. Run the script:
   ```bash
   bash cachyos-setup
   ```

This script will configure your system to use CachyOS Repos.

#### Xlibre setup

The `xlibre-setup` script is designed to add the xlibre binary packages to arch linx

4. Run the script:
   ```bash
   bash xlibre-setup
   ```

this script will configure your pacman to add the xlibre database so you can download the packages.

---

## Keeping Your System Updated

It is essential to regularly update your system to receive the latest patches and features. Follow the guidelines provided below to ensure your system stays up-to-date:

- For **CachyOS**, refer to its repository: [CachyOS/linux-cachyos](https://github.com/CachyOS/linux-cachyos#cachyos-repositories)
- For **Chaotic AUR**, see the official documentation: [Chaotic AUR Docs](https://aur.chaotic.cx/docs)
- For **Xlibre**, refer to its README file: [Xlibre README](https://x11libre.net/repo/arch_based/x86_64/README.html)

---


Enjoy managing your packages with ease!
