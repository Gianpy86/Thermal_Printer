Bluetooth Low Energy<br>
Thermal Printer Library<br>
Copyright (c) 2020 BitBank Software, Inc.<br>
Written by Larry Bank<br>
bitbank@pobox.com<br>
<br>
![printer demo](/ble_prt.jpg?raw=true "Thermal_Printer")

<br>
This Arduino library allows you to easily generate text and graphics
and send them to a BLE thermal printer. Since there are many different
BLE APIs depending on the board manufacturer, I decided to support the more
popular ones - ESP32 and Arduino (Nano BLE 33). The two main features of
thermal printers are supported by this code - plain text and dot addressable
graphics. The graphics are treated like a display driver. You define a buffer and draw text, dots, lines and bitmaps into it, then send it to the printer. Text output supports the various font size+attribute options of the printer.
See the include (.H) file for a description of each function.
<br>

<br>
Features<br>
========<br>
- Supports the GOOJPRT PT-210 printer (so far) and PeriPage!<br>
- Compiles on ESP32, Adafruit nRF52 and Arduino Nano 33 BLE<br>
- Supports graphics (dots, lines, text, bitmaps) and plain text output<br>
- Includes easy to use BLE scanning and connection logic<br>
- Doesn't depend on any other 3rd party code<br>
<br>

If you find this code useful, please consider sending a donation.

[![paypal](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=SR4F44J2UR8S4)
