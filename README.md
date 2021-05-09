dotfile_mac
========

This repository includes a set of simple custom dotfiles which could be used in a fresh macbook pro. The install script will:

1. Back up any existing dotfiles in your home directory to `~/dot_files_old/`
2. Create symlinks to the dotfiles in `~/dot_files/` in your home directory

Usage
------------

``` bash
git clone git://github.com/lenciel/dotfile_mac  ~/dot_files
cd ~/dot_files
./makesymlinks.sh
```
