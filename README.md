# Ubuntu env setup

## Introduction

This is an article about how to build my own Ubuntu development environment.\
You can find some useful software and using tips here.\
If you have something to recommend me to use, just post an issue.\
This repository will keep on update.

Just for save some time on google.

## Language

- [English](README.md)
- [简体中文](README-CN.md)

## System

I am using the Ubuntu 20.04.

## Software Sources

<https://mirrors.tuna.tsinghua.edu.cn/help/ubuntu/>

## Git

`151.101.76.133 raw.githubusercontent.com`

```bash
# user information
git config --global user.name "AimerNeige"
git config --global user.email aimer.neige.soft@gmail.com

# proxy
git config --global http.proxy http://127.0.0.1:1080
git config --global https.proxy https://127.0.0.1:1080

# use this if doesn't work
git config --global http.proxy socks5://127.0.0.1:1080
git config --global https.proxy socks5://127.0.0.1:1080
```

## DE

### i3

<https://github.com/AimerNeige/i3>

### i3-status

<https://github.com/AimerNeige/i3status>

## Shell

### fish

<https://github.com/AimerNeige/fish>

### zsh

<https://github.com/AimerNeige/zsh>

## Terminal

### alacritty

```bash
sudo add-apt-repository ppa:mmstick76/alacritty
sudo apt install alacritty
```

<https://github.com/AimerNeige/alacritty>

### st

<https://github.com/AimerNeige/st>

### cool-retro-term

pass

## Editor

### neovim

<https://github.com/AimerNeige/neovim>

### vim

<https://github.com/AimerNeige/vim>

### vscode

## EFI

### refind

### refind-theme

## Daily Software

| Software             | Description | Download                                                  |
| -------------------- | ----------- | --------------------------------------------------------- |
| Chrome               | Browser     | https://www.google.com/chrome/                            |
| VirtualBox           | VM          | https://www.virtualbox.org/wiki/Linux_Downloads           |
| Code Insiders        | Code        | sudo snap install code --classic                          |
| VYM                  |             | sudo snap install --classic code                          |
| variety              |             | sudo snap install --classic code-insiders                 |
| Atom                 |             |                                                           |
| Sublime Text         |             |                                                           |
| typora               |             |                                                           |
| telegram             |             |                                                           |
| teamviewer           |             |                                                           |
| sm player            |             |                                                           |
| vlc                  |             |                                                           |
| mpv                  |             |                                                           |
| ranger               |             |                                                           |
| calibre              |             |                                                           |
| GHex                 |             |                                                           |
| GIMP                 |             |                                                           |
| KDEN Live            |             |                                                           |
| Htop                 |             |                                                           |
| qbittorrent          |             |                                                           |
| Okular               | PDF         |                                                           |
| light                |             |                                                           |
| SimpleScreenRecorder |             |                                                           |
| Qt                   |             |                                                           |
| compton              |             |                                                           |
| udiskie              |             |                                                           |
| i3lock-flancy        |             |                                                           |
| etcher               |             |                                                           |
| libreoffice          |             |                                                           |
| lazygit              |             |                                                           |
| neofetch             |             |                                                           |
| tree                 |             |                                                           |
| idea                 |             | sudo snap install intellij-idea-ultimate --classic --edge |
| cargo                |             | sudo apt install cargo                                    |
| feh                  |             |                                                           |
