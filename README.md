# Mario Yepes DotFiles

This is fork of mathiasbynens dotfiles `https://github.com/mathiasbynens/dotfiles`


## Installation
```bash
git clone https://github.com/marioy47/dotfiles.git && cd dotfiles && ./bootstrap.sh
```

To update, `cd` into your local `dotfiles` repository and then:

```bash
git pull origin master && ./bootstrap.sh
```

### Add custom commands without creating a new fork

If `~/.extra` exists, it will be sourced along with the other files. You can use this to add a few custom commands without the need to fork this entire repository, or to add commands you don’t want to commit to a public repository.

You could also use `~/.extra` to override settings, functions and aliases from my dotfiles repository. It’s probably better to [fork this repository](https://github.com/mathiasbynens/dotfiles/fork) instead, though.

### Sensible OS X defaults

When setting up a new Mac, you may want to set some sensible OS X defaults:

```bash
./.osx
```

## Powerline fonts
Install Powerline fonts from  `http://github.com/powerline/fonts.git` and configure your terminal to use one of the provided fonts

## Install Homebrew formulae
When setting up a new Mac, you may want to install some common [Homebrew](http://brew.sh/) formulae (after installing Homebrew, of course):

```bash
./brew.sh && brew-cask.sh
```

### OH MY ZSH
I prefer z shell instead of bash. So go ahead and install it
```bash
sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```

