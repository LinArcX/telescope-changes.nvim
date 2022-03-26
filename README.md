# :telescope: telescope-changes.nvim

Telescope extension wrapper around `:changes`

# Installation

### Vim-Plug

```viml
Plug "nvim-telescope/telescope.nvim"
Plug "LinArcX/telescope-changes.nvim"
```

### Packer

```lua
use { "nvim-telescope/telescope.nvim" }
use { "LinArcX/telescope-changes.nvim" }
```

# Setup and Configuration

```lua
require('telescope').load_extension('changes')
```

# Usage
`:Telescope changes`

# Contribution
If you have any idea to improve this project, please create a pull-request for it. To make changes consistent, i have some rules:
1. Before submit your work, please format it with [StyLua](https://github.com/JohnnyMorganz/StyLua).
    1. Just go to root of the project and call: `stylua .`

2. There should be a one-to-one relation between features and pull requests. Please create separate pull-requests for each feature.
3. Please use [snake_case](https://en.wikipedia.org/wiki/Snake_case) for function names ans local variables
4. If your PR have more than one commit, please squash them into one.
5. Use meaningful name for variables and functions. Don't use abbreviations as far as you can.
