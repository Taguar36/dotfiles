# My dotfiles

This directory contains the dotfiles of my system

## Requirements

Ensure you have the following installed on your system

### Git

```
pacman -S git
```

### Stow

```
pacman -S stow
```

## Installation

First, check out the dotfiles repo in your $HOME directory using git

```
$ git clone git@github.com:Taguar36/dotfiles.git
$ cd dotfiles
```

then use GNU stow to create symlinks

```
$ stow .
```


> [!IMPORTANT]
> https://www.youtube.com/watch?v=y6XCebnB9gs
