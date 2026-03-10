# My Dotfiles

My portable configs — clone everything or just what you need.

## Quick Install

```bash
bash <(curl -s https://raw.githubusercontent.com/itme-brain/dotfiles/main/install)
```
OR
```bash
./install
```

Interactive menu lets you pick which configs to install. Each one is cloned as its own repo — no dependency on this dotfiles repo.

## Configs

| Config | Repo | Location | What it is |
|--------|------|----------|------------|
| **bash** | [itme-brain/bash](https://github.com/itme-brain/bash) | `~/.config/bash` | Bash config with aliases, prompt, and functions |
| **git** | [itme-brain/git](https://github.com/itme-brain/git) | `~/.config/git` | My global git config and ignores |
| **vim** | [itme-brain/vim](https://github.com/itme-brain/vim) | `~/.vim` | Lightweight vim for servers and quick edits. Plugins auto-install on first run |
| **nvim** | [itme-brain/nvim](https://github.com/itme-brain/nvim) | `~/.config/nvim` | Full IDE setup with LSP, treesitter, telescope |

## Install one at a time

```bash
git clone git@github.com:itme-brain/bash.git ~/.config/bash && echo "source ~/.config/bash/bashrc" >> ~/.bashrc
git clone git@github.com:itme-brain/git.git ~/.config/git
git clone git@github.com:itme-brain/vim.git ~/.vim
git clone git@github.com:itme-brain/nvim.git ~/.config/nvim
```

## Updating

Each config is its own repo. Just pull:

```bash
cd ~/.config/bash && git pull
cd ~/.config/git && git pull
cd ~/.vim && git pull
cd ~/.config/nvim && git pull
```

## Requirements

`git` and `curl`
