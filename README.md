# jMBus

[![License](https://img.shields.io/badge/License-MPL%202.0-brightgreen.svg)](http://mozilla.org/MPL/2.0/)

This is a fork of [kaikreuzer fork](https://github.com/kaikreuzer/jmbus).

- It fixes the endless read on wired mbus by enforcing the timeout in underlying rxtx lib.
- It allows to use serial by path linux feature as serial port name (aka /dev/serial/by-path/xxx), by decoding the symlink when possible.


