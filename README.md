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

### vscode

## EFI

### refind

### refind-theme

## Daily Software

| Software             | Description       | Download                                                  |
| -------------------- | ----------------- | --------------------------------------------------------- |
| Chrome               | Browser           | https://www.google.com/chrome/                            |
| VirtualBox           | VM                | https://www.virtualbox.org/wiki/Linux_Downloads           |
| Code Insiders        | Code              | sudo snap install code --classic                          |
| VYM                  | Code              | sudo snap install --classic code                          |
| variety              | Wallpaper         | sudo snap install --classic code-insiders                 |
| Atom                 |                   |                                                           |
| Sublime Text         |                   |                                                           |
| typora               |                   |                                                           |
| telegram             | chat              | sudo apt install telegram-desktop                         |
| teamviewer           |                   |                                                           |
| sm player            | video             | sudo apt install smplayer                                 |
| vlc                  | video             | sudo apt install vlc                                      |
| mpv                  | video             | sudo apt install mpv                                      |
| ranger               | file manager      | sudo apt install ranger                                   |
| calibre              | eBoot manager     | sudo apt install ranger                                   |
| GHex                 | hex reader        | sudo apt install ghex                                     |
| GIMP                 | picture make      | sudo apt install gimp                                     |
| KDEN Live            | video make        | sudo apt install kdenlive                                 |
| Htop                 |                   | sudo apt install htop                                     |
| qbittorrent          | torrent           | sudo apt install qbittorrent                              |
| Okular               | PDF reader        | sudo apt install okular                                   |
| light                | screenlight       |                                                           |
| SimpleScreenRecorder | record screen     | sudo apt install simplescreenrecorder                     |
| Qt                   |                   |                                                           |
| compton              | window compositor | sudo apt install compton                                  |
| udiskie              | auto mount disk   | sudo apt install udiskie                                  |
| i3lock-flancy        | nice look i3-lock |                                                           |
| etcher               | make live-CD      |                                                           |
| libreoffice          | office soft       | sudo apt install libreoffice                              |
| lazygit              | git               | sudo add-apt-repository ppa:lazygit-team/release          |
|                      |                   | sudo apt-get update                                       |
|                      |                   | sudo apt install lazygit                                  |
| neofetch             | systeminfo        | sudo apt install neofetch                                 |
| tree                 | file tree         | sudo apt install tree                                     |
| idea                 |                   | sudo snap install intellij-idea-ultimate --classic --edge |
| cargo                |                   | sudo apt install cargo                                    |
| feh                  | wallpaper change  | sudo apt install feh                                      |
| figlet               | ascii picture     | sudo apt install figlet                                   |
