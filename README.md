
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
## Windows Users

This project uses Docker to ensure a consistent ROS 2 environment.

Steps:
1. Install Docker Desktop for Windows
2. Clone the repository
3. Build the container:
   docker build -t lumeneye_ros .
4. Run the container:
   docker run -it lumeneye_ros
