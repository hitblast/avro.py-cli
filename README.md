# avro.py-cli

A command-line wrapper for avro.py to ease Bangla phonetic workflow inside your terminal.

[![Linting](https://github.com/hitblast/avro.py-cli/actions/workflows/linting.yml/badge.svg?branch=main)](https://github.com/hitblast/avro.py-cli/actions/workflows/linting.yml)
![License](https://img.shields.io/pypi/l/avro.py-cli.svg?color=black&label=License)
![Python Version](https://img.shields.io/pypi/pyversions/avro.py-cli.svg?color=black&label=Python)

<img src="static/terminal_demo.png" alt="Terminal Demo">

## Overview

This Python package wraps around [avro.py](https://pypi.org/project/avro.py) in order to add support for terminal-based Bangla text parsing. It's completely optional over its parent package and completely depends on your workflow as a developer or as a conventional user.

<br>

## Installation

avro.py-cli can be installed with development environments running **Python 3.8** or later. You'll also need to have the latest version of [avro.py](https://pypi.org/project/avro.py) installed in order for the wrapper to actually work. If not installed, though, the command below will also install it as a dependency.

```bash
# installation / upgrade

$ pip install -U avro.py-cli
```

<br>

## Usage Guide

If you have done the installation correctly, the usage should be pretty easy as well:

```bash
# Get help regarding the CLI inside your terminal.
$ python3 -m avro --help 
$ avro --help 
# Minified, both of them can work depending on your environment.

# Parse a text.
$ avro parse --text "ami banglay gan gai."
$ avro parse -t "eije dekh waTar." 
# Minified --text option.

# Parse multiple texts.
$ avro parse -t "amar swopnera" -t "Dana mele ure cole" -t "obarito nIle."
```

Note that each time you parse some text, the output will be automatically copied to your clipboard for convenience.

<br>

## License

```
MIT License

Copyright (c) 2022 HitBlast

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
```

The original license text can be found [in this document.](https://github.com/hitblast/avro.py-cli/blob/main/LICENSE)