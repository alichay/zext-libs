# ZEXT-libs
### A set of public domain library bindings meant to go with [ZEXT](https://github.com/zangent/ZEXT).

It is reccomended to use the `./bindings` directory as a collection.
These libraries depend on ZEXT, and it must be added as a collection named `zext`.
An example build: `odin my_program.odin -collection=zext-libs=../ZEXT-libs/bindings -collection=zext=../ZEXT/lib`