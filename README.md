# `present.nvim`

This is a plugin for presenting markdown files.

# Features

Can execute code in lua blocks, when you have them in a slide.

```lua
print("Hello, world!", 37)
```

# Usage

To start a presentation, use the following Lua code:

```lua
require("present").start_presentation()
```

Keymaps:
- `n`: next slide
- `p`: previous slide
- `q`: quit presentation
- `X`: run codeblock
