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

## 🎥 Project Video

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
                     │ PICK & PLACE    │


✨ Features
🤖 Autonomous mobile robot platform
🧭 Autonomous navigation
🚧 Obstacle detection and avoidance
👁️ Computer vision
🎯 Object detection
📍 Target localization
🦾 Robotic arm manipulation
📦 Pick-and-place functionality
⚡ Embedded motor control
🔌 Sensor integration
💻 Python-based vision processing
🔗 Communication between processing and control systems
🧩 Modular hardware and software architecture
🛠️ Tech Stack
👁️ Computer Vision & AI
<p align="left"> <a href="https://www.python.org/"> <img src="https://skillicons.dev/icons?i=python" width="60"> </a> <a href="https://opencv.org/"> <img src="https://skillicons.dev/icons?i=opencv" width="60"> </a> </p>

Technologies

Python
OpenCV
YOLO — Object Detection
Image Processing
Object Localization
⚡ Embedded Systems
<p align="left"> <a href="https://www.arduino.cc/"> <img src="https://skillicons.dev/icons?i=arduino" width="60"> </a> <a href="https://isocpp.org/"> <img src="https://skillicons.dev/icons?i=cpp" width="60"> </a> </p>

Technologies

Arduino
Embedded C/C++
Sensors
Motor Control
Servo Control
Serial Communication
🧮 Simulation & Engineering
<p align="left"> <a href="https://www.mathworks.com/"> <img src="https://skillicons.dev/icons?i=matlab" width="60"> </a> </p>

Technologies

MATLAB
Simulink
Robotics Simulation
Kinematic Analysis
💻 Development & Version Control
<p align="left"> <a href="https://code.visualstudio.com/"> <img src="https://skillicons.dev/icons?i=vscode" width="60"> </a> <a href="https://git-scm.com/"> <img src="https://skillicons.dev/icons?i=git" width="60"> </a> <a href="https://github.com/"> <img src="https://skillicons.dev/icons?i=github" width="60"> </a> </p>
🏗️ System Architecture
<p align="center"> <img src="images/system_architecture.png" alt="System Architecture" width="850"> </p>
System Layers
Layer	Responsibility
👁️ Perception	Camera and sensor data acquisition
🧠 Intelligence	Object detection and decision making
🧭 Navigation	Robot movement and obstacle avoidance
⚡ Control	Motor and actuator control
🦾 Manipulation	Robotic arm and pick-and-place
🔌 Communication	Data exchange between systems
🧠 System Concept

The robot functions as a mobile manipulator, combining autonomous mobility with physical interaction.

             ENVIRONMENT
                  │
                  ▼
          ┌──────────────┐
          │   SENSING    │
          └──────┬───────┘
                 │
                 ▼
          ┌──────────────┐
          │ PERCEPTION   │
          │ Computer     │
          │ Vision       │
          └──────┬───────┘
                 │
                 ▼
          ┌──────────────┐
          │   DECISION   │
          │    MAKING    │
          └──────┬───────┘
                 │
          ┌──────┴──────┐
          ▼             ▼
    ┌───────────┐  ┌────────────┐
    │ NAVIGATE  │  │ MANIPULATE │
    └─────┬─────┘  └──────┬─────┘
          │               │
          └───────┬───────┘
                  ▼
          ┌──────────────┐
          │ TASK COMPLETE│
          └──────────────┘
🔩 Hardware Requirements
#	Component	Specification	Quantity	Purpose
01	Microcontroller	TODO	TODO	Robot control
02	Robot Chassis	TODO	1	Mobile platform
03	DC Motors	TODO	TODO	Locomotion
04	Motor Driver	TODO	TODO	Motor control
05	Camera	TODO	1	Computer vision
06	Sensors	TODO	TODO	Environment sensing
07	Robotic Arm	TODO	1	Object manipulation
08	Servo Motors	TODO	TODO	Arm actuation
09	Gripper	TODO	1	Object grasping
10	Battery	TODO	1	Power supply
💻 Software Requirements
#	Software / Tool	Purpose
01	Python	Computer vision and high-level processing
02	OpenCV	Image processing
03	YOLO	Object detection
04	Arduino IDE	Embedded programming
05	MATLAB	Modelling and simulation
06	Simulink	System simulation
07	VS Code	Development
08	Git / GitHub	Version control
🔄 Methodology
Phase 01 — Research
Literature survey
Existing system analysis
Problem identification
Requirement analysis
Phase 02 — Design
Robot chassis design
Electronics architecture
Sensor placement
Robotic arm integration
Software architecture
Phase 03 — Development
Hardware assembly
Motor control
Sensor integration
Computer vision implementation
Robotic arm control
Phase 04 — Integration
Integrate computer vision
Establish communication
Integrate navigation
Integrate robotic arm
Test complete workflow
Phase 05 — Testing
Navigation testing
Obstacle avoidance testing
Object detection testing
Pick-and-place testing
Full system testing
🧭 Autonomous Navigation

The navigation system is responsible for moving the robot toward the required destination while detecting and avoiding obstacles.

Navigation Pipeline
Sensor Input
     │
     ▼
