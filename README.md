# .dotfiles @ kerikun11

My UNIX Configuration Files

```
      _       _    __ _ _           
     | |     | |  / _(_) |          
   __| | ___ | |_| |_ _| | ___  ___ 
  / _` |/ _ \| __|  _| | |/ _ \/ __|
 | (_| | (_) | |_| | | | |  __/\__ \
(_)__,_|\___/ \__|_| |_|_|\___||___/
```

> Note that .gitconfig contains my personal information.
> Don't install it as is, except for me.

## install .dotfiles @ kerikun11

```sh
wget -O- https://raw.githubusercontent.com/kerikun11/.dotfiles/master/install.sh | bash
```

## configure automatically

```sh
## install common packages
wget -O- https://raw.githubusercontent.com/kerikun11/.dotfiles/master/tools/install_common.sh | sh

# Manjaro Linux Cinnamon 19.2
wget -O- https://raw.githubusercontent.com/kerikun11/.dotfiles/master/tools/manjaro_setup.sh | bash

# Linux Mint 19.3
wget -O- https://raw.githubusercontent.com/kerikun11/.dotfiles/master/tools/mint_setup.sh | sh
```

## mirror list

```sh
# Manjaro
Server = http://ftp.riken.jp/Linux/manjaro/stable/$repo/$arch
Server = http://ftp.tsukuba.wide.ad.jp/Linux/manjaro/stable/$repo/$arch
```

## .zshenv

```sh
# MSYS2
export PATH="$PATH:/c/Windows"
alias e="/c/Windows/explorer.exe"
alias code="'/c/Users/kerikun11/AppData/Local/Programs/Microsoft VS Code/Code.exe'"

# PengWin
export DISPLAY=localhost:0.0
```
