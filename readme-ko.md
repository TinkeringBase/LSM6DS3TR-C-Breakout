[English](https://github.com/FTIndustries/LSM6DS3TR-C-Breakout/blob/main/readme.md)
# FTIndustries BMI270 IMU breakout
![미리보기](https://github.com/FTIndustries/LSM6DS3TR-C-Breakout/blob/main/3dpreview.png?raw=true)\
ST의 LSM6DS3TR-C 6DoF IMU를 사용한 센서 브레이크아웃 모듈입니다. Sparkfun Qwiic 시스템을 지원합니다.\
낮은 가격에 쓸만한 성능을 낼 수 있어, 보급형 모듈로 추천합니다.

## 사양
Supply Voltage (VDD): 1.71~3.6V \
Logic Low (VIL): 0.3\*VDD max \
Logic High (VIH): 0.7\*VDD min \
Current consumption: around 0.9mA at performance mode \
자세한 내용은 [기술 데이터](https://www.st.com/en/mems-and-sensors/lsm6ds3tr-c.html)를 참조하세요.

## I2C 주소
모듈은 기본적으로 I2C 주소 0b1101000(0x6A)을 사용합니다. 0b1101001(0x6B)로 변경하려면 모듈 뒷면의 점퍼를 납땜하세요.