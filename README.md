💳 Banking Risk Analytics 

# 💳 Loan Risk Analytics Dashboard

# 📘 Project Overview

This project simulates a real-world use case in the banking and financial services sector, where data analytics is used to assess customer creditworthiness and minimize loan default risk. I built a complete end-to-end risk analytics solution using Power BI, Python, and SQL, enabling financial institutions to make informed, data-driven lending decisions.

## 🎯 Business Problem

### A bank must evaluate loan applicants based on various risk factors such as income, engagement history, and advisor relationships. Challenges include:

❌ Lack of visibility into customer credit risk

❌ Manual and inconsistent approval processes

❌ Poor segmentation for targeting and risk profiling


### 💡 Project Objective

To develop a loan risk analytics dashboard that provides insights into customer profiles and lending risk, helping banks:

🧠 Predict whether an applicant is likely to repay a loan

✅ Approve or reject loans based on data-driven insights

🔍 Segment customers into actionable income and risk bands


| Component            | Technology Used           |
| -------------------- | ------------------------- |
| Data Modeling        | MySQL, Excel              |
| Data Analysis        | Python, Pandas, NumPy     |
| Visualization & BI   | Power BI Desktop          |
| Feature Engineering  | Python (Jupyter Notebook) |
| Data Cleaning & Prep | Excel, Pandas             |
| Reporting Layer      | Power BI (.pbix)          |





















































## 📊 Dataset Overview
The dataset includes multiple interrelated tables connected via primary and foreign keys:

- **Banking Relationship**
- **Client-Banking**
- **Gender**
- **Investment Advisor**
- **Period**

These tables contain comprehensive client and bank details essential for risk assessment.

## 🧹 Data Cleaning & Feature Engineering

- Created **Engagement Timeframe** in the `Client-Banking` table to represent the timeline of client activity.
- Calculated **Engagement Days** to quantify how long a client has been with the bank.
- Categorized **Estimated Income** into income bands:
  - `≤ 100,000` as `Low`
  - `< 300,000 and > 100,000` as `Mid`
  - `≥ 300,000` → `High` 
- Added **Processing Fees** based on the `Fee Structure`:
  - If `Fee Structure = High`, then `Processing Fees = 0.05`
  - If `Fee Structure = Medium`, then `Processing Fees = 0.03`
  - If `Fee Structure = Low`, then `Processing Fees = 0.01`

These features improve model accuracy and interpretability.

## 📈 Power BI Dashboard Highlights

The dashboard provides data-driven insights to support risk assessment and loan approval decisions, including:

- 🔍 Identification of clients with high, medium, or low estimated income bands
- 📅 Analysis of client engagement duration with the bank
- 💰 Evaluation of fee structure and its impact on processing fees
- 👥 Gender-based and advisor-based segmentation for risk profiling
- 📈 Trends over different time periods to assess historical risk patterns
- ✅ Visual cues to help determine whether a loan should be approved or rejected

## 🛠️ Tools Used

- Microsoft Power BI Desktop
- DAX for measures and calculations
- Excel for raw data management
- Data modeling and relationships
- MYSQL
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  



## 📁 Repository Structure

| Folder        | Contents                              |
|---------------|-------------------------------------|
| `data/`       | Raw data files (Excel spreadsheets) |
| `dashboard/`  | Power BI `.pbix` file and screenshots |
| `notebooks/`  | Python notebooks for analysis |
| `README.md`   | Project documentation                |

## 🖼️ Dashboard Preview
<img width="586" height="325" alt="image" src="https://github.com/user-attachments/assets/bed31a09-828e-49f4-8c00-65b2f595cf9a" /> 
<img width="596" height="327" alt="image" src="https://github.com/user-attachments/assets/da07499d-6433-47b4-a792-a8424dc964ce" />
<img width="582" height="328" alt="image" src="https://github.com/user-attachments/assets/29031cd8-e63b-42a1-b95b-5e791757e788" />





## 🤝 Acknowledgments

This project serves as a practical case study for understanding and applying risk analytics in the banking sector to reduce financial losses through informed lending decisions.
