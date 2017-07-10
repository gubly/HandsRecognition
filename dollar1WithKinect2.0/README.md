# 基于深度相机的非接触式交互研究

此项目旨在使用Kinect 2.0实现一个非接触式交互系统。


## 运行环境

- 软件：
    - win8.1或更高的windows版本
    - Kinect SDK 2.0
    - OpenCV 2.4.* (>=2.4.9)
    - Visual Studio 2015/2017 (需安装Tools and Windows SDK 10.0.10240)

- 硬件：
    - Kinect 2.0 一台

## 简介

此项目基于Kinect 2.0实现，使用中值滤波等滤波方式来给Kinect收集到的手的位置数据降噪，使用[$1 Unistroke Recognizer][1]算法实现手势识别。


[1]: http://depts.washington.edu/madlab/proj/dollar/index.html
