# 🔐 AI-Powered Anomaly-Based Intrusion Detection System (IDS)

> 🚀 Finalist - Aignite Cybersecurity Hackathon 2025 (Top 50 out of 4000+)  
> Built using Raspberry Pi 4, this project is a **plug-and-play, lightweight, and real-time IDS** designed for detecting and mitigating cyber-attacks such as DDoS, brute-force, and port scans. It features automated IP blocking, real-time system monitoring, and a live Flask-based dashboard.

---

## 📌 Table of Contents

- [📖 Project Summary](#-project-summary)
- [🎯 Target Audience](#-target-audience)
- [🛠️ Tech Stack](#️-tech-stack)
- [📐 System Architecture](#-system-architecture)
- [💡 Key Features](#-key-features)
- [🧠 Machine Learning Details](#-machine-learning-details)
- [📈 Live Dashboard](#-live-dashboard)
- [⚙️ Installation & Usage](#️-installation--usage)
- [🧪 Testing Tools](#-testing-tools)
- [📦 Product Launch Strategy](#-product-launch-strategy)
- [💥 Future Impact](#-future-impact)
- [❌ Known Limitations](#-known-limitations)
- [🏆 Why This Project Stands Out](#-why-this-project-stands-out)
- [👥 Team Members](#-team-members)
- [📞 Contact](#-contact)

---

## 📖 Project Summary

This AI-Powered IDS is a **cost-effective, real-time network defense tool** intended for homes, schools, and small organizations. It monitors system usage, processes incoming network data, detects threats using trained ML models, auto-blocks malicious IPs via `iptables`, and displays everything on a clean Flask dashboard.

The system is **plugged in between the router and switch** for seamless traffic analysis, designed to work even in offline environments (ideal for remote and rural deployments).

---

## 🎯 Target Audience

- 👨‍🏫 Educational Institutes and Labs  
- 🏠 Smart Homes and IoT Networks  
- 🏢 Small & Medium Enterprises (SMEs)  
- 🛡️ Defense and Government Organizations  
- 🧠 Research Labs and Cybersecurity Students

---

## 🛠️ Tech Stack

| Component       | Tool/Library                         |
|----------------|--------------------------------------|
| Device          | Raspberry Pi 4 (4 GB RAM)           |
| OS              | Raspberry Pi OS (Debian-based)      |
| Programming     | Python 3.11                         |
| ML Model        | XGBoost / Random Forest             |
| Data Source     | MQTT-Based Intrusion Dataset        |
| Dashboard       | Flask + HTML + Chart.js + AJAX      |
| Monitoring      | psutil, netstat                     |
| Security        | iptables, RSA                       |
| Alerts          | Twilio (SMS), smtplib (Email)       |
| Testing Tools   | hping3, hydra, netcat, Wireshark    |

---

## 📐 System Architecture
