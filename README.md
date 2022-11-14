# [archVM-Hyper-V](#archvm-hyper-v)

## Arch Linux virtual machine on Windows10 Hyper-V <br>with Enhanced Session Mode

<p align="center"><a href="https://github.com/k247tEK/archVM-Hyper-V/tree/master/2022-06" target="_blank">
 <img src="images/archVM-Hyper-V_k247tEK.png" alt="archinstall" width="800" height="auto" border="3" />
</a></p>

### <p align="right ">[2022-11 - archlinux-2022.11.01-x86_64.iso](2022-06/)<br>[current install]</p>

### 2022-11 - fix Xrdp starting again..

```console
$ sudo systemctl enable xrdp 
$ sudo systemctl enable xrdp-sesman
$ sudo pacman -S openssl-1.1
$ yay -S paru
$ sudo xrdp-keygen xrdp /etc/xrdp/rsakeys.ini
$ sudo reboot
```

---

#### <p align="right ">[2022-10 - archlinux-2022.10.01-x86_64.iso](2022-06/)<br>[previous install]</p>

### 2022-10 - remove python2 & ceph..

```console
$ sudo pacman -Rcns python2 
$ yay -Rns ceph
```

---

#### <p align="right ">[2022-07 - archlinux-2022.07.01-x86_64.iso](2022-06/)<br>[previous install]</p>

### 2022-07 - pulseAudio in Xrdp working again..

---

#### <p align="right ">[2022-06 - archlinux-2022.06.01-x86_64.iso](2022-06/)<br>[first install]</p>

### 2022-06 - let the fun begin..

### Host

- #### s/w

            Windows 10 Pro 21H2 OS Build 19044.1706
            WSL2 / Hypervisor Platform & Hyper-V enabled
- #### h/w<br>

            Lenovo Ideapad G560-M274YGE
            Intel Core i5-450M (2.40GHz, 2 cores - 4 threads)
            8GB (DDR3 1066MHz)
            NVIDIA GeForce 310M

unfortunately..

[<p align="left"><img src="images/noupdate4u.PNG" alt="archVM-Hyper-V" width="680" /></p>](#)

sooo, Desperately Seeking OS.. ;-]...

found.. [arch Linux](https://archlinux.org) 2022-06, xfce-Desktop install via archinstall...

### [Xfce Desktop Environment](https://wiki.archlinux.org/title/xfce) | [Xorg](https://wiki.archlinux.org/title/xorg) | [Xrdp](https://wiki.archlinux.org/title/xrdp) | [pulseaudio-module-xrdp](https://aur.archlinux.org/packages/pulseaudio-module-xrdp)

ref: https://www.xfce.org

###### <p align="right">[Acknowledgments & Thanks](Acknowledgments.md) | [License](LICENSE.txt) | [<img src="images/Arch-linux-logo.png" alt="klock xfce session lock" width="40" />](https://github.com/k247tEK/archVM-Hyper-V/tree/master/2022-06)</p>

---

#EOF