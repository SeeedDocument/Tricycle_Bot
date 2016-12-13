#Tricycle Bot

##Introduction

![](https://github.com/SeeedDocument/Tricycle_Bot/blob/master/images/3.jpg?raw=true)

The Tricycle Bot is a easy-to-assemble and Grove_Compatible DIY Robot platform for education. It includes the eletronic materials and structure materials which could be assembled easily via the guideline. The Tricycle Bot has three floors and five shores between the 2nd and 3th floor, the 3th floor can be fixed many modules via screws and nuts.

Further more, you can fix the Arduino board and breadboard as the heart of the robot in the 2nd floor and each shore can be fixed 1-2 plug-n-play Grove modules as the wings of the robot to strengthen the functions accordingly, such as RGB LEd and ultrasonic Grove module. The supply voltage of Tricycle Bot is provided by a 12V battery holder.


##Features

- Multi-platform supportted
- Grove Compatible Shores
- Easy-to-assemble
- RF/BLE/Wi-Fi Control Choices

##Part List

![](https://github.com/SeeedDocument/Tricycle_Bot/blob/master/images/4.jpg?raw=true)

|Parts name|Specification|Quantity|
|:---------|:-----------:|:------:|
|Wheel     |Ф64mm*W30mm  |2       |
|Deceleration DC Motor|/ |2       | 
|Universal Wheel|49\*32\*22mm|1   |
|Battery Holder|62\*58\*30mm|1    |
|Binding Ties|20.5\*31.8mm|1      |
|Btm Plate(1st floor)|220\*155\*3.8mm|1|
|Mid Board(2nd floor)|220\*155\*3.8mm|1|
|Top Plate(3rd floor)|160\*158\*3.8mm|1|
|Front Shore|62\*56\*3.8mm|1      |
|Side Shore|62\*31\*3.8mm|4       |
|Rivet\_1  |R3090        |4       |
|Standoffs\_2|M3\*22     |6       |
|Standoffs\_3|M3\*55+6   |4       |
|Screw\_4  |PM3\*8       |14      |
|Screw\_5  |PM3\*25      |4       |
|Nut\_6    |M3\*2.3      |6       |
|Rivet\_7  |R2064        |15      |
|Screw\_8  |KM2\*10      |15      |
|Nut\_9    |M2\*1.5      |15      |
|Wrench    |/            |2       |
|ScrewDriver|/           |1       |


**This kit does not include the Arduino/Genuino 101 and breadboard.**


##Assembly Introdutions

![](https://github.com/SeeedDocument/Tricycle_Bot/blob/master/images/1.png?raw=true)

![](https://github.com/SeeedDocument/Tricycle_Bot/blob/master/images/2.png?raw=true)

##Platform Recommendation


You could fix any boards you like on Tricycle Bot to drive this Robot Platform, such as Arduino, Raspberry Pi and BeagleBone. And to drive the DC motors and Grove modules, motor cape and Grove cape are good helper for you.

As there are so many boards to choose, here we will make a introduction of how to choose the suitable board for you between Arduino, Raspberry and BeagleBone. 


###Arduino Platform

Arduino is the most famous open-source prototyping platform as its easy-to-use hardware and software. We believe that you could DIY a funny and creative robot car with Arduino easily. And as we have so much Grove modules for Arduino, it is convenient to expand function for your robot car, such as LED effect, obstacle detection or remote control(RF/Bluetooth/Wi-Fi).


####[Seeeduino V4.2](https://www.seeedstudio.com/Seeeduino-V4.2-p-2517.html)
Seeeduino v4 is an Open Source, Arduino-compatible ATmega328 MCU development board. We think Seeeduino v4 is one of the best Arduino derivatives/compatibles available. Seeeduino v4 is feature rich, much more stable, easy-to-use and even good looking.
![](https://raw.githubusercontent.com/SeeedDocument/SeeeduinoV4/master/images/cover.JPG)


####[Motor Shield V2.0](https://www.seeedstudio.com/Motor-Shield-V2.0-p-1377.html)
The Motor Shield is a driver module for motors that allows you to use Arduino to control the working speed and direction of the motor.
![](https://github.com/SeeedDocument/Motor_Shield_V2.0/blob/master/image/500px-Motorshield_01.jpg?raw=true)


####[Base Shield V2](https://www.seeedstudio.com/Base-Shield-V2-p-1378.html)

As an expansion board, Base Shield v2 has many Grove connectors, making it convenient for you to use Grove module together. And It is compatible with a series of Arduino products.
![](https://raw.githubusercontent.com/SeeedDocument/Base_Shield_V2/master/img/Base_Shield_v2-1.png)


####Recommendation Grove Modules

- **[Digital RGB LED Flexi-Strip](https://www.seeedstudio.com/Digital-RGB-LED-Flexi-Strip-60-LED-1-Meter-p-1666.html)**

	Digital RGB LED Flexi-Strip is an intelligent light source, you could make super cool LED effect on your robot car with it.
	
	![](https://statics3.seeedstudio.com/images/product/60led%20Strip.jpg)

- **[Grove - Ultrasonic Ranger](https://www.seeedstudio.com/Grove-Ultrasonic-Ranger-p-960.html)**  

	This Grove - Ultrasonic sensor is a non-contact distance measurement module, suitable for robot car obstacle detection.
	![](https://raw.githubusercontent.com/SeeedDocument/Grove_Ultrasonic_Ranger/master/image/350px-Ultrasonic_Ranger.jpg)

- **[Grove Line Finder](https://www.seeedstudio.com/Grove-Line-Finder-p-825.html)**
	
	Line finder Grove is designed for line following robot.
	![](https://github.com/SeeedDocument/Grove_Line_Finder/raw/master/images/Grovelinefinder1.jpg)
	
- **[Grove Buzzer](https://www.seeedstudio.com/Grove-Buzzer-p-768.html)**

	Grove Buzzer is an easy-to-use module for making sound.
	![](https://github.com/SeeedDocument/Grove_Buzzer/raw/master/images/Grove%20Buzzer.jpg)

- **[Grove Serial RF Pro](https://www.seeedstudio.com/Grove-Serial-RF-Pro-p-794.html)**

	With Grove Serial RF Pro, you are able to remote controll your DIY robot car!  
	![](https://statics3.seeedstudio.com/images/113030000%201.jpg)
	
- **[Grove Serial Bluetooth v3.0](https://www.seeedstudio.com/Grove-Serial-Bluetooth-v3.0-p-2475.html)**

	Grove - Serial Bluetooth is an easy to use module compatible with the existing Grove Base Shield, and designed for transparent wireless serial connection setup. 
	![](https://raw.githubusercontent.com/SeeedDocument/Grove-Serial_Bluetooth_v3.0/master/img/Grove-Serial_Bluetooth_v3.0.jpg)

###Raspberry Pi Platform

树莓派是目前最火热的linux board computer之一，网上资源丰富，最新版的树莓派自带wifi和蓝牙功能，方便做远程控制 他的性能要比arduino强大许多，编程门槛较高，
The Raspberry Pi is one of the most popular single-board computer now, it has much more powerful computing performance than Arduino, 

####[Raspberry Pi Motor Board v1.0](https://www.seeedstudio.com/Raspberry-Pi-Motor-Board-v1.0-p-2411.html)

####[GrovePi+](https://www.seeedstudio.com/GrovePi%2B-p-2241.html)


####Recommendation Grove Modules

- **[USB Webcam](https://www.seeedstudio.com/300K-Pixel-USB-2.0-Mini-Webcam-p-1499.html)**

	Webcam is not a Grove module, but it can provide video streaming to your board. It is always cool to add a camera to your remote controlled robot car, so that you can see where its heading exactly. 
	![](https://statics3.seeedstudio.com/product/Webcam_01.jpg)



###BeagleBone Platform


BeagleBone is also one of the most popular linux single-board computer. Compared with Raspberry, BeagleBone has an advantage on programming Grove module, as its Mraa and UPM library.


####[BeagleBone Green Wireless](http://www.seeedstudio.com/SeeedStudio-BeagleBone-Green-Wireless-p-2650.html)
SeeedStudio BeagleBone Green Wireless is based on the open-source hardware design of BeagleBone Black, but it has a high-performance flexible WiFi/Bluetooth interface, making it easier to develop remote controlled, such as [BBGW Wi-Fi Car](http://www.instructables.com/id/Super-Quickly-DIY-Web-RC-Car-With-Python-and-Beagl/).

![](https://github.com/SeeedDocument/BeagleBone_Green_Wireless/raw/master/images/BBGW_cover.png?raw=true)

####[Motor Bridge Cape v1.0](https://www.seeedstudio.com/Motor-Bridge-Cape-p-2569.html)
The Motor Bridge Cape can control two stepper motors or four brushed DC motors with 6~15V DC power and about 1A current draw per motor. It also has six servo control interfaces and six expand I\O, which means that you could DIY a robot arm on your robot car.  
	
![](https://raw.githubusercontent.com/SeeedDocument/Motor_Bridge_Cape_v1.0/master/img/Motor_bridge_driver.jpg)

####[Grove Base Cape for BeagleBone v2](https://www.seeedstudio.com/Grove-Base-Cape-for-Beaglebone-v2.0-p-2644.html)
Grove Base Cape for BeagleBone v2 is a Grove system expansion board for BeagleBone platform. This cape makes it convenient to connect many transducers (sensors and actuators) available as Grove modules with BeagleBone platform. 

![](https://github.com/SeeedDocument/Grove_Base_Cape_for_BeagleBone_v2/raw/master/img/Grove_Base_Cape_for_BeagleBone_v2_product_view_1200.jpg)

####Recommendation Grove Modules

- **[USB Webcam](https://www.seeedstudio.com/300K-Pixel-USB-2.0-Mini-Webcam-p-1499.html)**

	Webcam is not a Grove module, but it can provide video streaming to your board. It is always cool to add a camera to your remote controlled robot car, so that you can see where its heading exactly. 
	![](https://statics3.seeedstudio.com/product/Webcam_01.jpg)
	
	
- **[Digital RGB LED Flexi-Strip](https://www.seeedstudio.com/Digital-RGB-LED-Flexi-Strip-60-LED-1-Meter-p-1666.html)**

	Digital RGB LED Flexi-Strip is an intelligent light source, you could make super cool LED effect on your robot car with it.
	
	![](https://statics3.seeedstudio.com/images/product/60led%20Strip.jpg)

- **[Grove - IMU 9DOF v2.0](http://www.seeedstudio.com/Grove-IMU-9DOF-v2.0-p-2400.html)**

	Grove - IMU 9DOF v2.0 features three 16-bit ADC for digitizing the gyroscope outputs and three 16-bit ADCs for digitizing the accelerometer outputs and three 16-bit ADCs for digitizing the magnetometer outputs, providing you to detect the movement posture of the robot car.
	![](https://raw.githubusercontent.com/SeeedDocument/Grove-IMU_9DOF_v2.0/master/img/Grove-IMU_9DOF_v2.0.JPG)

##Simple Example

Here is a simple example of making a Tricycle Bot with Arduino.

Arduino UNO, [Motor Shield V2.0](https://www.seeedstudio.com/Motor-Shield-V2.0-p-1377.html),[Base Shield V2](https://www.seeedstudio.com/Base-Shield-V2-p-1378.html),is used,12

<div class="img-wrapper ng-scope" ng-if="fileType === 'video'">
<video ng-src="http://ohpam657y.bkt.clouddn.com/IMG_1346%202.MOV" width="280" controls="" src="http://ohpam657y.bkt.clouddn.com/IMG_1346%202.MOV"></video>
</div>

##Attachments

[Tricycle Bot Assembly Instructions(pdf)](https://github.com/SeeedDocument/Tricycle_Bot/blob/master/resources/Tricycle%20Bot%20Assembly%20Instructions.pdf)


