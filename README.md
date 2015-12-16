# .dotfiles

# Linux Install
- `cd ~`
- `git clone https://github.com/bfalk8/.dotfiles.git && cd .dotfiles`
- `git submodule init`
- `git submodule update`
- `./ubuntu-init.sh`
- sit back and let NIX magic happen :)

# Windows Install

## install git
download and install _git-scm_ from [git-scm](https://git-scm.com/download/win) or [github](https://git-for-windows.github.io/)

## install scoop
Run these commands in powershell
- `set-executionpolicy unrestricted -s cu`
- `iex (new-object net.webclient).downloadstring('https://get.scoop.sh')`
- `scoop install 7zip concfg curl grep python python27 sudo touch vim wget`

## install ConEmu
Download portable version from [ConEmu](http://conemu.github.io/)
- unzip portable version in ~/dev/tools
- set ConEmu.xml to be located in ~/dev/tools

## clone the repo and install
- `cd` into your home directory
- `git clone https://github.com/bfalk8/.dotfiles.git`
- `cd .dotfiles`
- `git submodule init`
- `git submodule update`
- `./windows-init.ps1`

# Post-Init
# vim
open vim and run `:PluginInstall`
