# arch-kde-installer

Arch installer with LXQt Desktop Environment

Created with [archiso](https://wiki.archlinux.org/title/archiso)

This project is just an arch live iso / installer but with a functioning desktop environment. I created this after running into issues with Arch install scripts and decided to just do a vanilla install, but I wanted to do so from a useable desktop so I could pull up the Arch wiki while doing so.


Image is based on the releng profile with the following packages added:
* gparted
* xorg-xinit
* xorg-server
* xf86-video-amdgpu
* mesa
* lib32-mesa
* firefox
* nvidia
* dolphin
* konsole
* plasma-meta
* testdisk

# Building

See [wiki](https://wiki.archlinux.org/title/archiso#Build_the_ISO)

Replace "/path/to/profile/" with the directory you extracted this repo to (ex. ~/arch-kde-installer/)

I do not intent to provide much in terms of update or support, this project is mostly for personal reference.
