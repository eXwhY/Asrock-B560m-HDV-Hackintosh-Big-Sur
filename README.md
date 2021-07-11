# Asrock-B560m-HDV-Hackintosh-Big-Sur


SMBIOS: iMac20,1
CPU: Intel i5-10400
Motherboard: Asrock B560M HDV
GPU: UHD 630
RAM: 16GB DDR4 3200 Mhz
Wifi & Bluetooth: BCM94352HMB / DW1550 SSD (disabled in EFI while working on framebuffers):
OS: macOS Big Sur 11.4
OC Version: 0.7.0

Issue: All Displays do not work - VGA, DVI and HDMI .  I used flag -igfxvesa to finish the installation, and then installed VNC to work on the framebufferes through another Hack.  Unfortunately, I have had no luck.  I have created a config.plist for a dGPU however I do not have access one.  Feel free to test.

Until I have access to dGPU or I manage to get the iGPU to work, I will not be testing other components e.g. wifi/BT, sound (ports and HDMI), sleep and USB Patching. 

This repo is for personal use only. No support is given but welcome to contribute.
