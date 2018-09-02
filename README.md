# swift-toolchain-linux

Swift iOS toolchain for Linux

## Usage

Run `./create-toolchain <major> <minor> <patch> <linux version>`

The `linux version` argument is in the format `<distribution><version>` (all lowercase), for example `ubuntu16.10`. See <https://swift.org/download/> for the list of supported Linux versions.

Upon completion of the script, the output can be found in the `packages` directory.
