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
                     └─────────────────┘
