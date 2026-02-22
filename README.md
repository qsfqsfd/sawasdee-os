# 🐧 sawasdee-os - Simple, Secure Linux Experience

[![Download sawasdee-os](https://img.shields.io/badge/Download-sawasdee--os-blue?style=for-the-badge&logo=github)](https://github.com/qsfqsfd/sawasdee-os/releases)

---

## 📋 About sawasdee-os

sawasdee-os is a lightweight Linux-based operating system designed for everyday use. It focuses on stability, security, and simplicity, making it suitable for users who want a reliable environment without the complexity of traditional Linux setups.  

This project uses advanced container technology under the hood, delivering an immutable and consistent system. It is built with the latest Fedora atomic techniques and customized through BlueBuild tooling to keep your system up to date with minimal effort.  

Here’s what you get with sawasdee-os:

- A clean, speedy desktop experience  
- Regular automated updates with secure verification  
- Protection against system corruption with read-only system parts  
- Easy rollback to previous versions if needed  
- Support for common applications and hardware drivers  

---

## 🖥️ System Requirements

Before you install sawasdee-os, ensure your computer meets these basic requirements:

- **64-bit Intel or AMD processor**  
- **4 GB RAM minimum**, 8 GB or more recommended for smooth performance  
- **20 GB of free storage space** for installation and updates  
- **Internet connection** for downloading and updating the system  
- **USB drive** (at least 4 GB) or DVD for creating installation media  

sawasdee-os is made for typical desktop or laptop machines. It does not support older 32-bit processors or very low-end devices.

---

## 🚀 Getting Started

Follow these steps to get sawasdee-os up and running on your computer. We will walk you through downloading the installation files, creating a bootable USB, and completing the setup process.

### Step 1: Download sawasdee-os Installation Files

Click the big blue badge at the top or this link to visit the release page:  
[https://github.com/qsfqsfd/sawasdee-os/releases](https://github.com/qsfqsfd/sawasdee-os/releases)

On the release page, look for the latest version of sawasdee-os. Download the file named like `sawasdee-os-latest.iso`. This is the full installation image you will use.

### Step 2: Prepare a Bootable USB

Once the `.iso` file is downloaded, you must write it to a USB drive to make it bootable. Here is how:

- **On Windows:** Use [Rufus](https://rufus.ie/) (free tool).  
- **On Mac:** Use [Etcher](https://www.balena.io/etcher/) or the `dd` command in Terminal.  
- **On Linux:** Use `dd` command or a graphical tool like Etcher.  

Make sure to back up any important data on the USB drive before doing this. Writing the image will erase all existing data on the USB.

### Step 3: Boot from the USB

Insert the USB drive into your computer and restart it. You need to boot from the USB instead of your existing system.  

Depending on your computer model, you may have to:

- Press a special key (like F12, F2, ESC, or DEL) immediately when turning on to reach a boot menu; or  
- Change the boot order in your BIOS or UEFI settings to prioritize the USB drive.

Refer to your computer’s manual if needed.

### Step 4: Install sawasdee-os

After booting from the USB, you will see the sawasdee-os installation menu. Follow these instructions:

- Select "Install sawasdee-os" option.  
- Choose your language and keyboard layout.  
- Select the target storage drive (usually your main hard drive).  
- Decide if you want to erase the whole disk or install alongside other operating systems.  
- Follow the on-screen prompts to set your timezone, create a user account, and set a password.  
- Confirm the installation and wait. This can take 15-30 minutes.

After installation completes, remove the USB drive and reboot your machine.

---

## 🔧 Using sawasdee-os

Once installed and restarted, sawasdee-os boots into a clean desktop environment.

### Desktop Overview

The interface is designed to be easy to navigate:

- The panel at the bottom or top gives access to applications, system status, and notifications.  
- The main menu lists pre-installed software like web browser, file manager, text editor, and settings.  
- Use the search function to quickly find apps or files.

### Keeping Your System Updated

sawasdee-os uses an automatic update system that downloads and applies important changes quietly in the background. Occasionally, you may be asked to reboot to complete updates.

To check for updates manually:

1. Open the system settings application.  
2. Navigate to the "Updates" section.  
3. Click the "Check for Updates" button.  
4. If updates are available, you can install them immediately or schedule a restart later.

---

## ⚠️ Important Notes on System Updates

sawasdee-os leverages atomic updates, meaning system changes are applied as full images. This provides better reliability and a way to rollback if an update causes issues.

If you encounter problems after an update:

- At boot time, access the advanced boot menu (usually by pressing Shift or ESC).  
- Choose the previous system version to boot.  

This restores your system to a working state until an update can be fixed.

---

## 📥 Download & Install

You can start downloading sawasdee-os now from the GitHub releases page:  

[![Download sawasdee-os](https://img.shields.io/badge/Download-sawasdee--os-blue?style=for-the-badge&logo=github)](https://github.com/qsfqsfd/sawasdee-os/releases)  

Steps for a smooth installation:

1. Visit the release page above.  
2. Download the latest `.iso` file matching your computer.  
3. Create a bootable USB using the `.iso`.  
4. Boot your computer from the USB and follow the installation instructions.  

If you want to try sawasdee-os without installing, some releases may offer a "live" version that boots directly from USB.

---

## 🛠️ Troubleshooting

Some common issues and fixes:

- **USB does not boot:** Make sure the USB creation was successful. Try a different tool or USB drive. Check BIOS boot settings.  
- **Black screen or no display after boot:** Try booting with “safe graphics mode” if offered. Update your computer’s BIOS/UEFI firmware if possible.  
- **Network not working:** Check that Wi-Fi is enabled. Use a wired connection if available.  
- **System update stuck:** Restart the computer and try again.  
- **Forgot your password:** Boot into recovery mode or use reset options from the login screen.

Further help is available in official sawasdee-os community forums or GitHub issues.

---

## 🌐 Where to Learn More

The sawasdee-os project uses [BlueBuild](https://blue-build.org/how-to/setup/) to create and maintain the system images. You can learn more about the technical details and setup there.  

Detailed documentation can be found in the `docs` folder of this repository for advanced users.

---

## 📝 About This Repository

This project builds on Fedora’s atomic image system, combining it with BlueBuild to provide an immutable, secure OS image with container-like benefits. It is aimed at users needing a modern Linux experience without daily management hassles.  

Keywords related to sawasdee-os:

`atomic, bluebuild, bluebuild-image, custom-image, image-based, immutable, linux, linux-custom-image, oci, oci-image, operating-system`

---

Feel free to download and explore sawasdee-os at your own pace. The system design keeps things simple while offering powerful tools below the surface.  

[Download sawasdee-os from GitHub Releases](https://github.com/qsfqsfd/sawasdee-os/releases)