# 🏥 Hospital Supply Chain Optimization & Forecasting Project

## 📦 Overview

Welcome to the **Hospital Supply Chain Optimization Project** — a data-driven exploration into how hospital inventory workflows can be analyzed, improved, and predicted using real operational data.

This project focuses on understanding **pick ticket activity**, identifying inefficiencies in daily supply distribution, and leveraging **time series forecasting models** to anticipate future demand across hospital departments.

---

## 🎯 Objectives

* Analyze hospital supply chain data to uncover workflow inefficiencies
* Compare **high-volume vs. low-volume departments**
* Optimize scheduling of supply pulls for better daily workload balance
* Build predictive models to forecast supply demand
* Present findings through reports, dashboards, and visualizations

---

## 📁 Project Structure

```
hospital-supply-chain-optimization/
│
├── 📊 hospital_supply_chain_raw_data.xlsx
│   → Raw dataset containing supply pick activity across hospital departments
│
├── 📈 Hospital-Supply-Chain-Pick-Ticket-Analysis.pptx
│   → Presentation summarizing findings, trends, and recommendations
│
├── 📄 Hospital Supply Chain Analysis Report.docx
│   → Full written report with data analysis, insights, and conclusions
│
├── 🤖 Hospital_Supply_Chain_Prediction_Model.ipynb
│   → Google Colab Notebook with time series forecasting model
│
├── 📄 Hospital Supply Chain Prediction Model.ipynb - Colab.pdf
│   → Exported version of the predictive model notebook
```

---

## 🔍 Key Insights

### 🏥 Department Activity Differences

* **High-volume areas** (e.g., OR, ER):

  * Scanned **daily**
  * High consistency in workload
* **Low-volume areas** (e.g., ANES, Med-Surg units):

  * Scanned **2x per week**
  * Cause uneven workload distribution

➡️ **Insight:** Workload imbalance is driven more by *scheduling patterns* than total volume.

---

### ⚖️ Workflow Imbalance

* Some days are overloaded with supply pulls
* Other days are underutilized

➡️ **Opportunity:** Redistribute scan days to create **balanced daily workloads**

---

### 📉 Data-Driven Recommendation

* Adjust scanning schedules for lower-volume departments
* Align workload across the week
* Reduce inefficiencies in supply retrieval

---

## 🤖 Predictive Modeling

This project includes a **Time Series Forecasting Model** designed to:

* Predict future supply demand trends
* Account for **non-working days (weekends excluded)**
* Identify peak demand periods
* Support proactive inventory planning

### 🔧 Model Features

* Uses historical OR (Operating Room) data
* Handles irregular scanning schedules
* Designed for scalability to other departments

---

## 🧠 Model Improvements (Future Work)

* Upgrade to advanced models such as:

  * ARIMA / SARIMA
  * Facebook Prophet
  * LSTM Neural Networks

➡️ **Best Fit:** Prophet is ideal for this scenario due to its ability to handle irregular trends and missing dates.

---

## 📊 Tools & Technologies

* 📘 Microsoft Excel (Data Cleaning & Exploration)
* 📓 Jupyter Notebook / Google Colab (Modeling)
* 📈 PowerPoint (Visualization & Presentation)
* 📄 Microsoft Word (Reporting)
* 🐍 Python (Time Series Forecasting)

---

## 🚀 How to Use This Project

1. Open the Excel file to explore raw data
2. Review the report for full analysis
3. View the PowerPoint for summarized insights
4. Run the Jupyter Notebook to explore the prediction model

---

## 💡 Why This Project Matters

Hospital supply chains directly impact:

* Patient care efficiency
* Staff workload
* Operational costs

By combining **data analysis + predictive modeling**, this project demonstrates how even small scheduling changes can lead to **major operational improvements**.

---

## 👨‍💻 Author

**Jayson Nason**
Computer Science Major | Finance Minor

---

## ✨ Final Thoughts

This project blends **healthcare operations, data analytics, and machine learning** to solve a real-world problem. It highlights how thoughtful analysis can transform raw data into actionable insights that improve efficiency and outcomes.

---

⭐ *If you found this project helpful or interesting, feel free to star the repo!* ⭐
