﻿# Introduction

This opensource project is a tiny RISC-V processor core which written by verilog. It is very simple and easy to understand. Tinyriscv has the following characteristics:

- Implemented RV32I instruction set.

- Use three-stage flow line.

- Can run simple C program.


# How to use

Tinyriscv run on windows platform, it compiled and simulated with iverilog. Before to use, you need install these tools below:

1. iverilog

Download from http://bleyer.org/icarus/, install it and add to system environment PATH.

2. GNU Toolchain

Download from BaiduNetDisk https://pan.baidu.com/s/1bYgslKxHMjtiZtIPsB2caQ, extraction code is 9n3c, decompress it into tools directory.

3. make

Download from BaiduNetDisk https://pan.baidu.com/s/1nFaUIwv171PDXuF7TziDFg, extraction code is 9ntc, decompress it and add to system environment PATH.

Take the **add** instruction as an example to show how to use:

Open the CMD and go to the sim directory and run command below:

```
sim_new_nowave.bat ..\tests\isa\generated\rv32ui-p-add.bin inst.data
```

You can see the following print if it run successfully:

![](./pic/add.jpg)
