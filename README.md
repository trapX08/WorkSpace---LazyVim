# WorkSpace - LazyVim

A workspace configuration for [LazyVim](https://www.lazyvim.org/), a Neovim setup powered by [lazy.nvim](https://github.com/folke/lazy.nvim).

## Overview

This repository contains a customized LazyVim workspace setup for efficient development. LazyVim is a Neovim configuration that aims to make it easy to customize and extend your config.

## Development Location

This workspace is configured for local development. The development location structure follows standard LazyVim conventions:

- **Configuration Path**: `~/.config/nvim/`
- **Data Path**: `~/.local/share/nvim/`
- **State Path**: `~/.local/state/nvim/`
- **Cache Path**: `~/.cache/nvim/`

### Setup Instructions

1. **Clone this repository** to your local machine
2. **Backup your existing Neovim configuration** (if any):
   ```bash
   mv ~/.config/nvim ~/.config/nvim.bak
   mv ~/.local/share/nvim ~/.local/share/nvim.bak
   ```
3. **Link or copy** this workspace to your Neovim config location:
   ```bash
   ln -s /path/to/WorkSpace---LazyVim ~/.config/nvim
   ```
4. **Start Neovim** and let LazyVim install plugins:
   ```bash
   nvim
   ```

## Features

- Pre-configured LazyVim setup
- Optimized for development workflows
- Easy to customize and extend
- Plugin management with lazy.nvim

## Prerequisites

- Neovim >= 0.9.0
- Git
- A Nerd Font (optional, but recommended)
- For telescope.nvim: ripgrep and fd

## Usage

Simply start Neovim in your development directory:

```bash
nvim
```

Check out the [LazyVim documentation](https://www.lazyvim.org/) for keybindings and customization options.

## Contributing

Feel free to fork this repository and customize it for your own needs. If you have improvements or suggestions, pull requests are welcome!

## License

This workspace configuration is provided as-is for personal use.
