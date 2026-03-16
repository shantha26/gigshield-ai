#GigShield AI
AI-Powered Income Protection Platform for Gig Delivery Workers

### Team: Straw Hats

![Hackathon](https://img.shields.io/badge/Hackathon-DEVTrails%202026-blue)
![Status](https://img.shields.io/badge/Project-Phase%201-green)
![License](https://img.shields.io/badge/License-MIT-yellow)

---

## Overview

The gig economy has become an important part of India’s workforce. Delivery partners working with platforms like **Swiggy, Zomato, Amazon, and Zepto** depend on daily deliveries to earn their income.

However, their earnings are highly affected by external disruptions such as **heavy rainfall, extreme heat, floods, severe pollution, or sudden curfews**. When these events occur, deliveries may stop or reduce significantly, leading to a direct loss of income for gig workers.

Unlike traditional employees, gig workers usually do not have financial protection that compensates them during such disruptions.

To address this challenge, we propose **GigShield AI**, an AI-powered parametric insurance platform designed to protect delivery workers from income loss caused by environmental or social disruptions.

The platform provides a **simple weekly insurance model**, automated disruption detection, and quick compensation payouts.

---

## Problem Statement

Platform-based delivery workers are an essential part of the digital economy, but they face income instability due to external disruptions beyond their control.

Events such as **extreme weather conditions, floods, pollution spikes, or temporary city restrictions** can prevent workers from completing deliveries. When these disruptions occur, workers lose valuable working hours and earnings.

Currently, there are limited solutions that provide financial protection specifically for **income loss caused by external disruptions**.

Our project aims to solve this problem by creating a system that detects disruption events automatically and compensates workers through a **parametric insurance model**.

---

## Target Persona

Our primary user is a **delivery partner working in the gig economy**.

These workers rely on completing multiple deliveries per day to earn their income. Any disruption that prevents them from working directly affects their earnings.

GigShield AI provides them with a safety net during such situations.

---

## Example Persona

**Name:** Arjun
**Age:** 28  
**Location:** Chennai  
**Occupation:** Food Delivery Partner (Swiggy)

Ravi earns money based on the number of deliveries he completes daily. On normal days, he can earn consistently by completing several orders.

However, during heavy rainfall or extreme weather conditions, deliveries may slow down or stop completely. This results in a loss of income for Ravi.

GigShield AI helps protect Ravi’s earnings by providing compensation when external disruptions prevent him from working.

---

## Proposed Solution

GigShield AI is designed as an **AI-enabled parametric insurance platform**.

Instead of requiring workers to manually submit claims, the platform continuously monitors external data sources such as **weather reports, environmental alerts, and city disruptions**.

When predefined disruption conditions are detected, the system automatically triggers compensation for insured workers.

Key goals of the solution include:

- Affordable **weekly insurance coverage**
- AI-based **risk prediction**
- Automated **claim triggering**
- Quick and transparent **payout processing**
- Simple user experience for gig workers

---

## Application Workflow

The platform follows a simple and automated workflow:

1. A delivery worker registers on the platform.
2. The worker selects a weekly insurance plan.
3. The system calculates the weekly premium based on risk factors.
4. External data sources (weather APIs, city alerts) are continuously monitored.
5. If disruption thresholds are exceeded, a claim is automatically triggered.
6. The system verifies the event.
7. The payout is processed and sent to the worker.

This approach removes the need for complex manual claim processes.

---

## Weekly Premium Model

The platform follows a **weekly pricing structure**, which matches the earning pattern of gig workers.

Example premium model:

| Risk Level | Weekly Premium |
|-------------|---------------|
| Low Risk Area | ₹20 |
| Medium Risk Area | ₹30 |
| High Risk Area | ₹40 |

Premiums are determined using historical data such as weather patterns and disruption frequency.

---

## Parametric Triggers

Claims are triggered automatically when predefined disruption conditions occur.

Example triggers include:

- Rainfall exceeding a defined threshold
- Extreme temperature levels
- Flood alerts
- Government-issued curfews
- Severe air pollution levels

Once these conditions are detected through integrated data sources, the system automatically initiates the payout process.

---

## AI / Machine Learning Integration

Artificial Intelligence is used to enhance the platform’s efficiency.

### Risk Prediction
Machine learning models analyze historical weather and disruption data to estimate risk levels.

### Dynamic Premium Calculation
Premiums are adjusted based on regional risk factors.

### Fraud Detection
AI models detect unusual patterns such as suspicious claim activity or location inconsistencies.

These features ensure fairness and reliability within the system.

---

## Technology Stack

**Frontend**

React.js / Next.js  
Responsive mobile-friendly interface

**Backend**

Node.js + Express.js  
Handles APIs and application logic

**Database**

PostgreSQL / Firebase  
Stores user profiles, policies, and claims

**AI / ML**

Python with Scikit-learn  
Used for risk analysis and fraud detection

**External APIs**

- Weather API (OpenWeatherMap)
- Traffic / disruption APIs
- Payment gateway sandbox (Razorpay / Stripe)

---

## Platform Choice

The solution is designed as a **mobile-first web application**.

Delivery partners primarily use smartphones while working, so the platform must be lightweight, accessible, and easy to navigate on mobile devices.

---

## Future Enhancements

Possible future improvements include:

- Predictive disruption alerts
- Risk heatmaps for cities
- Integration with delivery platforms
- Advanced dashboards for insurers
- Personalized insurance plans based on worker activity

---

## Repository Structure


gigshield-ai
│
├── frontend
├── backend
├── ai-model
└── docs


This structure keeps the project modular and easier to scale in later phases.

---

## Phase 1 Prototype

For **Phase 1**, the project focuses on demonstrating the core concept.

The prototype will include:

- Basic user onboarding flow
- Weekly insurance plan concept
- Premium calculation logic
- Disruption trigger simulation
- Automated claim logic

Future phases will expand this into a fully functional platform.

---

## Team

**Straw Hats Hackathon Team**  
Project: **GigShield AI**

---
