# Windows Server 2025 Installation and Configuration Guide

## Overview

This repository provides a step-by-step tutorial on installing and configuring Windows Server 2025, Microsoft's latest Long-Term Servicing Channel (LTSC) release. The guide covers system requirements, installation procedures, and post-installation configurations to help you set up a secure and efficient server environment.

## Table of Contents

- [System Requirements](#system-requirements)
- [Installation Steps](#installation-steps)
- [Post-Installation Configuration](#post-installation-configuration)
- [Additional Resources](#additional-resources)
- [Contributing](#contributing)
- [License](#license)

## System Requirements

Before installing Windows Server 2025, ensure your hardware meets the following minimum requirements:

- **Processor:** 1.4 GHz 64-bit processor
- **RAM:** 512 MB (2 GB for Server with Desktop Experience installation option)
- **Disk Space:** 32 GB
- **Network:** Gigabit (10/100/1000baseT) Ethernet adapter
- **Other:** DVD drive (if installing from media), UEFI 2.3.1c-based system and firmware that supports secure boot

For detailed requirements, refer to Microsoft's official documentation.

## Installation Steps

1. **Download the ISO:**
   - Visit the [Microsoft Evaluation Center](https://www.microsoft.com/en-us/evalcenter/download-windows-server-2025) to download the Windows Server 2025 ISO file.

2. **Create Bootable Media:**
   - Use tools like Rufus to create a bootable USB drive with the downloaded ISO.

3. **Install Windows Server 2025:**
   - Boot from the USB drive and follow the on-screen instructions to install the server operating system.

For a visual walkthrough, you can refer to the following tutorial:

[![Windows Server 2025 Installation Guide](https://img.youtube.com/vi/-S4HvxtZZDU/0.jpg)](https://www.youtube.com/watch?v=-S4HvxtZZDU)

## Post-Installation Configuration

After installation, perform the following configurations:

- **Set Up Administrator Account:**
  - Create a strong password for the administrator account during the initial setup.

- **Configure Network Settings:**
  - Assign a static IP address and configure DNS settings as per your network requirements.

- **Enable Remote Desktop:**
  - Navigate to System Properties > Remote and enable Remote Desktop for remote management.

- **Install Updates:**
  - Run Windows Update to install the latest security patches and updates.

## Additional Resources

- [What's New in Windows Server 2025](https://learn.microsoft.com/en-us/windows-server/get-started/whats-new-windows-server-2025)
- [Windows Server 2025 Evaluation](https://www.microsoft.com/en-us/evalcenter/download-windows-server-2025)
- [Windows Server 2025 Blog](https://www.microsoft.com/en-us/windows-server/blog/)

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature/YourFeature`.
3. Commit your changes: `git commit -m 'Add YourFeature'`.
4. Push to the branch: `git push origin feature/YourFeature`.
5. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
