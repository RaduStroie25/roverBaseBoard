# roverBaseBoard
My Rover Project, too lazy to write another description. View documentation in the files. :P
STATUS: Unfinished

### Board Pins (Input)
These are the board pins that take input from the Microcontroller:
- 8x Digital pins. (for all motor driver direction control)
- 4x PWM or Analog pins. (for all motor speed control)
- 1x VCC pin (for driver logic voltage that can be 2.5V-5.5V)
- 1x Digital pin. (for driver Standby pins)
- 1x POWERLATCH pin (keep high while running)

### Board Pins (Output)
These are the pins that the board offers to a microcontroller:
- 1x Adjustable VCC power pin.
- 1x GND into the same source.
- 1x SCL (ina219)
- 1x SDA (ina219)



## Notes
- Measured TT motor max draw per motor 110mA-120mA. (without load or wheels on)
- do not run 75A through jumper cables... *
