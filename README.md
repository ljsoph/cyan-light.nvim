# cyan-light.nvim

Basically the default light theme with small tweaks to my liking.

Made with [lush.nvim](https://github.com/rktjmp/lush.nvim)

===

## Installation

(like anyone will use this)

Using `lazy.nvim`

```lua
{
  "ljsoph/cyan-light.nvim",
  dependencies = "rktjmp/lush.nvim",
  lazy = false,
  priority = 1000,
  config = function()
    vim.cmd("colorscheme cyan-light")
  end
}
```
