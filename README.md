# ROS_Drv_Bridge 程序介绍

Robot Drive-Kit 与 ROS系统之间数据交换程序

bridge 程序是通过串行接口在Robot Drive-Kit 和上层ROS 系统之间搭建的一座桥梁。

程序接口简介说明 Wiki https://github.com/ROS-Robotics/ros_drv_bridge/wiki/ROS_DRV_BRIDGE-README

**********************************************************************

下载编译详细步骤如下：

1 创建工作空间：

$ mkdir -p ~/catkin_ws/src

$ cd ~/catkin_ws/

$ catkin_make

２　下载程序：

$ cd src

$ git clone https://github.com/ROS-Robotics/ros_drv_bridge.git

$ cd ..

$ catkin_make

3 修改串口权限：

$ cd

$ cd /dev

$ sudo chmod 666 ttyUSB0(默认值)

４　启动程序

$ source ~/catkin_ws/devel/setup.bash

$ roslaunch ros_drv_bridge bridge_node.launch





