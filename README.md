# vim-metarw-redmine.vim

We'll given the power of vim into redmine.
(You can use redmine from vim.)

## installation
```vim
" dein.vim
call dein#add('zebult/vim-metarw-redmine.vim')
" neobundle.vim
NeoBundle 'zebult/vim-metarw-redmine.vim'
```

## Dependences
- kana/vim-metarw

## Usage
```vim
:e redmine:
```

## Settings
```vim
let g:metarw_redmine_server = 'http://xxx.xxx'
let g:metarw_redmine_apikey = 'xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx'
let g:metarw_redmine_projectkey = '3'
let g:metarw_redmine_queryid = '5'
```

