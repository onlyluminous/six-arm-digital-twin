# 六自由度机械臂数字孪生仿真平台

毕业设计 | Unity3D + MATLAB/Simscape + Python TCP通信

## 项目介绍

本项目为本科毕业设计，搭建六自由度工业机械臂的数字孪生虚拟仿真平台。Unity3D负责三维可视化，MATLAB/Simscape完成多体动力学解算，Python通过TCP通信连接虚实两端，实现虚拟模型与真实机械臂的实时同步。

## 技术栈

**可视化前端**：Unity3D (C#)

**动力学仿真**：MATLAB / Simscape Multibody

**通信中间件**：Python (socket / pyserial)

**机器人描述**：URDF

**机器人操作系统**：ROS2

**容器化部署**：Docker

## 主要功能

**三维可视化**：六轴机械臂建模与运动学实时显示

**动力学仿真**：Simscape多体建模与轨迹跟踪

**虚实通信**：Python TCP协议实现数据双向交互

**虚拟调试**：Unity中预演作业路径，替代30%实物调试

**低延迟**：通信延迟控制在20ms以内

## 学习路线

基于 Unity-Robotics-Hub 官方教程学习与二次开发，从ROS2环境搭建、URDF模型导入、MoveIt运动规划，到Unity虚拟场景同步与Python通信脚本编写，逐步完成虚实结合的数字孪生系统。

> 本仓库为学习参考用途，毕业设计为独立实现。
> 
