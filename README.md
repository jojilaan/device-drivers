# Hardware Datasheet sensehat
https://www.raspberrypi.org/documentation/hardware/sense-hat/images/Sense-HAT-V1_0.pdf

8x8 RGB LED matrix -> aangestuurd door LED2472G -> aangestuurd door de ATTINY88 vai SDI ( Serial Digital Interface ( Zoek nog even een mooie datasheet ) <br/>
CAT24C32WI-GT3 -> 32kb EEPROM -> wordt aangestuurd via I2C. <br/>
HTS221 is een digitala sensor voor luchtvochtigheid en temperatuur <br/>
LED2472G is een 24-bit shift register for LED panels. <br/>
LSM9DS1 beschikt over een 3D digitale lineare acceleratie sensor, 3D digital magnetic sensor, 3D Gyroscoop. <br/>
LPS25H is een ultro compacte druksensor ( barometrische druk ) <br/>
SKRHABE010 is de joystick 


## Communicatie protocollen

SDI ( Serial Digital Interface )
I2C ( Inter-intergrated Circuit )

## Datasheet
24-bit shift register designed for LED panel: [LED2472G](https://www.st.com/resource/en/datasheet/led2472g.pdf) <br/>
EEPROM Serial 32-Kb I2C: [CAT24C32WI-GT3](https://www.onsemi.com/pub/Collateral/CAT24C32-D.PDF) <br/>
Capacitive digital sensor for relative humidity and temperature: [HTS221](https://www.st.com/resource/en/datasheet/hts221.pdf) <br/>
iNEMO inertial module: 3D accelerometer, 3D gyroscope, 3D magnetometer: [LSM9DS1](https://www.st.com/resource/en/datasheet/DM00103319.pdf) <br/>
MEMS pressure sensor: 260-1260 hPa absolute digital output barometer: [LPS25H](https://www.st.com/resource/en/datasheet/dm00066332.pdf) <br/>

5-weg joystick

## Sensoren
+Gyroscoop
+Accelerometer
+Magnetometer
+Temperatuur
+Barometrische druk
+Luchtvochtigheid

## Pinout Raspi + sensehat

Sensehat pinout: [Sensehat pinout](https://pinout.xyz/pinout/sense_hat)


## sensehat source code

Python library [Sensehat library](https://github.com/RPi-Distro/python-sense-hat)
