# 🤖 Autonomous Mobile Robot | ROS 2 Jazzy & Gazebo Harmonic

This project is a complete simulation of a differential drive robot designed for **ROS 2 Jazzy**. It integrates the latest **Gazebo Sim (Harmonic)** for realistic physics and sensor simulation, including LiDAR-based **SLAM**.

## 🌟 Key Features
*   **Modern Simulation**: Built specifically for Gazebo Harmonic and ROS 2 Jazzy.
*   **Detailed URDF**: High-fidelity robot model with Xacro for easy parameter tuning.
*   **SLAM Navigation**: Integrated with `slam_toolbox` for real-time 2D mapping.
*   **ros2_control**: Professional-grade controller configuration for differential drive.

## 📂 Project Architecture
*   **`description/`**: URDF/Xacro files defining the robot's physical and visual model.
*   **`launch/`**: Python launch files to bring up the simulation, robot state, and RViz.
*   **`config/`**: YAML files for SLAM parameters and controller settings.

## 🚀 Getting Started

### 1. Environment Setup
Ensure you have ROS 2 Jazzy and Gazebo Harmonic installed. 

### 2. Build the Workspace
```bash
cd ~/dev_ws
colcon build --symlink-install
source install/setup.bash
