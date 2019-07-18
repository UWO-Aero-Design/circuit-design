# WE Aero Design Onboard Hardware

## Goal
The hardware soloution will contain sensors that allow the team to accurately determine the height and position of the aircraft at any given moment. Also, the system should allow for communication with the ground station through an onboard radio. Logging of in-flight data and accurate GPS information will be necessary. Finally, the system must be able to control 16 individual servos or DC motors.

## Design
Below are screenshots of the current revision of the schematic and board (created in Eagle).
###Schematic
![Schematic](./schematic_ref)
### Board
![board](./board_ref)

## Features
#### Radio
[RFM95W](https://www.adafruit.com/product/3072)

#### IMU
[MPU9250](https://www.sparkfun.com/products/13762)

#### Evironment Sensing
[MPL3115A2](https://www.adafruit.com/product/1893)

#### GPS
[Adafruit Ultimate GPS Breakout](https://www.adafruit.com/product/746?gclid=CjwKCAjwscDpBRBnEiwAnQ0HQNEhq5xu14W7TX12W0gVZqHBnbDJNApMf9mEeb73NOOZy2kR0mpCVRoCgI8QAvD_BwE)

#### Battery Monitoring
[INA219](https://www.adafruit.com/product/904)

#### Servo Driver
[PCA9686](https://cdn-shop.adafruit.com/datasheets/PCA9685.pdf)

#### Power
[L7805 and L7806](https://www.mouser.ca/datasheet/2/389/l78m-974157.pdf)

## TODO
- [x] Select parts
- [x] Create schematic
- [x] Layout board
- [ ] Route board
- [ ] Add Aero Design logo to board
- [ ] Order board
- [ ] Test board