## Pre-requests

**Add Nerd fonts to the system**

Can be downloaded [**here**](https://www.nerdfonts.com/).

> [!NOTE]
> In the current configuration the **JetBrainsMono Nerd Font** is used.

**Install fzf**

For installation details, see the fzf [repository](https://github.com/junegunn/fzf).

**Install zsh**

For installation details, see the [zsh installation part](https://github.com/ohmyzsh/ohmyzsh/wiki/Installing-ZSH#install-and-set-up-zsh-as-default).

To copy the configuration file, you can run the following command (it's better to backup your current _.zshrc_):

```
cp ./zsh/.zshrc ~/.zshrc
```

**Install Oh My Posh**

For installation details, see the Oh My Posh [documentation](https://ohmyposh.dev/).

To copy the configuration file, you can run the following command:

```
mkdir -p ~/.config/oh-my-posh

cp ./oh-my-posh/oh-my-posh.toml ~/.config/oh-my-posh/oh-my-posh.toml
```

**Install Alacritty**

For installation details, see the Alacritty [repository](https://github.com/alacritty/alacritty).

To copy the configuration file, you can run the following command:

```
mkdir -p ~/.config/alacritty

cp ./alacritty/alacritty.toml ~/.config/alacritty/alacritty.toml
```

**Install tmux**

For installation details, see the Alacritty [documentation](https://github.com/tmux/tmux/wiki).

To copy the configuration file, you can run the following command:

```
mkdir -p ~/.config/tmux

cp ./tmux/tmux.conf ~/.config/tmux/tmux.conf
```
