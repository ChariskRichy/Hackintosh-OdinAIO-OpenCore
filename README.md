# Hackintosh-OdinAIO-OpenCore
A set of EFI for Odin,with the objective of running hackintosh in your school!Your classmate will be amazed.
## Hardware Information
👋W.I.P.🚧
## What's working
- [x] Bootable macOS(of course!)
- [x] W.I.P
## What's NOT working
- [ ] Coreship Ethernet Network Card(No Proper Kext)
- [ ] The second HDMI display(in Odin Android Console)(I am working on it!)
- [ ] W.I.P
## NOTICE

### Integrated Graphics Device Properties Injection
The built-in monitor is actually HDMI-connected monitor.As for its IGFX Configuration,con1 with busid=0x2 is confirmed to work!While the other one in Odin Android Console may not work at the same time.(Glitches may be occurred!!!)
### Audio adjustment
Due to the defect of Odin Android Smart Screen,you CANNOT adjust the volume through macOS(No HDMI Audio Mixer code support) and Third-party software like Lunar or BetterDisplay(DDS not supported).The only way to adjust volume is its button on the bottom of the screen!
### USB Power issue
Due to weird reason,the USB which is integrated into the Odin device don't work properly sometimes.According to GK,this might be the Power Supply issue.As a result,the macOS will get stuck near boot.efi stage(with the line "LKC").
### Why should I install Hackintosh in MY SCHOOL?!?!
The answer is simple.To Zhuang Bi.

## Contributions
- [Apple](https://www.apple.com) for macOS
- [Team Acidanthera](https://github.com/acidanthera) for OpenCore Bootloader and its powerful Kexts
- [Team Dortania](https://dortania.github.io) for its amazing Guide
- [Team VoodooI2C](https://github.com/VoodooI2C) for its Voodoo Kexts(Touchscreen support)
- [Team OpenIntelWireless](https://github.com/OpenIntelWireless) for Intel Bluetooth and Intel Wireless Kext
- [GoopyKibbles](https://github.com/GoopyKibbles) for the encouragememt and the thinking of the Bluetooth Verification issue
- My teacher and friends
