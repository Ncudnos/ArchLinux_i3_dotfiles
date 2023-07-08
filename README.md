# ArchLinux_i3_dotfiles

0. Install `ArchLinux` with `i3` Desktop. You can also install `ArchLinux mininal` and install needed `i3-gaps` packages

1. Install `yay`

```bash
pacman -Sy --needed git base-devel && git clone https://aur.archlinux.org/yay.git && cd yay && makepkg -si

```

2. Install needed packages

```bash
yay -S git curl gcc jdk-openjdk jre-openjdk python-pip brillo teamviewer ibus rofi neofetch htop ibus-bamboo zip unzip xclip rar ttf-hack-nerd nordic-theme-git papirus-icon-theme-git nordzy-cursors alacritty alacritty-themes neovim lsd brave-bin lxappearance variety feh pdftk && yay -Rncs firefox && yay -S nvm

```

3. Clone the repo

```bash

git clone https://github.com/ncudnos/ArchLinux_i3_dotfiles.git && cd ArchLinux_i3_dotfiles

```

4.Create folders and remove the old folders/files if they are created

```bash

mkdir Documents Music Pictures Downloads && sudo rm -rf ~/.config/alacritty ~/.config/i3 ~/.config/neofetch ~/.config/rofi ~/.config/mimeapps.list /etc/profile

```

5. Move my folders/files into right places

```bash

mv alacritty ~/.config/ && mv i3 ~/.config/ && mv neofetch ~/.config/ && mv nvim ~/.config/ && mv rofi ~/.config/ && sudo mv profile /etc/ && mv mimeapps.list ~/.config/

````

