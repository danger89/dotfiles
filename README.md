# dotfiles + extra software

My Linux dotfiles, a collection of custom configuration files. See [home/melroy](Melroy's home) folder.

I'm using Manjaro v17/v18.

Besides my dot files you will see some configuration files from [/etc](etc) folder.

## Extra packages

Extra installed packages:

`# pacman -S nfs-utils telegram-desktop etcher compton conky conky-manager celestia darktable deepin-calculator deepin-calendar deepin-voice-recorder filezilla transmission-gtk dnsutils retroarch retroarch-assets-xmb libretro-snes9x libretro-shaders-cg libretro-reicast libretro-ppsspp libretro-overlays libretro-mupen64plus libretro-gambatte libretro-core-info`

Extra installed AUR packages:

`atom-editor-bin green-recorder emulationstation`

Try:

`simplescreenrecorder`

Replaced packages:
* `ligh-locker` -> `xscreensaver` (light-locker crashed)
* Via Manjaro Settings Manager, installed Nvidia driver (v340 in my case): `video-nvidia-340xx`

## Firewall rules (ufw)

This is the graphical viewer (`gufw`):

![Firewall rules](firewall_rules.png)