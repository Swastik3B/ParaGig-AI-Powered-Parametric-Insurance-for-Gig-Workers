##### **🚀 ParaGig: AI-Powered Parametric Insurance for Gig Workers**

ParaGig is an automated, AI-driven insurance platform designed to provide financial security to gig economy workers (Swiggy, Zomato, etc.) whose earnings are vulnerable to external disruptions like extreme weather, high pollution, or lockdowns.

###### 

##### **📌 Problem Statement**

Gig workers depend on daily deliveries for income. When external conditions like heavy rainfall, extreme heat, or hazardous AQI occur, they face a total loss of daily earnings.



Traditional insurance:



* **Slow processing**
* **Heavy paperwork**
* **Not suitable for micro-losses**



Solution



ParaGig uses Parametric Insurance, where payouts are:

* **Automatically triggered**
* **Based on real-time data thresholds**
* **Instantly credited to workers**

##### 

##### **✨ Features**

🔹 **Dynamic Risk Scoring**

AI-based evaluation of delivery zones for fair premium calculation

**🔹 Automated Triggers**

No claims required — payouts happen automatically

**🔹 Fraud Mitigation**

Cross-verifies worker location with real-time data

**🔹 Micro-Premiums**

Affordable plans (e.g., ₹20/week)

**🔹 Instant Settlement**

UPI/Digital wallet-ready payouts



##### **🛠️ Tech Stack**

  **Layer             Technology**    

       

  **Frontend :- React.js, Tailwind CSS**      

  **Backend  :- FastAPI (Python)**            

  **Database :- MongoDB Atlas**               

  **AI/ML    :- Scikit-learn, Pandas, NumPy** 

  **APIs     :- OpenWeather API, WAQI API**   



##### **🤖 AI Implementation**



The system uses AI in three key areas:

**1. Risk Assessment**

* Analyzes historical weather patterns
* Evaluates delivery density
* Assigns zone-based risk scores



**2. Premium Calculation**

&nbsp;   Premium=(Base Rate × Risk Score) + Adjustments



**3. Anomalous Claim Detection**

* Ensures data consistency
* Prevents misuse and fraud

###### 

##### **🌦️ Parametric Triggers \& Coverage**

###### 

**Heavy Rain**

**Threshold: > 15mm within 3 hours**

**Data Source: OpenWeather API**



**Air Pollution**

**Threshold: AQI > 400 (Severe)**

**Data Source: WAQI API**



**Extreme Heat**

**Threshold: Temperature > 45°C**

**Data Source: OpenWeather API**



**Lockdown/Curfew Alert**

**Threshold: Official API / News Feed**

**Data Source: Government Sources**



###### **🔄 System Workflow**



1. Onboarding → Worker selects delivery zone
2. Analysis → AI calculates premium
3. Subscription → Worker pays micro-premium
4. Monitoring → System tracks real-time data
5. Trigger → Threshold crossed
6. Payout → Instant credit to wallet



###### **⚙️ Getting Started**

**📋 Prerequisites**



* **Python 3.9+**
* **Node.js \& npm**
* **MongoDB Atlas account**



###### **🚀 Future Scope**



🔹 Integration with Swiggy/Zomato APIs

🔹 IoT-based hyper-local weather sensors

🔹 Dedicated mobile app (Flutter/React Native)

🔹 Expansion to more risk categories

🔹 Multi-city deployment across India



###### **📊 Conclusion**



ParaGig leverages FastAPI and Machine Learning to bridge the gap between financial services and the gig economy.



It ensures:

⚡ Instant payouts

🤖 Smart risk analysis

💰 Financial protection for gig workers

