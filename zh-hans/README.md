# 概述 {#概述}

---

![Pixhack v5](../assets/flight-controller/pixhack-v5/pixhack-v5.jpg)

### 全新的V5 CORE 平台

PixHack V5采用了全新的V5 CORE平台；将飞控核心部分集成于V5 core上，底板可拆卸，只作为对外接口载体，给予消费者定制化的空间，用户可根据自身需求自行设计自己的底板。

### 更快的处理器

在硬件配置上，pixhack v5抛弃了px4家族原有的STM32F427处理器而选用了更为高级的STM32F765处理器，其主频高达216MHZ并且含有2MB FLASH/512K RAM，主频更高，RAM更大，速度将实现大幅度提升。

### 更稳定的传感器

传感器方面PixHack V5与pixhawk2.1一样，同样采用三度冗余imu，但其选用了更为稳定的ICM-20602/ICM-20689/BMI055/IST8310等传感器，提高了其在不同温度下的适应能力。

### 除此之外，V5还具有以下优势：

1、支持RTK厘米定位；  
2、模块化设计方便集成；  
3、内置3组IMU冗余；  
4、丰富的I/O端口；  
5、金属外壳内置减震；  
6、支持众多丰富机型。

## 硬件参数 {#硬件参数}

|  | **硬件参数** |
| :--- | :--- |
| 主处理器 | STM32F7653  \(32 Bit Arm® Cortex®-M7, 216MHz, 2MB flash, 512KB RAM\) |
| 协处理器 | STM32F100 \(32 Bit Arm® Cortex®-M3, 24MHz, 8KB SRAM\) |
| **传感器** |  |
| 加速计 | ICM-20602/ICM-20689/BMI055 |
| 陀螺仪 | ICM-20602/ICM-20689/BMI055 |
| 电子罗盘 | IST8310 |
| 气压计 | MS5611 |
| **接口** |  |
| UART串口 | 5 |
| I2c | 4 |
| PWM输出 | 标准8 PWM IO+6个可编程IO |
| 遥控器信号输入协议 | PPM/SBUS/DSM/DSM2 |
| RSSI输入 | PWM或3.3模拟电压 |
| CAN标准总线 | 2 |
| 电流电压输入 | 2 |
| 安全开关 | 1 |
| GPS接口 | 1 |
| Debug/F7 SWD接口 | 1 |
| USB接口 | 1\(Type-C\) |
| SPI接口 | 1 |
| **支持机型** |  |
| PX4固件 | 固定翼/3-8旋翼/直升机/VTOL垂直起降/无人车/无人船等 |
| **工作环境及物理参数** |  |
| PM工作电压 | 4.3 ~ 5.4 V |
| USB电压 | 5V +- 0.25v |
| 伺服输入 | 0-36v |
| 工作温度 | -20 ~ 80°c |
| **尺寸** |  |
| 长X宽X高 | 89\*42.5\*33mm |
| 重量 | 90g |

### 接口定义 {#接口定义}

![Pixhack v5](../assets/flight-controller/pixhack-v5/pixhack-v5-connectors.jpg)

> **Warning** RCIN接口只限于给遥控器供电，不可接入任何电源/负载.

### 固件编译命令 {#编译命令}

`make px4fmu-v5_default upload`

### 外围设备 {#外围设备}
* [空速计传感器](http://doc.cuav.net/tutorial/plane/optional-hardware/airspeed.html)
* [遥测无线电模块](http://doc.cuav.net/tutorial/plane/optional-hardware/radio.html)
* [测距仪/距离传感器 ](http://doc.cuav.net/tutorial/copter/optional-hardware/rangefinders/rangefinders.html)




