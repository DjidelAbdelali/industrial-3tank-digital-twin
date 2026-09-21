# Industrial 3-Tank Digital Twin & Supervision

<div align="center">

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Interactive-brightgreen?style=for-the-badge&logo=googlechrome&logoColor=white)](https://djidelabdelali.github.io/industrial-3tank-digital-twin/)
[![Portfolio](https://img.shields.io/badge/Portfolio-DJIDEL%20Abdelali%20Rayan-blue?style=for-the-badge&logo=react&logoColor=white)](https://djidelabdelali.github.io/portfolio/)
[![GitHub Repo](https://img.shields.io/badge/GitHub-Repository-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/DjidelAbdelali/industrial-3tank-digital-twin)

</div>

---

## 📌 Project Overview

Web-based industrial supervision application for a three-tank system. Features real-time level and flow rate visualization, interactive valve control, and pedagogical digital twin interface for industrial automation training.

This project is an engineering module built by **DJIDEL Abdelali Rayan** (Systems & Automation Engineer, USTHB).

---

## 🏗️ System Architecture & Data Flow

```mermaid
graph LR
    Inflow[Pump Inflow Q1] --> Tank1[Tank 1 Level H1]
    Tank1 --> Valve1[Interconnecting Valve V1]
    Valve1 --> Tank2[Tank 2 Level H2]
    Tank2 --> Valve2[Interconnecting Valve V2]
    Valve2 --> Tank3[Tank 3 Level H3]
    Tank3 --> Outflow[Discharge Valve V3]
    Tank1 & Tank2 & Tank3 --> PLC[PID Level Controller]
    PLC --> Inflow
```

---

## 🛠️ Key Technologies & Frameworks

- **React**
- **Real-time Simulation**
- **Industrial Supervision**
- **SVG Animation**
- **PID Regulation**

---

## 🚀 Live Interactive Web Demo

No installation required! Test and interact with the full web simulation live in your browser:
🔗 **[Launch Interactive Web Demo](https://djidelabdelali.github.io/industrial-3tank-digital-twin/)**

---

## 🔗 Connected Portfolio Ecosystem

- 🌐 **Main Portfolio**: [djidelabdelali.github.io/portfolio](https://djidelabdelali.github.io/portfolio/)
- 💻 **GitHub Profile**: [github.com/DjidelAbdelali](https://github.com/DjidelAbdelali)
- 💼 **LinkedIn Profile**: [DJIDEL Abdelali Rayan](https://linkedin.com/in/djidel-abdelali-rayan-814b25207)

---

<div align="center">
  <sub>Developed by DJIDEL Abdelali Rayan — Systems & Automation Engineering</sub>
</div>
