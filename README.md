# How to use

To install nvim:
```
sudo apt-get install fuse libfuse2

curl -LO https://github.com/neovim/neovim/releases/latest/download/nvim.appimage
chmod u+x nvim.appimage
./nvim.appimage

sudo mv nvim.appimage /usr/bin/nvim
```

To install this for your neovim configuration

```
git clone https://github.com/NvChad/NvChad ~/.config/nvim --depth 1
git clone git@github.com:zlin888/neovim-python.git ~/.config/nvim/lua/custom
```

Then open up neovim and let everything install.

Restart Neovim and install the treesitter syntax

```
:TSInstall python
```

Install Mason package fro python setup according to https://www.youtube.com/watch?v=4BnVeOUeZxc
```
:MasonInstallAll
```
