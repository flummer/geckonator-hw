# Geckonator development boards

The Geckonator development boards are a series of tools for working with the USB microgontrollers from Silabs in the Happy Gecko family.

These boards have a very low component count, in part due to the built in features of the controller, eg. built in voltage regulator.

These boards are in part inspired by [Thumbinator][thumbinator] and the [Tomu][tomu] and combines parts from both of these projects.

[thumbinator]: https://github.com/kbeckmann/thumbinator-hw
[tomu]: https://github.com/im-tomu/tomu-hardware

## Hardware
The initial version of the hardware (found in this repository) is a small thumbdrive sized board with a male USB A connector directly on the board and only two LEDs.

The next version ([Geckonator Dev Edition][geckonator-dev]) is a larger board, with a few more components, higher pincount microcontroller and a larger prototyping area for adding other stuff.

[geckonator-dev]: https://github.com/flummer/geckonator-dev

## Firmware

This board is designed for the development of the [Geckoboot bootloader][geckoboot], and for developing applications for this, the [Geckonator][geckonator] repository can be used as a base

[geckoboot]: https://github.com/flummer/geckoboot
[geckonator]: https://github.com/flummer/geckonator

## License

The contents of this repository is released under the following licence:

 * the "Creative Commons Attribution-ShareAlike 4.0 International License"
   (CC BY-SA 4.0) full text of this license is included in the LICENSE file
   and a copy can also be found at
   http://creativecommons.org/licenses/by-sa/4.0/