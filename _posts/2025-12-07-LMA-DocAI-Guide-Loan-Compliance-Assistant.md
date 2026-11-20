---
layout: post
title: "Project: LMA DocAI Guide – AI-Powered Loan Documentation & Compliance"
date: 2025-12-07 12:00:00 +0100
categories: projects ai
tags: [AI, FinTech, compliance, React, Node.js, Express, MongoDB, JWT]
---
## Overview
**LMA DocAI Guide** is an AI-powered loan documentation and compliance management system that helps loan officers and financial professionals manage loan documents and verify **covenant compliance**.

📁 Back-end repository: [LMA_BACK](https://github.com/Razi-Ammari/LMA_BACK)

## Key Features
- **Company-centric architecture**: each user is permanently tied to one company; compliance evaluation, document analysis and AI assistance are automatically scoped to it.
- **AI assistant** for loan documentation questions, with conversation history.
- **Compliance checking** and document management workflows.
- Modern animated React landing page and dashboard.

## Back-end
- **Express** REST API with **MongoDB Atlas**.
- **JWT** authentication (signup / login / logout) with **bcrypt** password hashing and cookie sessions.
- Protected assistant endpoints: `POST /api/assistant/message`, `GET /api/assistant/history`.

## Tech Stack
`React + TypeScript` · `Node.js / Express` · `MongoDB Atlas` · `JWT` · `bcrypt`
