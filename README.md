Neovim and terminal configuration
------

This is my Neovim editor setup, with zsh and tmux configurations.
Feel free to fork it
and submit a pull request if you found any bug.

**Warning**: Install script removes all previous configuration (zshrc, oh-my-zsh, nvim, tmux)

Installation
-----------

    $ git clone https://github.com/kristijanhusak/neovim-config.git ~/neovim-config
    $ cd ~/neovim-config
    $ chmod +x ./install.sh
    $ ./install.sh
    $ nvim
    $ :UpdateRemotePlugins

Plugins
----------------

* [k-takata/minpac](https://github.com/k-takata/minpac)
* [Shougo/deoplete.nvim](https://github.com/Shougo/deoplete.nvim)
* [Shougo/neosnippet](https://github.com/Shougo/neosnippet)
* [w0rp/ale](https://github.com/w0rp/ale)
* [Raimondi/delimitMate](https://github.com/Raimondi/delimitMate)
* [manasthakur/vim-commentor](https://github.com/manasthakur/vim-commentor)
* [tpope/vim-surround](https://github.com/tpope/vim-surround)
* [tpope/vim-repeat](https://github.com/tpope/vim-repeat)
* [tpope/vim-fugitive](https://github.com/tpope/vim-fugitive)
* [AndrewRadev/splitjoin.vim](https://github.com/AndrewRadev/splitjoin.vim)
* [airblade/vim-gitgutter](https://github.com/airblade/vim-gitgutter)
* [sheerun/vim-polyglot](https://github.com/sheerun/vim-polyglot)
* [mattn/emmet-vim](https://github.com/mattn/emmet-vim)
* [dyng/ctrlsf.vim](https://github.com/dyng/ctrlsf.vim)
* [junegunn/fzf](https://github.com/junegunn/fzf)
* [junegunn/fzf.vim](https://github.com/junegunn/fzf.vim)
* [ludovicchabant/vim-gutentags](https://github.com/ludovicchabant/vim-gutentags)
* [phpactor/phpactor](https://github.com/phpactor/phpactor)
* [kristijanhusak/vim-js-file-import](https://github.com/kristijanhusak/vim-js-file-import)
* [kristijanhusak/vim-dirvish-git](https://github.com/kristijanhusak/vim-dirvish-git)
* [kristijanhusak/deoplete-phpactor](https://github.com/kristijanhusak/deoplete-phpactor)
* [vimwiki/vimwiki](https://github.com/vimwiki/vimwiki)
* [editorconfig/editorconfig-vim](https://github.com/editorconfig/editorconfig-vim)
* [morhetz/gruvbox](https://github.com/morhetz/gruvbox)
* [justinmk/vim-dirvish](https://github.com/justinmk/vim-dirvish)
* [andymass/vim-matchup](https://github.com/andymass/vim-matchup)
* [haya14busa/vim-asterisk](https://github.com/haya14busa/vim-asterisk)
* [osyo-manga/vim-anzu](https://github.com/osyo-manga/vim-anzu)
* [autozimu/LanguageClient-neovim](https://github.com/autozimu/LanguageClient-neovim)
* [soywod/vim-keepeye](https://github.com/soywod/vim-keepeye)
* [wellle/targets.vim](https://github.com/wellle/targets.vim)

Font used:
* current - [Iosevka](https://github.com/be5invis/Iosevka)
* previous (and on screenshots) - [Inconsolata for powerline](https://github.com/ryanoasis/nerd-fonts/blob/master/patched-fonts/Inconsolata/complete/Inconsolata%20for%20Powerline%20Nerd%20Font%20Complete.otf)

License
-------

This project is licensed under MIT License (see LICENSE file for details). But
each plugin has its own license, so check each one to see what you can do.
