# dotfiles.daykoo
Make sure to clone the repo with submodules:
```bash
git clone --recurse-submodules git@github.com:D4ykoo/dotfiles.daykoo.git
```

## Current managed dotfiles
- git
- neovim

## Basic commands
**Add dotfiles:** `stow <dir1> <dir2> <dir3>`  
**Remove dotfiles:** `stow -D <dir>`  
**Refresh:** `stow -R`  
**Test dotfiles symlink:**  `stow --simulate -v <dir>`  
