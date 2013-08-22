VIMRC
=====

My personal settings for VIM.

Setup and Installation
----
This setup includes (for now) a custom .vimrc.after file, and my .fonts directory.
This will only work as expected with [Janus](https://github.com/carlhuda/janus) and [Airline](https://github.com/bling/vim-airline) installed (and patched).

To Install
----

- Install janus
- Clone this repo
- If ~/.vimrc.after exists replace it with the one from here, otherwise copy it to your home directory
- Copy the contents of my .fonts directory into ~/.fonts and run fc-cache -vf ~/.fonts/
- Clone powerline into ~/.vim/.janus
- Open gvim and make sure that all the icons are correct and the plugins are installed
- Enjoy!!
