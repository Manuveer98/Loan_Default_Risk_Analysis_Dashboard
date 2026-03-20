📊 Loan Default Risk Analysis
---

## 📌 Project Background
Loan defaults are one of the primary risks faced by financial institutions, directly impacting profitability and long-term stability.  

This project analyzes **250,000+ loan records (2013–2018)** to evaluate borrower behavior, loan distribution, and risk patterns across demographic and financial variables.  

The goal is to identify **hidden risk signals** and assess whether current lending patterns align with borrower risk profiles.

---
https://app.powerbi.com/links/YZ2o39qcJw?ctid=fd0853e9-4432-4693-8bd9-5cac61a80641&pbi_source=linkShare

## 📈 Executive Summary
The analysis highlights a critical mismatch between **borrower risk and lending behavior**.

While expected risk indicators such as employment instability do influence default rates, the lending strategy does not consistently adjust for these risks. Notably, **lower credit score borrowers are receiving comparable or even higher loan amounts**, indicating weak risk-based allocation.

Additionally, the loan portfolio is heavily concentrated in specific categories (e.g., home loans), exposing the institution to **sector-specific risk**.  

Overall, the findings suggest the need for **more disciplined, risk-adjusted lending policies**.

---

## 🔍 Key Insights
<img width="1920" height="972" alt="Screenshot (1940)" src="https://github.com/user-attachments/assets/51eca84c-c084-4567-a882-38d5b5e06065" />

### 1. Employment Stability is a Key Risk Driver
- Default rate is highest among **unemployed borrowers (3.39%)**
- Lowest among **full-time employees (2.36%)**

👉 Indicates strong correlation between **income stability and repayment ability**

---

### 2. Loan Portfolio is Highly Concentrated
- Majority of loans are issued for **home purposes (~6545M)**

👉 Overexposure to a single category increases **systemic risk**

---

### 3. Risk-Based Lending is Inefficient (Critical Insight)

<img width="1920" height="980" alt="Screenshot (1941)" src="https://github.com/user-attachments/assets/5dde55da-d4de-4a34-b420-84cf466c56db" />

- Borrowers with **low credit scores receive the highest median loan (~128.4K)**
- High credit score borrowers receive slightly lower loan amounts

👉 Suggests poor **risk-adjusted loan sizing**, increasing default exposure

---

### 4. Default Rates Show Cyclical Behavior
- Peak in **2015–2016 (~11.7%)**
- Drop in 2017, followed by recovery in 2018

👉 Indicates influence of **external or macroeconomic factors**

---

### 5. Education and Loan Distribution
- Majority of loans issued to **Bachelor’s degree holders (~64K loans)**

👉 Suggests demographic concentration in lending patterns

---

### 6. Credit Distribution Across Age Groups is Uniform
- Loan distribution across age groups is nearly equal (~25% each)

👉 Age is not a strong differentiator in lending decisions

---

### 7. Credit Score vs Loan Allocation Imbalance
- Medium and high credit groups dominate total lending
- Low credit groups still receive significant loan volumes

👉 Indicates **incomplete risk filtering**

---

## 💡 Recommendations

### 1. Implement Risk-Based Loan Sizing
- Adjust loan amounts based on credit score and DTI ratio

---

### 2. Strengthen Employment-Based Screening
- Apply stricter criteria for:
  - Unemployed
  - Part-time borrowers

---

### 3. Diversify Loan Portfolio
- Reduce overdependence on home loans
- Expand into diversified lending categories

---

### 4. Introduce Tiered Interest Rates
- Higher interest rates for high-risk borrowers
- Balance risk vs return

---

### 5. Monitor Temporal Risk Trends
- Investigate spikes (2015–2016)
- Build early warning systems for default risk

---

## 🛠️ Tech Stack Used

- **Data Source**: CSV Files  
- **Database**: MS SQL Server  
- **Data Visualization**: Power BI Desktop  
- **Deployment & Sharing**: Power BI Service  
- **Data Modeling & Calculations**: DAX  

---

## 📊 Dashboard Overview

The report is structured into three key pages:

### 1. Loan Default & Overview
- Loan distribution by purpose  
- Default rate by employment type  
- Default trend over time  

### 2. Applicant’s Demographics & Profile
- Loan distribution by credit score and age  
- Education-based segmentation  
- Credit behavior analysis  

### 3. Financial Risk Metrics
<img width="1920" height="983" alt="Screenshot (1942)" src="https://github.com/user-attachments/assets/0309788f-361a-4f0f-9e81-c12374a83916" />

- Default rate growth trends  
- YTD loan distribution by credit score & marital status  
- Risk segmentation insights
  
https://app.powerbi.com/links/YZ2o39qcJw?ctid=fd0853e9-4432-4693-8bd9-5cac61a80641&pbi_source=linkShare

