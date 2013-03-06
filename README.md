# liquidsoap.vim

Vim syntax highlighting for liquidsoap scripts.

## INSTALL

Use your favorite vim package manager, I like Vundle.

```
Bundle 'mcfiredrill/vim-liquidsoap'
```

Then run `:BundleInstall`.

You also probably want to add this to your .vimrc to .liq files are detected:

```
au BufRead,BufNewFile *.liq setfiletype liquidsoap
```
