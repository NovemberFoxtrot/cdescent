
# cDescent

  C recursive descent parser generator based on _why's "greg", which is a slightly modified reentrant version Ian Piumarta's [peg(1)](http://piumarta.com/software/peg/).

## Features

  Features that differentiate cDescent from peg(1):
  
    - reentrant
    - `=` or `:` are valid for rule assignment
    - trailing action semi-colon is optional

## Build

    $ make
    $ ./bin/cdescent

## Installation

    $ make install

## Documentation

  Currently the syntax is relatively untouched, just cleaning up some logic. so check out the "leg" sections of [http://piumarta.com/software/peg/peg.1.html](http://piumarta.com/software/peg/peg.1.html).

## License 

(The MIT License)

Copyright (c) 2011 TJ Holowaychuk &lt;tj@vision-media.ca&gt;

Copyright (c) 2008 why the lucky stiff

Copyright (c) 2007 by Ian Piumarta

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
'Software'), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
