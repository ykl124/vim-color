White style theme For vim

create by KELLY base on molokai date: 2017-05-29

How to use ?

download /colors/*.vim file to your computer
move colors file to path: ~/.vim/colors/*.vim
modify ~/.vimrc like this:

  syntax enable
  syntax on
  " display number
  set nu
  " display cursor position
  set ruler
  " highlight current line
  set cursorline
  " when a file is not save or read-only, a confirmation dialog pops up
  set confirm
  " enable file type detection
  filetype on
  " according to file type load different plug-in
  filetype plugin on
  " set background theme
  set background=light
  " the name of your theme file in `~/.vim/colors/`, do not contain suffix
  colorscheme Kelly
enjoy it
