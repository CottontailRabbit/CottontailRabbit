<h1 align="center">Hongcheol Kim</h1>

<p align="center">
  <b>Robotics Software Engineer</b> · ROS 2 drivers for dexterous hands &amp; grippers · C++ / Python / Rust
</p>

<p align="center">
  <a href="mailto:hongcheol@kakao.com"><img src="https://img.shields.io/badge/Email-hongcheol%40kakao.com-D14836?logo=gmail&logoColor=white" /></a>
  <img src="https://img.shields.io/badge/Location-Korea-555555" />
</p>

---

## 👋 About

I build the software layer between robot hardware and ROS 2: device drivers, `ros2_control` hardware interfaces,
and MoveIt 2 / Gazebo integration, mostly for multi-fingered robotic hands and grippers.

- 🖐️ Developing and maintaining the ROS 2 stack for **Tesollo DELTO** hands and grippers (DG-1F to DG-5F)
- 🔌 Fieldbus and device I/O: Modbus TCP/RTU, raw TCP sockets, UR RTDE
- 🦀 Robotics in Rust: kinematics, servo drivers, control design tools
- 🔬 Interested in dexterous manipulation, hand retargeting, and sim-to-real

---

## 🖐️ Tesollo DELTO: ROS 2

| Project | Description |
|---|---|
| [**tesollo_ros2**](https://github.com/tesollodelto/tesollo_ros2) | Unified ROS 2 drivers for Tesollo hands &amp; grippers: `ros2_control`, MoveIt 2, Gazebo, SDK integration |
| [**delto_m_ros2**](https://github.com/tesollodelto/delto_m_ros2) | DELTO M gripper ROS 2 package: topic-based and `ros2_control` interfaces over Modbus TCP |
| [**delto_b_ros2**](https://github.com/tesollodelto/delto_b_ros2) | ROS 2 driver for DELTO B-series grippers |
| [**dg_sdk_ros2_bridge**](https://github.com/tesollodelto/dg_sdk_ros2_bridge) | ROS 2 bridge for the Tesollo DG SDK: nodes, custom messages, and services |

## 🛠️ Personal Projects

| Project | Description | Stack |
|---|---|---|
| [**modern_robotics_rs**](https://github.com/CottontailRabbit/modern_robotics_rs) | Rust implementation of *Modern Robotics* (Lynch &amp; Park): kinematics, dynamics, motion planning | Rust |
| [**LX16A_RUST**](https://github.com/CottontailRabbit/LX16A_RUST) | Rust library for LX-16A serial bus servos | Rust · Serial |
| [**ros2_pid_tuner_gui**](https://github.com/CottontailRabbit/ros2_pid_tuner_gui) | GUI for live-tuning `ros2_control` PID gains | Python · PyQt5 · ROS 2 |
| [**Pickit_ROS2_interface**](https://github.com/CottontailRabbit/Pickit_ROS2_interface) | ROS 2 interface for the Pickit 3D vision system | C++ · ROS 2 |
| [**dg_modbus**](https://github.com/CottontailRabbit/dg_modbus) | Python Modbus TCP library for Tesollo DG-3F / 4F / 5F | Python · Modbus |
| [**codekata-cli**](https://github.com/CottontailRabbit/codekata-cli) | Terminal coding kata with executed judging and online ranking | Python |

---

## 🚀 Tech Stack

**Languages**<br/>
![C++](https://img.shields.io/badge/C%2B%2B-00599C?logo=c%2B%2B&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?logo=rust&logoColor=white)
![MATLAB](https://img.shields.io/badge/MATLAB-0076A8)

**Robotics**<br/>
![ROS 2](https://img.shields.io/badge/ROS%202-22314E?logo=ros&logoColor=white)
![ros2_control](https://img.shields.io/badge/ros2__control-22314E)
![MoveIt 2](https://img.shields.io/badge/MoveIt%202-EC4D37)
![Gazebo](https://img.shields.io/badge/Gazebo-9E9E9E)
![Isaac Sim](https://img.shields.io/badge/Isaac%20Sim-76B900?logo=nvidia&logoColor=white)

**Protocols &amp; I/O**<br/>
![Modbus](https://img.shields.io/badge/Modbus-TCP%2FRTU-0A66C2)
![UR RTDE](https://img.shields.io/badge/UR%20RTDE-00599C)
![TCP/IP](https://img.shields.io/badge/TCP%2FIP-555555)

**UI**<br/>
![Qt](https://img.shields.io/badge/Qt-41CD52?logo=qt&logoColor=white)
![Electron](https://img.shields.io/badge/Electron-2B2E3A?logo=electron&logoColor=white)

**Tools**<br/>
![Linux](https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black)
![CMake](https://img.shields.io/badge/CMake-064F8C?logo=cmake&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white)
![GitLab CI/CD](https://img.shields.io/badge/GitLab%20CI%2FCD-FC6D26?logo=gitlab&logoColor=white)
![SolidWorks](https://img.shields.io/badge/SolidWorks-F88909)
