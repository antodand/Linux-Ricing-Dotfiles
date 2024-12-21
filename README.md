- [Introduction](#introduction)
- [Installation](#installation)
  - [Main packages](#main-packages)
  - [Extra packages](#extra-packages)
    - [Configuration](#configuration)
    - [Softwares](#softwares)

# Introduction 

In this folder there is everything about my Hyprland experience.

This README file explains the procedures to install and configure a generic Hyprland rice, plus some comments and tips!

For more specific (and reliable) information, check the [official Hyprland website](https://hyprland.org/).

# Installation

I usually install Hyprland starting from an EndeavourOS installation with:

+ No desktop environment
+ No EndeavourOS theme
+ Swapfile in ext4 format
+ Systemd-boot bootloader

Then, I install different packages after the post-installation reboot. 

## Main packages

```
sudo pacman -S hyprland neovim qt5ct qt6ct foot nemo nemo-fileroller nemo-image-converter pamixer waybar otf-font-awesome polkit-kde-agent python-requests xdg-desktop-portal-hyprland intel-media-driver libva-mesa-driver mesa-vdpau libva-utils wofi mako brightnessctl hyprpaper hyprlocl hypridle
```

```
yay -S hyprshot
```

## Extra packages

### Configuration

```
sudo pacman -S ttf-jetbrains-mono nwg-look
```

### Softwares

```
sudo pacman -S telegram-desktop discord xed evince vlc
```

```
yay -S librewolf-bin brave-bin visual-studio-code-bin spotify
```