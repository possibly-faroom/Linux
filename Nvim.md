# Neovim

neovim is one of the best terminal editor, with the right plugins it could be super powerfull. preferably i would use the lua script feature.

For the icons it'll be handled by the [[Fonts#Nerd Font|NerdFont]]

my end goal is to make something similar to [NvChad](https://github.com/NvChad/NvChad), and [LunarVim](https://github.com/LunarVim/LunarVim)

i'll create my own plugin for the themes and use one of the collor pallets from [[Collor Palletes]]

# Plugins
My prefered package manager is the [packer](https://github.com/wbthomason/packer.nvim) package manager, which is reliabel


### [alpha-nvim](https://github.com/goolord/alpha-nvim)

![[alpha_nvim.png]]

alpha vim is used for making the start menu when just running plain ` nvim `

```lua
use {
    'goolord/alpha-nvim',
    requires = { 'kyazdani42/nvim-web-devicons' },
    config = function ()
        require'alpha'.setup(require'alpha.themes.startify'.config)
    end
}
```



