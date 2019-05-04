# robot-udacity-project4
_Robotics Software Engineer Nanodegree Program: Project 4_

[![Udacity - Robotics NanoDegree Program](https://s3-us-west-1.amazonaws.com/udacity-robotics/Extra+Images/RoboND_flag.png)](https://www.udacity.com/robotics)

## Description

### "Map My World" Project

In this project you will create a 2D occupancy grid and 3D octomap from a simulated environment using your own robot with the RTAB-Map package.

TAB-Map (Real-Time Appearance-Based Mapping) is a popular solution for SLAM to develop robots that can map environments in 3D.

For this project we will be using the rtabmap_ros package, which is a ROS wrapper (API) for interacting with RTAB-Map. Keep this in mind when looking at the relative documentation.

The project flow will be as follows:

* You will develop your own package to interface with the rtabmap_ros package.

* You will build upon your localization project to make the necessary changes to interface the robot with RTAB-Map. An example of this is the addition of an RGB-D camera.

* You will ensure that all files are in the appropriate places, all links are properly connected, naming is properly setup and topics are correctly mapped. Furthermore you will need to generate the appropriate launch files to launch the robot and map its surrounding environment.

* When your robot is launched you will teleop around the room to generate a proper map of the environment.

#### Note: 
teleop_twist_keyboard-master is taken from [https://github.com/ros-teleop/teleop_twist_keyboard] but it required for submission for udacity 
