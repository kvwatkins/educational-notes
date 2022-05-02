# General Notes

## VMWare

- slow snapshots
  
``` 
mainMem.ioBlockPages = "4096" 
mainMem.iowait = "0" 
```

## Vim 

- Setting tabs to 2 spaces add to .vimrc
  
``` filetype plugin indent on
" show existing tab with 4 spaces width
set tabstop=4
" when indenting with '>', use 4 spaces width
set shiftwidth=4
" On pressing tab, insert 4 spaces
set expandtab 
```
- Convert all tabs to spaces :retab after the above is set

## Haskell

|  Description     | Explanation  |
| -------------    |:-------------|
| Turn off prelude | In a module ```{-# LANGUAGE NoImplicitPrelude #-}``` or in ghci ```:set -XNoImplicitPrelude``` followed by ```:m -Prelude```
| Set ghci Editor  | :set editor vim.
| Edit from ghci   | :edit
| run shell script | :! some shell command