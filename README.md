# HP-Elitebook-830-G6-Hackintosh
- Running MacOS from Catalina (10.15.1), it should work for other HP Elitebook 8xx Gx with relevant specs.
![Screen Shot 2021-09-06 at 13 33 04](https://user-images.githubusercontent.com/38579777/132171534-dbd9e851-36cd-40c1-9675-9a0c189e4e0f.png)

# Basic Information
- Intel i5-8265U with UHD 620
- 16 GB of RAM (2 slots 8/8)
- Intel Wi-Fi AC9560

# What Works
- Speakers / Headphones output, Mic input
- Trackpad
- Cabled internet
- WebCam
- Wi-Fi
- Bluetooth
- Facetime, Imess, iCloud sync
- Vault can be turned on for installing company's profiles to pass checking device to install intune portal (Outlook, Teams)

# SMBIOS
- I added it for you already. No change needed.

# How to use:
- Make bootable Catalina USB
- Place my EFI into EFI partition on the USB
- Bios settings: Fastboot, Vtx, Vtd, Wake on USB, Lan are switched OFF. Set to 64-512MB
- Boot with USB and install. It will take 15-30mins depending on your hardware. 
- After installation, mount USB to copy EFI folder to place it into EFI of your Catalina EFI partition. If not, you will need to boot with USB in order to start the OSX.
- Post-installtion EFI, please ping me.

# Buy me a coffee! 
- It took me a motnh to work on this laptop to eventually release it for you. If it works for you and helps you save your time.
- Let buy me a coffe to cheer!
- https://www.buymeacoffee.com/stevedat
- https://nhantien.momo.vn/github/50000
