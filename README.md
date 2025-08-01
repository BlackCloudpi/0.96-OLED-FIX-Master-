## Wiring Diagram
VCC -> 3.3V
GND -> GND
SDA -> GPIO21
SCL -> GPIO22

![image alt](https://github.com/BlackCloudpi/0.96-OLED-FIX-Master-/blob/b9b528b7d1a901d89f4676944edeb86b309e0e70/ISSUE.jpg)


# ISSUE
you might have face this issue .if no then its great to hear. 
but in case if you face.
it is not harware fault. its for incorrect driver issue. Arduino ide basically using outdated driver. but this is SH1106 display. so you have to use U8g2 library.
Arduino will use Adafruit_GFX or I2C. But that will become nightmare.if you face the error. Looks like brick. but your display is perfectly OK.
