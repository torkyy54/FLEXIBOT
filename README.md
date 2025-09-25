# 🚑 Autonomous Mobile Manipulator for Hospital Logistics

## 📌 Project Overview
This graduation project presents an **autonomous mobile robot** designed to improve hospital logistics by transporting medical supplies and equipment safely and efficiently.  
The robot integrates a **6-DOF manipulator** for interacting with its environment (e.g., opening doors, pressing elevator buttons) and uses advanced navigation, security, and control systems for reliable operation.  

---

## 🚀 Key Features
- **Autonomous Navigation**: LiDAR + IMU sensor fusion for localization and obstacle avoidance.  
- **6-DOF Manipulator**: Capable of performing physical tasks such as opening doors.  
- **RFID-Based Secure Storage**: Protects sensitive medical supplies during delivery.  
- **Elevator & Door Interaction**: Manipulator and vision system used to press buttons and handles.  
- **Real-Time Monitoring**: Interface for medical staff to track and control the robot.  

---

## 🛠️ Hardware Components
- **Mobile Platform** – Differential drive base with Hub motors.  
- **6-DOF Robotic Arm** – Custom-designed manipulator.  
- **Sensors** – LiDAR, IMU, RFID module, and cameras.  
- **Controllers** – Tiva-C microcontroller, Jetson TX2, Raspberry Pi 4.  

---

## 💻 Software & Tools
- **Programming Languages**: Python, Embedded C, C++  
- **Frameworks/Tools**:  
  - Robot Operating System (**ROS**)  
  - MoveIt! for motion planning  
  - DWA Local Planner & Base Local Planner for navigation  
  - OpenCV for computer vision tasks  
  - Embedded C for microcontroller control  

---

## ⚙️ System Architecture
1. **Navigation System**: LiDAR + IMU fusion in ROS for SLAM and path planning.  
2. **Manipulator Control**: MoveIt! + Python scripts for trajectory planning.  
3. **Embedded Layer**: Tiva-C for low-level control of actuators and sensors.  
4. **High-Level Control**: Jetson TX2 & Raspberry Pi 4 for vision, navigation, and system coordination.  
5. **User Interface**: Simple GUI for monitoring robot status and deliveries.  

---

## 📊 Results
- Successfully navigated simulated hospital corridors.  
- Performed door/elevator button pressing using manipulator.  
- Demonstrated secure RFID-based storage and delivery of medical supplies.  
- Validated feasibility of using robotics for **low-cost healthcare automation in the MENA region**.  

---

## 📸 Demo
![CAD Model](media/hospital_robot_cad.png)  
