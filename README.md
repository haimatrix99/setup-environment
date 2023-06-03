# setup-environment


## Setup VIM Text Editor
```bash
git clone --depth=1 https://github.com/amix/vimrc.git ~/.vim_runtime
sh ~/.vim_runtime/install_awesome_vimrc.sh
```

## Setup One Dark Theme in VIM
```bash
cat > ~/.vim_runtime/my_configs.vim << EOF
call plug#begin('~/.vim/plugged')
    Plug 'joshdick/onedark.vim'
call plug#end()
EOF

echo "syntax on\ncolorscheme onedark" >> ~/.vimrc
```
