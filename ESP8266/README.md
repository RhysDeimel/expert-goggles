# ESP8266
> The ESP8266 is a low-cost Wi-Fi chip with full TCP/IP stack and MCU (microcontroller unit) capability produced by Shanghai-based Chinese manufacturer, Espressif Systems.

## General Notes

 - Drama with ESP8266 - http://www.instructables.com/id/Beginners-Guide-to-ESP8266-and-Tweeting-Using-ESP8/
 - Uses 3.3v logic. Arduino Uno uses 5v. Convert?
 - Webserver without library - http://allaboutee.com/2014/12/30/esp8266-and-arduino-webserver/
 - !!!! Change ESP baud rate with "AT+UART_DEF=9600,8,1,0,0". Arduino Uno has problems with 115200 - http://www.instructables.com/id/Cheap-Arduino-WiFi-Shield-With-ESP8266/
 - https://github.com/bportaluri/WiFiEsp: Seems like a promising library.
 - Wiring schemes: http://yaab-arduino.blogspot.com.au/2015/03/esp8266-wiring-schemas.html

---

 - ESP8266 resources: http://yaab-arduino.blogspot.com.au/2015/03/esp8266-resources.html