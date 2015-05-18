Dotfiles
========

This is a collection of my dotfiles used on GNU/Linux and Mac OS X.

The files are managed using [rcm](https://github.com/thoughtbot/rcm).


## Contents ##

The dotfiles are related to

- BASH
- GNU Screen
- GNU Stow
- Git
- LaTeX
- R
- Ruby gems
- Vim
- ZSH
- rcrc
- tmux


## Computer specific setup

At home I have one Mac and multiple computers with GNU/Linux.
At work I have a laptop with GNU/Linux and access to (but no administration rights over) servers with GNU/Linux.

Where possible, I use ZSH as my shell and tmux as my terminal multiplexer.
Alternatively, I use BASH and GNU Screen.
To manage this, I have the following setup:

- A `host` folder for my Mac.
- A `tag` for GNU/Linux.
- A `tag` for BASH (that also includes the `screenrc`).

Currently the operating systems only differ in the shell aliases.


## Vim

My one & only editor is Vim and I manage plugins with [Vundle](https://github.com/gmarik/Vundle.vim).
On a fresh install/new user Vundle has to be installed and the plugins have to be downloaded and installed.
As illustrated on the Thoughbots [webpage](https://robots.thoughtbot.com/rcm-for-rc-files-in-dotfiles-repos), this can be accomplished with a hook.

The `.vim` directory is symlinked on the top level (as specified in the `rcrc` file).


## ZSH

My ZSH plugins are managed by [zgen](https://github.com/tarjoilija/zgen).

My `zshrc` file is heavily inspired [Oh My ZSH](https://github.com/robbyrussell/oh-my-zsh).

