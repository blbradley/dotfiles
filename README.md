dotfiles
========

my dotfiles using [GNU Stow](http://www.gnu.org/software/stow/)


Programs Managed
----------------

* pyenv
* IPython
* vim
* tmux
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

* GNU Stow makes symlinks in your home directory to these files (technically, it symlinks the files up a directory, meaning dotfiles must live in your home directory for the files to be symlinked into ~).
* Programs and their plugins should be managed via separate directories to avoid nested git submodule. They are a nasty beast.
* Is it possible to keep separate environments too?
