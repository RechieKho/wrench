# Wrechie 
`wrechie`, a [wren] runtime ready to be extended. `wrechie` is aimed to provide a runtime for [wren] that allows easy C or C++ intergration.

In future, there will be a built-in package manager.

It currently packed with features such as:

- relative import (`import "./module.wren"`)
- built-in package import (`import "package"`)
- C library loader (`Lib.load("m")`)


## Running wren on wrechie
To run a wren script, call `path/to/wrechie path/to/script.wren` in your terminal to run `script.wren`.


[wren]: https://wren.io/