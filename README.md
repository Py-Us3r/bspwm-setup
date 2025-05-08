
# bspwm-setup

bspwm-setup is a bash script designed to automatically set up a custom bspwm environment for https://github.com/Py-Us3r. 

## Prerequisites

A Debian-based Linux distribution (preferably Kali Linux)

## Installation

1. Update repository:
```bash
sudo apt update -y
sudo apt upgrade -y
```
2. Clone the repository:  
```bash
git clone https://github.com/Riieiro/bspwm-setup.git
cd bspwm-setup
```
3. Make the script executable:
```bash
chmod +x setup.sh
```
4. Run the script:
```bash
./setup.sh
```
5. Follow the on-screen instructions and restart your system when prompted.

## Usage

Once the environment is installed, you need to change it in the login panel:

![imagen](https://github.com/user-attachments/assets/14dd75f1-0631-40d5-8dfa-4d73e19ba59f)



## Overview
![imagen](https://github.com/user-attachments/assets/448e979e-44d8-48cc-81ed-9296b6308e23)
![imagen](https://github.com/user-attachments/assets/1d54d0e7-e135-48b9-99ad-e4c518cb242f)
![imagen](https://github.com/user-attachments/assets/d536ecad-73e3-4bb8-922d-2b7a86a0d7b1)
![imagen](https://github.com/user-attachments/assets/914c1290-23f5-4cf4-b718-f4bb0748cfe9)

# Keybindings for bspwm

- **Terminal**: `super + Return` → Opens `kitty`
- **Program Launcher**: `super + d` → Opens `rofi`
- **Reload sxhkd**: `super + Escape` → Reload configuration

- **Quit/Restart bspwm**: `super + shift + {q,r}`
- **Close/Kill Window**: `super + {_,shift + }q`
- **Tiled/Monocle Layout**: `super + m`
- **Swap Nodes**: `super + g`
- **Set Window State**: `super + {t,shift + t,s,f}`

- **Focus Direction**: `super + {_,shift + }{Left,Down,Up,Right}`
- **Focus Next/Prev Window**: `super + {_,shift + }c`
- **Focus Last Node/Desktop**: `super + {grave,Tab}`
- **Focus Desktop**: `super + {_,shift + }{1-9,0}`

- **Preselect Direction**: `super + ctrl + alt + {Left,Down,Up,Right}`
- **Cancel Preselection**: `super + ctrl + alt + space`

- **Move Window**: `super + shift + {Left,Down,Up,Right}`
- **Custom Resize**: `super + alt + {Left,Down,Up,Right}`

- **Firefox**: `super + shift + f`
- **Burpsuite**: `super + shift + b`

## Uninstallation

To remove BSPWM and related components, manually delete the installed packages and configurations:

```bash
sudo apt remove --purge bspwm sxhkd rofi polybar kitty picom zsh neofetch bat lsd -y rm -rf ~/.config/bspwm ~/.config/sxhkd ~/.config/polybar ~/.config/rofi ~/.config/kitty ~/.config/picom ~/.zshrc ~/.p10k.zsh ~/Pictures/Wallpapers ~/.local/share/fonts
```

## Credits

- **Author:** [Py-Us3r](https://github.com/Py-Us3r)
