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

## Target Persona

Our primary users are gig delivery workers operating in urban environments.

These individuals depend on completing multiple deliveries per day, and their income is directly tied to their working hours. Any disruption, even for a few hours, can affect their weekly earnings.

GigShield AI aims to provide them with a safety net that activates automatically during such disruptions.

---

## Example Persona

**Name:** Arjun  
**Age:** 28  
**Location:** Chennai  
**Occupation:** Food Delivery Partner  

Arjun typically works long hours and earns based on completed deliveries. On days with heavy rainfall or extreme heat, his delivery count drops significantly or stops entirely.

GigShield AI ensures that Arjun does not suffer a complete income loss during such events by providing automated compensation.

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

## AI / Machine Learning Integration

AI plays a key role in improving decision-making within the platform.

**Risk Prediction**  
Forecasts disruption likelihood using historical data  

**Dynamic Pricing**  
Adjusts premiums based on regional risk  

**Fraud Detection**  
Identifies abnormal claim patterns and suspicious activity  

---

## Adversarial Defense & Anti-Spoofing Strategy 🚨

To address large-scale fraud scenarios such as GPS spoofing and coordinated fake claims, the platform incorporates a multi-layered defense strategy.

### Multi-Source Verification
Location data is validated using multiple signals such as GPS, IP-based location, and movement consistency.

### Behavioral Analysis
Unusual patterns such as sudden claim spikes, repetitive claims, and irregular activity timing are flagged.

### Event Correlation
All claims are cross-verified with real-world data sources (weather, traffic, alerts). Claims without supporting events are rejected.

### Device Intelligence
Multiple accounts originating from the same device or network are detected and flagged.

### Trust Scoring
Each user is assigned a dynamic trust score based on past activity and claim behavior.

### Fraud Ring Detection
Clusters of suspicious users with similar behavior patterns are identified using anomaly detection techniques.

### Fairness Mechanism
Instead of immediate rejection:
- Suspicious cases are flagged  
- Edge cases are reviewed  
- Genuine users are protected from false negatives  

This ensures a balance between fraud prevention and user trust.

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
