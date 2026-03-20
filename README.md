<img width="1536" height="1024" alt="ChatGPT Image Mar 20, 2026, 03_53_03 PM" src="https://github.com/user-attachments/assets/bd29f743-8f85-4faf-9c00-65a942338c9d" />

# AI-Powered Income Protection & Smart Savings for Gig Workers | DEVTrails 2026

GigKavach is an AI-powered parametric insurance and smart savings platform designed to protect gig workers from unpredictable income loss caused by external disruptions.

Meet Rahul, a 25-year-old delivery partner working with Zepto in BTM Layout, Bengaluru. He works 10–11 hours a day, completing 15–20 deliveries and earning around ₹900–₹1,100 on a good day. Like millions of gig workers across India, Rahul has no fixed salary, no paid leave, and no job security. His income is entirely dependent on daily work.

However, when unexpected events such as heavy rain, pollution, or local disruptions occur, Rahul is forced to stop working—leading to a sudden drop in earnings with no financial backup.

GigKavach addresses this critical gap by combining AI-driven parametric insurance with a micro-savings model, enabling workers to:

Contribute small amounts seamlessly from their daily earnings

Receive instant payouts during disruptions

Or get their savings returned with interest if no disruption occurs

By ensuring both financial protection and savings growth, GigKavach empowers gig workers with a reliable safety net in an otherwise uncertain work environment.

### How GigKavach Works for Rahul (Example)

1. **Daily Work & Micro-Savings:** As Rahul earns his daily income, a micro-deduction of **₹2 to ₹5 per order** is automatically made.
2. **Coverage Active:** This deduction updates his Wallet / Savings Pool, making his **Coverage Active**.
3. **Disruption Check:** The system continuously monitors for disruptions like **Rain, poor AQI, or Curfews**.

* **Scenario A: Disruption Occurs (YES)**
  * GigKavach calculates a payout of **₹200–₹400 for the day**.
  * Rahul receives an **Instant Payment via UPI**, ensuring his daily financial needs are met. *(Process Ends)*

* **Scenario B: No Disruption Occurs (NO)**
  * Rahul works normally until the **End of Plan is Reached**.
  * A **10% Company Fee** is deducted from his pool.
  * An **Interest of 4–5%** is added to his remaining savings.
  * The final amount **(Savings + Interest)** is safely **returned to Rahul**. *(Process Ends)*


## What We're Building
GigKavach is an AI-powered platform that protects gig workers’ income from disruptions like weather and pollution. It provides a unified dashboard to track earnings, savings, and coverage in real time. The system uses AI to assess risk, suggest optimal work decisions, and recommend safer working zones. It offers automatic insurance with instant payouts during disruptions and a fully automated claim process. Along with protection, it enables micro-savings and cashback with interest if no claims occur. Overall, it combines insurance, savings, and intelligent assistance to improve financial stability and productivity for gig workers.


## MVP_Features

1. Aay Darpan (Earnings Dashboard) – Displays real-time daily and weekly    earnings along with protected income.

2. Jokhim Soochak (Risk Indicator) – Provides live risk insights using weather and AQI data.

3. Suraksha Kavach (Smart Insurance) – Automatically activates coverage and gives instant payouts during disruptions.

4. Swayam Claim (Auto Claim System) – Processes claims automatically with real-time status updates.

5. Sahi Chayan (Smart Order Selection) – Recommends the best orders based on earnings, distance, and demand.

6. Surakshit Kshetra Map (Safe Zone Map) – Shows live maps of low, medium, and high-risk working areas.

7. AI Margdarshak (AI Assistant) – Suggests optimal working time and locations for maximum earnings.

8. Vishwas Score (Trust Score) – Detects fraud and assigns a reliability score to users.

9. Kaarya Pradarshan (Performance Tracker) – Monitors work efficiency and delivery performance.

10. SurakshaPay (Savings Wallet) – Enables micro-savings with easy deposit and withdrawal options.

11. Bonus Vaapsi (Cashback Rewards) – Returns savings with interest if no claims are made.

12. Bhasha Sathi (Language Assistant) – Provides multilingual voice support for better accessibility.

13. Smart Suchna (Smart Notifications) – Sends real-time alerts for risks, disruptions, and earning opportunities.


## Core Disruptions Covered
GigKavach protects gig workers from income loss caused by:

1. 🌦️ Environmental Disruptions

    1.1 Heavy Rainfall

    1.2 Flooding / Waterlogging

    1.3 Extreme Heat

    1.4 High Pollution (AQI levels)

2. 🚧 Human-Created Disruptions

    2.1 Traffic Congestion

    2.2 Curfews / Local Restrictions

    2.3 Strikes / Roadblocks

    2.4 Sudden Zone Closures


## 🏗️ Architecture Diagram

![Architecture Diagram](images/nnew.png)


## Technology Stack

| Layer | Technology | Rationale |
| :--- | :--- | :--- |
| **Mobile App** | 📱 Flutter (Dart) | Cross-platform, background GPS, offline tolerance |
| **Backend API** | ⚙️ FastAPI (Python) | Async-first, ideal for real-time polling loops |
| **Database** | 🗄️ Supabase (PostgreSQL) | Managed Postgres, built-in auth, real-time subscriptions |
| **Geospatial** | 🗺️ PostGIS (via Supabase) | Zone mapping, GPS-to-zone assignment, spatial queries |
| **ML / AI** | 🧠 Python · scikit-learn · Prophet | Gradient Boosting for risk scoring + fraud; Prophet for forecasting |
| **Weather API** | ⛅ OpenWeatherMap (free tier) | Rainfall, temperature, wind speed, storm alerts |
| **Pollution API** | 🏭 AQICN (free tier) | Real-time AQI per city zone |
| **Payment** | 💳 Razorpay Sandbox | Simulated premium collection + payout disbursement |
| **Notifications** | 🔔 Firebase Cloud Messaging | Push alerts for disruption events and payout confirmations |


## Development Plan

### ✅ Phase 1: Core Backend & Data Ingestion (Completed)
- [x] Node.js Business Logic and Authentication setup
- [x] API Gateway configuration for secure request routing
- [x] Data Storage schema design (User Profiles, Location Data, Earnings Data, Risk Scores)
- [x] Integration with 🌐 External APIs (Weather API, AQI API, Traffic API)
- [x] Setting up basic Admin Dashboard for Live Tracking
- [x] Core architecture planning & finalization

### 🚀 Phase 2: ML Engine & Automated Triggers (Current)
- [ ] 🧠 ML Engine setup (Data Preprocessing pipelines, Income Estimation)
- [ ] Implement Risk Prediction modeling using real-time API data
- [ ] Deploy statistical Fraud Detection models
- [ ] ⚡ Trigger Engine implementation (Rain, AQI, Traffic, and Heat triggers)
- [ ] Automated risk score evaluation pipeline (ML Engine → Trigger Engine)
- [ ] Risk Heatmap integration on the Admin Dashboard

### ⏳ Phase 3: Client Apps & Payment Execution (Upcoming)
- [ ] 📱 User Layer Development (Mobile App for gig workers, Web Dashboard)
- [ ] Linking continuous user requests directly into the Backend System
- [ ] 💳 Payment System implementation (Stripe Payment Gateway, Digital Wallet mechanism)
- [ ] End-to-end auto-payout trigger testing (Trigger Engine → Payment System)
- [ ] Payout Analytics module deployment on the Admin Dashboard
- [ ] Final end-to-end simulation (Simulated environmental triggers → Instant Payouts via Wallet)

