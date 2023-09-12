# PICOMO Hardware

## Pin assignment

| Pin    | Function                         |
|--------|----------------------------------|
| GPIO00 | Buzzer (active low)              |
| GPIO01 | Button Bottom-Right (active low) |
| GPIO02 | Button Middle-Right (active low) |
| GPIO06 | Temperature SDA (I2C)            |
| GPIO06 | Temperature SCL (I2C)            |
| GPIO08 | Button Top-Right (active low)    |
| GPIO09 | LED blue (PWM, active low)       |
| GPIO10 | LED red (PWM, active low)        |
| GPIO11 | LED green (PWM, active low)      |
| GPIO22 | Button Top-Left (active low)     |
| GPIO23 | Button Middle-Left (active low)  |
| GPIO25 | Button Bottom-Left (active low)  |

Note : The buttons do not have external pull-ups, so
you need to active it at the GPIO internal level.
