# Ryzen-OSX
My Personal Hackintosh Setup using macOS 10.13.6 (should work on 10.14 and 10.15 too) and an AMD Ryzen CPU/Chipset

CPU: AMD Ryzen 7 2700X (Overclocked to 4Ghz All-Cores) - You can use any Ryzen Series 1000, 2000 or 3000 CPU without Graphics
Motherboard: Gigabyte B450M DS3H (Rev. 1.0)
RAM: 16 GB DDR4 3000Mhz CL14 (Overclocked) - You can use any Ryzen-compatible RAM, as well as any amount you like
GPU: NVIDIA GTX 970 4GB (ASUS Strix DirectCU II)
SSD: Samsung 970 EVO Plus NVMe 500GB
HDD: 500GB Seagate Barracuda (+ 120 GB SanDISK Cruzer SSD for Windows)

This Setup is completely Silent. I have configuered the Fans to only start spinning when necessary, which they almost never do.

Case and Power-Supply don't matter for OSX, but if you are going to replicate this system I recommend you use at least a 430 or even 500+ Watt Power-Supply and a case that you like.

# What works?

Almost Everything!

this includes:
- iMessage / FaceTime
- iCloud & App Store
- Sleep & Wake functionality
- NVIDIA Graphics (only 10.13 High Sierra)
- full NVMe Speed (3,2+ GB/s transfer speeds, sweeeeeet.)
- LAN
- USB 3

The System is very stable, haven't had a single crash, reboot or anything funky yet. Awesome!

# What doesn't work?

- AirDrop & Handoff (& Sidecar in 10.15) - I don't use it personally (Android Phone - never Use AirDrop on my MacBook Pro), but I might add it sometime in the future. Basically just requires a compatible Bluetooth and Wifi card/dongle and some additional kexts.
- Onboard Audio - will fix it soon! Although I use a Steinberg UR22 USB DAC.
- 32bit Apps tc. - Limited by the OSX Vanilla patches, but 32bit should finally be dying.
- CPU handling - because it isn't supported with AMD CPUs on OSX.

# Files

Kexts:
- AppleALC.kext  -  for internal Audio handling
- Lilu.kext  -  needed for other kexts
- NullCPUPowerManagement  -  to make macOS accept the CPU
