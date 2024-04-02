# snippets

My personal snippets for use in vscode or with luasnips in nvim.

https://github.com/L3MON4D3/LuaSnip?tab=readme-ov-file#add-snippets

All of the snippets live in snippets.code-snippets for now. 

## Install

### VSCode

Clone and put `snippets.code-snippets` in `.vscode/`

### nvim

* Clone and put `snippets.code-snippets` in `path/of/your/nvim/config/`

* Load the snippet in your config: `require("luasnip.loaders.from_vscode").lazy_load({ paths = { "./snippets.code-snippets" } })
`

I may end up moving them further into my user config, which is also stored in github and might be more self contained that way
