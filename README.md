Type-C Standard Library
===

This repository contains the source code of the Type-C Standard Library. 
The library contains 2 parts:
- FFI declarations: These are the type declarations of the C modules, that are used by the library and parts of the VM.
- Type-C Standard Library: The standard library, built on top of the FFI declarations.

It is important to provide layers of abstraction between the low level FFI and the high level standard library.