# Navigationsystem
This navigation system is developed for a differential drive mobile robot as a bachelor thesis at The University of Agder. 

The system is based on using ROS Kinetic. 

ros_ardino_brigde is from: https://github.com/hbrobotics/ros_arduino_bridge

ros_arduino_brigde has been modified to include PID Controller for each wheel. The modifications are provided by Diego Robots:  https://github.com/diegorobot/diego1

The system utilizes a RpLiDAR A2M6 for navigation purpose. The package can be downloaded from: https://github.com/robopeak/rplidar_ros.git


 Additionally, The library for Pololu VNH5019 Dual Motor Shield have to be downloaded and included in Arduino library: 
https://github.com/pololu/Dual-VNH5019-Motor-Shield 



Changes in ros_arduino_brigde:

- In the motor_driver.ino sketch, the PWM frequency has been overided from 20 KHz to 488.92 Hz.

- PId controller bug fixed In the diff_controller.h.

- The encoder pin "Pd2" has been changed to "Pd5" in the encoder_driver.h.

- Due to changes in enocder pins, the encoder_driver.ino sketch was fixed to achieve correct amount of pulses/revolution.    

 

