Installation

    git clone git://github.com/PointCloudYC/dotfiles.git

Create required directories:

    mkdir -p ~/.config/nvim
    mkdir -p ~/tmp

Create symlinks:

    ln -s ~/dotfiles/bashrc ~/.bashrc
    ln -s ~/dotfiles/vimrc ~/.vimrc
    ln -s ~/dotfiles/gvimrc ~/.gvimrc
    ln -s ~/dotfiles/vim ~/.vim
    ln -s ~/dotfiles/init.vim ~/.config/nvim/init.vim
    ln -s ~/dotfiles/ctags ~/.ctags
    ln -s ~/dotfiles/jshintrc ~/.jshintrc
    ln -s ~/dotfiles/tmux.conf ~/.tmux.conf
    ln -s ~/dotfiles/gitconfig ~/.gitconfig
    ln -s ~/dotfiles/global-gitignore ~/.gitignore

# VIM #

My preferences for Vim are stored in `dotfiles/vimrc` and `dotfiles/gvimrc`
respectively. All plugins and scripts are stored in the `dotfiles/vim`
directory.

# PYTHON #

TODO