# Windows 虚拟终端序列

[![Build Status](https://travis-ci.org/godoes/winseq.svg?branch=master)](https://travis-ci.org/godoes/winseq)
[![Go Report Card](https://goreportcard.com/badge/github.com/godoes/winseq)](https://goreportcard.com/report/github.com/godoes/winseq)
[![GitHub license](https://img.shields.io/github/license/godoes/winseq.svg)](https://github.com/godoes/winseq/blob/master/LICENSE)

- [English](https://github.com/godoes/winseq/blob/master/README.md)
- [简体中文](https://github.com/godoes/winseq/blob/master/README_cn.md)

在 Windows 中使用 类Unix序列

虚拟终端序列是控制字符序列，其可以在写入输出流时控制光标移动，颜色/字体模式和其他操作。  
还可以响应于输出流查询信息序列在输入流上接收序列，或者在设置适当模式时作为用户输入的编码接收序列。  

[文档](https://docs.microsoft.com/en-us/windows/console/console-virtual-terminal-sequences)

## 用法

``` golang

import _ "github.com/godoes/winseq"

```

[控制终端颜色](https://github.com/wzshiming/ctc)  
[控制终端光标](https://github.com/wzshiming/cursor)  

## 许可证

软包根据MIT License。有关完整的许可证文本，请参阅[LICENSE](https://github.com/godoes/winseq/blob/master/LICENSE)
