## install ##
* mv govim .vim
* ln -s .vim/vimrc .vimrc
#install autocomplete plugin, but need high-version vim
cd ~/.vim/bundle 
git clone https://github.com/Shougo/neocomplete.vim.git
cd ~/.vimrc
#add 
let g:neocomplete#enable_at_startup = 1
#and if you want to know details of other plugins, please go to
#https://wuwen.org/2014/7/1/setup-vim-go-dev-environment.html
