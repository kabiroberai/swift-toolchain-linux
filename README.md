# swift-toolchain-linux

Swift iOS toolchain for Linux

## Prerequisites

For Linux

* cpio ([ubuntu18.04](https://packages.ubuntu.com/bionic/cpio))
* [xar](http://mackyle.github.io/xar/)

## Usage

Run `./create-toolchain <version> <linux version>`

The `linux version` argument is in the format `<distribution><version>` (all lowercase), for example `ubuntu18.04`. See <https://swift.org/download/> for the list of supported Linux versions.

Upon completion of the script, the output can be found in the `packages` directory.
