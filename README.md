# About
This is my custom nvim config built on top of NvChad (https://github.com/NvChad/NvChad)

## Installation
**Optional:** Backup your nvim config
```git
git clone https://github.com/ycmarcoli/nvim-config ~/.config/nvim && nvim
```
Run `:MasonInstallAll` command after lazy.nvim finishes downloading plugins. \
Delete the `.git` folder from nvim folder.

## Update
Run `Lazy sync` command.

## Uninstallation
```git
# Linux / Macos (unix)
rm -rf ~/.config/nvim
rm -rf ~/.local/state/nvim
rm -rf ~/.local/share/nvim

# Flatpak (linux)
rm -rf ~/.var/app/io.neovim.nvim/config/nvim
rm -rf ~/.var/app/io.neovim.nvim/data/nvim
rm -rf ~/.var/app/io.neovim.nvim/.local/state/nvim

# Windows CMD
rd -r ~\AppData\Local\nvim
rd -r ~\AppData\Local\nvim-data

# Window PowerShell
rm -Force ~\AppData\Local\nvim
rm -Force ~\AppData\Local\nvim-data
```
