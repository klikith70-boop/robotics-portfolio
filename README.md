# Robotics & Embedded Systems Engineering Portfolio

A curated portfolio of engineering projects spanning embedded firmware, holonomic drive kinematics, autonomous navigation, and edge TinyML perception.

---

## Portfolio Index

| Project | Primary Domain | Core Stack | Repository |
| :--- | :--- | :--- | :--- |
| **ArrayButton** | Edge TinyML & Audio Processing | ESP32, INMP441, TFLM, C++ | [View Code](https://github.com/SH047/ArrayButton) |
| **Automated Wet Floor Dryer Robot** | Mechatronics & Sensor Integration | Arduino, C++, Electro-mechanics | [View Code](https://github.com/klikith70-boop/automated-wet-floor-dryer-robot) |
| **4-Wheel Mecanum Mobile Platform** | Kinematics & Holonomic Locomotion | Arduino, L293D, Bluetooth, Embedded C | [View Code](https://github.com/klikith70-boop/mecanum-wheel-omnidirectional-robot) |
| **LiDAR Autonomous Maze Solver** | Autonomous Navigation & SLAM | ROS 2 Humble, Python, 2D LiDAR | [View Code](https://github.com/klikith70-boop/lidar-autonomous-maze-solver) |

---

## Detailed Project Case Studies

### 1. ArrayButton: Edge TinyML Acoustic Trigger & Interface
* **Repository:** [SH047/ArrayButton](https://github.com/SH047/ArrayButton) (Collaborative Development)
* **Role:** Firmware Architecture & TinyML Pipeline Integration
* **Highlights:**
  * Implemented real-time 16 kHz 32-bit audio acquisition over I2S using DMA buffering on an ESP32.
  * Deployed quantized (int8) neural inference models on-chip using TensorFlow Lite for Microcontrollers (TFLM).
  * Designed deterministic event-triggering logic on target acoustic classification.
* **Tech Stack:** C++, ESP32 / ESP32-S3, INMP441 Microphone, DMA, TFLM.

---

### 2. Automated Wet Floor Dryer Robot
* **Repository:** [klikith70-boop/automated-wet-floor-dryer-robot](https://github.com/klikith70-boop/automated-wet-floor-dryer-robot)
* **Highlights:**
  * Developed a dual-stage floor remediation mechanism integrating mechanical squeegee absorption and active thermal convection.
  * Programmed state-machine firmware for surface moisture sensing, obstacle detection, and automated motor sequencing.
* **Tech Stack:** Embedded C++, Arduino, Analog/Digital Sensors, H-Bridge Drivers.

---

### 3. 4-Wheel Mecanum Omnidirectional Mobile Platform
* **Repository:** [klikith70-boop/mecanum-wheel-omnidirectional-robot](https://github.com/klikith70-boop/mecanum-wheel-omnidirectional-robot)
* **Highlights:**
  * Engineered a 4-wheel independent drive platform utilizing 45° Mecanum rollers for holonomic planar locomotion.
  * Implemented an 8-direction velocity decomposition matrix interfaced via HC-05 serial Bluetooth communication.
* **Tech Stack:** Arduino Uno, Embedded C, L293D Motor Shield, Kinematic Vectoring.

---

### 4. LiDAR Autonomous Maze Solver
* **Repository:** [klikith70-boop/lidar-autonomous-maze-solver](https://github.com/klikith70-boop/lidar-autonomous-maze-solver)
* **Highlights:**
  * Developed a reactive path-finding pipeline utilizing 360° 2D laser scan data for enclosed corridor navigation.
  * Implemented real-time sector filtering for dead-end detection and proportional wall-following control.
* **Tech Stack:** ROS 2 Humble, Python 3, NumPy, `sensor_msgs/LaserScan`, `geometry_msgs/Twist`.

---

## Technical Competencies
* **Middleware & Software:** ROS 2 Humble, PyBullet, OpenCV, Linux (Ubuntu/WSL), Git
* **Embedded & Hardware:** ESP32, Arduino, I2S, SPI, I2C, UART, Motor Actuation, Sensor Interfacing
* **Languages:** C++, Python, Embedded C
