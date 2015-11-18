# geobins

[![Build Status](https://travis-ci.org/hanwang/geobins.svg?branch=master)](https://travis-ci.org/hanwang/geobins)

- [Dependencies](#dependencies)
- [Build Instructions](#build-instructions)
- [Running Tests](#running-tests)
- [To do](#to-do)
- [Contributions](#contributions)
- [License](#license)

#### Dependencies

This project depends on ```CMake```, which can be installed with:
```
$ git clone https://github.com/Kitware/CMake.git
$ ./bootstrap && make && make install
```
All other dependencies will be installed via CMake
 
#### Build Instructions

This project is built with CMake.  The ```Makefile``` is generated by:
```
cmake CMakeLists.txt
```
and built with:
```
make
```

#### Running Tests

Tests are not implemented yet, but will be executed with:
```
make test
```

#### To do

#### Contributions

#### License

The MIT License (MIT)

Copyright (c) 2015 Han Wang, Alex Hortin, Oliver Lum

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
