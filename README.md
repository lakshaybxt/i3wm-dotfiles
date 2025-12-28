# Dotfiles

Personal i3wm setup on EndeavourOS.

## Includes
- i3wm
- picom (terminal-only blur)
- alacritty
- Wallpapers

## Screenshot
![Image 1: ](screenshots/image-1)
![Image 2: ](screenshots/image-2)
![Image 3: ](screenshots/image-3)

## Notes
- Tested on EndeavourOS + i3
- Laptop focused, battery friendly

## Things to install after configuring file
```
# Fonts for System & Terminal
sudo pacman -S inter-font ttf-jetbrains-mono noto-fonts noto-fonts-emoji
```

```
# Theme
yay -S nordic-theme
yay -S whitesur-icon-theme
```

```
# For Backgoroud blur (optional)
sudo pacman -S picom
picom --backend glx --vsync -b
```
