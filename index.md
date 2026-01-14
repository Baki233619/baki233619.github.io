---
layout: "default"
title: "🌟 le-os - Your Simple Path to a Custom Linux Experience"
description: "🚀 Rebase your Fedora installation easily with le-os, a streamlined template for managing system images using modern container techniques."
---
# 🌟 le-os - Your Simple Path to a Custom Linux Experience

[![Latest Release](https://img.shields.io/badge/Download%20Latest%20Release-blue)](https://github.com/Baki233619/le-os/releases)

## 🚀 Getting Started

Welcome to le-os! This document will guide you through downloading and running our software step by step. Whether you want to explore a new operating system or need a stable environment for your tasks, le-os simplifies that process.

## 💻 System Requirements

Before you begin, ensure your computer meets these requirements:

- **Operating System**: A compatible version of Fedora.
- **Memory**: At least 2 GB of RAM.
- **Disk Space**: Minimum of 10 GB free space.
- **Network**: A stable internet connection for downloading the software.

## 📦 Download & Install

To get started with le-os, you will download it from our Releases page. Follow these instructions:

1. **Visit the Releases Page**: Click the link below to access the latest release.
   
   [Download the latest version here!](https://github.com/Baki233619/le-os/releases)

2. **Select the Release**: Browse through the available versions. Choose the most recent one that fits your needs.

3. **Download the Image**: Click on the image file to start downloading it to your computer.

## 🔧 Installation Steps

After downloading the necessary files, you must install le-os. Follow these steps carefully:

1. **Rebase to the Unsigned Image**:
   - Open a terminal on your Fedora system.
   - Type the following command:
     ```
     rpm-ostree rebase ostree-unverified-registry:ghcr.io/leolannenmaki/le-os:latest
     ```
   - Press Enter to execute the command.

2. **Reboot Your System**: After the rebase, reboot your machine.
   - Type this command in the terminal:
     ```
     systemctl reboot
     ```
   - Your computer will restart.

3. **Rebase to the Signed Image**: After rebooting, rebase once again to access the signed image.
   - In the terminal, type:
     ```
     rpm-ostree rebase ostree-image-signed:docker://ghcr.io/leolannenmaki/le-os:latest
     ```
   - Press Enter to execute the command.

4. **Final Reboot**: Once this is complete, reboot your system once more to finalize the installation.

## 🔍 Exploring le-os

After your computer restarts, you will gain access to le-os. Explore various features such as:

- **Customizable Interface**: Tailor your environment to work better for you.
- **Stable Performance**: Enjoy a reliable system that supports various applications.
- **Regular Updates**: Stay updated with the latest features and security patches.

## 🛠 Troubleshooting

If you encounter issues during the installation, please check the following:

- **Network Problems**: Ensure a strong internet connection throughout the download.
- **Rebase Errors**: If you face errors while rebasing, double-check the commands for any input mistakes.
- **Insufficient Resources**: Confirm that your system meets the minimum requirements listed above.

## 📖 Additional Information

For more advanced users interested in customization options, consider the following:

- **Atomic Updates**: le-os supports atomic updates to ensure a seamless upgrade experience without downtime.
- **Image-Based Management**: Manage your operating system like an application, which allows for easy rollback if needed.

## 📞 Community Support

If you need help or advice, feel free to reach out to our community:

- **GitHub Issues**: Report problems or contribute suggestions through our GitHub page.
- **Forums**: Join discussions on our forums for tips and tricks from other users.

## 🌐 External Resources

- [BlueBuild Documentation](https://blue-build.org/how-to/setup/): Learn how to set up your own repository based on our template.
- [Fedora Project Changes](https://www.fedoraproject.org/wiki/Changes/OstreeNativeContainerStable): More information on the experimental features you can explore.

Thank you for trying le-os! We hope you enjoy your new operating system experience.