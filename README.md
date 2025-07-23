# Linux Mint Installation Guide

A complete step-by-step guide to install **Linux Mint** (Cinnamon, MATE, or Xfce editions) on your computer.

---

## System Requirements

| Component    | Minimum            | Recommended        |
|--------------|--------------------|--------------------|
| RAM          | 2 GB               | 4 GB or more       |
| Disk Space   | 20 GB              | 100 GB or more     |
| Architecture | 64-bit             | 64-bit             |

---

## 1. Download Linux Mint ISO

- Visit the official [Linux Mint Download Page](https://linuxmint.com/download.php)
- Choose:
  - **Edition**: Cinnamon (default), MATE, or Xfce
  - **Architecture**: 64-bit
- Optionally verify the ISO using checksums or signatures

---

## 2. Create Bootable USB

- Use one of the following tools:
  - [Rufus](https://rufus.ie/) – Windows
  - [balenaEtcher](https://etcher.io/) – Windows/macOS/Linux
  - [Ventoy](https://www.ventoy.net/) – Multi-ISO USB boot
  - Or use the `dd` command on Linux

Note: All data on the USB will be erased.

---

## 3. Boot from USB

1. Insert the USB drive into your computer
2. Reboot and press `F2`, `F10`, `DEL`, or `ESC` to open the boot menu
3. Choose the USB drive
4. Select **Start Linux Mint**

---

## 4. Try Linux Mint (Live Mode)

- Test your hardware: internet, display, sound, touchpad
- If everything works, double-click **Install Linux Mint**

---

## 5. Install Linux Mint

### Language and Region
- Choose your preferred language and keyboard layout

### Network
- Connect to Wi-Fi or Ethernet

### Installation Type
- Choose one of the following:
  - **Erase disk and install Linux Mint** (wipes entire disk)
  - **Install alongside existing OS** (dual boot)
  - **Something else** (manual partitioning)

### Automatic Partitioning
If "Erase disk" is selected:
- `/` (root) for OS and files
- `swap` for memory overflow (optional)
- `/home` for personal files (optional)

---

## 6. Final Setup

- Set your timezone
- Create a username and password
- Review settings and click **Install Now**

---

## 7. Restart

- When prompted, click **Restart Now**
- Remove USB when asked

---

## 8. First Boot

- Login using your credentials
- Linux Mint is ready to use

---

## 9. Post-Installation Checklist

### Update the System
```bash
sudo apt update && sudo apt upgrade -y
```
