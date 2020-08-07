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

### install YouCompleteMe

follow instructions from [docs](https://github.com/VundleVim/Vundle.vim)

To install stuff on ubuntu 18.04 use these commands:

```
sudo apt install gnupg ca-certificates
sudo apt-key adv --keyserver hkp://keyserver.ubuntu.com:80 --recv-keys 3FA7E0328081BFF6A14DA29AA6A19B38D3D831EF
echo "deb https://download.mono-project.com/repo/ubuntu stable-bionic main" | sudo tee /etc/apt/sources.list.d/mono-official-stable.list
sudo apt update
sudo apt install mono-devel

sudo add-apt-repository ppa:longsleep/golang-backports
sudo apt update
sudo apt install golang-go

sudo apt install nodejs
sudo apt install npm
```

if it fails and with python error try these: 

```
export PYTHON_CONFIGURE_OPTS="--enable-shared"
pyenv install some.python.version
pyenv global some.python.version
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
