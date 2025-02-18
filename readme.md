[한국어](https://github.com/TinkeringBase/ICM42688/LSM6DS3TR-C-Breakout/blob/main/readme-ko.md)
# TinkeringBase/ICM42688 LSM6DS3TR-C IMU breakout
![preview](https://github.com/TinkeringBase/ICM42688/LSM6DS3TR-C-Breakout/blob/main/3dpreview.jpg?raw=true)\
Sensor breakout using ST's LSM6DS3TR-C 6DoF IMU, supports Sparkfun Qwiic system.\
While it has low price tag, it provides acceptable performance. So we recommend as entry-level IMU.

## Specification
Supply Voltage (VDD): 1.71~3.6V \
Logic Low (VIL): 0.3\*VDD max \
Logic High (VIH): 0.7\*VDD min \
Current consumption: around 0.9mA at performance mode \
for more information, see [techdata](https://www.st.com/en/mems-and-sensors/lsm6ds3tr-c.html)

## I2C address
the module uses I2C address 0b1101001 (0x6B) by default. to change it to 0b1101000 (0x6A), solder the jumper at the back side of the module.
