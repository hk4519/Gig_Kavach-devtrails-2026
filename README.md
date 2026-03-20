
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

## Architecture Diagram

The GigKavach platform is built on a highly modular and automated architecture to ensure real-time protection and seamless payouts. The system consists of the following interconnected components:

1. 📱 User Layer

  1.1 Mobile App

  1.2 Web Dashboard

2. 🌐 External APIs

  2.1 Weather API

  2.2 AQI API

  2.3 Traffic API

3. ⚙️ Backend System

  3.1 API Gateway

  3.2 Authentication

  3.3 Business Logic (Node.js)

4. 🗄️ Data Storage

  4.1 User Profiles

  4.2 Location Data

  4.3 Earnings Data

  4.4 Risk Scores

5. 🧠 ML Engine

  5.1 Data Preprocessing

  5.2 Risk Prediction

  5.3 Fraud Detection

  5.4 Income Estimation

6. ⚡ Trigger Engine

  6.1 Rain Trigger

  6.2 AQI Trigger

  6.3 Traffic Trigger

  6.4 Heat Trigger

7. 💳 Payment System

  7.1 Payment Gateway

  7.2 Digital Wallet

8. 📊 Admin Dashboard

  8.1 Live Tracking

  8.2 Risk Heatmap

  8.3 Payout Analytics

### System Data Flow

* **User Requests & External Data**: The *User Layer* sends requests to the *Backend System* via an API Gateway, while *External APIs* feed real-time environmental data (Weather, AQI, Traffic).
* **Data Storage**: The Backend stores and retrieves user profiles, location, earnings, and risk scores from *Data Storage*.
* **Machine Learning Analysis**: The *Backend System* routes raw data to the *ML Engine*, which performs data preprocessing, risk prediction, fraud detection, and income estimation.
* **Automated Decision & Triggers**: The computed risk score is passed to the *Trigger Engine*. Triggers like Rain, AQI, Traffic, or Heat evaluate the risk to decide on action.
* **Instant Payouts**: Verified events fire an auto-payout trigger to the *Payment System*, instantly sending an instant payout to the user.
* **Monitoring**: Analytics and payout events are continuously synchronized with the *Admin Dashboard* for live tracking and heatmaps.

## 🏗️ Architecture Diagram

![Architecture Diagram](images/nnew.png)
