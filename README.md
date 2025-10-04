#  Autonomous Mobile Robot for Smart Parking Management

##  Project Overview
This project presents the design and implementation of an **autonomous mobile robot** for **smart parking management**.  
The system combines **computer vision**, **embedded systems**, and **robotics algorithms** to optimize parking space utilization, reduce CO₂ emissions, and enhance urban mobility.

### Main Objectives
- Detect available and occupied parking spots.  
- Navigate autonomously while avoiding obstacles.  
- Generate and update a **real-time dynamic parking map**.

---

##  Table of Contents
1. [Introduction](#introduction)  
2. [Project Concept](#project-concept)  
3. [Hardware Components](#hardware-components)  
4. [Mathematical Models & Algorithms](#mathematical-models--algorithms)  
5. [Software & Programming](#software--programming)  
6. [Implementation & Results](#implementation--results)  
7. [Discussion & Future Improvements](#discussion--future-improvements)  
8. [How to Run the Project](#how-to-run-the-project)  
9. [Images of the Project](#images-of-the-project)

---

##  Introduction

### Context & Motivation
Urban parking management has become a major issue due to the continuous increase in vehicle numbers. Drivers often spend excessive time searching for parking, leading to:
- Higher fuel consumption  
- Increased CO₂ emissions  
- Traffic congestion  

This project proposes an **autonomous robotic solution** capable of detecting available parking spaces, avoiding obstacles, and maintaining a **real-time parking map**.

### Value Added
-  **Innovative Solution:** Automates parking management to enhance efficiency.  
-  **Low-Cost Design:** Built using Raspberry Pi, Arduino, and LIDAR for affordability.  
-  **Modular Architecture:** Supports future extensions like license plate recognition.  
-  **Eco-Friendly Impact:** Reduces unnecessary vehicle movements and emissions.

---

##  Project Concept

### Problem Statement
Urban environments lack automated systems for real-time parking monitoring, resulting in inefficient space usage, long search times, and environmental pollution.

### Proposed Solution
The developed robot:
- Scans parking spaces using onboard cameras and sensors.  
- Detects vehicle presence via computer vision.  
- Avoids obstacles during navigation.  
- Updates a **dynamic digital parking map** in real-time.

---

##  Hardware Components

| Component | Description |
|------------|-------------|
| **Chassis** | 4-wheel mobile platform for stability and mobility |
| **Motors & Driver** | DC motors controlled via L293D motor driver shield |
| **Raspberry Pi 4** | Main processing unit for image analysis and control |
| **Arduino Uno** | Handles low-level sensor data processing |
| **Camera (Pi Camera v3)** | Captures images for vehicle detection |
| **LIDAR (TF Luna)** | Measures distances and detects obstacles |
| **Ultrasonic Sensors** | Assist in obstacle detection and avoidance |
| **Servo Motor** | Controls camera orientation for area scanning |
| **Lithium Batteries & Powerbank** | Provide power to the system |

---

##  Mathematical Models & Algorithms

### Parking Space & Obstacle Detection
- **Matrix-based parking representation** for efficient map management.  
- **Ultrasonic and LIDAR data** for real-time obstacle detection.  
- **Dynamic map updates** according to detected vehicles.

### Vehicle Detection
- Implemented using **OpenCV** for image processing.  
- Identifies car shapes and updates the digital parking layout.  

---

##  Software & Programming

### Languages
- **Python:** Main control and image processing on Raspberry Pi.  
- **C++:** Sensor and motor control on Arduino.

### Libraries
| Library | Function |
|----------|-----------|
| **OpenCV** | Vehicle detection and image processing |
| **NumPy** | Matrix operations and map representation |
| **RPi.GPIO** | GPIO control for Raspberry Pi peripherals |
| **Arduino Libraries** | Motor and sensor communication |

---

##  Implementation & Results

### Development Phases
1. Hardware assembly (motors, sensors, camera).  
2. Integration of sensors (LIDAR, ultrasonic).  
3. Implementation of image-based car detection (OpenCV).  
4. Development of autonomous navigation algorithms.  
5. Real-world testing and validation.

### Results
✅ Successfully identified **occupied and free parking spaces**.  
✅ Efficient obstacle avoidance.  
✅ Generated a **real-time dynamic parking map**.  

### Limitations
- No wheel encoders → reduced positional accuracy.  
- Detection affected by lighting and environmental noise.

---

##  Discussion & Future Improvements

### Strengths
- Low-cost and scalable system.  
- Real-time updates and autonomous navigation.  
- Modular architecture for further development.

### Limitations
- No GPS for large-scale localization.  
- Limited performance under low-light conditions.

### Future Enhancements
- Integration of **license plate recognition**.  
- Implementation of **AI-based navigation and mapping**.  
- Adaptation for **large and outdoor parking environments**.

---

##  How to Run the Project
1. Connect all hardware components.  
2. Upload Arduino code to handle sensors and motors.  
3. Run the Python script on Raspberry Pi for detection and mapping.  
4. Observe the parking visualization in real-time.  

---


## 📸 Images of the Project

### 🧱 3D Model (SolidWorks)
![3D Model](./3D_model.jpg)

### 🚗 Final Robot
![Final Robot](./final_robot.jpg)

### 🅿️ Robot in the Parking Lot
![Robot in Parking](./robot_parking.jpg)


---

###  Author
**Mohamed Bofarha**  
Final-Year Robotics Engineering Student  
📍 Morocco  
