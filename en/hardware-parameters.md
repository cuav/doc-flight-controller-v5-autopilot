## Hardware parameters {#硬件参数}

|  | **Hardware parameters** |
| :--- | :--- |
| Main FMU Processor | STM32F7653  \(32 Bit Arm® Cortex®-M7, 216MHz, 2MB flash, 512KB RAM\) |
|  | STM32F100 \(32 Bit Arm® Cortex®-M3, 24MHz, 8KB SRAM\) |
| **On-board Sensors** |  |
| Accel/Gyro | ICM-20602/ICM-20689/BMI055 |
| Accel/Gyro | ICM-20602/ICM-20689/BMI055 |
| Magnetometer | IST8310 |
| Barometer: | MS5611 |
| Interfaces: |  |
| UAR serial port | 5 |
| 2c | 4 |
| PWM outputs  | 6 from IO, 8 from FMU |
|  R/C signal input protocol | PPM/SBUS/DSM/DSM2 |
| RSSI input | PWM or 3. 3 analog voltage |
| CAN Standard bus | 2 |
| Analog inputs for voltage | 2 |
| Safety switch | 1 |
| GPS interface | 1 |
| Debug/F7 SWD interface | 1 |
| USB interface | 1\(Type-C\) |
| SPI interface | 1 |
|  |  |
| ** Support model for mobile** |  |
| PX4固件 | 固定翼/3-8旋翼/直升机/VTOL垂直起降/无人机/无人船等 |
| **工作环境及物理参数** |  |
| PM工作电压 | 4.3~ 5.4 V |
| USB电压 | 5V +- 0.25v |
| 伺服输入 | 0-36v |
| 工作温度 | -20 ~ 80°c |
| **尺寸** |  |
| 长X宽X高 | 89\*42.5\*33mm |
| 重量 | 90g |

## Quick Summary

* Main FMU Processor: STM32F765
  * 32 Bit Arm® Cortex®-M7, 216MHz, 2MB memory, 512KB RAM
* IO Processor: STM32F100
  * 32 Bit Arm® Cortex®-M3, 24MHz, 8KB SRAM
* On-board sensors:

  * Accel/Gyro: ICM-20689
  * Accel/Gyro: BMI055
  * Magnetometer: IST8310
  * Barometer: MS5611

* Interfaces:

  * 8-14 PWM outputs \(6 from IO, 8 from FMU\)
  * 3 dedicated PWM/Capture inputs on FMU
  * Dedicated R/C input for CPPM
  * Dedicated R/C input for Spektrum / DSM and S.Bus with analog / PWM RSSI input
  * Dedicated S.Bus servo output
  * 5 general purpose serial ports
  * 4 I2C ports
  * 4 SPI buses
  * Up to 2 CANBuses for dual CAN with serial ESC
  * Analog inputs for voltage / current of 2 batteries

* Power System:

  * Power module output: 4.3~5.4V
  * USB Power Input: 4.75~5.25V
  * Servo Rail Input: 0~36V

* Weight and Dimensions:
  * Weight: 90g
  * Dimensions: 44x84x12mm
* Other Characteristics:
  * Operating temperature: -20 ~ 80°c



