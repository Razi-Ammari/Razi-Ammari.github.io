---
layout: post
title: "1st Place at GAICA – AI Camera Challenge Hackathon with Vision X"
date: 2025-12-20 12:00:00 +0100
categories: hackathon gaica
tags: [hackathon, winner, AI, computer vision, YOLOv8, DeepSORT, OpenCV, Telegram]
image: /images/competitions/Vision-X-Winner-GAICA-AI-Camera-Challenge.png
---
## Overview
🏆 **We did it!** Our team **Vision X** won the **AI Camera Challenge Hackathon (GAICA)**, organized by **Novation City** in collaboration with **Anavid**.

In under **24 hours** we designed and delivered a production-ready AI system that turns ordinary camera footage into **real-time operational intelligence** for counters and patisseries.

📁 Repository: [Vision_X](https://github.com/Razi-Ammari/Vision_X)

## My Role – Team Lead
I led Vision X from setting the strategic vision to orchestrating a high-pressure, high-speed development process: making data-driven decisions, keeping collaboration seamless and letting every teammate play to their strengths.

**Team:** Razi Ammari (lead), Ikram Menyaoui, Tasnim Mtir, Aya Mekni, Nour Saibi.

## The Problem
Patisseries face long waiting times, checkout bottlenecks at peak hours, no visibility on rush periods and customers abandoning the queue — and most decisions rely on intuition, not data.

## What We Built
- **Real-time person detection** with **YOLOv8**.
- **Identity-consistent tracking** with **DeepSORT** (stable, non-switching customer IDs).
- A **zone-based state machine** (Enter → Wait → Pay → Exit) measuring waiting time, payment duration and customer flow.
- A **live KPI engine**: waiting time, service duration, queue length and congestion peaks.
- **Automated Telegram alerts** (`patisserie_waiting_bot`) for long waits, slow service and queue saturation — with snapshots and live queue graphs.
- **Dynamic heatmaps** of customer movement.
- **CSV reports**, annotated analytics video and a live HUD dashboard.
- A web front-end presenting the product and demo.

## Tech Stack
`Python` · `YOLOv8 (Ultralytics)` · `DeepSORT` · `OpenCV` · `PyTorch` · `Pandas` · `NumPy` · `Telegram Bot API` · `Google Colab`

## Takeaways
This hackathon taught me more in 24 hours than many experiences teach in weeks: **leadership under pressure**, problem-solving and the power of a committed team working toward a shared vision.
