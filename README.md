# mega65-vim-acme
Syntax highlighting for the ACME 6502/4510/45GS02-family assembler

## Install

### [Vim-plug](https://github.com/junegunn/vim-plug) Users

Put
```vim
Plug 'titanlab/mega65-vim-acme'
```
into your plugged-section in your ```~/.vimrc``` and run
```vim
:PlugInstall
```

### Other Users

```bash
git clone git@github.com:titanlab/mega65-vim-acme.git
ln -s vim-acme/ftdetect/acme.vim ~/.vim/ftdetect/.
ln -s vim-acme/syntax/acme.vim ~/.vim/syntax/.
```
