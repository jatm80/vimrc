#Installing deoplete-go:

1) Install gocode 
```
go install github.com/stamblerre/gocode@latest
```

2) Then add ${HOME}/go/bin to the PATH in .bashrc:
``` 
export PATH=$PATH:/${HOME}/bin/go
```

#Installing vimrc: 
1) Copy vimrc file into home directory.  In Linux ~/.vimrc 
2) Run  `vim +PlugInstall +qall`

#References:
- https://vim-bootstrap.com/ (used to bootsrap initial version of vimrc )
