# 👋 Hi, I'm Aishwarya Malhotra

I'm a Data & Business Analyst with 5+ years of experience helping banks, fintechs, and cross-functional teams turn complex data into actionable insights and robust solutions. My expertise lies at the intersection of **finance, analytics, and technology**—from building machine learning pipelines for credit risk to automating regulatory reporting with cloud tools.

- 📍 Based in Boston, USA  
- 🎓 MS in Applied Business Analytics (Boston University)  
- 👩‍🔬 Former Research Assistant at BU (Prof. Pinsky, Quantitative Finance)  
- 🔬 **Currently:** Visiting Researcher – Data Science & Quantitative Finance at Boston University 

---

## 🚀 What I Do  

### 🏦 Credit & Financial Risk Modeling (FinTech/Banking)  
- Developed **PD, LGD, EAD, EL models** using ML (XGBoost, Logistic Regression) aligned with **Basel III & IFRS-9**.  
- Conducted **stress testing & scenario analysis** for portfolio resilience and capital optimization.  

### 🔐 Fraud Analytics & AML Monitoring  
- Built **real-time anomaly detection systems** in Python/Databricks, integrated with **AWS + SIEM**.  
- Reduced fraud detection latency by **60%**, cutting false positives and accelerating investigations.  

### 📊 Marketing Science & Experimentation (Tech/Product)  
- Designed **incrementality testing frameworks** (Bayesian Structural Time Series, causal inference).  
- Ran **A/B and multivariate experiments** on product flows and campaigns, quantifying **true lift**.  

### ☁️ Data Engineering & Cloud Analytics  
- Automated **ETL pipelines** with AWS Glue, Redshift, Snowflake, and Databricks.  
- Delivered governed **data models** for both risk reporting and marketing analytics workflows.  

### 📈 Visualization & BI Dashboards  
- Built **Tableau, Power BI, and Looker dashboards** for portfolio risk monitoring, KPI tracking, and product experimentation.  

### 🤝 Collaboration & Agile  
- Partnered with cross-functional teams (Risk, Compliance, Marketing, Product, UX).  
- Translated requirements into **Epics, acceptance criteria, and Jira deliverables** for scalable deployments.  


---

## 🏆 Featured Projects

### Flipkart E-Commerce Product Analytics & Experimentation 

At Flipkart, I led the **data science workstream** for experimentation across search, checkout, and recommendation systems, partnering with Product, UX, and Marketing teams to optimize conversion funnels.

✅ **Technical Contributions:**
- Designed and executed **A/B and multivariate test frameworks** with defined **KPIs, sample size calculations, and power analysis**  
- Built **SQL pipelines (Snowflake/Redshift)** and **Python-based statistical models** to validate experiments and measure lift with confidence intervals  
- Applied **causal inference and segmentation analysis** to uncover heterogeneous treatment effects across customer cohorts  
- Optimized checkout flows (↓ **18% cart abandonment**) and recommendation engines (↑ **12% average order value**)  
- Automated **Tableau dashboards & retrospective analyses**, integrating results into the product roadmap for continuous experimentation  

💡 **Impact:**  
Established a **scalable experimentation framework** that accelerated product release cycles, delivered measurable revenue impact, and strengthened **data-driven decision making** across cross-functional teams.  

📊 **Tech Stack:**  
SQL (Snowflake, Redshift) | Python (Pandas, NumPy, SciPy, Scikit-learn, Statsmodels) | Experimentation Frameworks (A/B, MVT, causal inference) | Tableau | KPI Automation  

✨ Passionate about leveraging **applied statistics, experimentation frameworks, and scalable analytics pipelines** to optimize e-commerce platforms and drive measurable business growth.  

\#Experimentation \#ABTesting \#CausalInference \#SQL \#Python \#Tableau \#Ecommerce \#ProductAnalytics \#DataScience

---

### Basel III Regulatory Reporting Automation (Illimity Bank)  
 
- Automated end-to-end Basel III reporting pipeline using AWS Glue and Python, standardizing and validating Excel inputs from multiple business units.
- Reduced reporting delays by 40% and improved data accuracy to 99%.
- Enabled real-time dashboards in Power BI, empowering compliance teams with live risk metrics and full audit traceability.
- Ensured regulatory alignment and mitigated audit risks by designing robust, auditable data flows.

