# RobotV_Disorderly-grabbing
RGB-D camera combined with robotic arm for unordered grasping system
# orbbec_robotCatch

硬件配置： Astra pro深度相机；Zora P1开发板

## 环境要求
1. pcl 1.8
2. opencv 3.2

  In industrial production, automated grasping has a wide range of application scenarios, such as automotive assembly, workpiece manufacturing, and other processes. The grasping technology of planar targets based on 2D machine vision has become very mature in industrial production applications.
  However, such applications have strict requirements for the position of processed parts, requiring them to be placed separately on the same plane without overlap. This type of technology only needs to locate the two-dimensional position of the parts, without considering the three-dimensional pose of the parts. However, in actual industrial production, the production environment and operational requirements are relatively complex, and it is often necessary to grab parts from chaotic material boxes. The target parts to be grabbed may overlap or be obscured. Under these conditions, 2D machine vision based planar grasping technology is obviously unable to successfully complete the grasping work.
  Therefore, we utilized the Zora P1 development board and RGBD camera provided by Obi Zhongguang Technology Group Co., Ltd., as well as the Kawasaki robot (6-axis) provided by the Intelligent Optical Measurement Research Institute of the School of Physics and Optoelectronics Engineering at Shenzhen University, to develop a three-dimensional reconstruction and disorderly grasping system for complex machined parts that can be placed arbitrarily by combining an RGB-D camera with a robotic arm
