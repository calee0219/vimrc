# Gavin Lee's vimrc settlement

This is [Gavin Lee's](https://github.com/calee0219) vimrc settlement.

Basically, I just used [amix's vimrc](https://github.com/amix/vimrc).

I have also copy the rc script from [vgod's vimrc](https://github.com/mattn/emmet-vim).

I also add some [appending tool](vimrcs/append) to improve it

## How to install
* First, type the command below in your termainal or cmd
```shell
git clone https://github.com/calee0219/vimrc.git ~/.vim
cd ~/.vim
```

* (On Linux) If you don't have python and pip or you're not sure what's this, type:
```shell
sudo preinstall.sh
```

* (On Windows) Just go [here](https://www.python.org/) to download and install python.

* Last, type:
```shell
chmod 755 ~/.vim/install_vimrc.sh
sudo ~/.vim/install_vimrc.sh
```
That's it!

## Add your own rc script

If you want to add your own rc script, I recommend to add it in [~/.vim/vimrcs/my.vimrc](vimrcs/my.vimrc)

Of couse, you can also add it in [~/.vim/my_configs.vim](my_configs.vim) or just add it in ~/.vimrc

## Auto title

If you want to create files with title automatically set on it,

   such as: in C++ file, adding #indlude\<iostream\>...

you can add tax into [vimrcs/append/tital](vimrcs/append/tital)
