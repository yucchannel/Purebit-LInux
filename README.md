# Purebit OS

**Purebit** is a custom Debian-based Linux distribution created using `live-build`.  
It features a lightweight XFCE desktop environment and is optimized for fast boot and user customization.

## Features

- Based on Debian stable
- XFCE desktop (lightweight and fast)
- Easy to build using `live-build`
- Ready for QEMU / VirtualBox

## Build Instructions

```bash
sudo apt install live-build
git clone https://github.com/yucchannel/Purebit-LInux.git
cd Purebit
sudo lb config
sudo lb build