Environment Perception
     │
     ▼
Obstacle Detection
     │
     ▼
Motion Decision
     │
     ▼
Motor Command
     │
     ▼
Robot Movement
     │
     ▼
Feedback
     │
     └──────────────► Repeat
👁️ Computer Vision

Computer vision provides the robot with visual perception.

The camera captures frames which are processed by the vision pipeline.

Camera
  │
  ▼
Image Acquisition
  │
  ▼
Pre-processing
  │
  ▼
Object Detection
  │
  ▼
Object Localization
  │
  ▼
Target Selection
  │
  ▼
Robot Action
Vision Stack
Python
   │
   ▼
OpenCV
   │
   ▼
YOLO
   │
   ▼
Object Detection
   │
   ▼
Decision
   │
   ▼
Robot Action
🦾 Robotic Arm

The robotic arm allows the mobile platform to physically interact with objects.

Pick-and-Place Workflow
Approach Target
      │
      ▼
Position Robot
      │
      ▼
Locate Object
      │
      ▼
Move Arm
      │
      ▼
Open Gripper
      │
      ▼
Reach Object
      │
      ▼
Close Gripper
      │
      ▼
Lift Object
      │
      ▼
Move to Destination
      │
      ▼
Release Object
Arm Operations
Arm positioning
Servo control
Gripper control
Object grasping
Object transportation
Object placement
🔌 Communication Architecture
┌───────────────────────────────┐
│          HIGH LEVEL PC        │
│                               │
│      Python + OpenCV + YOLO   │
└───────────────┬───────────────┘
                │
                │ Communication
                ▼
┌───────────────────────────────┐
│        MICROCONTROLLER        │
│                               │
│       Arduino / C++           │
└───────────────┬───────────────┘
                │
          ┌─────┴─────┐
          ▼           ▼
     ┌─────────┐ ┌──────────┐
     │ Motors  │ │  Servos  │
     └─────────┘ └──────────┘

TODO: Replace the communication method with the final implementation.

📐 Design Files
File	Description
📐 CAD Model	Robot chassis and mechanical design
⚡ Circuit Diagram	Electrical connections
🔌 PCB Design	Electronics / PCB
🔄 Flowchart	System algorithm
🧮 Simulation	MATLAB / Simulink files
CAD Model
<p align="center"> <img src="images/cad_model.png" alt="CAD Model" width="700"> </p>
Circuit Diagram
<p align="center"> <img src="images/circuit_diagram.png" alt="Circuit Diagram" width="800"> </p>
📁 Repository Structure
BE-Capstone-Project/
│
├── README.md
│
├── docs/
│   ├── literature_survey.md
│   ├── project_report.pdf
│   └── presentation.pptx
│
├── hardware/
│   ├── circuit_diagram.png
│   ├── pcb_design/
│   └── cad_model/
│
├── software/
│   ├── computer_vision/
│   ├── navigation/
│   ├── robotic_arm/
│   ├── communication/
│   └── tests/
│
├── models/
│   └── trained_model/
│
├── images/
│   ├── banner.png
│   ├── system_architecture.png
│   ├── cad_model.png
│   ├── circuit_diagram.png
│   ├── prototype_photo.jpg
│   ├── electronics.jpg
│   ├── arm.jpg
│   └── results.png
│
└── references/
    └── papers/
⚙️ Implementation Details
Hardware Implementation

The hardware subsystem consists of the mobile chassis, drive motors, motor driver, sensors, camera, robotic arm, actuators, and power system.

The embedded controller handles communication with sensors, motors, and actuators.

TODO: Add exact circuit connections, pin configuration, component specifications, and power architecture.

Software Implementation

The software system is divided into several modules.

Computer Vision

Responsible for:

Camera input
Image processing
Object detection
Object localization
Navigation

Responsible for:

Sensor processing
Obstacle detection
Motion control
Navigation decisions
Robotic Arm

Responsible for:

Arm positioning
Servo control
Gripper control
Pick-and-place
Communication

Responsible for communication between the high-level processing system and embedded controller.

▶️ How to Run
Step 1 — Clone Repository
git clone https://github.com/username/project-name.git
cd project-name
Step 2 — Install Dependencies
pip install -r requirements.txt
Step 3 — Run Computer Vision
python main.py

TODO: Replace main.py with the actual entry point.

Step 4 — Upload Embedded Code

Using Arduino IDE:

Connect the microcontroller.
Select the correct board.
Select the correct COM port.
Upload the firmware.

Or using Arduino CLI:

arduino-cli upload -p COMx --fqbn board_name
🧪 Testing & Results
Test Cases
Test	Description	Expected Result	Actual Result	Status
01	Motor Movement	Robot moves correctly	TODO	⏳
02	Sensor Detection	Obstacles detected	TODO	⏳
03	Object Detection	Target detected	TODO	⏳
04	Navigation	Robot reaches target	TODO	⏳
05	Arm Movement	Arm reaches target	TODO	⏳
06	Gripper	Object grasped	TODO	⏳
07	Pick & Place	Object successfully moved	TODO	⏳
08	Full System	Complete task executed	TODO	⏳
📊 Performance Results

