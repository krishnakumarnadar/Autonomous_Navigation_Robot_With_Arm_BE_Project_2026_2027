# 🤖 MULTIPURPOSE AUTONOMOUS NAVIGATION ROBOT WITH ARM

<p align="center">
  <img src="images/banner.png" alt="Multipurpose Autonomous Navigation Robot" width="900">
</p>

<p align="center">
  <b>Autonomous Navigation • Computer Vision • Robotic Manipulation • Embedded Systems</b>
</p>

<p align="center">

![Project Status](https://img.shields.io/badge/Project-Under%20Development-orange?style=for-the-badge)
![Domain](https://img.shields.io/badge/Domain-Robotics-blue?style=for-the-badge)
![Computer Vision](https://img.shields.io/badge/Computer%20Vision-OpenCV-green?style=for-the-badge)
![Embedded](https://img.shields.io/badge/Embedded-Arduino-red?style=for-the-badge)

</p>

---

## 🚀 Overview

The **Multipurpose Autonomous Navigation Robot with Arm** is a mobile robotic platform designed to combine **autonomous navigation, computer vision, obstacle detection, and robotic manipulation** into a single system.

The robot is designed to perceive its environment, identify relevant objects, navigate toward a target, and use its robotic arm to perform pick-and-place operations.

### Core Concept

> 🧠 **Artificial Intelligence** + 👁️ **Computer Vision** + 🧭 **Autonomous Navigation** + 🦾 **Robotic Manipulation**

---

## 🎥 Project Proposal Video

<p align="center">

<a href="https://www.youtube.com/watch?v=KK-MWK9cCMU">
<img src="https://img.youtube.com/vi/KK-MWK9cCMU/maxresdefault.jpg" width="800">
</a>

</p>

<p align="center">
<b>▶️ Click the thumbnail to watch the project video</b>
</p>

---

## 📌 Problem Statement

Traditional mobile robots generally perform a limited set of tasks. A navigation robot may be capable of moving autonomously but may not be able to physically interact with objects, while a robotic arm may perform manipulation but require a fixed or manually controlled platform.

This project aims to develop an integrated robotic system capable of:

- Autonomous movement
- Obstacle detection and avoidance
- Object identification
- Target localization
- Navigation toward the target
- Robotic arm control
- Pick-and-place operations

The overall objective is to develop a **mobile manipulation platform** capable of performing useful tasks with minimal human intervention.

---

## 💡 Proposed System

The proposed system integrates a **mobile robot chassis, sensors, camera, embedded controller, computer vision pipeline, and robotic arm**.

The robot receives information from its environment, processes the information, determines an appropriate action, navigates toward the required location, and performs manipulation using the robotic arm.

### High-Level Workflow

```text
                    ┌──────────────────┐
                    │      CAMERA      │
                    └────────┬─────────┘
                             │
                             ▼
                    ┌──────────────────┐
                    │ COMPUTER VISION  │
                    │   / OBJECT       │
                    │    DETECTION     │
                    └────────┬─────────┘
                             │
                             ▼
┌───────────────┐    ┌──────────────────┐    ┌─────────────────┐
│    SENSORS    │───►│  MAIN CONTROLLER │───►│ MOBILE PLATFORM │
└───────────────┘    └────────┬─────────┘    └─────────────────┘
                              │
                              ▼
                    ┌─────────────────┐
                    │  ROBOTIC ARM    │
                    │  PICK & PLACE   │
                    └─────────────────┘

```
# ✨ FEATURES

<p align="center">
  <b>A complete mobile manipulation platform combining perception, navigation and robotic control.</b>
</p>

<br>

| 🤖 AUTONOMOUS NAVIGATION | 👁️ COMPUTER VISION | 🦾 ROBOTIC MANIPULATION |
|:---:|:---:|:---:|
| Autonomous movement | Object detection | Pick & Place |
| Obstacle avoidance | Target localization | Servo control |
| Motion control | Image processing | Gripper control |

<br>

### 🚀 KEY CAPABILITIES

- 🤖 Autonomous mobile robot platform
- 🧭 Autonomous navigation
- 🚧 Obstacle detection and avoidance
- 👁️ Computer vision
- 🎯 Object detection
- 📍 Target localization
- 🦾 Robotic arm manipulation
- 📦 Pick-and-place functionality
- ⚡ Embedded motor control
- 🔌 Sensor integration
- 💻 Python-based vision processing
- 🔗 Communication between processing and control systems
- 🧩 Modular hardware and software architecture

---

# 🛠️ TECH STACK

<p align="center">
  <b>Technologies used to build the autonomous robotic system</b>
</p>

<br>

## 👁️ COMPUTER VISION & AI

<p align="center">
  <img src="https://skillicons.dev/icons?i=python" width="70">
  <img src="https://skillicons.dev/icons?i=opencv" width="70">
</p>

<p align="center">
  <b>Python &nbsp; • &nbsp; OpenCV &nbsp; • &nbsp; YOLO</b>
</p>

<br>

## ⚡ EMBEDDED SYSTEMS

<p align="center">
  <img src="https://skillicons.dev/icons?i=arduino" width="70">
  <img src="https://skillicons.dev/icons?i=cpp" width="70">
</p>

<p align="center">
  <b>Arduino &nbsp; • &nbsp; Embedded C/C++ &nbsp; • &nbsp; Sensors &nbsp; • &nbsp; Motor Control</b>
</p>

<br>

## 🧮 SIMULATION & ENGINEERING

<p align="center">
  <img src="https://skillicons.dev/icons?i=matlab" width="70">
</p>

<p align="center">
  <b>MATLAB &nbsp; • &nbsp; Simulink &nbsp; • &nbsp; Robotics Simulation</b>
</p>

<br>

## 💻 DEVELOPMENT & VERSION CONTROL

<p align="center">
  <img src="https://skillicons.dev/icons?i=vscode" width="70">
  <img src="https://skillicons.dev/icons?i=git" width="70">
  <img src="https://skillicons.dev/icons?i=github" width="70">
</p>

<p align="center">
  <b>VS Code &nbsp; • &nbsp; Git &nbsp; • &nbsp; GitHub</b>
</p>

---

# 🧠 SYSTEM CONCEPT

<p align="center">
  <b>PERCEPTION → DECISION → NAVIGATION → MANIPULATION</b>
</p>

The robot operates as a **mobile manipulator**, combining autonomous mobility with physical interaction.

| 🧠 PERCEPTION | 🎯 DECISION | 🧭 NAVIGATION | 🦾 MANIPULATION |
|:---:|:---:|:---:|:---:|
| Camera | Target identification | Path planning | Arm movement |
| Sensors | Object detection | Obstacle avoidance | Gripper control |
| OpenCV / YOLO | Action selection | Motor control | Pick & Place |

---

# 🔩 HARDWARE

<p align="center">
  <b>Physical components of the autonomous mobile manipulation platform</b>
</p>

<br>

| # | COMPONENT | SPECIFICATION | QTY | PURPOSE |
|---|---|---|---:|---|
| 01 | 🧠 Microcontroller | `TODO` | `TODO` | Robot control |
| 02 | 🚗 Robot Chassis | `TODO` | 1 | Mobile platform |
| 03 | ⚙️ DC Motors | `TODO` | `TODO` | Locomotion |
| 04 | 🔌 Motor Driver | `TODO` | `TODO` | Motor control |
| 05 | 📷 Camera | `TODO` | 1 | Computer vision |
| 06 | 📡 Sensors | `TODO` | `TODO` | Environment sensing |
| 07 | 🦾 Robotic Arm | `TODO` | 1 | Object manipulation |
| 08 | ⚙️ Servo Motors | `TODO` | `TODO` | Arm actuation |
| 09 | 🖐️ Gripper | `TODO` | 1 | Object grasping |
| 10 | 🔋 Battery | `TODO` | 1 | Power supply |

---

# 💻 SOFTWARE

| SOFTWARE / TOOL | PURPOSE |
|---|---|
| 🐍 Python | Computer vision & high-level processing |
| 👁️ OpenCV | Image processing |
| 🎯 YOLO | Object detection |
| ⚡ Arduino IDE | Embedded programming |
| 🧮 MATLAB | Modelling & simulation |
| 📊 Simulink | System simulation |
| 💻 VS Code | Software development |
| 🌐 Git / GitHub | Version control |

---

# 🧭 AUTONOMOUS NAVIGATION

<p align="center">
  <b>Perceive → Decide → Move → Verify</b>
</p>

### Navigation Pipeline

| STEP | PROCESS |
|:---:|---|
| 01 | 📡 Sensor Input |
| 02 | 🌍 Environment Perception |
| 03 | 🚧 Obstacle Detection |
| 04 | 🧠 Navigation Decision |
| 05 | ⚙️ Motor Command |
| 06 | 🤖 Robot Movement |
| 07 | 🔄 Feedback |

---

# 👁️ COMPUTER VISION

<p align="center">
  <b>Giving the robot the ability to perceive and identify its environment</b>
</p>

### Vision Pipeline

```text
📷 CAMERA
    │
    ▼
🖼️ IMAGE ACQUISITION
    │
    ▼
⚙️ IMAGE PROCESSING
    │
    ▼
🎯 YOLO OBJECT DETECTION
    │
    ▼
📍 OBJECT LOCALIZATION
    │
    ▼
🧠 DECISION MAKING
    │
    ▼
🤖 ROBOT ACTION
```

---

# 🦾 ROBOTIC ARM

<p align="center">
  <b>Autonomous object manipulation and pick-and-place</b>
</p>

### Pick & Place Pipeline

```text
📍 TARGET LOCATION
        │
        ▼
🤖 POSITION ROBOT
        │
        ▼
🦾 MOVE ARM
        │
        ▼
🖐️ OPEN GRIPPER
        │
        ▼
🎯 GRASP OBJECT
        │
        ▼
✊ CLOSE GRIPPER
        │
        ▼
⬆️ LIFT OBJECT
        │
        ▼
📦 MOVE TO DESTINATION
        │
        ▼
🖐️ RELEASE OBJECT
        │
        ▼
✅ TASK COMPLETE
```

---

# 🔌 COMMUNICATION ARCHITECTURE

| SYSTEM | TECHNOLOGY | FUNCTION |
|---|---|---|
| 💻 High-Level Computer | Python / OpenCV / YOLO | Vision & decision making |
| ⚡ Microcontroller | Arduino / C++ | Low-level control |
| 🚗 Mobile Platform | Motors + Driver | Robot movement |
| 🦾 Robotic Arm | Servos | Manipulation |
| 📡 Sensors | `TODO` | Environment feedback |

> **TODO:** Add the final communication protocol once the hardware architecture is finalized.

---

# 📐 DESIGN & ENGINEERING

## 🧱 CAD MODEL

<p align="center">
  <img src="images/cad_model.png" alt="CAD Model" width="850">
</p>

## ⚡ CIRCUIT DIAGRAM

<p align="center">
  <img src="images/circuit_diagram.png" alt="Circuit Diagram" width="850">
</p>

## 🔄 FLOWCHART

<p align="center">
  <img src="images/flowchart.png" alt="Project Flowchart" width="850">
</p>

---

# 🧪 TESTING & RESULTS

| TEST | DESCRIPTION | EXPECTED RESULT | ACTUAL RESULT | STATUS |
|---|---|---|---|---|
| 01 | Motor Movement | Correct movement | `TODO` | ⏳ |
| 02 | Sensor Detection | Obstacles detected | `TODO` | ⏳ |
| 03 | Object Detection | Target detected | `TODO` | ⏳ |
| 04 | Navigation | Target reached | `TODO` | ⏳ |
| 05 | Arm Movement | Correct positioning | `TODO` | ⏳ |
| 06 | Gripper | Object grasped | `TODO` | ⏳ |
| 07 | Pick & Place | Object moved | `TODO` | ⏳ |
| 08 | Full System | Complete task | `TODO` | ⏳ |

---

# 📊 PERFORMANCE

| PARAMETER | RESULT |
|---|---:|
| 🎯 Object Detection Accuracy | `TODO %` |
| ⚡ Detection FPS | `TODO FPS` |
| 🧭 Navigation Success Rate | `TODO %` |
| 🦾 Pick-and-Place Success Rate | `TODO %` |
| ⏱️ Average Navigation Time | `TODO sec` |
| 📦 Maximum Payload | `TODO g` |
| 🔋 Operating Time | `TODO min` |

---

# 📸 PROTOTYPE

<p align="center">
  <img src="images/prototype_photo.jpg" alt="Robot Prototype" width="900">
</p>

---

# 🎬 DEMONSTRATION

<p align="center">
  <a href="https://www.youtube.com/watch?v=KK-MWK9cCMU">
    <img src="https://img.youtube.com/vi/KK-MWK9cCMU/maxresdefault.jpg" width="800">
  </a>
</p>

<p align="center">
  <b>▶️ WATCH THE ROBOT IN ACTION</b>
</p>

---

# 🌍 APPLICATIONS

| 🏭 INDUSTRIAL | 📦 LOGISTICS | 🏥 SERVICE |
|:---:|:---:|:---:|
| Factory automation | Material handling | Service robotics |
| Inspection | Warehouse tasks | Indoor assistance |

| 🗑️ WASTE MANAGEMENT | 🚨 HAZARDOUS ENVIRONMENTS | 🔬 RESEARCH |
|:---:|:---:|:---:|
| Waste collection | Remote operation | Robotics research |
| Sorting assistance | Risk reduction | Autonomous systems |

---

# 🚀 FUTURE SCOPE

### 🧠 ARTIFICIAL INTELLIGENCE
- Improved object detection
- Custom-trained models
- Multi-object recognition
- Intelligent task planning

### 🧭 AUTONOMOUS NAVIGATION
- SLAM
- Autonomous mapping
- Localization
- Dynamic obstacle avoidance
- Advanced path planning

### 🦾 ROBOTIC MANIPULATION
- Improved inverse kinematics
- Grasp planning
- Increased payload capacity
- Autonomous object placement

### 🌐 ADVANCED ROBOTICS
- ROS / ROS 2 integration
- LiDAR-based navigation
- Sensor fusion
- Edge AI
- Cloud monitoring
- Multi-robot coordination

---

# 🏆 PROJECT STATUS

<p align="center">

![Status](https://img.shields.io/badge/STATUS-ACTIVE%20DEVELOPMENT-orange?style=for-the-badge)
![Robotics](https://img.shields.io/badge/ROBOTICS-MOBILE%20MANIPULATOR-blue?style=for-the-badge)
![AI](https://img.shields.io/badge/AI-COMPUTER%20VISION-purple?style=for-the-badge)

</p>

<p align="center">

### 🤖 NAVIGATION × 👁️ VISION × 🦾 MANIPULATION

</p>

---

<p align="center">

### 🤖 Built with curiosity. Engineered with robotics. Driven by automation.

</p>


