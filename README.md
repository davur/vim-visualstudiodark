# Visual Studio Dark Color Scheme for Vim

visualstudiodark is a Vim port of the Dark theme from Visual Studio

256-Color terminal colors are not currently included. For use with 256-Color terminals consider installing 'godlygeek/csapprox'.

## Installation

### Option 1: Manual installation

1.  Move `visualstudiodark.vim` to your `.vim/colors` directory. After downloading the 
    vim script or package:

        $ cd vim-visualstudiodark/colors
        $ mv visualstudiodark.vim /.vim/colors/


### Option 2: Vundle installation ***(recommended)***

1. Download and install gmarik's [Vundle].

2. Add the following to your .vimrc

    Plugin 'dsclementsen/vim-visualstudiodark' " Visual Studio Dark colorscheme

[Vundle]:               https://github.com/gmarik/vundle


### Modify .vimrc

After either Option 1 or Option 2 above, add the following two lines in your 
.vimrc:

    syntax enable
    set background=dark
    colorscheme visualstudiodark
