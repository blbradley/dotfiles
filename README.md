dotfiles
--------

my dotfiles using [GNU Stow](http://www.gnu.org/software/stow/)


Programs Managed
================

* IPython
* vim


Ubuntu
======

I wrote this without testing it. Is it possible to keep separate environments too?

	sudo apt-get install git stow
	cd ~
	git clone https://github.com/blbradley/dotfiles && cd dotfiles
	git submodule init
	stow vim
	stow ...
