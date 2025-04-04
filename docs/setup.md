## Packages

Install rust for future packages: 

```rs
sudo pacman -S rustup
```

Use the default stable rust: 

```rs
rustup default stable
```

Download and build paru AUR helper:

```rs
git clone https://aur.archlinux.org/paru.git ~/paru
cd paru && EDITOR=true makepkg -si --noconfirm --needed
```

Install GNU Stow: 

```rs
paru -S stow
```

Install you preferred text editor for editing config files (e.g. neovim, nano, emacs, vscode, etc...):

```rs
# Use your favorite editor 
paru -S neovim
```

Install nerd-fonts:

```rs
paru -S nerd-fonts-fira-code ttf-jetbrains-mono-nerd
```

Install fish: 

```rs
paru -S fish
```

Install starship: 

```rs
paru -S starship
```

## Starship

Make starship use nerd font symbols

```rs
starship preset nerd-font-symbols -o ~/.config/starship/starship.toml
```

Set the default location of the starship config file: 

```rs
export STARSHIP_CONFIG=~/.config/starship/starship.toml
```