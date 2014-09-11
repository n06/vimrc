VIMRC
=====

My personal settings for VIM.

Setup and Installation
----
This setup includes (for now) a custom .vimrc.after file, and my .fonts directory.
This will only work as expected with [Janus](https://github.com/carlhuda/janus) and [Airline](https://github.com/bling/vim-airline) installed.

To Install
----

- Install janus
- Clone this repo
- If ~/.vimrc.after exists replace it with the one from here, otherwise copy it to your home directory
- Copy the contents of my .fonts directory into ~/.fonts and run fc-cache -vf ~/.fonts/
- Clone powerline into ~.janus (if the .janus/ directory does not exist, create it).
- Open gvim and make sure that all the icons are correct and the plugins are installed
- Enjoy!!

Includes
----
This vim setup includes [Janus](https://github.com/carlhuda/janus) and all of its default plugins,
[Airline](https://github.com/bling/vim-airline) which is a beautiful vim status line,
and my own custom made .vimrc.after which includes the following customizations:

- Sets airline for gvim
- All tabs are now 4 spaces.
- Shows you any trailing whitespace and tab characters
- (Default off) sets linewrap at 72
- (Default off) removes any trailing whitespace when saving the file.
