# Symlink

Symbolic links are great in Linux. But in Windows it sucks. In Windows the only option we have is to use [Link Shell Extension](https://schinagl.priv.at/nt/hardlinkshellext/linkshellextension.html).

**Symlink a folder**
```sh
ln -fs ~/.dotfiles/.config ~
```
**Symlink a file**
```sh
ln -fs ~/.dotfiles/.tmux.conf ~
```
[Symlink Tutorial in Linux – How to Create and Remove a Symbolic Link](https://www.freecodecamp.org/news/symlink-tutorial-in-linux-how-to-create-and-remove-a-symbolic-link/)