Dotfiles @criemen
=================

A simple set of dotfiles, based on [dotbot]: https://github.com/anishathalye/dotbot.

To upgrade your submodules to their latest versions, you could periodically run
`git submodule update --init --remote`.

To install, run either of these options (depending on SSH key availability) for all users
on the affected machine:
* `git clone git@github.com:criemen/dotfiles.git && cd dotfiles && ./install && sudo chsh -s $(which zsh)`
* `git clone https://github.com/criemen/dotfiles.git && cd dotfiles && ./install && sudo chsh -s $(which zsh)`

License
-------

This software is hereby released into the public domain. That means you can do
whatever you want with it without restriction. See `LICENSE.md` for details.
