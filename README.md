# Ryzen-OSX
My Personal Hackintosh Setup using macOS Big Sur 11.1 (should work on 10.13, 10.14 and 10.15 too) and an AMD Ryzen CPU/Chipset

CPU: AMD Ryzen 7 2700X (3.6 Ghz Base - 4.15 Ghz Boost) - You can use any Ryzen Series 1000, 2000 or 3000 CPU without Graphics
Motherboard: Gigabyte B450M DS3H (Rev. 1.0)
RAM: 16 GB DDR4 3000Mhz CL16 (Overclocked) - You can use any Ryzen-compatible RAM, as well as any amount you like
GPU: AMD RX 5600 XT 6 GB (Gigabyte - Factory Overclocked)
SSD: Samsung 970 EVO Plus NVMe 500GB
HDD: 500GB Seagate Barracuda (+ 240 GB SanDISK Cruzer SSD for Windows)

This Setup is completely Silent. I have configuered the Fans to only start spinning when necessary, which they almost never do.

Case and Power-Supply don't matter for OSX, but if you are going to replicate this system I recommend you use at least a 430 or even 500+ Watt Power-Supply and a case that you like.

# What works?

Everything!

this includes:
- iMessage / FaceTime - iCloud in General
- Airdrop & Handoff
- iCloud & App Store
- Sleep & Wake functionality
- AMD Graphics
- full NVMe Speed (3,2+ GB/s transfer speeds, sweeeeeet.)
- LAN
- USB 3
- Onboard Audio
- limited AMD CPU Management - with AMD Power Gadget
- Dualboot with Windows
- USB mapped

The System is very stable once correctly booted, haven't had a single crash, reboot or anything funky yet. Awesome!

# What doesn't work?

- 32bit Apps tc. - Limited by the OSX Vanilla patches, but 32bit should finally be dying.
- full CPU handling - because it isn't supported with AMD CPUs on OSX.
- Apps and Executables depending on Intel Specific Libraries/Instruction Sets/Dependencies, e.g. some Waves Audio Plugins

# Files

Kexts:
- AppleALC.kext  -  for internal Audio handling
- Lilu.kext  -  needed for other kexts
- NullCPUPowerManagement  -  to make macOS accept the CPU
todo
