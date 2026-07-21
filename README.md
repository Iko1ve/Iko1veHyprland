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
sudo pacman -S wofi kitty freetype2 zsh git hyprlock hyprpaper waybar ttf-font-awesome otf-font-awesome ttf-jetbrains-mono obsidian pavucontrol feh ranger thunar meson nwg-look papirus-icon-theme fastfetch file powerline-fonts inetutils ttf-font-awesome otf-font-awesome ttf-jetbrains-mono neovim code ttf-dejavu bluez bluez-utils blueman telegram-desktop vlc fastfetch xdg-desktop-portal-hyprland hyprpolkitagent sublime-text

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

cp -r kitty waybar wlogout wofi hypr fastfetch ~/.config

cd Graphite-gtk-theme
./install.sh
```
