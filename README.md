# Line Follower Robot

A line follower robot built using an L293D motor driver and 5 IR sensors to autonomously follow a predefined path.  
This project is designed for robotics enthusiasts, students, and hobbyists who want to explore embedded systems, sensor integration, and real-world robotic control using microcontrollers.

## 🛠️ Overview

The Line Follower Robot is a classic robotics challenge where a mobile robot detects and follows a line on the ground using infrared (IR) sensors. This project integrates hardware and software logic to interpret sensor feedback and actuate motors accordingly, enabling autonomous navigation along a designated track.

## 🔧 Key Features

- **Sensor-based navigation:** Uses 5 IR sensors to detect line contrast and determine robot direction.
- **Motor control:** Employs the L293D motor driver to regulate the speed and direction of DC motors.
- **Real-time decision making:** Continuously reads sensor values and adjusts movement to stay on track.
- **Compact and modular design:** Easy to assemble and extend with additional components.

## 📦 Repository Contents

- Source code for the microcontroller (Arduino or similar)
- Circuit schematics and wiring references
- Documentation and notes for testing and calibration
- Supporting images or simulation files (if included)

## 🧠 How It Works

1. **Line Detection:**  
   The IR sensors detect the difference between the track surface and the line (usually black on white or vice versa).

2. **Signal Interpretation:**  
   Each sensor sends a digital signal to the microcontroller indicating whether it is over the line or background.

3. **Control Logic:**  
   Based on the pattern of sensor readings, the microcontroller adjusts motor speeds/direction via the L293D motor driver to correct the robot’s path.

## 🧩 Components Used

- **Microcontroller:** Arduino or compatible controller
- **Motor Driver:** L293D
- **Sensors:** 5 Infrared (IR) line sensors
- **Actuators:** DC motors with wheels
- **Power Source:** Battery pack

## 🚀 Who This Is For

This repository is ideal for:
- Students learning **robotics fundamentals**
- Makers building autonomous ground vehicles
- Educators teaching **embedded systems and sensors**
- Anyone practicing hardware-software integration

## 📍 Next Steps

To enhance this project:
- Add PID control for smoother navigation
- Integrate Bluetooth/Wi-Fi for remote monitoring
- Use encoder feedback for precision movement
- Upgrade to obstacle detection

