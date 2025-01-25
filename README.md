# App Configurations

If you want to use GNU Stow to manage your dotfiles then if you are on a Debian based system, install GNU Stow:
```
sudo apt install stow
```

Then clone this repository into **~/** to have the dotfiles be located in the ~/dotfiles directory. 

To install the starship files:
```
stow starship
```

This will create a symlink: ~./config/starship.toml pointing to: ~/dotfiles/starship/.config/starship.toml

