# KDE Plasma Arch Linux ISO

This is a very simple edit of the basic [Archiso](https://wiki.archlinux.org/index.php/Archiso) releng profile that includes the KDE Plasma DE and some other extra packages.
The intent of this ISO is to provide basic GUI utilities for a live Arch Linux boot. Therefore this might be used as a rescue ISO or just a more packed version of the default Arch ISO so you can take advantage of the extra packages during your installtion process.

## Extra packages

These are the packages that have been added which are not in the default [Archiso](https://wiki.archlinux.org/index.php/Archiso) releng profile.
```
base
mesa
xorg
xorg-xinit
sddm
networkmanager
plasma-meta
kwrite
firefox
dolphin
konsole
gparted
pulseaudio
pulseaudio-alsa
```

## Build process

In a Arch Linux system, just run the build.sh script. The [Archiso wiki](https://wiki.archlinux.org/index.php/Archiso#Setup) recommends the files to be owned by the root user.