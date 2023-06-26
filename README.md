# esp-open-sdk-osx-standalone
xtensa-lx106 pre-built toolchain for building micropython on Mac OSX

To build micropython on ESP8266, you need to download the xtensa-lx106 pre-build toolchain from https://github.com/jepler/esp-open-sdk/releases/download/2018-06-10/xtensa-lx106-elf-standalone.tar.gz (refer to https://github.com/micropython/micropython/tree/master/ports/esp8266). However, that toolchain is only for Linux, and micropython requires a specific old version of the toolchain built in standalone mode.

This repository provide the standalone toolchain for building micropython on Mac OSX.
