<div align="center">

# dotfiles

**terminal, editor and reader configs from my kde setup, in catppuccin mocha**

<img alt="KDE Plasma" src="https://img.shields.io/badge/KDE%20Plasma-b6c4ff?style=flat-square&labelColor=1e1f25&logo=kdeplasma&logoColor=e3e1e9"> <img alt="Catppuccin Mocha" src="https://img.shields.io/badge/Catppuccin%20Mocha-cba6f7?style=flat-square&labelColor=1e1e2e"> <img alt="Neovim" src="https://img.shields.io/badge/Neovim-dce1ff?style=flat-square&labelColor=1e1f25&logo=neovim&logoColor=e3e1e9"> <img alt="kitty" src="https://img.shields.io/badge/kitty-c6c6d0?style=flat-square&labelColor=1e1f25">

</div>

## What's in it

| | |
|---|---|
| `kitty/` | Catppuccin Mocha, Caskaydia Cove Nerd Font, 70% translucent |
| `nvim/` | Lua config on packer: Treesitter, completion with snippets, nvim-tree, lualine, indent guides, Catppuccin |
| `starship.toml` | a two-line prompt with git status, languages, battery and command time |
| `fastfetch/` | system info with an image logo, drawn through kitty's graphics protocol |
| `zathura/` | the PDF reader in Catppuccin Mocha |

## Install

```bash
git clone https://github.com/ahadarshx/dotfiles.git ~/dotfiles
cp -r ~/dotfiles/{kitty,nvim,fastfetch,zathura} ~/.config/
cp ~/dotfiles/starship.toml ~/.config/
```

Back up your own configs first. In Neovim, run `:PackerSync` once to install the plugins. <kbd>Space</kbd> is the leader key.

<sub>kitty · Neovim · packer · starship · fastfetch · zathura · Catppuccin</sub>
