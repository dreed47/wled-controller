# WLED Controller (ESP32) - 4 Channels - Optional Current and power monitoring

## Features

- 4 Channels
  - Max 25A total
  - Max 10A per channel
- Every channel has _independent_ current, power and voltage monitoring (using INA219)
- Sending power monitoring data to HomeAssistant via MQTT
- Seperate 3.3V low noise voltage regulator for audio section
- _**Optional:** INMP441 I2S Microphone with low noise power supply_

Interactive [BOM can be found here](https://rawcdn.githack.com/dreed47/wled-controller/main/bom/ibom.html).

## Usermod

This board requires a usermod for WLED for full support of all features including power monitoring.

## 3D Board view

![image](/images/front.png)
![image](/images/back.png)

## Board

![image](/images/board.png)
