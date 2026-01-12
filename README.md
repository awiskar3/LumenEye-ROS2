# LumenEye: Shadow-Free Robotic Lamp for Precision Tasks

## Overview
LumenEye is a ROS 2 and Gazebo-based robotic lamp system designed to provide
shadow-free illumination for precision manual tasks.

## System Architecture
- Perception: Tool tip and hand detection
- Planning: Shadow avoidance and lamp pose selection
- Control: Inverse kinematics and smooth lamp motion
- Simulation: Gazebo-based human–robot workspace

## Setup (macOS Users)
ROS 2 is run inside Docker (Ubuntu 22.04).

Requirements:
- macOS
- Docker Desktop

Start container:
```bash
docker start -ai lumeneye_ros
