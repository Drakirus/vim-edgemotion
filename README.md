## EdgeMotion

[![](http://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![](http://img.shields.io/badge/doc-%3Ah%20edgemotion.txt-red.svg)](doc/edgemotion.txt)

`<Plug>(edgemotion-j)` and `<Plug>(edgemotion-k)` motion is like `j`, `k`, but stops at edge only.

![vim-edgemotion demo](https://raw.githubusercontent.com/haya14busa/i/4f66e3a746b4537397116e60979cc6e09348eb12/vim-edgemotion/vim-edgemotion%202017-11-04%2016-18.gif)

Inspired by EdgeMotion in [atom-vim-mode-plus](https://github.com/t9md/atom-vim-mode-plus)

[vmp: the most ambitious vim emulator](https://qiita.com/t9md/items/236d09fea9bcdfabdcea)

### Usage

```vim
map <C-j> <Plug>(edgemotion-j)
map <C-k> <Plug>(edgemotion-k)
```

The key mapping can be preceded by a number, if so, `edgemotion` will jump X
time.

### Option

```vim
let g:edgemotion#line_numbers_overwrite = 1
```
If the value of this variable is non-zero, `edgemotion` will overwrite the line
numbers, to contain the edgemotion jump count number. (Neovim only)

## Author
haya14busa (https://github.com/haya14busa) & Drakirus (https://github.com/Drakirus/)


## Document
[:h edgemotion.txt](doc/edgemotion.txt)

## Changelog
 - Drakirus add line_numbers_overwrite
 - Drakirus add support for count number
 - haya14busa initial release
