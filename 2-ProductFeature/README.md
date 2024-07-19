# Robot Parameter Description

> In Chapter 1, we explored the product's selling points and design philosophy, providing you with a panoramic view of the product's high-level understanding. Now, let's move on to Chapter 2 - Robot Parameter Description. This chapter is crucial for you to understand the technical details of the product. Understanding these technical parameters in detail will not only help you fully appreciate the advanced nature and practicality of our product but also ensure that you can effectively utilize these technologies to meet your specific needs.

## 1 Machine Specifications

| Indicator | Parameter |
|:------------: |:---------------------------: |
| Chinese Name | Mercury X1 Wheeled Dual-Arm Humanoid Robot |
| Name | Mercury X1 |
| Overall Height | 1.2 meters |
| Degrees of Freedom | 19 |
| Battery Life | 8 hours |
| Maximum Load of Robotic Arm | 1 kilogram |
| Repeatability of Robotic Arm | ±0.05 millimeters |
| Net Weight | 55KG |
| Operating Voltage | DC24V/9.2A |
| Chassis Drive Motor | High-performance direct drive motor |
| Maximum Running Speed | 1.2 meters/second |
| Maximum Climbing Angle | 15° |
| Storage Space | 15 liters |
| Main Control | 6-core Arm v8.2 64-bit CPU, 384-core Volta™ GPU |
| Computing Power | 21 TOPS |
| Chassis CPU | 4-core ARM Cortex-A57 CPU |
| Chassis GPU | 128 NVIDIA CUDA® cores |
| Screen | 9-inch touch screen |
| Sensors | LiDAR, ultrasonic radar, 2D vision |
| 3D Camera | Orbbec Deeyea |
| Microphone | Linear 4-microphone, 5 meters 180° pickup |
| IO | 24V 6 inputs, 6 outputs 2A |
| Communication Methods | CAN bus/WIFI/Ethernet/Bluetooth/USB/Serial Port |

## 2 Basic Software Function Support

| Function/Development Environment | Usage |
| :------------: | :--------: |
| Free Movement | Supported |
| Joint Movement | Supported |
| Cartesian Movement | Supported |
| Trajectory Recording | Supported |
| Wireless Control | Supported |
| Emergency Stop | Supported |
| Windows | Supported |
| Linux | Supported |
| MAC | Supported |
| ROS 1 | Supported |
| Python | Supported |
| C++ | Supported |
| C# | Supported |
| JavaScript | Supported |
| myblockly | Supported |
| Arduino | Supported |
| mystudio | Supported |
| Serial Control Protocol | Supported |
| TCP/IP | Supported |
| MODBUS | Supported |

# 3 Core Control Parameters

<!-- <img src="../../resources/8-FilesDownload/2-serialproduct/image.png " width="800" height="auto" /> -->

### Main Controller Specifications

| Indicator | Parameter |
| :---------------: | :----------------: |
| Main Control | Jetson Xavier |
| Main Control Model | Jetson Xavier NX |
| CPU | 6-core NVIDIA Carmel ARM®v8.2 64-bit CPU <br> 6MB L2 + 4MB L3 |
| GPU | 384-core NVIDIA Volta™ GPU with 48 Tensor cores |
| AI Performance | 21 TOPS |
| Storage | 16 GB eMMC 5.1 |
| CSI Camera | 2 CSI cameras |
| Network | 10/100/1000 BASE-T Ethernet |
| USB Interface | 1 USB 3.2 2.0 (10 Gbps) <br> 2 USB 2.0 interfaces |
| Other I/O | 2 UART serial ports |

### Left Arm Main Controller Specifications

| Indicator | Parameter |
| :---------------: | :----------------: |
| Main Control | Left Arm Main Control |
| Main Control Model | ESP32 |
| Core Parameters | 240MHz dual core. <br> 600 DMIPS, 520KB SRAM. <br> Wi-Fi, dual mode Bluetooth |
| Sub-Control Flash | 4MB |
| LED Display | 5X5 RGB |

### Right Arm Main Controller Specifications

| Indicator | Parameter |
| :---------------: | :----------------: |
| Main Control | Right Arm Main Control |
| Main Control Model | ESP32 |
| Core Parameters | 240MHz dual core. <br> 600 DMIPS, 520KB SRAM. <br> Wi-Fi, dual mode Bluetooth |
| Sub-Control Flash | 4MB |
| LED Display | 5X5 RGB |

### Sub-Controller Specifications

| Indicator | Parameter |
| :--------------: | :----------------: |
| Sub-Control | Jetson Nano |
| Sub-Control Model | Jetson Nano 4G |
| AI Performance | 472 GFLOPS |
| GPU | 128-core NVIDIA Maxwell™ architecture GPU |
| GPU Max Frequency | 921MHz |
| CPU | Quad-core ARM® Cortex®-A57 MPCore processor |
| CPU Max Frequency | 1.43GHz |
| Memory | 4GB 64-bit LPDDR4 |
| 25.6GB/s |
| CSI Camera | 1 CSI Camera |
| USB* | 1x USB3.0(5 Gbps)<br>2x USB 2.0 |
| Mechanical | 69.6mmx45mm<br>260-pin SO-DIMM connector |

