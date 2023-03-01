# Windows Console Virtual Terminal Sequences

[![Build Status](https://travis-ci.org/godoes/winseq.svg?branch=master)](https://travis-ci.org/godoes/winseq)
[![Go Report Card](https://goreportcard.com/badge/github.com/godoes/winseq)](https://goreportcard.com/report/github.com/godoes/winseq)
[![GitHub license](https://img.shields.io/github/license/godoes/winseq.svg)](https://github.com/godoes/winseq/blob/master/LICENSE)

- [English](https://github.com/godoes/winseq/blob/master/README.md)
- [简体中文](https://github.com/godoes/winseq/blob/master/README_cn.md)

Use Unix like Sequences in Windows

Virtual terminal sequences are control character sequences that can control cursor movement, color/font mode, and other operations when written to the output stream.  
Sequences may also be received on the input stream in response to an output stream query information sequence or as an encoding of user input when the appropriate mode is set.  

[Document](https://docs.microsoft.com/en-us/windows/console/console-virtual-terminal-sequences)

## Usage

``` golang

import _ "github.com/godoes/winseq"

```

[Console control colors](https://github.com/wzshiming/ctc)  
[Console control cursor](https://github.com/wzshiming/cursor)  

## License

Pouch is licensed under the MIT License. See [LICENSE](https://github.com/godoes/winseq/blob/master/LICENSE) for the full license text.
