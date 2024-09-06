# Turtlesim Controller Package
 
## Overview
 
This ROS package extends the popular `turtlesim` simulation to provide two modes of operation: **manual mode** and **autonomous mode**. The launch file is designed to handle a user-specified argument, allowing the turtle in the `turtlesim` node to either be driven autonomously or controlled manually through a GUI interface.
 
### Features
 
- **Autonomous Mode**: The turtle moves in circles autonomously without user interaction.
- **Manual Mode**: A control interface is provided to allow the user to manually control the turtle's movement.
- **Customizable Launch**: The mode can be selected using a command-line argument.
 
## Dependencies
 
This package requires the following ROS components:
- **ROS Noetic** (or compatible version)
- **turtlesim** package
 
You can install `turtlesim` using:
```bash
sudo apt-get install ros-noetic-turtlesim
