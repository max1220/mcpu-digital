# digital-mcpu

This directory contains implementations of the MCPU for the
[Digital logic simulator program by H. Neemann](https://github.com/hneemann/Digital).

Included is both a von-neuman style implementation in the `mcpu_soc.dig`
file with a dual-port memory that is shared between instruction and data,
as well as an harvard style implementation with separate instruction/data
memories, like the implementation in MineCraft.

For online documentation and a web-based assembler and an emulator, see
[mcpu-web](https://max1220.github.io/mcpu-web/)

![Demo video](demo_video.mp4)
