# NCL Tags

|from|tags|
|---|---|
|[ncl.dic](http://www.ncl.ucar.edu/Applications/Files/ncl.dic)|[ncl_dic_tags.txt](./ncl_dic_tags.txt)|
|[NCL_functions.txt](https://github.com/aaronspring/ncl_lazy_vim/blob/master/.vim/NCL_functions.txt)|[ncl_functions_tags.txt](./ncl_functions_tags.txt)|

## Usage

```viml
autocmd FileType ncl setlocal tags+=~/path_to/ncl_functions_tags.txt

" ycm
let g:ycm_collect_identifiers_from_tags_files = 1
```

## License

[MIT](./LICENSE)
