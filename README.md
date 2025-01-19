Type-C Standard Library
===

Type-C standard library.

structure:
- `std/vm_api/*`: FFI which uses libraries exported by Type-V. Usually requires wrappers
- `std/*`: Standard Library
- `tests/*`: Unit test cases
- `./testall.tc`: Unit test runner.

|package|description|state|tests|
|:---|:---|:---|:---|
|`fs.tc`|Filesystem IO|in progress|partial|
|`streams.tc`|Abstract Streams|in progress|no|
|`string`|UTF8 Strings|in progress|no|
|`math`|Math|in progress|no|
|`logging.tc`|Logging, only console logging for now|in progress|no|
|`date.tc`|Time & Date|in progress|no|
|`collections`|Array, Map, Iterators, etc|in progress|no|
|`unit.test`|Unit testing|Working|no|