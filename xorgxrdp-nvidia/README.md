# Xrdp

ref: https://wiki.archlinux.org/title/xrdp

 ## Tips and tricks
 
 ### Graphical acceleration

 >For Xorg sessions, you can enable `OpenGL` and `Vulkan` graphical acceleration by installing `xorgxrdp-glamor` `AUR` for Intel and AMD GPUs and `xorgxrdp-nvidia` `AUR` for Nvidia GPUs.

```console
$ yay -S xorgxrdp-nvidia
```

Shutdown virtual machine..

##### [ Host s/w : Windows 10 Pro 21H2 OS Build 19044.1706. ]

##### [ Host h/w : Lenovo Ideapad G560-M274YGE - Intel Core i5-450M (2.40GHz, 2 cores - 4 threads),<br>8GB (DDR3 1066MHz), NVIDIA GeForce 310M ]</p>

## NVIDIA GeForce 310M

<pre><code>
NVIDIA System Information report created on: 06/13/2022 16:33:15
System name: KG560

[Display]
Operating System:       Windows 10 Pro, 64-bit
DirectX version:        11.0 
GPU processor:          GeForce 310M
Driver version:         342.01
Direct3D API version:   10.1
CUDA Cores:             16 
Core clock:             625 MHz 
Shader clock:           1530 MHz
Memory data rate:       1580 MHz
Memory interface:       64-bit 
Total available graphics memory: 4095 MB
Dedicated video memory: 512 MB DDR3
System video memory:    0 MB
Shared system memory:   3583 MB
Video BIOS version:     70.18.4B.00.06
IRQ:                    16
Bus:                    PCI Express x16
Device ID:              10DE 0A75 392D17AA

[Components]

NvGFTrayPluginr.dll	    2.11.4.125		    NVIDIA GeForce Experience
NvGFTrayPlugin.dll	    2.11.4.125		    NVIDIA GeForce Experience
nvui.dll		        8.17.13.4201		NVIDIA User Experience Driver Component
nvxdsync.exe		    8.17.13.4201		NVIDIA User Experience Driver Component
nvxdplcy.dll		    8.17.13.4201		NVIDIA User Experience Driver Component
nvxdbat.dll		        8.17.13.4201		NVIDIA User Experience Driver Component
nvxdapix.dll		    8.17.13.4201		NVIDIA User Experience Driver Component
NVCPL.DLL		        8.17.13.4201		NVIDIA User Experience Driver Component
nvCplUIR.dll		    7.8.840.0		    NVIDIA Control Panel
nvCplUI.exe		        7.8.840.0		    NVIDIA Control Panel
nvWSSR.dll		        6.14.13.4201		NVIDIA Workstation Server
nvWSS.dll		        6.14.13.4201		NVIDIA Workstation Server
nvViTvSR.dll		    6.14.13.4201		NVIDIA Video Server
nvViTvS.dll		        6.14.13.4201		NVIDIA Video Server
NVSTVIEW.EXE		    7.17.13.4201		NVIDIA 3D Vision Photo Viewer
NVSTTEST.EXE		    7.17.13.4201		NVIDIA 3D Vision Test Application
NVSTRES.DLL		        7.17.13.4201		NVIDIA 3D Vision Module
nvDispSR.dll		    6.14.13.4201		NVIDIA Display Server
NVMCTRAY.DLL		    8.17.13.4201		NVIDIA Media Center Library
nvDispS.dll		        6.14.13.4201		NVIDIA Display Server
PhysX		            09.13.1220		    NVIDIA PhysX
NVCUDA.DLL		        8.17.13.4201		NVIDIA CUDA 6.5.51 driver
nvGameSR.dll		    6.14.13.4201		NVIDIA 3D Settings Server
nvGameS.dll		        6.14.13.4201		NVIDIA 3D Settings Server
</code></pre>

<br>

on Host.. from Nvidia Control Panel.. Manage 3D Settings.. Program Settings.. add Virtual Machine Connection..

<p align="center"><img src="images/manage3DSetting.PNG" alt="manage NVIDIA GeForce 310M 3D Setting" width="auto" /></p>

Restart windows Host..