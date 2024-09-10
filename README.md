# 🚀 Fastfetch Custom Configuration

Welcome to a stunning configuration for [Fastfetch](https://github.com/fastfetch-cli/fastfetch), the ultimate system information tool that turns your terminal into a work of art!

## 📋 Table of Contents

1. [Features](#-features)
2. [Preview](#-preview)
3. [Installation](#️-installation)
4. [Usage](#-usage)
5. [Customization](#-customization)
6. [Quick Download](#-quick-download)
7. [License](#-license)

## ✨ Features

- 🖥️ Comprehensive System Information (OS, Kernel, Uptime, Packages)
- 🎨 Detailed Desktop Environment Showcase (DE, WM, Theme, Resolution, Shell, Font)
- 💻 In-depth Hardware Specifications (CPU, GPU, Memory, Disk usage)
- 🌈 Vibrant Color Palette Display

## 👀 Preview

![Fastfetch-preview](https://github.com/user-attachments/assets/f249aabf-6850-4c45-938e-2a364c64b5ea)

## 🛠️ Installation

### 1. Install Fastfetch:

| System | Command |
|--------|---------|
| Arch Linux | `sudo pacman -S fastfetch` |
| Ubuntu/Debian | `sudo add-apt-repository ppa:fastfetch-devs/fastfetch && sudo apt update && sudo apt install fastfetch` |
| macOS (Homebrew) | `brew install fastfetch` |
| Windows (Scoop) | `scoop install fastfetch` |
| Windows (Winget) | `winget install fastfetch` |

For other systems, refer to the [official installation guide](https://github.com/fastfetch-cli/fastfetch#installation).

### 2. Set up the configuration:

| System | Command |
|--------|---------|
| Linux/macOS | `mkdir -p ~/.config/fastfetch && wget -O ~/.config/fastfetch/config.jsonc https://raw.githubusercontent.com/dacrab/fastfetch-config/main/config.jsonc` |
| Windows | ```New-Item -ItemType Directory -Force -Path "$env:APPDATA\fastfetch" ; Invoke-WebRequest -Uri "https://raw.githubusercontent.com/dacrab/fastfetch-config/main/config.jsonc" -OutFile "$env:APPDATA\fastfetch\config.jsonc"``` |

## 🚀 Usage

Simply type `fastfetch` in your terminal to display your system information in a beautifully formatted layout.

## 🎨 Customization

To tailor the display to your preferences:

1. Open the `config.jsonc` file in your preferred text editor.
2. Modify the settings according to your needs.
3. Save the file and run `fastfetch` to see your changes.

For detailed customization options and syntax, refer to the [Fastfetch documentation](https://github.com/fastfetch-cli/fastfetch/wiki/Configuration).

## 📥 Quick Download

For quick access to the configuration file:

[⬇️ Download config.jsonc](https://raw.githubusercontent.com/dacrab/fastfetch-config/main/config.jsonc)

## 📜 License

This configuration is available under the MIT License. See the [LICENSE](LICENSE) file for more details.

Enjoy your beautifully displayed system information! 🎉
