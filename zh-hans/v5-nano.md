# 概述 {#概述}

---

### 小身材，大能量

V5-NANO自动驾驶仪专为对空间极度敏感，但又想体验V5强大性能的企业和爱好者设计。V5-NANO在V5X强大的性能和丰富的扩展基础上，删减了极少数的通常未被使用的接口，并且将体积缩减到了XXmm。

### 高性能的处理器

v5-NANO继承了V5-AutoPilot高性能处理器（STM32F765\)，其支持双精度浮点运算，并且相较于STM32F4具有更大的主频、更大flash，更稳定的性能等特点。

### 更稳定的传感器

传感器方面V5-NANO与V5 AutoPilot一样，采用了相同的高精密传感器，能够适应复杂的应用环境。

### 支持丰富的机型

v5-NANO强大的性能加上mini的身材，使其不但能在普通无人机中使用，也能够在200mm轴距的微型无人机中使用。

#### 支持的机架类型

多旋翼、固定翼、垂直起降机、倾转式垂直起降机、无人车，无人机等。

### 更多特性

* Dronecode标准引脚
* 支持RTK厘米定位  
* 丰富的扩展硬件

### 硬件参数 {#硬件参数}

|  | **硬件参数** |
| :--- | :--- |
| 主处理器 | STM32F765  \(32 Bit Arm® Cortex®-M7, 216MHz, 2MB flash, 512KB RAM\) |
| **传感器** |  |
| 加速计 | ICM-20602/ICM-20689/BMI055 |
| 陀螺仪 | ICM-20602/ICM-20689/BMI055 |
| 电子罗盘 | IST8310 |
| 气压计 | MS5611 |
| **接口** |  |
| UART串口 | 5 |
| I2C | 4 |
| PWM输出 | 最多11路PWM输出 |
| PWM输入 | 4 |
| 遥控器信号输入协议 | PPM/SBUS/DSM |
| RC IN | 1 |
| PPM IN | 1 |
| RSSI输入 | PWM或3.3模拟电压 |
| CAN标准总线 | 2 |
| 电流电压输入 | 1 |
| 安全开关 | 1 |
| GPS接口 | 1 |
| Debug | 1 |
| JATG | 1 |
| USB接口 | 1\(Type-C\) |
| **支持机型** |  |
| PX4固件 | 固定翼/3-8旋翼/直升机/VTOL垂直起降/无人车/无人船等 |
| **工作环境及物理参数** |  |
| PM工作电压 | 4.5 ~ 5.5 V |
| USB电压 | 5V +- 0.25v |
| 伺服输入 | 0-36v |
| 工作温度 | -40 ~ 85°c |
| **尺寸** |  |
|  长X宽X高 | 60\*40\*14mm |
| 重量 | 50g |

### 接口定义 {#接口定义}

> **NOTE** 如显示不清晰，请点击右键“另存为”下载到本地查看。
>
> **Comment** 当V5-NANO运行ArduPilot\(MP\)固件时，支持11路PWM输出（CAP1、CAP2、CAP3分别为servo9、servo10、servo11\);DEBUG接口作为通用串行口，USB接口作为DEBUG调试接口。当V5-NANO运行PX4\(QGC\)固件时CAP接口为PWM输入接口，debug调试接口与丝印相符。

### PX4固件编译命令 {#编译命令}

`make px4fmu-v5_default upload`

### ArduPilot固件编译命令 {#编译命令}

`./waf configure --board CUAVv5`

`./waf copter --upload`

### 可选硬件设备 {#可选硬件}

* [空速计传感器](http://doc.cuav.net/tutorial/plane/optional-hardware/airspeed.html)
* [遥测无线电模块](http://doc.cuav.net/tutorial/plane/optional-hardware/radio.html)
* [测距仪/距离传感器 ](http://doc.cuav.net/tutorial/copter/optional-hardware/rangefinders/rangefinders.html)
* 更多可选硬件信息请访问[多旋翼可选硬件](http://preview.cuav.net/tutorial/copter/)/[固定翼可选硬件](http://preview.cuav.net/tutorial/plane/zh-hans/)界面
  ### 视频介绍



