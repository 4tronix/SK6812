# SK6812 [![Build Status](https://travis-ci.org/Microsoft/pxt-ws2812b.svg?branch=master)](https://travis-ci.org/Microsoft/pxt-ws2812b)

A driver for SK6812 etc programmable LEDs in MakeCode.
This is cloned from the Microsoft WS2812B driver to enable selective use of Bluetooth

## Usage

The package exposes ``sk6812.sendBuffer`` that bit-bangs a color buffer for SK6812 type LEDs over a pin.

See https://github.com/4tronix/smart-leds for an example of usage.

## ~ hint
 
**Bluetooth NOT disabled**: This package does not disable BLE, so ensure it isnot active when BT is required

## ~

## Simulator support

The ``sendBuffer`` function is supported by the micro:bit simulator!

## License

MIT

## Supported targets

* for PXT/microbit
* for PXT/calliope

(The metadata above is needed for package search.)


## Code of Conduct

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
