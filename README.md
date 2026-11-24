# ghost-recon-advanced-warfighter-2006-deadly-dozen-2001
## Ghost Recon Advanced Warfighter 2006 - Deadly Dozen 2001 Remake
A total conversion that rebuilds *Deadly Dozen* (2001) inside the **Ghost Recon Advanced Warfighter** (2006) engine — Deadly Dozen's WWII squad raids running on GRAW's squad AI, cover system, and PhysX physics.

## Github Treeview
[https://treegit.macosxjs.com/?url=igiteam/ghost-recon-advanced-warfighter-2006-deadly-dozen-2001](https://treegit.macosxjs.com/?url=igiteam/ghost-recon-advanced-warfighter-2006-deadly-dozen-2001)

## Github Tree Api Direct JSON
[https://api.github.com/repos/igiteam/ghost-recon-advanced-warfighter-2006-deadly-dozen-2001/git/trees/main?recursive=1](https://api.github.com/repos/igiteam/ghost-recon-advanced-warfighter-2006-deadly-dozen-2001/git/trees/main?recursive=1)

## Base of the gameplay
[![Deadly Dozen 2001](https://img.youtube.com/vi/aiUNPVVqfdU/maxresdefault.jpg)](https://ytembed.macosxjs.com/?YWlVTlBWVnFmZFU)

[![Tom Clancy's Ghost Recon Advanced Warfighter](https://raw.githubusercontent.com/igiteam/ghost-recon-advanced-warfighter-2006-deadly-dozen-2001/refs/heads/main/graw-ingame.png)](https://ytembed.macosxjs.com/?VmtqR0xxWGxUazQ)

[![Tom Clancy's Ghost Recon Advanced Warfighter](https://raw.githubusercontent.com/igiteam/ghost-recon-advanced-warfighter-2006-deadly-dozen-2001/refs/heads/main/graw-sliding.png)](https://ytembed.macosxjs.com/?OXBET2NJNHd0VVk)

## WS11WineCX20.0.4 (MacOSX Big Sur 32bit)
[WS11WineCX20.0.4.tar.7z](https://github.com/vitor251093/porting-kit-engines/releases/download/wineskin/WS11WineCX20.0.4.tar.7z)

[![wine windows games on macosx](https://raw.githubusercontent.com/igiteam/igi1-macbook-3d-workstation/refs/heads/main/wine-engine-config.png)](https://github.com/igiteam/wine_engines)

---


## Reference Links
[https://archive.org/details/graw-pc](https://archive.org/details/graw-pc)

[https://archive.org/download/ghost-recon-advanced-warfighter-2](https://archive.org/download/ghost-recon-advanced-warfighter-2)

[https://web.archive.org/web/20071201003502/http://www.ghostrecon.net/modder/index.php?option=com_content&task=view&id=25&Itemid=77](https://web.archive.org/web/20071201003502/http://www.ghostrecon.net/modder/index.php?option=com_content&task=view&id=25&Itemid=77)

[https://web.archive.org/web/20071026063324/http://www.ghostrecon.net/files2/index.php?act=category&id=26](https://web.archive.org/web/20071026063324/http://www.ghostrecon.net/files2/index.php?act=category&id=26)

[https://archive.org/details/ghost-recon-advanced-warfighter-2006-deadly-dozen-2001](https://archive.org/details/ghost-recon-advanced-warfighter-2006-deadly-dozen-2001)

[https://archive.org/details/nvidia-apex-sdk-udk](https://archive.org/details/nvidia-apex-sdk-udk)

[https://archive.org/details/nvidia-phys-x-for-autodesk-maya-2017](https://archive.org/details/nvidia-phys-x-for-autodesk-maya-2017)

[![GRAW 2 modo physx extreme](https://img.youtube.com/vi/Bpd211n87YY/hqdefault.jpg)](https://ytembed.macosxjs.com/?QnBkMjExbjg3WVk)

[![GRAW2 Ageia Physx demo 3](https://img.youtube.com/vi/46MustVBcpI/hqdefault.jpg)](https://ytembed.macosxjs.com/?NDZNdXN0VkJjcEk)

[![Ageia Physx](https://github.com/igiteam/ghost-recon-advanced-warfighter-2006-deadly-dozen-2001/blob/main/ageia_physx.jpg?raw=true)](https://github.com/igiteam/ghost-recon-advanced-warfighter-2006-deadly-dozen-2001/blob/main/ageia_physx.jpg?raw=true)

[![Nvidia Physx](https://raw.githubusercontent.com/igiteam/ghost-recon-advanced-warfighter-2006-deadly-dozen-2001/refs/heads/main/nvidia_physx.jpg)](https://raw.githubusercontent.com/igiteam/ghost-recon-advanced-warfighter-2006-deadly-dozen-2001/refs/heads/main/nvidia_physx.jpg)

[![GPU PhysX in Ghost Recon Advanced Warfighter 2](https://img.youtube.com/vi/5KHakdkKQH4/hqdefault.jpg)](https://ytembed.macosxjs.com/?NUtIYWtka0tRSDQ)

here is the legacy driver for physx that specifically mentions getting GRAW 1 to work... 
physx-9-13-0604-legacy-driver/
[https://github.com/igiteam/ghost-recon-advanced-warfighter-2006-deadly-dozen-2001/releases/tag/physx](https://github.com/igiteam/ghost-recon-advanced-warfighter-2006-deadly-dozen-2001/releases/tag/physx)

[https://github.com/igiteam/ghost-recon-advanced-warfighter-2006-deadly-dozen-2001/releases/download/physx/PhysXLoader.dll](https://github.com/igiteam/ghost-recon-advanced-warfighter-2006-deadly-dozen-2001/releases/download/physx/PhysXLoader.dll)
This re-enables most of the PhysX effects in GRAW 1, which are automatically disabled if you didn't have a PhysX PPU installed. These effects did not work with Nvidia PhysX GPUs, even back in the day.  90% of the effects are reenabled and run on the CPU, except for a fluid simulation effect which is disabled. This is a similar fix to the Cellfactor Revolution PhysX fix. Just drag and drop the .dll file into the game's directory with the exe and overwrite. Ensure the PhysX legacy driver is installed.

Driver 591.44 enables 32-bit PhysX Support for select titles below for 50-Series GPU. This does not impact 40 series or below as they support 32 bit PhysX (and CUDA)
GeForce Game Ready Driver 591.44 | Windows 11



| Game | Release Date | Physics Hardware | Architecture | Physics Features |
|---|---|---|---|---|
| Tom Clancy's Ghost Recon Advanced Warfighter | May 3, 2006 | PPU | 32-bit | Debris simulation |
| Tom Clancy's Ghost Recon Advanced Warfighter 2 | June 28, 2007 | GPU or PPU | 32-bit | Debris simulation, dynamic tearable cloth, dynamic tree and plant simulation, particle effects, additional level with destructible environments |


[![Nvidia GT8800 GRAW](https://raw.githubusercontent.com/igiteam/ghost-recon-advanced-warfighter-2006-deadly-dozen-2001/refs/heads/main/asus_gf8800_pic3.jpg)](https://raw.githubusercontent.com/igiteam/ghost-recon-advanced-warfighter-2006-deadly-dozen-2001/refs/heads/main/asus_gf8800_pic3.jpg)

| PhysX 1 | PhysX 2 | PhysX 3 | PhysX 4 | PhysX 5 |
| :---: | :---: | :---: | :---: | :---: |
| ![PhysX 1](https://raw.githubusercontent.com/igiteam/ghost-recon-advanced-warfighter-2006-deadly-dozen-2001/refs/heads/main/physx1.png) | ![PhysX 2](https://raw.githubusercontent.com/igiteam/ghost-recon-advanced-warfighter-2006-deadly-dozen-2001/refs/heads/main/physx2.png) | ![PhysX 3](https://raw.githubusercontent.com/igiteam/ghost-recon-advanced-warfighter-2006-deadly-dozen-2001/refs/heads/main/physx3.png) | ![PhysX 4](https://raw.githubusercontent.com/igiteam/ghost-recon-advanced-warfighter-2006-deadly-dozen-2001/refs/heads/main/physx4.png) | ![PhysX 5](https://raw.githubusercontent.com/igiteam/ghost-recon-advanced-warfighter-2006-deadly-dozen-2001/refs/heads/main/physx5.png) |


[![Deadly Dozen 2001](https://raw.githubusercontent.com/igiteam/ghost-recon-advanced-warfighter-2006-deadly-dozen-2001/refs/heads/main/Deadly_Dozen_Coverart.png)](https://archive.org/details/ghost-recon-advanced-warfighter-2006-deadly-dozen-2001)

[![GRAW 2006 PC](https://raw.githubusercontent.com/igiteam/ghost-recon-advanced-warfighter-2006-deadly-dozen-2001/refs/heads/main/ghost-recon-advanced-warfighter-2006.png)](https://archive.org/details/graw-pc)

[![GRAW Gamepad](https://raw.githubusercontent.com/igiteam/ghost-recon-advanced-warfighter-2006-deadly-dozen-2001/refs/heads/main/graw-gamepad-support.png)](https://raw.githubusercontent.com/igiteam/ghost-recon-advanced-warfighter-2006-deadly-dozen-2001/refs/heads/main/graw-gamepad-support.png)


## Dev Environment

**Official White Wii Remote With Nunchuk — Tested And Working — £14.99**
[https://www.ebay.co.uk/itm/800847189353](https://www.ebay.co.uk/itm/800847189353)

**Infrared Sensor Bar USB for Wii Emulator Remote Motion Detection Setup — £6.69**
[https://www.ebay.co.uk/itm/227423830875](https://www.ebay.co.uk/itm/227423830875)

**Apple MacBook Pro Retina 15in (2014) i7 2.8GHz 16GB 1TB SSD GT 750M — £120.30**
[https://www.ebay.co.uk/itm/800844561513](https://www.ebay.co.uk/itm/800844561513)

**WS11WineCX20.0.4 (Wine engine)**
[https://igiteam.github.io/wine_engines/](https://igiteam.github.io/wine_engines/)

**Official Genuine Sony PS3 PlayStation 3 DualShock 3 Wireless Controller Black — £19.99**
[https://www.ebay.co.uk/itm/840031043465](https://www.ebay.co.uk/itm/840031043465)

**Amazon Basics 4K HDMI Cable 3m — 18Gbps High Speed with Ethernet, 4K@60Hz, 2160p — £8.44**
[https://www.ebay.co.uk/itm/327352257557](https://www.ebay.co.uk/itm/327352257557)

**wiimote_nunchuk_macosx**
[https://github.com/igiteam/wiimote-nunchuk](https://github.com/igiteam/wiimote-nunchuk)

**xbox360_input_gui_py**
[https://github.com/igiteam/xbox360_input_gui_py](https://github.com/igiteam/xbox360_input_gui_py)

**logitec_mx_mouse_3_macos**
[https://github.com/igiteam/logitec_mx_mouse_3_macos](https://github.com/igiteam/logitec_mx_mouse_3_macos)

**igi1-macbook-3d-workstation**
[https://github.com/igiteam/igi1-macbook-3d-workstation](https://github.com/igiteam/igi1-macbook-3d-workstation)

---
