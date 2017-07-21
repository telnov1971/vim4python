# vim4pyton
My setting to vim for working with Python

Found on the https://github.com/Relrin/dotfiles plus my addons

Repeat from ...

Dotfiles for VIM/Conky/etc.
F.A.Q.

Q: What can I find there?
A: You can find there my settings for VIM/conky/etc. programms

Q: Can i steal this?
A: Of course, you can use this easily
How to install my VIM settings

    Installing VIM lastest version (skip this step, if already installed):

sudo add-apt-repository ppa:fcwu-tw/ppa
sudo apt-get update
sudo apt-get install vim

    Install powerline-fonts for vim-airline

    Install Vundle plugin

git clone https://github.com/gmarik/Vundle.vim.git ~/.vim/bundle/Vundle.vim

    Clone my repository somewhere and copy settings:

git clone https://github.com/Relrin/dotfiles.git ~/Downloads/dotfiles/
cp -r ~/Downloads/dotfiles/vim/* ~/.vim/
mv ~/Downloads/dotfiles/vim/.vimrc ~/

    Run VIM and enter:

:PluginInstall

    Restart VIM and get fun ;)
