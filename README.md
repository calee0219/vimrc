# Gavin Lee's vimrc settlement

This is [Gavin Lee's](https://github.com/calee0219) vimrc settlement.

In the last version, I just used [amix's vimrc](https://github.com/amix/vimrc), and copy the rc script from [vgod's vimrc](https://github.com/vgod/vimrc), and add some [appending tool](vimrcs/append) copy from [ma6174](https://github.com/ma6174/vim) to improve it

After a few week later, I suppose to modify my own vimrc setting because the last version is to hard to reallize and maintain. I hugely recommand you to modify your own vim setting for your own style. It will be the best vim setting for you!!!

I uniformly used [Vundle](https://github.com/VundleVim/Vundle.vim) to contral my vim plugin.

## How to install
#### Auto Install
* Use curl (for Mac OS X):
```shell
    curl -o - https://github.com/calee0219/vimrc/master/auto_install.sh | sh
```
* or wget (for most UNIX platforms):
```shell
    wget -O - https://github.com/calee0219/vimrc/master/auto_install.sh | sh
```

#### Manually Install
* First, type the command below in your termainal or cmd
```shell
git clone https://github.com/calee0219/vimrc.git ~/.vim
cd ~/.vim
```

* Then, type:
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

##Recommanding plugin


" plugin repo on GitHub
Plugin 'tpope/vim-sensible'                 " This is for some sensible layout
Plugin 'Valloric/YouCompleteMe'             " This is for auto complete
Plugin 'scrooloose/nerdtree'                " This is for NERDtree
Plugin 'jistr/vim-nerdtree-tabs'            " This is for bettering NERD
Plugin 'Xuyuanp/git-nerdtree'               " This is also for bettering NERDtree
Plugin 'scrooloose/nerdcommenter'           " This is for section comment
Plugin 'tpope/vim-fugitive'                 " This is for git in vim
Plugin 'tpope/vim-surround'                 " This is for change brackets
Plugin 'scrooloose/syntastic'               " This is for syntax checking
Plugin 'kien/ctrlp.vim'                     " This is for keyword searching
Plugin 'ervandew/supertab'                  " This is for using <Tab> for all your insert completion needs
Plugin 'jiangmiao/auto-pairs'               " This is for auto complete brackets
"Plugin 'cohama/lexima.vim'                 " This is for auto complete brackets
"Plugin 'Raimondi/delimitMate'              " This is for auto complete brackets
"Plugin 'fisadev/fisa-vim-config'           " This is for vim python IDE
Plugin 'vim-airline/vim-airline'            " This is for awesome outlook
Plugin 'vim-airline/vim-airline-themes'     " This is for awesome outlook
Plugin 'altercation/vim-colors-solarized'   " This is for better syntax
Plugin 'majutsushi/tagbar'                  " This is for an easy way to browse the tags
Plugin 'tomtom/tlib_vim'                    " This is for utility vim functions
Plugin 'SirVer/ultisnips'                   " This is for SirVer/ultisnips
Plugin 'airblade/vim-gitgutter'             " This is for making git easer to use
Plugin 'rking/ag.vim'                       " This is for better diff using ag
Plugin 'humiaozuzu/tabbar'                  " This is for better tabbar
