# GigShield AI
AI-Powered Income Protection Platform for Gig Delivery Workers

### Team: Straw Hats  
Guidewire DEVTrails 2026

![Hackathon](https://img.shields.io/badge/Hackathon-DEVTrails%202026-blue)
![Status](https://img.shields.io/badge/Project-Phase%201-green)

---

## Overview

The gig economy has become a critical part of India’s workforce, especially in urban delivery services such as food, groceries, and e-commerce. Delivery partners rely heavily on daily operations to sustain their income.

However, their earnings are highly vulnerable to external disruptions such as heavy rainfall, extreme temperatures, floods, pollution spikes, and sudden restrictions like curfews. During such events, delivery activity drops or stops entirely, directly impacting their income.

Unlike traditional employees, gig workers typically do not have access to structured financial protection mechanisms for such situations.

GigShield AI is designed to address this gap by offering a parametric insurance-based solution that ensures delivery workers receive compensation when external conditions prevent them from working.

---

## Problem Statement

Delivery partners in the gig economy face unpredictable income due to factors beyond their control. Environmental and social disruptions can significantly reduce their working hours, leading to immediate financial instability.

Existing insurance solutions are not tailored to this problem, as they primarily focus on health, accidents, or asset protection rather than **income loss caused by external events**.

The challenge is to design a system that:
- Detects real-world disruptions accurately  
- Automates claim processing  
- Prevents fraudulent claims  
- Remains simple and accessible for gig workers  

---

## Target Persona (Detailed)

Our primary users are gig delivery workers operating in urban environments who depend on daily task completion for income.

### Example Persona

**Name:** Arjun  
**Age:** 28  
**Location:** Chennai  
**Occupation:** Food Delivery Partner  

Arjun works 8–10 hours daily and earns based on completed deliveries. His income is highly sensitive to external disruptions such as heavy rain, extreme heat, or traffic restrictions.

Even a few hours of disruption can reduce his daily earnings significantly. Currently, there is no system that compensates for such income loss.

Arjun needs a solution that:
- Requires minimal effort  
- Works automatically  
- Provides quick financial support  
- Does not involve complex claim processes  

GigShield AI is designed specifically to meet these needs.

---

## Proposed Solution

GigShield AI is an **AI-enabled parametric insurance platform** that eliminates the need for manual claims.

Instead of relying on user-reported incidents, the system continuously monitors trusted external data sources such as weather APIs and city alerts. When disruption conditions cross predefined thresholds, compensation is triggered automatically.

Key aspects of the solution include:

- Weekly subscription-based insurance model  
- AI-driven risk assessment and pricing  
- Real-time disruption detection  
- Automated and transparent claim processing  
- Minimal user effort and faster payouts  

---

## Application Workflow

1. User registers on the platform  
2. Selects a weekly insurance plan  
3. System calculates premium based on risk factors  
4. External data sources are monitored continuously  
5. Disruption event is detected  
6. Claim is triggered automatically  
7. Payout is processed and credited to the user  

This workflow ensures a seamless experience with minimal manual intervention.

---

## Weekly Premium Model

The pricing model is designed around a **weekly cycle**, aligning with gig workers' earning patterns.

| Risk Level | Weekly Premium |
|------------|----------------|
| Low Risk   | ₹20            |
| Medium Risk| ₹30            |
| High Risk  | ₹40            |

Premiums are calculated based on:
- Historical weather data  
- Location-based risk patterns  
- Frequency of disruptions  

---

## Parametric Triggers

The system uses predefined conditions to trigger payouts:

- Rainfall above threshold  
- Extreme temperature conditions  
- Flood alerts  
- Government-imposed restrictions  
- High pollution levels  

These triggers are validated using reliable external APIs.

---

## AI / Machine Learning Approach

GigShield AI uses machine learning to improve decision-making, pricing, and fraud detection.

### Risk Prediction Model
The system analyzes historical data such as rainfall, temperature, pollution levels, and past disruptions to estimate the likelihood of future events in a specific region.

This generates a **risk score**, which helps determine how likely a disruption is to occur.

---

### Dynamic Premium Calculation
Based on the predicted risk score, the system adjusts weekly premiums.

Higher-risk areas → higher premium  
Lower-risk areas → affordable pricing  

This ensures fairness and sustainability.

---

### Fraud Detection Model
The platform combines rule-based logic with pattern analysis techniques:

- Detects unusual claim frequency  
- Identifies outliers in user behavior  
- Uses clustering to find suspicious user groups  

This helps detect fraud scenarios such as GPS spoofing and coordinated fake claims.

---

## System Design & Technical Approach

GigShield AI follows a modular architecture:

### Frontend
A mobile-first interface built using React.js that allows users to:
- Register  
- Select insurance plans  
- Track claims  

---

### Backend
Node.js with Express handles:
- API processing  
- Premium calculation  
- Claim triggering logic  

---

### Data Layer
PostgreSQL / Firebase stores:
- User profiles  
- Policy details  
- Claim history  

---

### External Data Integration
The system integrates real-time data from:
- Weather APIs  
- Traffic and environmental data  
- Government alerts  

---

### Decision Engine
A central logic engine:
- Monitors incoming data  
- Validates disruption conditions  
- Automatically triggers payouts  

This ensures a fully automated and reliable workflow.

---

## Adversarial Defense & Anti-Spoofing Strategy 🚨

To address large-scale fraud scenarios such as GPS spoofing and coordinated fake claims, the platform incorporates a multi-layered defense strategy.

### Multi-Source Verification
Location data is validated using GPS, IP-based location, and movement consistency.

### Behavioral Analysis
Unusual patterns such as sudden claim spikes and repeated claims are flagged.

### Event Correlation
Claims are validated against real-world events such as weather and alerts.

### Device Intelligence
Multiple accounts from the same device are detected and restricted.

### Trust Scoring
Each user is assigned a trust score based on past behavior.

### Fraud Ring Detection
Clusters of suspicious users are identified using pattern similarity.

### Fairness Mechanism
Suspicious claims are flagged instead of immediately rejected, ensuring genuine users are not penalized.

---

### Market Crash Scenario Handling

In large-scale fraud scenarios (e.g., hundreds of fake users attempting claims simultaneously):

- Claims are cross-verified using multiple independent data sources  
- Suspicious clusters are identified using behavior similarity  
- High-risk users are flagged before payout  
- Only claims supported by real-world disruption data are processed  

This ensures the system remains secure, even during coordinated fraud attacks.

---

## Technology Stack

**Frontend:** React.js / Next.js  
**Backend:** Node.js + Express.js  
**Database:** PostgreSQL / Firebase  
**AI/ML:** Python (Scikit-learn)  

**External Integrations:**
- Weather APIs  
- Traffic and disruption data  
- Payment gateway (sandbox mode)  

---

## Platform Choice

The system is designed as a **mobile-first web application**, considering that delivery workers primarily rely on smartphones during their work.

---

## Future Enhancements

- Predictive alerts for disruptions  
- Risk heatmaps for different regions  
- Integration with delivery platforms  
- Advanced dashboards for analytics  
- Personalized insurance plans  

---

## Repository Structure


gigshield-ai
├── frontend
├── backend
├── ai-model
└── docs


---

## Phase 1 Prototype

The Phase 1 prototype focuses on demonstrating:

- User onboarding  
- Insurance plan selection  
- Premium calculation logic  
- Disruption simulation  
- Automated claim triggering  

---

## Team

**Straw Hats Hackathon Team**  
Project: GigShield AI
