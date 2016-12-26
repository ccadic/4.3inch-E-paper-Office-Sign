# 4.3inch-E-paper-Office-Sign
ESP8266 &amp; 4.3inch e-paper combination to make office's door sign
(c) Dr CADIC Philippe, 25 Dec 2016 / Merry Xmas 


This is a simple project to create e-ink door signs for offices
You need a ESP8266 Dev 1.0 board
You need the e-paper from Waveshare: http://www.gearbest.com/lcd-led-display-module/pp_230469.html
You need the E-paper Library: Library Arduino 4.3inch e-Paper for Waveshare 4.3 inch E-Paper Display Module
This library can be downloaded from: https://github.com/sabas1080/LibraryEPD

Connexions are as below
E-Paper RED (+5v) wire to VIN (ESP8266)
E-Paper BLACK (GND) to any GND (ESP8266)
E-Paper BLUE(RST) to D2 (ESP8266)
E-paper YELLOW to D1(ESP8266)
E-Paper GREEN to TX(ESP8266)
E-Paper WHITE to RX(ESP8266)

Disconnect WHITE WIRE when you compile and upload the code to the ESP8266

