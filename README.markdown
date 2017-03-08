
# arduino-paceclock

This simple arduino paceclock ranges from 00:00 to 59:59 then cycles back to 00:00.

![arduino](https://www.arduino.cc/new_home/assets/illu-arduino-UNO.png)

## Hardware

  * 1 x Arduino Uno
  * 4 x 7-segment common-anode LED array displays
  * 4 x 8-bit shift registers

NOTE: For training, a real-time clock such as DS3231 should be used instead since it drifts less than a minute per year. The arduino crystal has an accuracy of +/- a few seconds per day (less than two tenths of a second per hour).

## Pin setup

  * latch pin: 8
  * clock pin: 12
  * data pin: 11

## License

The project is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).
