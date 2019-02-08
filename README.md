# Setup for ruby/puppet dev

My ~/.vimrc
```
execute pathogen#infect()
syntax on
filetype plugin indent on
set sw=4
set ts=4
:autocmd Filetype ruby set softtabstop=2
:autocmd Filetype ruby set sw=2
:autocmd Filetype ruby set ts=2

:autocmd Filetype puppet set softtabstop=2
:autocmd Filetype puppet set sw=2
:autocmd Filetype puppet set ts=2
```

Usage:
```
cd ~/.vim && git clone git@github.com:elmobp/vim-setup.git .
```

This will handle pathogen ect, puppet snippets have also been customised
