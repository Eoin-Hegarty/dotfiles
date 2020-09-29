# What is this?
These are Matthew McCullough's shell configuration dotfiles. The primary goal is to increase CLI productivity on Mac OSX, though many scripts run just fine on any POSIX implementation.

# Focus
The focus is on Zshell support, but there are plenty of cross-platform scripts in here. There are a few bash-specific ones.

# Inspirations
The contents of this repo have been partly invented from scratch, partly inspired by open source projects, and partly refactored from snippets from colleagues and friends. Many are attributed.

# Acquiring This Repo
This project contains submodules. It is suggested that you clone this into your home directory.

    cd ~
    git clone --recurse-submodules https://github.com/matthewmccullough/dotfiles .dotfiles

# Setup
There is a set up script that establishes the symlinks in your home directory. Run this once.

* For ZShell
        ~/.dotfiles/_setupdotfiles.zsh
* For Bash (needs some fixes)
        ~/.dotfiles/_setupdotfiles.bsh

> NOTE: Some personal configuration of Matthew's will remain after setup. These dotfiles are intended for your inspiration, forking, and for you to tweak to your specific needs.

# Non-automated, non-captured config

Reminder-to-self: Some additional personalization lives in the `~/.config/` directory.  Specifically, the `~/.config/gh/config.yml` file for [`gh`](https://cli.github.com). It is not yet in scope for capture or copy, but some uers have [shared their configuration in a Gist](https://gist.github.com/vilmibm/a1b9a405ac0d5153c614c9c646e37d13).

# Contributions
Contributions are always welcome in the form of pull requests with explanatory comments.

# Loathing, Mehs and Praise
1. Loathing should be directed into pull requests that make it better.
2. Bugs with the setup should be put as GitHub issues.
3. Mehs should be directed to /dev/null
4. Praise should be directed to [@matthewmccull](http://twitter.com/matthewmccull) on Twitter
