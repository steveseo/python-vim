# Python-Vim

This is a document for setting up a Vim environment for Python and other languages developers.

### Install [Pretty-Vim-Python](https://github.com/pfdevilliers/Pretty-Vim-Python):
  - make sure that you already had .vim directory.
  - If you don't .vim directory, create .vim directory.
```sh
$ mkdir ~/.vim
$ cd ~/.vim
```
  - Clone the Pretty-Vim-Python repository and move them to .vim directory.
```sh
$ git clone https://github.com/sentientmachine/Pretty-Vim-Python.git
$ mv Pretty-Vim-Python/* .
$ rm -rf Pretty-Vim-Python
```

### Change Vim environment setting
Every developrs have their own Vim setting(.vimrc file), but I would like to recommend the following settings for you, especially colorscheme. You can easily add, delete, or change any setting values.

```
set autoindent
set tabstop=4
set shiftwidth=4
set softtabstop=4
set expandtab
syntax on
set number
colorscheme molokai
highlight Comment cterm=bold
```

# HAPPY CODING!

