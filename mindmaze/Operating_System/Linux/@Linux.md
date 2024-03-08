# Linux

## Why [[Debian]] based distro?
- It's almost always stable.
- Most of the app are officially supported for Debian.
	- Ex: VSCode doesn't have official package for [[Arch Linux]]

## Initial Setup
On a freshly installed machine, always update and upgrade the system.
```sh
sudo apt install update && sudo apt install upgrade -y
```
As we keep on adding more packages to the system, new [[dotfiles]] are getting generated (NOT always). So, keeping track of the initial setup process can help us to create a [[bash script]].

>[!info]
> I have created a installation script. It is at a very early stage. As I keep learning new things, I will keep update the script.
> [HYP3R00T/.dotfiles](https://github.com/HYP3R00T/.dotfiles)

### Favorite Packages
- shell
	- zsh
		- zsh-autocompletions
		- zsh-syntax-highlighting
	- starship.rs
	- Article (https://harshithashok.com/tools/oh-my-zsh-with-starship/)
- utils
	- nala (apt wrapper)
	- neofetch
	- htop
	- tmux
	- GNU stow (to manage dotfiles using [[symlink]])