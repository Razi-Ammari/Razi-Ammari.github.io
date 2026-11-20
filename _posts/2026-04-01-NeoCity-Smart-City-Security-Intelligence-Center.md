---
layout: post
title: "Project: NeoCity – Smart City Platform with a Security & Intelligence Command Center"
date: 2026-04-01 12:00:00 +0100
categories: projects desktop
tags: [C++, Qt, Oracle Database, smart city, intrusion detection, ESPRIT]
image: /images/projects/NeoCity-Smart-City-Security-Intelligence-Center.png
---
## Overview
**NeoCity** is a **smart-city control center** desktop application built in **C++ / Qt** with an **Oracle Database** back-end. Its flagship module is the **Security & Intelligence Command Center**.

📁 Repository: [NeoCity_Project](https://github.com/Razi-Ammari/NeoCity_Project)

## Modules
- ♻️ Smart Recycling · 🚸 Pedestrian Safety · 💡 Smart Lighting
- 🏠 Smart Home Security · 🚉 Smart Station
- 📊 Analytics and 🧠 City Intelligence
- 🔐 **Security & Intelligence Command Center**

## Security & Intelligence Command Center
- **System health monitoring** of every city module (Operational / Warning / Critical, last signal, risk level).
- **Intrusion & threat detection**: fake speed-data injection, unrealistic waste-deposit patterns, sensor offline / communication loss, suspicious login attempts, abnormal energy consumption and data-integrity violations.
- Severity levels (**INFO / WARNING / CRITICAL**) with colour-coded dashboards.
- Predictive intelligence and decision-support KPIs with **Qt Charts**.

## Engineering
- Layered architecture: `db/` (connection manager + migrations), `models/`, `repositories/`, `services/`.
- Conceptual & relational data models (ERD) implemented in Oracle SQL.

## Tech Stack
`C++17` · `Qt 6 (Widgets, Charts, SQL)` · `Oracle Database` · `qmake`
