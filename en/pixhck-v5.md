## Summary

---

![Pixhack v5](../assets/flight-controller/pixhack-v5/pixhack-v5.jpg)

### The new V5 CORE platform

PixHack V5 adopts the new V5 CORE platform; the core of the flight controller is integrated on the V5 core, and the bottom plate is detachable. It is only used as the external interface carrier to give consumers the space for customization. Users can design their own backplane according to their own needs.

### Faster processor

In the hardware configuration, pixhack v5 abandoned the px4 family's original STM32F427 processor and chose a more advanced STM32F765 processor, its frequency up to 216MHZ and contains 2MB FLASH/512K RAM, higher frequency, greater RAM, Speed will be greatly improved.

### More stable sensors

The PixHack V5 is similar to the pixhawk2.1 in terms of sensors. It also uses the third-degree redundant imu, but it chose a more stable ICM-20602/ICM-20689/BMI055/IST8310 sensor to improve its adaptability to different temperatures. .

### In addition, V5 also has the following advantages:

1, support RTK centimeter positioning;

1. Modular design facilitates integration;

3, built-in 3 sets of IMU redundancy;

4, rich I / O port;

5, metal housing built-in shock absorption;

6, support for many rich models.

## Hardware parameters {#Hardware parameters}

|  | **Hardware parameters** |
| :--- | :--- |
| Mian FMU Procceor | STM32F7653  \(32 Bit Arm® Cortex®-M7, 216MHz, 2MB flash, 512KB RAM\) |
| On-board Sensors | STM32F100 \(32 Bit Arm® Cortex®-M3, 24MHz, 8KB SRAM\) |
| **Sensor** |  |
| Accelerator | ICM-20602/ICM-20689/BMI055 |
|  | Accel/Gyro |
|  | ICM-20602/ICM-20689/BMI055 |
| Electronic compass | IST8310 |
| Barometer | MS5611 |
| Interface |  |
| UART serial port | 5 |
| 12c | 4 |
| PWM Out put | Standard 8 pwm IO 6 programmable IO |
| R/C signal input protocol | PPM/SBUS/DSM/DSM2 |
| RSSI input | Pwm or 3. 3 analog voltage |
| CAN standard bus | 2 |
| Current voltage input | 2 |
| Safety Switch | 1 |
| GPS Interface | 1 |
| Debug/F7 SWD Interface | 1 |
| USB Interface | 1\(Type-C\) |
| SPI Interface | 1 |
|  |  |
| **Support model** |  |
| Px4 firmware | Fixed-wing / 3-8 rotor / helicopter / vtol vertical take-off / landing / UAV / UAV, etc. |
| Working environment and physical parameters |  |
| PM working voltage | 4.5 ~ 5.5 V |
| USB working voltage | 5V +- 0.25v |
| Servo  Input | 0-36v |
| Operating temperature | -40 ~ 85°c |
| Size |  |
|  | 89\*42.5\*33mm |
| Weight | 90g |

### Interface definition {#Interface definition}

![Pixhack v5](../assets/flight-controller/pixhack-v5/pixhack-v5-connectors.jpg)

> Warning The RCIN interface is limited to powering the remote control and cannot be connected to any power/load.

### Firmware compilation command {#Firmware compilation command}

`make px4fmu-v5_default upload`

### peripheral equipment {#Peripheral Equipment}

* Airspeed sensor
* Telemetry radio module
* Rangefinder/Distance Sensor