Replace these values with your actual experimental results.

Parameter	Result
Object Detection Accuracy	TODO %
Detection FPS	TODO FPS
Navigation Success Rate	TODO %
Pick-and-Place Success Rate	TODO %
Average Navigation Time	TODO sec
Maximum Payload	TODO g
Operating Time	TODO min
📸 Prototype
<p align="center"> <img src="images/prototype_photo.jpg" alt="Robot Prototype" width="800"> </p>
🎬 Demonstration
<p align="center"> <a href="https://www.youtube.com/watch?v=KK-MWK9cCMU"> <img src="https://img.youtube.com/vi/KK-MWK9cCMU/maxresdefault.jpg" width="750"> </a> </p> <p align="center">

<b>▶️ WATCH THE PROJECT VIDEO</b>

</p>
🌍 Applications

The system can potentially be adapted for:

📦 Material handling
🏭 Industrial automation
🏥 Service robotics
🗑️ Waste collection and segregation
🏢 Indoor service robotics
📦 Warehouse automation
🚨 Hazardous environment assistance
🔬 Robotics research and education
✅ Advantages
Combines navigation and manipulation
Reduces dependency on manual control
Modular hardware architecture
Modular software architecture
Computer vision based perception
Adaptable to multiple applications
Suitable for further autonomous robotics research
⚠️ Limitations
Sensor accuracy affects navigation
Computer vision performance depends on lighting
Robotic arm payload is limited by mechanical design
Navigation performance depends on the environment
Battery capacity limits operating duration
Prototype hardware may limit large-scale deployment
🚀 Future Scope
🧠 Artificial Intelligence
Improved object detection
Custom-trained detection models
Multi-object recognition
Intelligent task planning
🧭 Navigation
SLAM
Autonomous mapping
Localization
Dynamic obstacle avoidance
Advanced path planning
🦾 Manipulation
Improved inverse kinematics
Grasp planning
Increased payload capacity
Autonomous object placement
🌐 Advanced Robotics
ROS / ROS 2 integration
LiDAR-based navigation
Sensor fusion
Edge AI
Cloud monitoring
Multi-robot coordination
📅 Project Timeline
Week	Task	Status
Week 1	Problem Finalization	✅
Week 2	Literature Survey	TODO
Week 3	Requirement Analysis	TODO
Week 4	System Design	TODO
Week 5	Prototype Development	TODO
Week 6	Testing	TODO
Week 7	Documentation	TODO
Week 8	Paper Writing	TODO
📈 Weekly Progress
Week	Date	Work Completed	Next Week	Issues	Commit
01	TODO	TODO	TODO	TODO	TODO
02	TODO	TODO	TODO	TODO	TODO
03	TODO	TODO	TODO	TODO	TODO
04	TODO	TODO	TODO	TODO	TODO
05	TODO	TODO	TODO	TODO	TODO
06	TODO	TODO	TODO	TODO	TODO
07	TODO	TODO	TODO	TODO	TODO
08	TODO	TODO	TODO	TODO	TODO
👥 Team
#	Name	Roll No.	Branch
01	Krishnakumar Nadar	21	AURO
02	Piyush Patil	24	AURO
03	Sumeet Hinduja	8	AURO
04	Aryan Sahu	28	AURO
👩‍🏫 Project Guide

Dr. Nilima Warke

Department: Automation and Robotics
Institute: VESIT, Mumbai

📚 Research Paper
Item	Details
Paper Title	TODO
Conference / Journal	TODO
Paper Status	TODO
Submission Date	TODO
Paper Link	TODO
📖 References
[1] A. Author, B. Author, "Title of the Paper,"
    Journal/Conference Name, vol. X, no. Y, pp. xx-yy, Year.


[2] Datasheet / Website / Book reference.


[3] Additional research papers and technical documentation.
📝 Repository Guidelines
Update the README regularly.
Push code changes frequently.
Use meaningful commit messages.
Keep hardware and software organized.
Upload CAD, circuit diagrams and documentation.
Add project images to the images/ folder.
Do not upload unnecessary temporary files.
Maintain proper Git version control.
Example Commit Messages
feat: added object detection module
feat: implemented motor control
feat: integrated robotic arm
fix: corrected servo positioning
fix: improved obstacle detection
docs: updated system architecture
docs: added testing results
🏆 Project Status
<p align="center">






</p>
╔══════════════════════════════════════════════╗
║                                              ║
║       🤖 AUTONOMOUS ROBOTICS PLATFORM       ║
║                                              ║
║       NAVIGATION × VISION × ARM              ║
║                                              ║
╚══════════════════════════════════════════════╝
📜 Declaration

We declare that this project is carried out by our team as part of the BE Capstone Project. The project repository will be regularly updated with development progress, implementation details, testing results, and supporting documentation.

📄 License

This project is developed for academic and educational purposes.

<p align="center">
🤖 Built with curiosity. Engineered with robotics. Driven by automation.

© 2026 — BE Capstone Project | Automation & Robotics

</p> ```
                     └─────────────────┘
