# 🤖 Autonomous Docking and Navigation (TurtleBot3 + Gazebo)

## 📌 Overview
This project implements a **persistent autonomous navigation pipeline** for a mobile robot using **ROS**, **Gazebo**, and **TurtleBot3**.

The robot follows a predefined set of waypoints while simulating a **virtual battery system**. As the robot moves, its battery depletes. When the battery drops below a threshold, the robot **autonomously diverts** from its current mission, navigates to a **fixed docking station**, aligns itself for charging, and then resumes its task after recharging.

This project demonstrates:
- Intelligent decision-making
- Autonomous navigation
- Battery-aware planning
- Reliable docking behavior

---

## 🎯 Objectives
- Navigate through predefined waypoints continuously
- Simulate battery consumption during motion
- Detect low battery and trigger docking behavior
- Navigate and align accurately with docking station
- Resume mission after charging

---

## 🛠️ Tech Stack
- ROS (Robot Operating System)
- Gazebo Simulator
- TurtleBot3
- Python (ROS nodes)
- Navigation Stack (`move_base`, `amcl`)

---


---

## ⚙️ Features

### 🚗 Persistent Navigation
- Follows predefined waypoints
- Continuous operation in loop

### 🔋 Battery Simulation
- Battery level decreases during motion
- Configurable discharge rate
- Recharge mechanism at docking station

### ⚡ Autonomous Docking
- Detects low battery condition
- Interrupts current navigation
- Navigates to docking station
- Aligns precisely for charging

### 🔄 Mission Resume
- Resumes navigation after charging
- Continues from last waypoint

---

## ⭐ Bonus Features

### 🔄 Variable Power Consumption
- Battery drain varies with:
  - Speed
  - Rotation
  - Path complexity

### 🧮 Predictive Docking
- Robot decides when to dock based on:
  - Remaining path distance
  - Current battery level
- Prevents failure mid-navigation

### 📊 Monitoring
- Battery level visualization (RViz / logs)

---

## 🗺️ Simulation Environment
- Fixed Gazebo world
- Includes:
  - Predefined waypoints
  - Static docking station

---
