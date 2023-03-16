# Boring

A plain colorscheme for neovim.

<p align="center">
  <img width="985" alt="image" src="https://user-images.githubusercontent.com/5814535/225502226-61082dec-6375-4fe6-a74e-2ae6260ea128.png">
</p>

# Pre-requisites

- Neovim 0.7 or greater.
- `termguicolors` enabled.

# Installing

Using [lazy.nvim](https://github.com/folke/lazy.nvim)

```lua
{
  "anuragsoni/boring.nvim",
  dependencies = {
    "rktjmp/lush.nvim"
  }
}

vim.cmd.colorscheme("boring")
```

Using [packer.nvim](https://github.com/wbthomason/packer.nvim)

```lua
use {
  "anuragsoni/boring.nvim",
  requires = {
    "rktjmp/lush.nvim"
  }
}

vim.cmd.colorscheme("boring")
```

Using [vim-plug](https://github.com/junegunn/vim-plug)

```vimrc
Plug 'rktjmp/lush.nvim'
Plug 'anuragsoni/boring.nvim'

colorscheme boring
```
