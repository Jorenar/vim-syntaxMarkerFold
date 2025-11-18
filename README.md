syntaxMarkerFold
================

Emulates marker folds while using _syntax_ [`foldmethod`](https://vimhelp.org/fold.txt.html#fold-methods)

## Installation

#### [vim-plug](https://github.com/junegunn/vim-plug):
```vim
Plug 'Jorenar/vim-syntaxMarkerFold'
```

#### Vim's packages
```bash
cd ~/.vim/pack/plugins/start
git clone git://github.com/Jorenar/vim-syntaxMarkerFold.git
```

## Usage

You only need to install this plugin and have `foldmethod` set to `syntax`.
Markers should behave the way described in `:h fold-marker` (except `zf`
and `zd` mappings).

## Configuration

By default the max level of leveled marker (i.e. `{{{1`, `{{{2`, ...) is limited
to 5. If you wish to increase it, set `g:syntaxMarkerFold_maxlevel` to desired
value (local to buffer `b:syntaxMarkerFold_maxlevel` is also available).

Matching pairs markers are independent from this variable.

#### Minimal _vimrc_ setup
```vim
filetype plugin on  " must be before `syntax enable`
syntax enable
set foldmethod=syntax
```
