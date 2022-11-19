# swift-toolchain-linux

Swift iOS toolchain for Linux

## Prerequisites

### For Linux

* [cpio](https://packages.ubuntu.com/focal/cpio)
* [xar](http://github.com/mackyle/xar/)

### For macOS

* Xcode

## Usage

### For Linux

Run `./create-toolchain <swift version> <linux version>`

### For macOS

Run `./create-toolchain <linux version> <path to xctoolchain>`

The `linux version` argument is in the format `<distribution><version>` (all lowercase). See <https://swift.org/download/> for the list of supported Linux versions.

The currently supported versions are:
- `ubuntu18.04`
- `ubuntu20.04`
- `ubuntu22.04`

Upon completion of the script, the output can be found in the `packages` directory.
