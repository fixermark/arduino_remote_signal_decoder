# About

Simple IR signal decoder, based heavily on Limor's tutorial
(http://www.ladyada.net/learn/sensors/ir.html).

# Usage

This code is intended for use with a PNA4602 IR detector (or its friend, the
compatible GP1UX311QS [http://www.adafruit.com/products/157]). Once you've
wired the detector to input pin 2, the program will monitor for signal
detection and output what it observes to the serial port in plaintext
(formatted as a C array for easy copy-and-paste).

# License

This code is public domain, but for more information you should really go
to the source: http://www.ladyada.net/learn/sensors/ir.html1