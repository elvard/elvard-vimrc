Elvard's .vimrc
===============

Nothing amazing nor special, just gathered pieces of code from various sources.

It's mainly aimed at Python right now. There's some strange bug in *autoclose* 
plugin which cause problems with using arrow keys in insert mode. Setting 
term=linux is supposed to be workaround for this issue, but arrow keys are
still buggy.

Requirements
------------

  * pyflakes
  * terminal with 256-color support (like patched rxvt-unicode)

Install
-------

::

    git clone git://github.com/elvard/elvard-vimrc.git .vim

    # All plugins in bundle are submodules, so…
    cd .vim
    git submodule init
    git submodule update
    ln -s '~/.vim/vimrc' ~/.vimrc
