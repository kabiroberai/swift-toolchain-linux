# swift-toolchain-linux

Swift iOS toolchain for Linux

## Prerequisites

### For Linux

* cpio ([ubuntu20.04](https://packages.ubuntu.com/focal/cpio))
* [xar](http://mackyle.github.io/xar/)

### For macOS

* Xcode

## Usage

Run `./create-toolchain <linux version> [path to xctoolchain]`

The `linux version` argument is in the format `<distribution><version>` (all lowercase). See <https://swift.org/download/> for the list of supported Linux versions.

The currently supported versions are:
- `ubuntu16.04`
- `ubuntu18.04`
- `ubuntu20.04`

Upon completion of the script, the output can be found in the `packages` directory.
