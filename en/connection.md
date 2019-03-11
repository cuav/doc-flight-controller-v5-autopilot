### Interface definition {#Interface definition}

![V5 AutoPilot](../assets/flight-controller/v5-autopilot/v5-pinouts.jpg)
DSU7 is a new interface for cuav naming, including fmu swd and uart7 interfaces. When V5 runs PX4 firmware,uart7 is used as the DEBUG interface; when running ArduPilot firmware; uart7 is used as the communication serial port and usb is used to debug the output.
> Warning The RCIN interface is limited to powering the remote control and cannot be connected to any power/load.



