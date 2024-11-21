# WIP
- Target : Sonoma
- Opencore Debug : 1.0.2
  - Kexts
    - [AirportItlwm_v2.3.0_stable_Sonoma14.4.kext.zip](https://github.com/OpenIntelWireless/itlwm/releases/download/v2.3.0/AirportItlwm_v2.3.0_stable_Sonoma14.4.kext.zip)
    - [AppleALC.kext-1.9.3-Debug](https://github.com/dortania/build-repo/releases/download/AppleALC-dfeb479/AppleALC-1.9.3-DEBUG.zip)
    - [Lilu-1.7.0-DEBUG](https://github.com/dortania/build-repo/releases/download/Lilu-42326bd/Lilu-1.7.0-DEBUG.zip)
    - [USBToolBox.kext & UTBMap.kext](https://github.com/USBToolBox/tool/releases/tag/0.2)
    - [VirtualSMC-1.3.4-DEBUG](https://github.com/dortania/build-repo/releases/download/VirtualSMC-c6da306/VirtualSMC-1.3.4-DEBUG.zip)
    - [VoodooPS2Controller-2.3.6-DEBUG](https://github.com/dortania/build-repo/releases/download/VoodooPS2-80e0171/VoodooPS2Controller-2.3.6-DEBUG.zip)
    - [WhateverGreen-1.6.9-DEBUG](https://github.com/dortania/build-repo/releases/download/WhateverGreen-9818f96/WhateverGreen-1.6.9-DEBUG.zip)
   
## Status
🟢 Success install
> ~~when install proccess enable `AirportItlwm_v2.3.0_stable_Sonoma14.4.kext.zip`, but when booting first after install please disable, or will kernel panic.~~
<strong>Please set SecureBootModel Disabled when installing process.</strong>

🟡 Audio work using boot arg for now

🟢 GPU

> ~~still need use `-igfxvesa` for correctly boot~~

🔴 Webcam

🟢 Shutdown

🔴 Sleep 

> cannot wake from sleap

🔴 Brightnes keyboard

🔴 Bluetooth

🟢 Wifi

> ~~enable `AirportItlwm_v2.3.0_stable_Sonoma14.4.kext`, using `itlwm_v2.3.0_stable.kext` when installed and application [HeliPort](https://github.com/OpenIntelWireless/HeliPort)~~

🔴 Battery

🟢 Touchscreen

🔴 Another input like click left and right extra, and dot pointer

🔵 ETC...

## Next
- Try to fix 
  - ~~shutdown issue~~
  - accelerated graphic
  - ~~Wifi~~
  - Bluetooth
  - Sleep

## Thanks
[Acidanthera](https://github.com/acidanthera "Acidanthera")

[Help form reddit members](https://www.reddit.com/r/hackintosh/comments/1gr2dbl/can_anyone_help_with_tecra_x40f_laptop/ "Help form reddit members")
