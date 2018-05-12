# Navigationsystem
This navigation system is developed for a differential drive mobile robot as a bachelor thesis at The University of Agder. 

The system is based on using ROS Kinetic. 

ros_ardino_brigde is from: https://github.com/hbrobotics/ros_arduino_bridge

ros_arduino_brigde has been modified to include PID Controller for each wheel. The modifications are provided by Diego Robots: https://github.com/diegorobot/diego1

The system utilizes a RpLiDAR A2M6 for navigation purpose. The package can be downloaded from: https://github.com/robopeak/rplidar_ros.git


Additionally, the library for Pololu VNH5019 Dual Motor Shield have to be downloaded and included in Arduino library: 
https://github.com/pololu/Dual-VNH5019-Motor-Shield 
