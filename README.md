Here are my dotfiles.

To set up a new machine, run the following commands:

```bash
sudo pacman -S stow
git clone https://github.com/prenaissance/dotfiles ~/.dotfiles
cd ~/.dotfiles
./setup.sh
```

To synchronize installed pacman and AUR packages, run:

```bash
pacman -Qmeq > ~/.dotfiles/pacman/aur.txt
pacman -Qneq > ~/.dotfiles/pacman/pacman.txt
```
