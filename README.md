# This is repo for my vim config

## setup 

### clone Vundle
```
git clone https://github.com/gmarik/Vundle.vim.git ~/.vim/bundle/Vundle.vim
```

### install pathogen

```
mkdir -p ~/.vim/autoload ~/.vim/bundle && \
curl -LSso ~/.vim/autoload/pathogen.vim https://tpo.pe/pathogen.vim
```

### get .vimrc
```
wget https://raw.githubusercontent.com/otzhora/vim-config/master/vimrc -O ~/.vimrc
```

### install plugins 

```
vim
:PluginInstall
```
