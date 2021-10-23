# fs2comma-linux-path

This is a patched version of [fs2comma](https://github.com/hodgesmr/fs2comma) to compile on Linux. It currently implementes two diffs:

 * [41d433a](https://github.com/hodgesmr/fs2comma-linux-patch/commit/41d433a0ad51c23e537b7ad0519c05c44ce89837) - patch `readline.cpp` to check stream state 
 * [93f0841](https://github.com/hodgesmr/fs2comma-linux-patch/commit/93f08414ae47b29ac132b60798ed7988fbcdb683) - rename `stdafx.cpp` and `stdafx.h` to lowercase to fix imports

These two diffs were origninally proposed in a [fork](https://github.com/philipmnelson/fs2comma) of the origninal codebase, by user [philipmnelson](https://github.com/philipmnelson)

## A Matt Hodges project

This project is maintained by [@hodgesmr](http://twitter.com/hodgesmr).

_Please use it for good, not evil._
