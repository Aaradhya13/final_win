# Winova: AI-Powered Carbon Compliance Platform

## Table of Contents

- [Overview](#overview)
- [Problem Statement](#problem-statement)
- [Solution Highlights](#solution-highlights)
- [Core Features](#core-features)
- [Technology Stack](#technology-stack)
- [Impact & Benefits](#impact--benefits)
- [Business Model & Potential](#business-model--potential)
- [How to Run](#how-to-run)
- [Demo & Video Link](#demo--video-link)
---

## Overview

**Winova** is an AI-powered SaaS platform that enables enterprises to proactively track, predict, and comply with dynamic environmental regulations. By combining real-time emission tracking, predictive rule scanning, and financial risk simulation, Winova empowers organizations to reduce their carbon footprint, avoid penalties, and foster sustainable business practices.

---

## Problem Statement

Enterprises produce substantial carbon emissions across supply chains, yet regulatory compliance is complex due to fragmented, frequently changing environmental laws.

### Key Challenges:

- Lack of centralized, real-time visibility into carbon data  
- Rapidly evolving and region-specific environmental policies  
- High risk of costly fines, reputational damage, and operational disruptions  
- 60% of companies lack real-time regulatory monitoring; 40%+ fail ESG audits ([McKinsey](https://www.mckinsey.com/))  

---

## Solution Highlights

Winova offers:

- **Tracking:** Monitors carbon footprint by department, facility, and process  
- **Prediction:** Scans and forecasts new regulations using AI  
- **Explanation:** Translates complex laws into actionable steps using LLMs  
- **Simulation:** Conducts “what-if” analyses to compare compliance vs. penalty costs  
- **Alerting:** Sends real-time notifications on regulatory changes and compliance gaps  

---

## Core Features

- **Carbon Emission Dashboard:** Visualizes emissions by source, department, and timeline  
- **Granite LLM Action Plans:** Breaks down complex regulations into plain-language steps  
- **Cost-Benefit Simulator:** Models ROI for compliance decisions  
- **Dynamic Alerts & Reporting:** Provides real-time insights into environmental regulations  
- **Unified SaaS Interface:** Access all modules from a single streamlined dashboard  

---

## Technology Stack

- **Front-End:** Next.js, Tailwind CSS  
- **Back-End:** FastAPI (Python), MongoDB  
- **AI & Analytics:**  
  - Agentic AI for policy scanning and forecasting  
  - Data Prep Kit for cleaning and visualization  
  - IBM Granite LLM for legal/regulation interpretation  
- **Deployment:** Cloud-ready (IBM Cloud / AWS)  

---



## Impact & Benefits

- Prevents million-dollar fines and legal issues  
- Promotes informed emission reduction strategies  
- Supports ethical and sustainable corporate decision-making  

---

## Business Model & Potential

- **SaaS Subscription:** Enterprise access to dashboards, alerts, and simulators  
- **API Licensing:** Regulatory intelligence APIs for ESG consultants and legal tech platforms  

---

## How to Run

### 1. Clone the Repository
```bash
git clone https://github.com/Aaradhya13/final_win.git
cd final_win
```

### 2. Install Dependencies
- **Back-end:**
  ```bash
  cd backend
  pip install -r requirements.txt
  ```
- **Front-end:**
  ```bash
  cd frontend
  npm install
  ```

### 3. Configure Environment Variables
Configure environment variables (MongoDB, API keys) in `.env`.

### 4. Run Servers
- **Backend (FastAPI):**
  ```bash
  uvicorn main:app --reload
  ```
- **Frontend (Next.js):**
  ```bash
  npm run dev
  ```

### 5. Access
Browse to [http://localhost:3000](http://localhost:3000)

## Demo & Video Link
- [Demo Video](https://drive.google.com/file/d/12QpfdFqMfo_7K1rIx4dpu107x8BCjMHY/view?usp=sharing)






