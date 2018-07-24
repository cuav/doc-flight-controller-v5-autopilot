# 加载PX4原生固件

---

V5 AutoPilot支持ArduPilot,下面主要讲解如何加载这种固件。

ArduPilot团队对FMU V5硬件接触较晚，现支持V5 AutoPilot的固件尚处于测试版阶段，但已经经过了数次的优化及广大模友的测试，已经可以正常使用。

使用ArduPilot固件前请将[mission planner](http://firmware.ardupilot.org/Tools/MissionPlanner/)升级到1.3.57及以上版本地面站。

### 在线烧录固件：

将飞控接入到电脑，打开地面站，点击初始设置界面》安装固件》点击测试版固件》选择您需要的固件类型》等待烧录完成  
![](/assets/load-ardupilot-firmware.JPG)

### 本地烧录固件：

请先下载您需要的固件类型：  
[多旋翼\(3~8轴通用）](http://firmware.ardupilot.org/Copter/latest/CUAVv5/arducopter.apj)  
[传统直升机](http://firmware.ardupilot.org/Copter/latest/CUAVv5-heli/arducopter-heli.apj)  
[固定翼](http://firmware.ardupilot.org/Plane/latest/CUAVv5/arduplane.apj)（包含垂直起降机固件）  
[无人车](http://firmware.ardupilot.org/Rover/latest/CUAVv5/ardurover.apj)  
[无人船](http://firmware.ardupilot.org/Sub/latest/CUAVv5/ardusub.apj)
选择加载自定义固件》选择下载的固件》等待烧录完成
![](/assets/load-ardupilot-firmware2.JPG)

