# Мои конфиги для i3wm

## Установка на новой системе

### 1. Установка Paru:
sudo pacman -S --needed base-devel
git clone https://aur.archlinux.org/paru.git
cd paru
makepkg -si

### 2. Установить программы:
paru  -S  i3status-rust dunst feh opera-gx picom geany obsidian alacritty vlc neovim keepassxc pcmanfm git

### 3. Скачать конфиги:
git clone https://github.com/toxanb/dotfiles_i3-wm.git ~/dotfiles

### 4. Скопировать на места
cp ~/dotfiles/.config/i3/config ~/.config/i3/
cp ~/dotfiles/.config/i3status-rust/config.toml ~/.config/i3status-rust/
