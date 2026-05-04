# 🤖 Autonomous Differential Robot | ROS 2 Jazzy

This is a complete mobile robotics simulation developed using **ROS 2 Jazzy** and **Gazebo Sim (Harmonic)**. The project includes a differential drive robot equipped with a LiDAR for real-time SLAM.

## 🌟 Key Features
*   **URDF/Xacro Description**: Custom robot model with differential drive physics.
*   **Gazebo Harmonic Integration**: Modern simulation environment.
*   **SLAM Toolbox**: Real-time 2D mapping capability.
*   **ros2_control**: Precise velocity control via `diff_drive_controller`.

## 📂 Project Structure
*   `description/`: URDF and sensor configuration.
*   `launch/`: Files to start the simulation and SLAM.
*   `config/`: YAML files for controller and mapper parameters.

## 🚀 Quick Start

### 1. Build the project
```bash
cd ~/dev_ws
colcon build --symlink-install
source install/setup.bash
