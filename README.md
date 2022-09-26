# Information, packages, and dotfiles!
Everything I/you need to remember/know about my manjaro-i3 rice

# Picom modifications
in `~/.config/picom.conf`
1. **Firefox Shadow Removal**: Find the line `"class_g = 'Firefox' && argb",` and replace it with
```
"class_g = 'firefox'",
```
This is not useful for me, as I disabled all shadows with `shadow = false;`
2. **Alacritty translucent/transparent**: Add this line in `picom.conf` under `opacity-rule`
```
"80:class_g ; 'Alacritty'"
```
where 80 is the value of opacity out of 100.

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
