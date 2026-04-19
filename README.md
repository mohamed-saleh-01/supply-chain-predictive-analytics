# 🚚 Logistics & Supply Chain Operations: Strategic Analysis & Predictive Modeling

## 📌 Project Overview
In the high-stakes world of logistics, efficiency and predictability are the keys to profitability. This project is a comprehensive Case Study where I transformed raw supply chain data into a strategic asset. By integrating multiple data sources (Shipments, Drivers, Equipment, and Service Centers), I built a framework that identifies operational bottlenecks and predicts shipment delays with high precision.

---

## 📊 Dashboard Preview

### Cover
![Cover](Dashboard%20Images/1-%20Cover%20Page.png)

### Overview Insights
![Overview](Dashboard%20Images/2-%20Overview%20Page.png)  

### Operational Insights
![Operational](Dashboard%20Images/3-%20Operational%20Page.png)  

### Finanical Insights
![Finanical](Dashboard%20Images/4-%20Finanical%20Page.png)  

---

## 🛠️ The Challenge (Business Problem)
The logistics operation faced several critical challenges:
* Margin Volatility: Inconsistent gross margins across different industries.
* Service Failures: Rising claims and delays without a clear understanding of the root causes.
* Resource Fatigue: Potential driver burnout and equipment downtime affecting capacity.

---

## 🚀 Project Workflow (End-to-End)

### 1. Data Architecture & Modeling
I implemented a Star Schema to ensure data integrity and optimized reporting performance:
* Fact Table: FACT_Shipments (The core transactional data).
* Dimension Tables: * DIM_Customers: Segmented by industry and revenue bands.
    * DIM_Drivers: Performance tracking and experience tiering.
    * DIM_Equipments: Fleet age and maintenance lifecycle.
    * DIM_Service_Center: Regional hub categorization (Relay vs. Gateway).

### 2. ETL & Data Engineering
Using Python (Pandas), I handled the heavy lifting:
* Cleaning: Resolved null values in claim reasons and standardized categorical data.
* Feature Engineering: Developed critical KPIs including Gross_Margin_Pct, Revenue_Per_Mile, and On_Time_Status.

### 3. Machine Learning (Predictive Analytics) 🤖
To move from reactive to proactive, I built a predictive pipeline to forecast Late Shipments.
* Champion Model: Gradient Boosting Classifier.
* Model Performance: * Accuracy: 98%
    * Precision (On-Time): 98%
    * Recall (Late): 51% (Focusing on identifying late shipments before they happen).
* Key Features: Distance, Equipment Type, and Driver Experience were identified as the strongest predictors of delays.

---

## 💡 Key Business Insights

* 💰 Financials: The Aerospace and Electronics sectors are the most profitable, maintaining margins > 35%.
* 🚛 Operations: Relay Hubs contribute to 12% more delays than Gateway hubs, highlighting a need for process optimization in transit points.
* 👥 Human Capital: Drivers in the "Over Worked" category show a direct correlation with lower safety scores, posing a long-term operational risk.
* 🔧 Asset Management: Equipment older than 8 years in the Midwest region accounts for the majority of maintenance-related downtime.

---

## 🎯 Strategic Recommendations
1. Predictive Dispatching: Integrate the ML model into the dispatch system to flag "High Risk" shipments for senior driver assignment.
2. Dynamic Pricing: Implement accessorial surcharges for industries with high claim rates to protect the bottom line.
3. Preventive Maintenance: Shift to a usage-based maintenance schedule for high-mileage trucks to reduce emergency repairs.
4. Talent Retention: Implement a "Miles Rebalancing" program to shift loads from Over-Worked to Under-Utilized drivers.

---

## 💻 Tech Stack
* Analysis & ML: Python (Pandas, Scikit-Learn, NumPy, Seaborn).
* Visualization: Power BI (Advanced DAX modeling).
* Database Design: Star Schema / Relational Modeling.
* Documentation: Markdown & Git.

---

## 📂 Repository Structure
As shown in the project directory, the files are organized as follows:
* 📂 1- Data Source: Raw & cleaned datasets.
* 📂 2- EDA & Machine Learning: Python EDA, Feature Engineering & ML Modeling.
* 📂 3- Power BI Dashboard:  Interactive .pbix analytics hub.
* 📂 4- Storytelling Presentaton: to represent Project to Stakholder
* 📂 Dashboard Image: Dashboard Screenshots for project documentation.

---

## 📫 Connect with Me
Mohamed Saleh
* Linkedin: https://linkedin.com/in/mohamed-sale7
* Email: mohamed284saleh@gmail.com 
