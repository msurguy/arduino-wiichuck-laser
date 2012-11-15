arduino-wiichuck-laser
======================

Arduino Wiichuck driven servos with a Laser

Original blog post with Pictures and Video:
http://maxoffsky.com/maxoffsky-blog/arduino-wiichuck-steered-laser-pointer/


Parts list:

Arduino Uno
Original Wii Nunchuck
Nunchuk to Arduino adapter (link below)
Laser pointer
2 mini Servos

You can buy a WiiChuck adapter here :

http://todbot.com/blog/2008/02/18/wiichuck-wii-nunchuck-adapter-available/

We are using the Wire library for I2C communication with the Nunchuk. See this reference where the I2C pins are on your Arduino: http://www.arduino.cc/en/Reference/Wire. On Arduino Uno the I2C pins are A4 and A5.

