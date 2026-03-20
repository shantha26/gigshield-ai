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

---

## Weekly Premium Model

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

- Rainfall above threshold  
- Extreme temperature conditions  
- Flood alerts  
- Government-imposed restrictions  
- High pollution levels  

All triggers are validated using trusted external data sources.

---

## AI / Machine Learning Approach

GigShield AI uses data-driven models to support pricing, prediction, and fraud detection.

### Risk Prediction Model
Inputs:
- Rainfall intensity  
- Temperature patterns  
- Pollution levels  
- Historical disruption frequency  

Output:
- Region-specific **risk score**

This score helps estimate disruption probability and drives premium pricing.

---

### Dynamic Premium Calculation
Premiums are adjusted based on predicted risk:

Higher risk → higher premium  
Lower risk → affordable pricing  

This ensures sustainability and fairness.

---

### Fraud Detection Model
The system combines rule-based logic with behavioral analysis:

- Detects abnormal claim frequency  
- Identifies location inconsistencies  
- Flags unusual user activity patterns  
- Uses clustering to detect coordinated fraud groups  

---

## System Design & Technical Approach

GigShield AI follows a modular and scalable architecture:

### Frontend
Mobile-first UI (React.js) for onboarding, plan selection, and claim tracking.

### Backend
Node.js + Express handles:
- Premium calculation  
- Claim triggering  
- API communication  

### Data Layer
Stores:
- User profiles  
- Policy data  
- Claim history  

### External Data Layer
- Weather APIs  
- Government alerts  
- Environmental data  

### Decision Engine
- Continuously monitors data  
- Validates disruption thresholds  
- Automatically triggers payouts  

---

## Adversarial Defense & Anti-Spoofing Strategy 🚨

To handle large-scale fraud such as GPS spoofing and coordinated attacks, the system uses multiple validation layers.

### Multi-Source Verification
Combines GPS, IP location, and movement consistency to validate user presence.

### Behavioral Analysis
Detects:
- Sudden spikes in claims  
- Repeated patterns  
- Unusual timing  

### Event Correlation
Claims are validated against:
- Weather data  
- Traffic conditions  
- Government alerts  

### Device Intelligence
Detects multiple accounts from the same device or network.

### Trust Scoring
Each user has a dynamic trust score based on past behavior.

### Fraud Ring Detection
Clusters of users with similar patterns are identified and flagged.

### Fairness Mechanism
- Suspicious claims are flagged, not immediately rejected  
- Edge cases are reviewed  
- Genuine users are protected  

---

### Market Crash Scenario Handling

In extreme scenarios involving coordinated fraud (e.g., hundreds of fake users):

- Claims must match verified real-world disruption data  
- Clustered suspicious users are flagged before payout  
- High-risk accounts undergo stricter validation  
- Only verified and consistent claims are processed  

This ensures system stability even under large-scale attacks.

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

Mobile-first web application optimized for delivery workers.

---

## Future Enhancements

- Predictive disruption alerts  
- Risk heatmaps  
- Platform integrations  
- Advanced dashboards  
- Personalized plans  

---

## Repository Structure


gigshield-ai
├── frontend
├── backend
├── ai-model
└── docs


---

## Phase 1 Prototype

- User onboarding  
- Plan selection  
- Premium logic  
- Disruption simulation  
- Auto claim triggering  

---

## Team

**Straw Hats Hackathon Team**  
Project: GigShield AI
