# Hardware Datasheet sensehat
https://www.raspberrypi.org/documentation/hardware/sense-hat/images/Sense-HAT-V1_0.pdf


8x8 RGB LED matrix -> aangestuurd door LED2472G -> aangestuurd door de ATTINY88 vai SDI ( Serial Digital Interface ( Zoek nog even een mooie datasheet )
CAT24C32WI-GT3 -> 32kb EEPROM -> wordt aangestuurd via I2C.
HTS221 is een digitala sensor voor luchtvochtigheid en temperatuur
LED2472G is een 24-bit shift register for LED panels.
LSM9DS1 beschikt over een 3D digitale lineare acceleratie sensor, 3D digital magnetic sensor, 3D Gyroscoop.
LPS25H is een ultro compacte druksensor ( barometrische druk )
SKRHABE010 is de joystick

Communicatie protocollen:
SDI ( Serial Digital Interface )
I2C ( Inter-intergrated Circuit )

# Datasheet:
[LED2472G](https://www.st.com/resource/en/datasheet/led2472g.pdf)
[CAT24C32WI-GT3](https://nl.mouser.com/datasheetI/2/308/CAT24C32-D-111607.pdf)
[HTS221](https://www.st.com/resource/en/datasheet/hts221.pdf)
[LSM9DS1](https://www.st.com/resource/en/datasheet/DM00103319.pdf)
[LPS25H](https://www.st.com/resource/en/datasheet/dm00066332.pdf)

5-weg joystick

#Sensoren
+Gyroscoop
+Accelerometer
+Magnetometer
+Temperatuur
+Barometrische druk
+Luchtvochtigheid
