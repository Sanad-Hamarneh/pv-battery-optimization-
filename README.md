# ⚡ PV & Battery Sizing Optimization using Linear Programming  

This project focuses on optimizing the **sizing of PV panels and battery storage** using **Linear Programming (LP)** with **CPLEX Python**. The goal is to **minimize costs** while ensuring reliable power supply based on energy demand.  

## 📌 Problem Statement  
- Given a location with **solar power generation potential**, we need to determine:  
  - **Optimal number of PV panels** needed.  
  - **Battery storage capacity** required for energy reliability.  
  - **Minimization of costs**, including **installation & maintenance**.  

## 🛠️ Techniques Used  
- **Linear Programming (LP)** with **CPLEX Python**  
- **Cost optimization** based on energy demand & solar generation  
- **Battery charge/discharge constraints**  
- **Renewable energy integration** for **off-grid & grid-tied systems**  

## 📊 Inputs & Constraints  
- **Solar power generation data** ☀️  
- **Energy consumption profile** ⚡  
- **Battery storage efficiency & degradation** 🔋  
- **Economic parameters (costs, savings, incentives)** 💰  

## 🏆 Expected Outcomes  
- Optimal **PV and battery sizing** based on location & load  
- **Minimized cost** while ensuring **energy reliability**  
- Insights on **renewable energy integration** for sustainability  

## 🚀 How to Run  
1. Install dependencies:  
   ```bash
   pip install cplex numpy pandas matplotlib
