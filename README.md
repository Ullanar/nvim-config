# Nvim config

Install vim-plug for nvim

```sh
sh -c 'curl -fLo "${XDG_DATA_HOME:-$HOME/.local/share}"/nvim/site/autoload/plug.vim --create-dirs \
       https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim'
```
Insatall and build CoC (autocomplete support)
```sh
cd .local/share/nvim/plugged/coc.nvim/
```
```sh
yarn install
```
```sh
yarn build
```

Install CoC Ext
```vim
:CocInstall coc-tsserver coc-json coc-pyright coc-markdownlint coc-html coc-css
```
