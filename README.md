<div align="center">
<img alt="Profiles Pictures" src="https://github.com/FrogProg09/my-linux/blob/82a8df9a627c601c8f17605d98d9bc224ee22d0d/images/github_avatar.png" width="200" height="200"/>
</div>
<div align="center">
    <h1> Frogprog Hyprland Dotfiles</h1>
    <h4> A simple Hyprland configuration for linux (Arch). I use it as a productive setup on my thinkpad (14 inch)</h4>
</div>
</div>

### Things that are used in setup
| Sysetm part | Name |
|---|---|
| Compositor | [Hyprland](https://github.com/hyprwm/Hyprland) |
| Bar | [Waybar](https://github.com/Alexays/Waybar) |
| Lock | [Hyprlock](https://github.com/hyprwm/hyprlock) |
| App launcher | [Rofi-wayland](https://github.com/in0ni/rofi-wayland) |
| Term emulator | [Kitty](https://github.com/kovidgoyal/kitty) |
| Promt | [Starship](https://github.com/starship/starship) |

![image alt](https://github.com/FrogProg09/my-linux/blob/82a8df9a627c601c8f17605d98d9bc224ee22d0d/images/clean.png)

![image alt](https://github.com/FrogProg09/my-linux/blob/82a8df9a627c601c8f17605d98d9bc224ee22d0d/images/workflow.png)

## Installation

**The script should be fine, please report if something went wrong**

To install this setup I've created a script that will backup your cofings of programs that I use here in
~/.config/hyprland-oldconfigs/*version* directory

My script works only with files so that is why you have to make sure that everything is installed on your system:

```bash
sudo pacman -Suy
```
```bash
sudo pacman -S hyprland hyprlang hyprpaper hypridle hyprpolkitagent waybar rofi-wayland kitty nautilus mako starship git
```

```bash
yay -S hyprlock
```

So, there are two themes for now, it is dark and light gruvbox, depending on what you wnat, choose instalation process

### Dark

 Copy my repo and run script that will install my setup:
```bash
git clone -b gruvbox-dark --single-branch https://github.com/FrogProg09/my-linux.git
cd my-linux
chmod +x install.sh
./install.sh
```

### Light

```bash
git clone -b gruvbox-light --single-branch https://github.com/FrogProg09/my-linux.git
cd my-linux
chmod +x install.sh
./install.sh
```

And this is it! Besides I think shell setup (I use zsh), which you will need to do yourself.


If you want starship promt to work, you have to add one of these lines to the end of shell config respectively:

.bashrc
```
eval "$(starship init bash)"
```

.zshrc
```
eval "$(starship init zsh)"
```

and ~/.config/fish/config.fish
```
starship init fish | source
```

## Keybindings

Feel free to change and mess around with them, nothing will break if you know what you are doing after all.
Plus even I personally haven't come up with smth 100% convinient yet.

|Keybind|Result|
|---|---|
| Super + Return | Kitty |
| Super + D | Rofi |
| Super + E | Nautilus |
| Super + B | Bluetooth manager |
| Super + S | Hyprshot |
| Super + A | Wlogout |
| Super + M | Exit hyprland |
| Super + Q | Close window |
| Super + V | Toggle floating |
| Super + F | Toggle fullscreen |
| Super + H,J,K,L | Move focus |
| Super + 1-0 | Cange workspaces |
| Super + Shift + 1-0 | Move window to workspace |

This is it for now, in the future I'm gonna add cheatsheet to waybar

## Screenshots

![image alt](https://github.com/FrogProg09/my-linux/blob/82a8df9a627c601c8f17605d98d9bc224ee22d0d/images/pretty.png)

## Copying

You can basically do whaterver your heart desires with this repo, as long as it's under BSD-3 license.
I would be glad if someone wanted to contribute to this repo!

## Credits

- Thanks [r/unixporn](https://www.reddit.com/r/unixporn/) for awesome inspirational setups
- Thanks [1amSimp1e](https://github.com/1amSimp1e/dots) for amaizing readme example

*If you need to contact with me:*

- Discord: Frogprog
- Telegram: @Chocolate_waffels
