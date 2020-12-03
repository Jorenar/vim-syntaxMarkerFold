syntaxMarkerFold
================

Markers while using syntax fold method

## Installation

#### [minPlug](https://github.com/Jorengarenar/minPlug):
```vim
MinPlug Jorengarenar/vim-syntaxMarkerFold
```

#### [vim-plug](https://github.com/junegunn/vim-plug):
```vim
Plug 'Jorengarenar/vim-syntaxMarkerFold'
```

#### Vim's packages
```bash
cd ~/.vim/pack/plugins/start
git clone git://github.com/Jorengarenar/vim-syntaxMarkerFold.git
```

## Configuration

By default the max level of leveled marker (i.e. `{{{1`, `{{{2`, ...) is limited
to 5. If you wish to increase it, set `g:syntaxMarkerFold_maxlevel` to desired
value (local to buffer `b:syntaxMarkerFold_maxlevel` is also available).

Matching pairs markers are independent from this variable.
