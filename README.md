Lui is a dumb installer for [Luvit](https://github.com/luvit/luvit)
===

`Lui` is a helper script composing a Makefile and then executing it.

`Lui` depends on nothing more than vanilla system tools:
  * make
  * wget
  * tar/unzip
  * git, optionally

Installation
-----

As simple as putting `lui` script under your `$PATH`.

Usage
-----

Move to your package root and type:

    lui

`Lui` will analyze `package.lua`, if any, and will install dependencies under `modules/` directory. For each installed module `lui` will as well install dependencies.

License
-------

Copyright (c) 2011 Vladimir Dronnikov <dronnikov@gmail.com>

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the "Software"), to deal in
the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of
the Software, and to permit persons to whom the Software is furnished to do so,
subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS
FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR
COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER
IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN
CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
