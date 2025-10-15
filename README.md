Articubot One

Articubot One is a simple differential drive robot built in ROS 2.
It can move around, perform mapping, navigation, and object tracking (ball tracking) using camera data.
An Extended Kalman Filter (EKF) is used for sensor fusion and localization.

FEATURES:
Differential drive robot simulation in Gazebo
Teleoperation (keyboard / joystick)
2D SLAM mapping (using slam_toolbox)
Navigation using nav2
Sensor fusion with EKF
Ball tracking using computer vision
Fully compatible with RViz2 for visualization

TECH STACK:
ROS 2 (tested on Jazzy)
Gazebo simulator
RViz2 visualization
rclcpp / rclpy for ROS nodes
slam_toolbox, nav2, and robot_localization

INSPIRATION:
This project was made possible thanks to the Articulated Robotics YouTube channel
 —
a huge help in understanding ROS 2 fundamentals and robot simulation setup.
