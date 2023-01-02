# import-cost.nvim

Display the costs of javascript imports inside neovim with the power of
[import-cost](https://github.com/wix/import-cost)

![preview](https://user-images.githubusercontent.com/62671086/210182400-defdb8d5-5d0a-42b6-a2b2-014272a7d7a7.png)

## Installation

1. Install regularly with your package manager
2. Run the install script inside the directory:

```sh
sh install.sh
```

## Configuration

Configure via the setup function or use the defaults as shown below:

```lua
require('import-cost').setup(opts or {})
```

See `:h import-cost` for more information