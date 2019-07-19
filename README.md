###Homebrew
https://brew.sh/

###Setup zsh
```
sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
cp .zshrc ~/
```
https://denysdovhan.com/spaceship-prompt/#installing

###Setup vim

```
cp .vimrc ~/
mkdir -p ~/.vim/autoload ~/.vim/bundle && \
curl -LSso ~/.vim/autoload/pathogen.vim https://tpo.pe/pathogen.vim
cd ~/.vim/bundle
git clone https://github.com/ciaranm/detectindent
git clone https://github.com/ervandew/supertab
git clone https://github.com/robbevan/vagrantfile.vim
git clone https://github.com/sheerun/vim-polyglot
git clone https://github.com/tpope/vim-sensible.git
git clone https://github.com/flazz/vim-colorschemes.git 
git clone https://github.com/felixhummel/setcolors.vim.git
git clone https://github.com/tpope/vim-surround.git
git clone https://github.com/ctrlpvim/ctrlp.vim.git
```

###dev envs
```
brew install rbenv
```
https://github.com/nvm-sh/nvm


### Iterm
use `hardcore` color scheme

