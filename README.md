# zext-libs
### A set of non-public domain extensions meant to go with [zext](https://github.com/zangent/zext).

It is reccomended to use the `./bindings` directory as a collection.
These libraries depend on zext, and it must be added as a collection named `zext`.
An example build: `odin my_program.odin -collection=zext-libs=../zext-libs/bindings -collection=zext=../zext/lib`

 + `loaders/png.odin` - A port of [uPNG](https://github.com/elanthis/upng). [Zlib license](https://tldrlegal.com/license/zlib-libpng-license-(zlib))
