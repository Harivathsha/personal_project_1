# 🤖 Articubot One: Autonomous ROS 2 Explorer

[![ROS 2](https://img.shields.io/badge/ROS_2-Jazzy-34a853?style=flat&logo=ros)](https://docs.ros.org/en/jazzy/)
[![Gazebo](https://img.shields.io/badge/Simulator-Gazebo-ff6600?style=flat)](https://gazebosim.org/home)
[![OpenCV](https://img.shields.io/badge/Computer_Vision-OpenCV-white?style=flat&logo=opencv)](#)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](#)

**Articubot One** is a custom differential drive robot built from the ground up using ROS 2. It serves as a comprehensive platform for demonstrating core robotics concepts, including autonomous navigation, 2D mapping, sensor fusion, and computer vision-based object tracking.

This project encapsulates the fundamental building blocks of a modern autonomous mobile robot (AMR), providing a stable baseline for SLAM and AI experimentation.

---

## ✨ Core Capabilities

* 🧭 **Autonomous Navigation:** Full integration with the **Nav2** stack for dynamic path planning and obstacle avoidance.
* 🗺️ **2D SLAM Mapping:** Real-time environment mapping utilizing `slam_toolbox` to generate highly accurate occupancy grids.
* 🎯 **Computer Vision Tracking:** Onboard camera integration with an active OpenCV pipeline dedicated to real-time object detection and ball tracking.
* 📍 **Sensor Fusion & Localization:** Robust state estimation combining wheel odometry and IMU data through an Extended Kalman Filter (EKF) via `robot_localization`.
* 🎮 **Flexible Control:** Supports manual teleoperation via keyboard or standard joystick controllers, seamlessly handing off to autonomous control when required.
* 📊 **Full Visualization:** Fully compatible with **RViz2** for real-time debugging of TF trees, sensor data (`/scan`, `/odom`), and Nav2 costmaps.

---

## 🛠️ Technology Stack

### Frameworks & Simulation
* **Middleware:** ROS 2 (Jazzy)
* **Simulation Environment:** Gazebo
* **Visualization:** RViz2
* **Languages:** Python (`rclpy`) & C++ (`rclcpp`)

### ROS 2 Packages Used
* `nav2` (Navigation & Path Planning)
* `slam_toolbox` (Simultaneous Localization and Mapping)
* `robot_localization` (EKF Sensor Fusion)
* `cv_bridge` & `image_transport` (Computer Vision Pipeline)

---

## 🚀 Getting Started

### Prerequisites
Ensure you have ROS 2 Jazzy installed along with the required navigation and slam packages:
```bash
sudo apt install ros-jazzy-navigation2 ros-jazzy-nav2-bringup ros-jazzy-slam-toolbox ros-jazzy-robot-localization
```

![WhatsApp Image 2025-10-28 at 21 57 15](https://github.com/user-attachments/assets/ac7f90b7-1c7c-49f6-9ed8-bcd533ea61e7)


![WhatsApp Image 2025-10-28 at 22 18 03](https://github.com/user-attachments/assets/29b96c0f-55fa-4342-920a-541a19f7be44)
