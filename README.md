# HP-Elitebook-830-G6-Hackintosh
HP Elitebook 830 G6 running MacOS from Catalina (10.15.1)
![Screen Shot 2021-09-06 at 13 33 04](https://user-images.githubusercontent.com/38579777/132171534-dbd9e851-36cd-40c1-9675-9a0c189e4e0f.png)

# Basic Information
- Bios Version: R70 Ver. 01.05.03 04/27/2020 (Other not tested)
- Intel i5-8265U with UHD 620
- 16 GB of RAM (2 slots 8/8)
- Intel Wi-Fi AC9560

# What Works
- CPU and iGPU
- Speakers / Headphones output, Mic input
- Trackpad 
- LAN / Ethernet
- WebCam
- Wi-Fi (replace with airportitlwm after installation)

# Need patching
- Internal Mic
- Bluetooth

# SMBIOS
- I added it for you already. No change needed.

# How to use:
- Make bootable Catalina USB
- Place my EFI into EFI partition on the USB
- Bios settings: Fastboot, Vtx, Vtd, Wake on USB, Lan are switched OFF. Set to 64-512MB
- Boot with USB and install. It will take 15-30mins depending on your hardware. 
- After installation, mount USB to copy EFI folder to place it into EFI of your Catalina EFI partition. If not, you will need to boot with USB in order to start the OSX.

# Buy me a coffee! 
It took me a motnh to work on this laptop to eventually release it for you. If it works for you and helps you save your time.
Let buy me a coffe to cheer!
                    buymeacoffee.com/stevedat                
