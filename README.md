# swift-toolchain-linux

Swift iOS toolchain for Linux

## Prerequisites

### For Linux

* [libarchive-tools](https://packages.ubuntu.com/focal/libarchive-tools)

### For macOS

* Xcode

## Usage

### For Linux

Run `./create-toolchain <swift version> <linux version>`

### For macOS

Run `./create-toolchain <linux version> <path to xctoolchain>`

The `linux version` argument is in the format `<distribution><version>` (all lowercase). See <https://swift.org/download/> for the list of supported Linux versions.

The currently supported versions are:
- `ubuntu20.04`
- `ubuntu20.04-aarch64`
- `ubuntu22.04`
- `ubuntu22.04-aarch64`
- `ubi9`
- `ubi9-aarch64`

Upon completion of the script, the output can be found in the `packages` directory.