---

# 4 Structural Dimensions

> This chapter uses millimeters as the unit of distance and degrees as the unit of angle.

## Product Dimensions and Workspace
When selecting the installation location for the robot, the cylindrical space directly above and below the robot must be considered. Avoid moving tools into the cylindrical space as much as possible. This is because it can cause the joints to rotate too quickly when the tool moves slowly, resulting in low work efficiency and difficult risk assessment.

<!-- <img src="../resources/2-ProductFeature/产品尺寸.png " width="400" height="auto" /> -->
<!-- Figure 2.3.1 Product Dimensions -->

<!-- <img src="../resources/2-ProductFeature/工作空间.png " width="800" height="auto" />   -->
<!-- Figure 2.3.2 Product Workspace -->

<!-- ## 2 Chassis Installation Dimensions -->

<!-- <img src="../resources/2-ProductFeature/底座尺寸.png " width="400" height="auto" /> -->
<!-- Figure 2.3.3 Chassis Installation Dimensions -->

## Dual Arm End Flange Dimensions
<center>
<img src="../resources/2-ProductFeature/末端法兰.png" width="400" height="auto" />
<br>
Figure 2.3.4 End Dimensions</center>

# 5 Electrical Characteristics

## Chassis Interface Overview
<center>
<img src="./../resources/2-ProductFeature/底座正视图.jpg "
width="400" height="auto" />
<br>
Figure 1 Chassis Front View
<br>
<img src="./../resources/2-ProductFeature/底座左视图.jpg" width="400" height="auto" />
<br>
Figure 2 Chassis Left View
<br>
<img src="./../resources/2-ProductFeature/底座右视图.jpg " width="400" height="auto" />
<br>
Figure 3 Chassis Right View
<br>
<img src="./../resources/2-ProductFeature/05519a0595f3536c0b6d72ddc8b17e7.jpg " width="400" height="auto" />
<br>
Figure 4 Chassis Internal View
<br>
</center>

## Chassis Interface Description

| Number | Interface | Definition | Function | Remarks |
|:----:|:--------------:|:---------:|:-----------------:|:----------------:|
| 1 | Power Input Interface | DC24V Input | DC24V Input | |
| 2 | Switch | Power Switch | Control input power on/off | With light (lights up when powered) |
| 3 | Emergency Stop Interface | STOP | Emergency stop circuit interface | |
| 4 | Ethernet Port | | | |
| 5 | USB3.0 | USB3.0*2 | Can connect external devices or USB drives | |
<br>

#### 1 Power Input Interface: This interface is connected to the DC24V power adapter interface

#### 2 Power Switch: Controls the on/off of the main power input, when turned off, the controller is also powered off

#### 3 Emergency Stop Circuit Terminal: Connected to the emergency stop button box, can be used to control the robot emergency stop
> **Note**: The emergency stop switch must be connected during robot use, and ensure that the emergency stop switch circuit is in a connected state.

#### 4 Ethernet

#### 5 USB3.0 Interface: A data connection interface using the serial bus standard 3.0; users can use the USB interface to copy program files, or connect peripherals such as a mouse and keyboard

## End Interface Overview
<center>
<img src="./../resources/2-ProductFeature/左臂末端图.jpg" width="400" height="auto" />
<br>
Figure 5 Left Arm End View
<br>
<img src="./../resources/2-ProductFeature/右臂末端图.jpg" width="400" height="auto" />
<br>
Figure 6 Right Arm End View
<br>
</center>

## End Interface Description
| Number | Interface | Definition | Function | Remarks |
|:------:|:----------------:|:-----------:|:-------------------:|:------------------:|
| 6 | 4-pin USB Terminal | External Interface | Connects to camera | |
| 7 | M8 Aviation Socket | End Tool IO Interface | Interacts with external devices | |


#### As shown in the figure, the M8 aviation socket I/O diagram, the Mercury X1 robot provides one input and two outputs.
<center>
<img src="../resources/2-ProductFeature/机械臂末端工具说明.png" width="" height="auto" />
<br>
The definitions of each tool I/O port are shown in the table below. Note that the tool I/O, whether input or output, is of PNP type, and the wiring method is the same as the bottom output interface.
</center>

| Number | Signal | Explanation | Matching M8 Wire Color |
| :------: | :------: | :-----------------------: | :--------------------------: |
| 1 | GND | DC24V Negative | White |
| 2 | OUT1 | Tool Output Interface 1 | Brown |
| 3 | OUT2 | Tool Output Interface 2 | Green |
| 4 | 485A | Reserved, Not Developed | Yellow |
| 5 | 24V | DC24V Positive | Gray |
| 6 | IN1 | Tool Input Interface 1 | Pink |
| 7 | IN2 | Tool Input Interface 2 | Blue |
| 8 | 485B | Reserved, Not Developed | Purple |

#### USB Terminal: Used to connect to the camera

If you have read all the content of this chapter, you can continue to the next chapter.

[← Previous Chapter](../1-ProductIntroduction/README.md) | [Next Chapter →](../3-UserNotes/README.md)