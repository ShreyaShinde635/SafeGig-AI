# SafeGig AI – Parametric Insurance for Gig Workers

## Problem

Gig delivery workers working for platforms like Swiggy and Zomato lose income due to external disruptions such as heavy rain, extreme heat, pollution, and local curfews. These workers currently have no financial protection for income loss caused by such events.

For example, a delivery worker earning ₹700 per day may lose an entire day's income due to heavy rainfall or extreme weather conditions.

## Solution

SafeGig AI is an AI-powered parametric insurance platform designed to protect gig workers from income loss caused by external disruptions. The system continuously monitors environmental conditions and automatically triggers payouts when disruptions occur.

Workers do not need to manually submit claims. The platform detects disruptions automatically and initiates instant payouts.

## Target Persona

Food delivery partners working on platforms such as Swiggy and Zomato.

### Example Persona

Rahul – A Swiggy delivery partner in Mumbai earning approximately ₹700 per day. During heavy rainfall, deliveries drop drastically causing income loss.

## Weekly Insurance Plans

Gig workers operate on a weekly earning cycle, so the insurance model is structured on a weekly pricing basis.

Basic Plan – ₹10 per week → Protects ₹300 per day
Pro Plan – ₹20 per week → Protects ₹500 per day
Premium Plan – ₹30 per week → Protects ₹700 per day

This pricing model ensures affordability while providing income protection.

## Parametric Disruption Triggers

SafeGig AI uses parametric triggers to automatically detect disruptions.

• Rainfall greater than 80mm
• Temperature greater than 45°C
• Air Quality Index (AQI) greater than 350
• Local curfew or sudden delivery zone closure

When any of these thresholds are crossed, the system automatically activates a claim.

## AI Integration

Artificial Intelligence plays a critical role in the SafeGig AI platform.

### 1. Risk Assessment

Machine learning models analyze factors such as weather history, pollution levels, and geographic risk zones to dynamically calculate weekly insurance premiums.

Workers operating in safer zones may receive lower premiums, while high-risk areas may have slightly higher premiums.

### 2. Fraud Detection

AI helps detect fraudulent claims by identifying anomalies such as:

• GPS spoofing
• Duplicate claims
• Mismatched weather data
• Suspicious location patterns

This ensures the system remains fair and sustainable.

## System Workflow

Worker registers → Selects insurance plan → AI calculates risk → Policy activated → System monitors disruption triggers → Event detected → Claim automatically triggered → Worker receives instant payout.

## Technology Stack

Frontend: React
Backend: Node.js
Database: MongoDB
AI/ML: Python
APIs: Weather API, AQI API, Razorpay Test Payment Gateway

## System Architecture

Worker Mobile App
↓
React Frontend
↓
Backend API (Node.js)
↓
AI Risk Engine
↓
Database (MongoDB)
↓
External APIs
• Weather API
• AQI API
• Payment Gateway

## Smart Earnings Protection (Unique Feature)

Most insurance systems only rely on weather-based triggers. SafeGig AI goes a step further by introducing **AI-based earnings protection**.

The system monitors delivery activity and identifies sudden drops in order volume that may indicate disruptions such as platform outages, unexpected market closures, or reduced demand due to external events.

### Example Scenario

Normal Orders Per Day: 25
Orders Today: 5

If the system detects a sudden drop in orders compared to the worker’s historical average, it can automatically trigger compensation for lost earning hours.

### How It Works

1. The platform collects historical delivery activity data.
2. AI models calculate the worker’s normal earning pattern.
3. If a significant drop in delivery orders is detected, the system flags a potential disruption.
4. The claim process is automatically triggered and the worker receives compensation.

This feature ensures gig workers are protected not only from environmental disruptions but also from unexpected platform or demand-related issues.

## Future Scope

The SafeGig AI platform can scale across India to protect millions of gig workers and integrate with multiple delivery platforms such as Swiggy, Zomato, Amazon, and Zepto.

In the future, the system can incorporate advanced AI analytics, predictive risk modeling, and real-time platform integrations to create a robust safety net for the gig economy.


