dotfiles
========

my dotfiles using [GNU Stow](http://www.gnu.org/software/stow/)


Programs Managed
----------------

* pyenv
* IPython
* vim
* zsh


Requirements
------------

**Ubuntu**

	sudo apt-get install git stow

**OSX**

	brew install stow


Usage
-----
	cd ~
	git clone https://github.com/blbradley/dotfiles && cd dotfiles
	git submodule init
	git submodule update
	stow vim
	stow ...


Notes
-----

* Programs and their plugins should be managed via separate directories to avoid nested git submodule. They are a nasty beast.
* Is it possible to keep separate environments too?
