# balenaSound with WiFi Connect

Balena multi-app that combines:

- [balenaSound](https://sound.balenalabs.io)
- [WiFi Connect](https://github.com/balena-io/wifi-connect)

## Deploy

_Warning: This project uses git submodules which are currently not supported by
balenaCloud/openBalena, so you'll have to use `balena push` instead of `git`._

    git checkout https://github.com/erlend/balena-sound
    cd balena-sound
    git submodule update --init
    balena push YOUR_APP_NAME

## Usage

The WiFi hotspot only starts when the device is not already connected to a
network. Information on supported hardware and configuration can be found in the
[balenaSound docs](https://sound.balenalabs.io/docs/usage/).
