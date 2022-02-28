# What is this?
These are Eoin's shell configuration dotfiles. The goal is to increase CLI productivity on Linux (mainly Ubuntu) and OSX, though many scripts run just fine on any POSIX implementation.

# Focus
The focus is on Bash support.

# Inspirations
The contents of this repo are based on Matthew McCullough's original (https://github.com/matthewmccullough/dotfiles) and Jim Lawton's additions to them (https://github.com/jimlawton/dotfiles) with some slight tweaks for my own use.

# Acquiring This Repo
This project contains submodules. It is suggested that you clone this into your home directory.

    cd ~
    git clone --recurse-submodules https://github.com/jimlawton/dotfiles

# Setup

Personalisation settings are in `personalisation`. Replace the values with your
own.

There is a set up script that establishes the symlinks in your home directory. Run this once. *Note:* You need to set MOVE=true on your first run.
```console
$ ~/dotfiles/_setupdotfiles.sh
```

> NOTE: Some of my personal configuration will remain after setup. You should fork and tweak to your specific needs.

# Non-automated, non-captured config
The `~/.gitconfig` will be pointing at `~/dotfiles/gitconfig`.
Running a `cp ~/dotfiles/gitconfig-macos ~/dotfiles/gitconfig` fixes the issue on macos. Similar workaround for linux.

Setting up zsh is done via:
```console
$ ~/dotfiles/_setupzsh.sh
```

# Contributions
Contributions are always welcome in the form of pull requests with explanatory comments.