---

### Credit Risk Modeling – PD, LGD, EAD, and EL 
*[Repository Link](https://github.com/Aish-BU/Credit_Risk_Modelling)*  

Built a credit risk modeling framework in Python to calculate **Probability of Default (PD)**, **Loss Given Default (LGD)**, **Exposure at Default (EAD)**, and **Expected Loss (EL)**, aligning with Basel III/IFRS-9 standards.

✅ **Technical Contributions:**
- Developed classification models (**Logistic Regression, Random Forest, XGBoost**) to estimate PD from borrower characteristics and macroeconomic indicators  
- Applied regression models and **survival analysis** to forecast LGD, incorporating collateral values and recovery rates  
- Estimated EAD using credit conversion factors and exposure dynamics; combined PD, LGD, and EAD to compute portfolio-level EL  
- Conducted **stress testing and scenario analysis** to evaluate model resilience under macroeconomic shocks  
- Validated models using **ROC/AUC, confusion matrix, precision/recall, and backtesting** to ensure robustness and regulatory alignment  

💡 **Impact:**  
Delivered a scalable, **machine learning–driven framework** for credit risk estimation, enabling accurate capital allocation, risk segmentation, and regulatory compliance.  

📊 **Tech Stack:**  
Python (Pandas, NumPy, Scikit-learn, Statsmodels) | Risk Analytics | Basel III & IFRS-9 | Logistic Regression | XGBoost | Survival Analysis | Stress Testing  

✨ Passionate about combining **machine learning and financial risk modeling** to drive smarter lending decisions, improve portfolio resilience, and strengthen regulatory compliance.  

\#CreditRisk \#MachineLearning \#RiskManagement \#BaselIII \#IFRS9 \#PD \#LGD \#EAD \#ExpectedLoss \#Python \#DataScience


---

### 🎵 Spotify KNN Classification Project  
*[Repository Link](https://github.com/Aish-BU/Spotify-Music-Recommendation-Listener-Preference-Analysis)* 

A dataset of **2,017 Spotify songs** with 17 audio features (danceability, valence, acousticness, speechiness, etc.) was used to predict whether a listener (*George*) liked (`1`) or disliked (`0`) each track.  

The goal was to build a **classification model** that outperforms the baseline 50% accuracy.  

I conducted **t-tests** to identify significant predictors (danceability, speechiness, valence, acousticness) and removed non-significant ones (tempo, energy, liveness). The data was **normalized** and split into **60% training (1,211 songs)** and **40% validation (806 songs)**. KNN models were evaluated for **k = 1–35**.  

The **best performance occurred at k = 31**, achieving **~65.6% accuracy** (~15% above baseline). Liked songs were more danceable (+0.058), higher in valence (+0.056), and more speech-heavy (+0.027), while disliked songs were more acoustic (+0.076). For example, *“Enemy – Arcane”* by Imagine Dragons was correctly predicted as **liked**.  

**Conclusion:** KNN effectively captured music preference patterns from acoustic features, demonstrating its potential for **personalized recommendation systems**.  
---

### Incrementality Testing Using Bayesian Structural Time Series (BSTS) 

Developed an incrementality testing framework to measure the causal impact of in-store media campaigns using **Bayesian Structural Time Series (BSTS)** models.

✅ **Technical Contributions:**
- Built counterfactual models to estimate baseline performance (what would have occurred without intervention)  
- Quantified incremental lift of marketing campaigns with credible intervals and posterior distributions  
- Incorporated time-series components (**trend, seasonality, external regressors**) to improve robustness and interpretability  
- Delivered actionable performance metrics (**ROI, lift, uncertainty bounds**) to marketing teams for campaign optimization  

💡 **Impact:**  
Enabled causal measurement of campaign effectiveness beyond correlation, helping decision-makers allocate spend with confidence and identify true incremental business value from marketing initiatives.  

📊 **Tech Stack:**  
Python (PyMC3, Prophet, Statsmodels) | Bayesian Inference | Time-Series Forecasting | Causal Impact Modeling | Experimentation Analytics  

\#Bayesian \#CausalInference \#Incrementality \#BSTS \#MarketingAnalytics \#Experimentation \#DataScience \#Python

---

### Real-Time Fraud Detection & AML Monitoring 

Traditional **rule-based AML systems** struggled with high false positives and slow detection, delaying investigations and increasing compliance risk. To solve this, I **developed and deployed ML-powered anomaly detection models** integrated into a real-time fraud monitoring pipeline.

✅ **What I did:**
- Built and trained **anomaly detection & predictive models** in **Python (XGBoost, clustering, decision trees)**
- Deployed models on **Databricks**, integrated with **SIEM workflows** for real-time alerting  
- Reduced fraud detection latency by **60%**, accelerating investigative efficiency  
- Augmented rule-based AML systems with ML-driven insights to cut false positives  
- Delivered dashboards for **investigators and compliance teams** in Tableau/Power BI for transparent monitoring  

💡 **Impact:**  
This project significantly improved the **speed, accuracy, and efficiency** of fraud and AML monitoring, enabling compliance teams to respond to threats faster and with fewer false alerts.

📊 **Skills applied:**  
Python | Databricks | SQL | SIEM Integration | Tableau | Power BI | Fraud Analytics | AML Compliance | Real-Time Monitoring  

✨ Excited to keep advancing **fraud detection and risk resilience** with scalable, AI-driven solutions in fintech and banking.  

\#FraudDetection \#AML \#RiskManagement \#MachineLearning \#Compliance \#RealTimeAnalytics \#Databricks \#FinancialCrime


---

### Sector Rotation Strategy Research (Boston University, Research)  
*[Repository Link](https://github.com/Aish-BU/SPY_ETFs_Rotation_Trading_Strategy)* 
- Designed and tested a novel median sector rotation strategy for S&P 500 ETFs using 25 years of historical data.
- Demonstrated that the strategy doubled long-term returns versus buy-and-hold and halved drawdowns, especially during major crises.
- Provided a simple, practical approach for retail investors seeking robust performance with lower risk.
- Published key findings and code for transparency and reproducibility.

---

### Airbnb Zurich Data Mining Project  
*[Repository Link](https://github.com/Aish-BU/Airbnb_Project)* 
- Analyzed Airbnb Zurich listings using clustering, regression, and classification to uncover price drivers and segment the market.
- Achieved R² > 0.8 for price prediction and identified key factors impacting occupancy and revenue.
- Built interactive dashboards for hosts and platform managers to support data-driven pricing and listing optimization.
- Offered actionable recommendations that improved occupancy by 10–15% for participating hosts.

---

## 🛠️ Tech Toolbox

**Languages:** Python (Pandas, NumPy, scikit-learn, TensorFlow, PySpark, SciPy), R, SQL  
**Cloud/Big Data:** AWS (Glue, Redshift, S3, SageMaker), Databricks, Snowflake, Hadoop  
**Analytics/Visualization:** Tableau, Power BI, Matplotlib, Seaborn, SPSS  
**Engineering:** Data Modeling, ETL, Azure Data Factory, MySQL  
**Project Management:** Jira, Confluence, Agile/Scrum, Figma  
**Other:** Git, CI/CD, API integration

---

## 📈 Quick Stats

- 🚀 Improved credit model accuracy by **28%** and reduced fraud alert time by **60%**
- 📊 Managed data pipelines processing **2M+ records** for regulatory compliance
- 🥇 Published research on ETF sector rotation strategies & portfolio optimization

---

## 📫 Let's Connect!

- 💼 [LinkedIn](https://www.linkedin.com/in/aishwarya-malhotra-78546275/)
- 📬 Email: [aish7@bu.edu](mailto:aish7@bu.edu)

---

## 🌟 Currently

As a **Visiting Researcher in Data Science & Quantitative Finance**, I’m actively exploring new methods in risk analytics, financial modeling, and investment strategy research. I’m always open to connect on innovative projects, research collaborations, or analytics-driven roles.

> *"Bridging the gap between data and business strategy—one solution at a time."*

---
