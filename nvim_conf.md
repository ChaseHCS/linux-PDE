# Nvim Config

Nvim conf file is located in "~/.config/nvim/init.lua"

### Distro = LazyVim

## Installation

```bash
$ curl -LO https://github.com/neovim/neovim/releases/latest/download/nvim-linux-x86_64.tar.gz
$ sudo rm -rf /opt/nvim-linux-x86_64
$ sudo tar -C /opt -xzf nvim-linux-x86_64.tar.gz

# Add to zsh conf
export PATH="$PATH:/opt/nvim-linux-x86_64/bin"
```

## LazyVim Install ~/.config/nvim/init.lua

```bash
$ mv ~/.config/nvim{,.bak}
$ git clone https://github.com/LazyVim/starter ~/.config/nvim
$ rm -rf ~/.config/nvim/.git
```
