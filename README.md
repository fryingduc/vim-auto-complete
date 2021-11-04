# vim-auto-complete
## Installation
1. Clone this repository or just copy the content of words.txt.
2. Install [this plugin](https://github.com/vim-scripts/AutoComplPop).
3. Add this to your .vimrc:
```vim
setlocal complete+=k    " or kspell
setlocal dictionary+=<path to words.txt>    " Ex: /home/kh0i/file/words.txt
set completeopt=menuone,longest
set shortmess+=c
```
