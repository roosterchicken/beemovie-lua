# beemovie-lua
a beemovie text generator that is written in lua
## Requirements
A Lua 5.1 compatible interpreter, so like all of the modern ones like LuaJIT and Lua 5.4
## Installation
You can install this rock with luarocks.
```
luarocks install beemovie --local
```
You can run it without the `--local` option if you want to install the rock systemwide
## Usage
If you want to use it, require it in your script
```lua
local Beemovie = require "beemovie"
```
The API has 4 functions, that would be, `Sentence()`, `Script()`, `Word()`, and `Paragraph()`. Examples will be shown below
### Examples
#### Sentence()
```lua
local Beemovie = require "beemovie"
local barry = Beemovie:Sentence(1)
print(barry)
```
#### Script()
```lua
local Beemovie = require "beemovie"
local barry = Beemovie:Script()
print(barry)
```
#### Word()
```lua
local Beemovie = require "beemovie"
local barry = Beemovie:Word(1)
print(barry)
```
#### Paragraph()
```lua
local Beemovie = require "beemovie"
local barry = Beemovie:Paragraph(1)
print(barry)
```
