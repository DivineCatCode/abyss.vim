## Abyss.vim

*abyss.vim* is a dark blue theme for vim.

## Installation

1. Add `Plug 'ulwlu/abyss.vim'` in your .vimrc within vim-plug's loading function.
2. Run `:PlugInstall`
3. Activate by `colorscheme abyss`
4. Use `set termguicolors` as well

## Issues
This theme is in early development. If you find some bugs, please submit a issue. If some highlight is strange, please submit an issue with a result of a command below.

```
:echo "hi<" . synIDattr(synID(line("."),col("."),1),"name") . '> trans<' . synIDattr(synID(line("."),col("."),0),"name") ."> lo<" . synIDattr(synIDtrans(synID(line("."),col("."),1)),"name") . ">"<CR>
```

## Thanks

- [ayu-vim](https://github.com/ayu-theme/ayu-vim) - I use this theme for three years. I used the code as a reference.
- [vim-one](https://github.com/rakr/vim-one) - I used the code of airline autoload as a reference.
