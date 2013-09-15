# Vim Syntax for ocp-build files

Copy the files "ocpbuildroot.vim" and "ocpbuild.vim" into:
  ~/.vim/syntax/

Then you can add into your "~/.vimrc" the following lines:
```
au BufNewFile,BufRead *.ocp set filetype=ocpbuild
au BufNewFile,BufRead *.root set filetype=ocpbuildroot
```

