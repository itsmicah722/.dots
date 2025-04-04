# Dotfiles

These are my *work-in-progress* dotfile configurations for Hyprland in Arch Linux; will later be merged with my [simple-arch](https://github.com/itsmicah722/simple-arch) repository. This is designed specifically for me personally but I am making it public if anyone finds it handy or interesting. 

> **NOTE:** I'm an amateur in both Arch Linux and dotfile configurations of any kind *(Ricing)* 

Guide in development: [here](docs/setup.md)

## Structure

The directory & file layout of this codebase will attempt to follow the [XDG Base Directory](https://github.com/itsmicah722/simple-arch) specification standards. All of the actual *Dotfiles* will be stored in our cloned repo: `~/.dots`, and use the [GNU Stow](https://www.gnu.org/software/stow/manual/stow.html#Introduction) tool to manage the configurations with Git VCS. In Arch Linux, most packages like neovim or hyprland will use configurations for their apps. These configurations are typically located in the `~/.config` directory, which we will link to our repository. This will allow us to have all of our dots in one directory (i.e. this repository), while still maintaining all of the correct config locations in the linux filesystem. 