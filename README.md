# Dotfiles Repository

This repository contains a curated collection of personal configuration files for a minimalist, terminal-centric Unix environment. It is intended for users who value efficiency, keyboard-driven workflows, and resource-conscious setups.

## Included Configurations

- **Shell**  
  - `zshrc.config`, `zprofile.config` – Zsh shell configuration
  - `bash_aliases.config`, `bash_func.config` – Bash aliases and functions
- **Editor**  
  - `vimrc.config` – Vim/Neovim configuration for TUI editing
- **Terminal Multiplexer**  
  - `tmux.config` – Tmux session and window management
- **Music Player**  
  - `cmusrc.config` – Cmus keybindings and layout preferences
- **News Reader**  
  - `newsboat.config` – Newsboat RSS reader setup
- **PDF Reader**  
  - `zathurarc.config` – Zathura keybindings and interface options
- **Task Manager**  
  - `taskrc.config` – Taskwarrior configuration
- **Input**  
  - `inputrc.config` – Readline settings for CLI usability
- **X11**  
  - `xinitrc.config` – X session startup script

## Usage

Symbolically link the desired `.config` files to their respective destinations. For example:

```bash
ln -s /path/to/repo/vimrc.config ~/.vimrc
```
