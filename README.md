# My dotfiles

This directory contains the dotfiles for my system

## Requirements

Ensure you have the following installed on your system

### Git

On Arch and Debian,

```
sudo pacman -S git
```

On Ubuntu,

```
sudo apt install git
```

On RHEL-based systems (RedHat Enterprise Linux, Fedora, CentOS, Oracle Linux, Rocky, etc.)

```
sudo dnf install git
```

### Stow

```
pacman -S stow
```

On Ubuntu,

```
sudo apt install stow
```

On RHEL-based systems

```
sudo dnf install stow
```

## Installation

First, check out the dotfiles repo in your $HOME directory using git

```
$ git clone git@github.com:dreamsofautonomy/dotfiles.git
$ cd dotfiles
```

then use GNU stow to create symlinks (-v makes stow tell us what it's doing while it's doing it)

```
$ stow -v .
```
