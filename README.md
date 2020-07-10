# NCL Tags

|from|tags|
|---|---|
|[ncl.dic](http://www.ncl.ucar.edu/Applications/Files/ncl.dic)|[ncl_dic_tags.txt](./ncl_dic_tags.txt)|
|[NCL_functions.txt](https://github.com/aaronspring/ncl_lazy_vim/blob/master/.vim/NCL_functions.txt)|[ncl_functions_tags.txt](./ncl_functions_tags.txt)|
|[NCL_resources.txt](https://github.com/aaronspring/ncl_lazy_vim/blob/master/.vim/NCL_resources.txt)|[ncl_resources_tags.txt](./ncl_resources_tags.txt)|

## Usage

```bash
wget https://raw.githubusercontent.com/chuling/ncl_tags/master/ncl_dic_tags.txt
wget https://raw.githubusercontent.com/chuling/ncl_tags/master/ncl_functions_tags.txt
wget https://raw.githubusercontent.com/chuling/ncl_tags/master/ncl_resources_tags.txt
```

```viml
" autocmd FileType ncl setlocal tags+=~/path_to/ncl_dic_tags.txt
autocmd FileType ncl setlocal tags+=~/path_to/ncl_functions_tags.txt
autocmd FileType ncl setlocal tags+=~/path_to/ncl_resources_tags.txt

" ycm
let g:ycm_collect_identifiers_from_tags_files = 1
```

## License

[MIT](./LICENSE)
