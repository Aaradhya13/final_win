# Winova: AI-Powered Carbon Compliance Platform

## Table of Contents

- [Overview](#overview)
- [Problem Statement](#problem-statement)
- [Solution Highlights](#solution-highlights)
- [Core Features](#core-features)
- [Technology Stack](#technology-stack)
- [Architecture](#architecture)
- [Impact & Benefits](#impact--benefits)
- [Business Model & Potential](#business-model--potential)
- [Team](#team)
- [How to Run](#how-to-run)
- [Demo & Video Link](#demo--video-link)
- [License](#license)
- [Contact](#contact)

## Overview

**Winova** is an AI-powered SaaS platform that helps enterprises proactively track, predict, and comply with dynamic environmental regulations. By combining real-time emission tracking, predictive rule scanning, and financial risk simulation, Winova empowers organizations to reduce their carbon footprint, avoid penalties, and support sustainable business practices.

## Problem Statement

Enterprises generate massive carbon emissions across supply chains, yet regulatory compliance is difficult due to fragmented and frequently changing environmental laws.

**Challenges:**
- No centralized, real-time visibility into carbon data
- Fast-changing, region-specific environmental policies
- High risk of costly fines, reputational damage, and disruption
- 60% of companies lack real-time regulatory monitoring; 40%+ fail ESG audits ([McKinsey](https://www.mckinsey.com/))

## Solution Highlights

Winova provides:
- **Tracking:** Carbon footprint by department, facility, and process
- **Prediction:** Foresight into upcoming environmental laws via government regulatory scanning
- **Explanation:** Converts regulations into plain-language steps using LLMs
- **Simulation:** "What-if" analysis for compliance vs. non-compliance costs
- **Alerting:** Real-time notifications and compliance tracking

## Core Features

- **Carbon Emission Dashboard:** Visualizes detailed emissions by source, department, and timeline
- **Granite LLM Action Plans:** Explains complex policy in actionable steps
- **Cost-Benefit Simulator:** Models the cost/ROI of compliance vs. penalties
- **Dynamic Alerts & Reporting:** Real-time updates on critical regulations
- **Unified Interface:** All features accessible on a single SaaS dashboard

## Technology Stack

- **Front-End:** Next.js, Tailwind CSS
- **Back-End:** FastAPI (Python), MongoDB
- **AI & Analytics:**
  - Agentic AI (policy/regulatory scan & forecast)
  - Data Prep Kit (data cleaning, visualization)
  - IBM Granite LLM (legal/regulation interpretation)
- **Deployment:** Cloud-ready (IBM/AWS)

## Impact & Benefits

- Saves companies from million-dollar fines
- Reduces emissions by informed tracking and simulation
- Empowers ethical, sustainable business decisions

## Business Model & Potential

- **SaaS Subscription:** Enterprises pay for analytics, alerts, and compliance tools
- **API Licensing:** Regulatory intelligence API for ESG consultants and legal platforms

## How to Run

1. **Clone the repository**
    ```
  git clone https://github.com/Aaradhya13/final_win.git
  
  ```
   2. **Install dependencies**
- Back-end:
  ```
  cd backend
  pip install -r requirements.txt
  ```
- Front-end:
  ```
  cd frontend
  npm install
  ```
3. **Configure environment variables** (MongoDB, API keys) in `.env`.
4. **Run servers**
- Backend (FastAPI):
  ```
  uvicorn main:app --reload
  ```
- Frontend (Next.js):
  ```
  npm run dev
  ```
5. **Access:** Browse to [http://localhost:3000](http://localhost:3000)

## Demo & Video Link

- [Demo Video](#) <https://drive.google.com/file/d/12QpfdFqMfo_7K1rIx4dpu107x8BCjMHY/view?usp=sharing>






