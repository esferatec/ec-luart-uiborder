# ec-luart-uiborder

This project provides various border ui objects for [LuaRT](https://www.luart.org/).
It has been designed to simplify and improve the creation of graphical user interfaces with the LuaRT ui module.

[![LuaRT 2.2.0](https://badgen.net/badge/LuaRT/2.2.0/blue)](https://github.com/samyeyo/LuaRT)

## Features

The module provides the following extension objects:

| Name | Description |
| --- | --- |
| [BorderLabel](docs/borderlabel/README.md) | Represents a label control with a border. |
| [BorderPicture](docs/borderpicture/README.md) | Represents a picture control with a border. |

More detailed descriptions and usage examples can be found in the docs folder.

## Installation

1. Create a folder called "ecluart" in your application.
1. Copy the "uiborder.lua" file into this folder.

```text
[application]
|
|----ecluart
|   |
|   |----uiborder.lua
|   |----...
|
|----app.wlua
```

## Usage

The extension module can be loaded using the function *require()*:

```lua

local uiborder = require("ecluart.uiborder")  
```

## License

Copyright (c) 2023 by esferatec.
It is open source, released under the MIT License.
See full copyright notice in the LICENSE.md file.
