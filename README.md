# talos-radxa-zero-3e

Talos overlay for Radxa ZERO 3E single-board computer (SBC).

# Why does this exist?

U-Boot is needed for devices to correctly boot.

This project relies on the mainline U-Boot and on the repository created by [Sidero Labs](https://github.com/siderolabs/sbc-template)

# Device Support

* [Radxa Zero 3E](https://docs.radxa.com/en/zero/zero3?model=zero-3e)

## Requirements

Using a sbc project templates assume docker is installed on your machine.

## Usage

* Run `make rekres`
* Now run `make help` on instructions on setting up `buildx` builder if one is not already setup.

# Disclaimer

This is NOT supported or endorsed by Rockchip, Radxa, or Sidero Labs - please do not go to them with support requests!
