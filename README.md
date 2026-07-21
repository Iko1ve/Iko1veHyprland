authentication agent: hyprpolkitagent

terminal: kitty

wallpaper: hyprpaper

notification daemon: mako

application launcher: wofi

file manager: dolphin

pipewire: pipewire

xdg desktop portal: xdg-desktop-portal-hyprland

status bar: waybar

clipboard: cliphist 

screenshot: hyprshot

## Step 1
```
sudo pacman -Syu wofi kitty freetype2 zsh git hyprlock hyprpaper waybar ttf-font-awesome otf-font-awesome ttf-jetbrains-mono pavucontrol feh ranger thunar meson nwg-look papirus-icon-theme fastfetch file powerline-fonts inetutils ttf-font-awesome otf-font-awesome ttf-jetbrains-mono neovim ttf-dejavu bluez bluez-utils blueman vlc fastfetch xdg-desktop-portal-hyprland hyprpolkitagent sublime-text xdg-utils wl-clipboard-rs mako-git

git clone https://aur.archlinux.org/yay.git
cd yay
makepkg -si

yay -S hyprshot wlogout

```

## Step 2
```
cd Documents

git clone https://github.com/vinceliuice/Graphite-gtk-theme.git
git clone https://github.com/Iko1ve/Iko1veHyprland.git
```

## Step 3
```
cd Iko1veHyprland

cp -r kitty waybar wlogout wofi hypr fastfetch mako wallpaper ~/.config

cd Graphite-gtk-theme
./install.sh
```

## Step 4
Check [rust](https://wiki.archlinux.org/title/Rust) and [go](https://aur.archlinux.org/packages/go-git?all_reqs=1) installation |
 Download [cliphist](https://github.com/sentriz/cliphist) |
 Download/setup [mako](https://github.com/emersion/mako)
