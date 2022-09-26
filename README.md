# Information, packages, and dotfiles!
Everything I/you need to remember/know about my manjaro-i3 rice

# Picom modifications
in ~/.config/picom.conf
1. **Firefox**: Find the line `"class_g = 'Firefox' && argb",` and replace it with
```
"class_g = 'firefox'",
```

# Getting rounded corners on a default install
Run these commands:

```
sudo pacman -Rdd i3-gaps && yay -S i3-gaps-rounded-git
```

and then add a `border_radius x` line in `~/.i3/config`

# Useful packages:
- `polymc-cracked-git`
- `breaktimer`
- `lutris`
- `discord`
- `godot`
- `hplip`
- `imagewriter`
- `spotify-adblock`
