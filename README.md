Pixmox - Proxmox for the Raspberry Pi
===

Pimox is a port of Proxmox to the Raspberry Pi allowing you to build a Proxmox cluster of Rapberry Pi's or even a hybrid cluster of Pis and x86 hardware.

Requirements
---
* Raspberry Pi 4
* Pre-installed Debian based 64-bit OS ___(not 32-bit)___

Setup
---
1. sudo -s
2. curl https://gitlab.com/minkebox/pimox/-/raw/master/dev/KEY.gpg | apt-key add -
3. curl https://gitlab.com/minkebox/pimox/-/raw/master/dev/pimox.list > /etc/apt/sources.list.d/pimox.list
4. apt update
5. apt install pve-manager

Notes
---
This repo just contains the precompiled debian packages. The original Proxmox sources can be found at git.proxmox.com
