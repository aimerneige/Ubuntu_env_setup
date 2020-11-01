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

`~/.ssh/config`

```
Host github.com
HostName github.com
User git
Port 22
ProxyCommand /usr/bin/ncat --proxy 127.0.0.1:1080 --proxy-type socks5 %h %p
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

```bash
sudo apt install refind
```

### refind-theme

## Daily Software

| Software             | Description       | Download                                                     |
| -------------------- | ----------------- | ------------------------------------------------------------ |
| Chrome               | Browser           | <https://www.google.com/chrome/>                             |
| VirtualBox           | VM                | <https://www.virtualbox.org/wiki/Linux_Downloads>            |
| sdcv                 | dictionary        |                                                              |
| Code                 | Code              | `sudo snap install code --classic`                           |
| Code Insiders        | Code              | `sudo snap install code-insiders --classic`                  |
| VYM                  | Mind Map          |                                                              |
| feh                  | Wallpaper         | `sudo apt install feh`                                       |
| variety              | Wallpaper         | `sudo apt install variety`                                   |
| Atom                 |                   | `sudo snap install atom --classic`                           |
| Sublime Text         | Code editor       | `sudo snap install sublime --classic`                        |
| typora               |                   | `sudo snap install typora`                                   |
| telegram             | chat              | `sudo apt install telegram-desktop`                          |
| teamviewer           |                   |                                                              |
| sm player            | video             | `sudo apt install smplayer`                                  |
| vlc                  | video             | `sudo apt install vlc`                                       |
| mpv                  | video             | `sudo apt install mpv`                                       |
| ranger               | file manager      | `sudo apt install ranger`                                    |
| calibre              | eBoot manager     | `sudo apt install calibre`                                   |
| GHex                 | hex reader        | `sudo apt install ghex`                                      |
| GIMP                 | picture make      | `sudo apt install gimp`                                      |
| KDEN Live            | video make        | `sudo apt install kdenlive`                                  |
| Htop                 |                   | `sudo apt install htop`                                      |
| qbittorrent          | torrent           | `sudo apt install qbittorrent`                               |
| Okular               | PDF reader        | `sudo apt install okular`                                    |
| light                | screenlight       | `sudo apt install light`                                     |
| SimpleScreenRecorder | record screen     | `sudo apt install simplescreenrecorder`                      |
| compton              | window compositor | `sudo apt install compton`                                   |
| udiskie              | auto mount disk   | `sudo apt install udiskie`                                   |
| i3lock-flancy        | nice look i3-lock |                                                              |
| etcher               | make live-CD      |                                                              |
| libreoffice          | office soft       | `sudo apt install libreoffice`                               |
| lazygit              | git               | `sudo add-apt-repository ppa:lazygit-team/release`           |
|                      |                   | `sudo apt-get update`                                        |
|                      |                   | `sudo apt install lazygit`                                   |
| neofetch             | systeminfo        | `sudo apt install neofetch`                                  |
| tree                 | file tree         | `sudo apt install tree`                                      |
| Idea                 | java              | `sudo snap install intellij-idea-ultimate --classic`         |
| PyCharm              | python            | `sudo snap install pycharm-professional --classic`           |
| CLion                | c / c++           | `sudo snap install clion --classic`                          |
| cargo                |                   | `sudo apt install cargo`                                     |
| figlet               | ascii picture     | `sudo apt install figlet`                                    |
| qt                   |                   | `sudo apt-get install qt5-default qtcreator`                 |
|                      |                   | `sudo apt-get install build-essential`                       |
|                      |                   | `sudo apt-get install qtdeclarative5-dev libgl1-mesa-dev`    |
|                      |                   | `sudo apt-get install qt5-doc qt5-doc-html qtbase5-doc-html` |
|                      |                   | `sudo apt-get install qtbase5-examples`                      |
| uget                 |                   |                                                              |
| feeluown             |                   |                                                              |
| axel                 |                   |                                                              |
| go-for-it            |                   | sudo add-apt-repository ppa:go-for-it-team/go-for-it-daily   |
|                      |                   | sudo apt-get update                                          |
|                      |                   | sudo apt-get install go-for-it                               |
