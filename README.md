# tpcc-generator

This is a simple tool to create input in [csv](https://en.wikipedia.org/wiki/Comma-separated_values) format for the popular database benchmark TPC-C ([link](http://www.tpc.org/tpcc/)). The implementation is based on the code provided in the TPC-C specification.

## Build

The tool is simply build using make. It requires a C++ compiler which supports c++11.

```bash
make
```

## Run

With the following command you can create TPC-C input with _5_ warehouses. All files are stored in the my_tpcc_input directory. Note: The directory has to exist before starting the generator. But, no worries, if does not exists the generator will complain.

```bash
mkdir my_tpcc_input
./tpcc-generator 5 my_tpcc_input
```

## Licence

MIT License

Copyright (c) 2017 Alexander van Renen

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
