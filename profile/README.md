# SomnGuard

<p align="center">
  <img src="../logo/logo.svg" alt="SomnGuard Logo" width="200"/>
</p>

<p align="center">
  <strong>Intelligent system for preventing accidents caused by fatigue and microsleep in drivers</strong>
</p>

---

## 🚗 Description

**SomnGuard** is a comprehensive system (software + hardware) designed for road safety. It monitors the driver's alertness in real time through visual analysis, generates preventive alerts, and records evidence during critical events while driving.

The system combines a device installed in the vehicle with an advanced analysis platform, with the goal of reducing accidents caused by fatigue, drowsiness, or microsleep at the wheel.

---

## 🎯 Key Features

- 👁️ **Continuous monitoring** of the driver via camera
- 🧠 **Fatigue and microsleep detection** through AI-powered facial analysis
- 🔔 **Automatic sound alerts** differentiated by risk level
- 📂 **Structured logging** of warning events and critical events
- ☁️ **Data transmission** to the external system for advanced analysis
- 📊 **Historical analysis and insight generation** on the external platform

---

## 👥 Team

Formative project — team of 4 members. Repository under active development.

---

## ⚙️ Tech Stack

| Component         | Technology         |
|-------------------|--------------------|
| Device            | Python             |
| Backend           | Java / Spring Boot |
| Web Frontend      | React              |
| Mobile App        | React Native       |
| Database          | PostgreSQL              |

---

## 🗂️ Project Structure

```
SomnGuard/
├── hardware/      # Python scripts — facial analysis, detection, alerts
├── backend/       # API and services in C# (.NET)
├── web/           # Web dashboard in React
├── mobile/        # Mobile application in React Native
├── docs/          # SRS, diagrams, technical documentation
```

---

## 🏗️ General Architecture

```
[ Camera ]   →   [ Device (Python) ]
                          │
                  Real-time analysis
                  Alert generation
                  Event logging
                          │
                          ▼
               [ Backend API (C# / .NET) ]
                          │
            ┌─────────────┴──────────────┐
            ▼                             ▼
   [ Web Dashboard (React) ]   [ Mobile App (React Native) ]
            └─────────────┬──────────────┘
                          ▼
                  [ PostgreSQL Database ]
```

---

## 👤 User Types

| User                | Description                                                   |
|---------------------|---------------------------------------------------------------|
| **Driver**          | Receives automatic sound alerts while driving                 |
| **External User**   | Consults records and analysis on the platform                 |
| **Administrator**   | Manages, configures, and maintains the system                 |

---

## 📌 Project Status

> 🔒 The repository is under development and will be made public soon.

---

## 📄 License

Educational project — All rights reserved to the **SomnGuard** team © 2026
