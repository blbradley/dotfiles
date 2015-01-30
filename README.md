dotfiles
--------

my dotfiles using [GNU Stow](http://www.gnu.org/software/stow/)


Programs Managed
================

* pyenv
* IPython
* vim
* zsh


Ubuntu
======

I wrote this without testing it. Is it possible to keep separate environments too?

	sudo apt-get install git stow
	cd ~
	git clone https://github.com/blbradley/dotfiles && cd dotfiles
	git submodule init
	stow vim
	stow ...

Notes
=====

* Programs and their plugins should be managed via separate directories to avoid nested git submodule. They are a nasty beast.
