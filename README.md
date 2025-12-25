# Hyprland 2.0

<img width="1280" height="720" alt="20251225_21h38m42s_grim" src="https://github.com/user-attachments/assets/e36bdd9c-a2fc-4124-8cbc-814a80b8c37a" />

## Requirements

1. `hyprland`
2. `waybar`
3. `wofi`
4. `nvim`
5. `alacritty`
6. `tmux`
7. `pywal`
8. `wlogout`
9. `thunar`
10. `blueberry`

### Arch systems:

**yay**

```
yay -S hyprland waybar wofi nvim alacritty tmux pywal-git wlogout thunar blueberry stow
```


**paru**

```
paru -S hyprland waybar wofi nvim alacritty tmux pywal-git wlogout thunar blueberry stow
```


### Nixos

```
nix-env -i hyprland waybar wofi nvim alacritty tmux pywal wlogout thunar blueberry stow
```


## Installation

### Manual

```
git clone https://github.com/GeraltdDima/Hyprland-2.0.git ~/.dotfiles
cd ~/.dotfiles
stow .
```


### Make

```
git clone https://github.com/GeraltdDima/Hyprland-2.0.git ~/.dotfiles
cd ~/.dotfiles
make install
```


## Uninstall

### Manual

```
cd ~/.dotfiles
stow -D .
```


### Make
```
cd ~/.dotfiles
make uninstall
```
