# Dotfiles

My (incomplete) dotfiles


# Application

- Distribution : Arch 

- package manager : pacman and paru
- Terminal : Alacritty
- Shell : zsh 
- Navigator : Firefox
- Mail : Thunderbird
- Editor : Doom Emacs (and vim)
- Password Manager : KeePassXC

- Desktop environment : kde

> Note : a hypr desktop with eww or waybar and rofi is started but it takes times
> (Problem with wifi card in particular)


# Installation
Needs : `stow` and `git`

```sh
git clone git@github.com:Lzebulon/dotfiles.git
cd dotfiles
stow --target=$HOME .
```


This maybe needed
```sh
stow --target=$HOME --adopt .
```
