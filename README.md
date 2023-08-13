vim-odoo-snippets
=================

This repository contains snippets files for Odoo, for the famous [coc-snippets](https://github.com/neoclide/coc-snippets) plugin for Vim.

Note
----
This work is derived from module made for UltiSnips

How to install
-------------
Using [Vim-Plug](https://github.com/junegunn/vim-plug)
-------------

Add the following code in your vimrc
```Vim
    " Install CoC
    Plug 'neoclide/coc.nvim', {'branch': 'release'}
```

Then copy the current snippets files from ultisnips directory to ~/.config/coc/ultisnips
```bash
cp ultisnips/*.snippets ~/.config/coc/ultisnips/
```

Then run

```Vim
    :PluginInstall
    :CocInstall coc-snippets
```

Contribution
-------------

If you would like to contribute to this project, then just fork it in GitHub and send a pull request.

License
-------------

The source code and the config files are released under "THE BEER-WARE" license. http://en.wikipedia.org/wiki/Beerware ;) (if possible belgium beer, the best of the world)

