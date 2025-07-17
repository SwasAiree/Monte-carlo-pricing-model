# Monte-carlo-pricing-model
Monte Carlo simulation model with scenario and risk analysis for hotel pricing decisions.

# Coastal Nest Motel – Pricing Strategy Simulation Model

This project delivers a dynamic decision-support model for optimizing room pricing and overbooking strategy at Coastal Nest Motel. Built entirely in Excel, the model simulates daily bookings, cancellations, costs, and profits using Monte Carlo techniques. The goal is to guide strategic pricing under uncertainty during peak season.

---

## 🎯 Objective

To identify the optimal room rate ($150 vs. $200) by analyzing demand fluctuations, cancellation risks, and profit variability. The model supports management in selecting the most resilient and profitable pricing strategy through robust scenario and risk analysis.

---

## 🧠 Key Features

- **Decision Variables:** Room rate and overbooking buffer  
- **Stochastic Inputs:** Online bookings, cancellation rate, walk-in demand, and miscellaneous daily costs  
- **Fixed Inputs:** Housekeeping cost, cancellation penalty, room count  
- **Outputs:** Daily revenue, cost, profit, sold-out status  

---

## 💻 Excel Decision Model Overview

The simulation model is structured in Excel with a modular, color-coded layout designed for clarity and ease of use. It supports flexible input adjustments and includes five key blocks:
<img width="1401" height="1202" alt="image" src="https://github.com/user-attachments/assets/a45804f6-2cbe-4ba9-ab74-296a7464ac9a" />

---

### 1. 🎯 Decision Variables Block
- **Room Rate:** Primary pricing decision ($150 vs. $200)
- **Overbooking Buffer:** Set at 5 or 10 rooms to absorb cancellations
- User-modifiable to simulate different strategies


---

### 2. 🎲 Stochastic Inputs Block
- **Online Bookings** – Normally distributed (µ ≈ 35, symmetrical variability)
- **Cancellation Rate** – Beta distribution (α=2, β=5; skewed right)
- **Walk-In Demand** – Empirical distribution (based on historical ranges)
- **Misc. Costs** – Uniform distribution ($20–$100)

Each variable is simulated 1,000 times to capture demand uncertainty.


---

### 3. 🧱 Fixed Inputs Block
- **Housekeeping Cost per Room:** $40
- **Cancellation Penalty:** $60 per guest
- **Total Rooms:** 70 (single room type modeled)


---

### 4. 🧮 Calculated Metrics Block
- **Revenue:** Based on bookings × selected rate
- **Costs:** Sum of housekeeping, miscellaneous, and cancellation compensation
- **Profit:** Revenue – Total Costs
- **Occupancy Status:** Tracks full or underutilized days

---

### 5. 📊 Final Output Block
- Aggregated results across 1,000 simulations:
  - Average Profit
  - Profit Range
  - Probability of Reaching Target
  - Sold-Out Frequency

📸 *Screenshot Tip:* Output table showing summary stats for each strategy

---

## 📘 Advanced Features

### ✅ Scenario Analysis
- Evaluates profit under base, best, and worst-case booking conditions
- Helps compare strategy robustness across market states

📸 *Screenshot Tip:* Table or bar chart comparing scenarios ($150 vs. $200)

---

### ✅ Sensitivity Analysis
- Quantifies how input changes impact profit
- Online bookings and cancellation rate show highest sensitivity

📸 *Screenshot Tip:* Line chart or tornado chart showing variable impact

---

### ✅ Risk Analysis
- Simulated profit bands for both rates
- $200 rate shows broader upper tail and higher mean
- $150 has tighter clustering but lower ceiling

📸 *Screenshot Tip:* Histogram or box plot for profit distributions

---

### ✅ Convergence Analysis
- Tracks stability of outputs across 1,000 runs
- Confirms statistical reliability of results

📸 *Screenshot Tip:* Convergence line chart for mean profit across iterations

---

## 🔍 Key Findings

- **$200 rate** yields higher average profit ($5,834 vs. $4,742)
- 93.3% of simulations for $200 strategy exceed $4,500 profit
- Online bookings and cancellations are the most influential variables
- Profit stabilizes after ~200 iterations – model is robust
- Strong business case to adopt $200 rate with cancellation control

---

## 📈 Final Recommendations

1. **Adopt $200 Room Rate** – Consistent performance and strong upside
2. **Keep Overbooking Buffer at 5** – Balanced risk/occupancy strategy
3. **Monitor Booking Demand** – Forecast trends to optimize inputs
4. **Control Cancellations** – Consider deposits or stricter refund terms
5. **Update Simulation Quarterly** – Refresh with seasonal or historical shifts

---

## 📁 Files Included

- `Report A2.xlsx`: Excel simulation model (with all formulas and assumptions)
- `Report A2.pptx`: Executive summary slide deck for stakeholder presentation

---

## 🛠 Tools & Technologies

- Microsoft Excel (Monte Carlo Simulation, data tables, formulas)
- Microsoft PowerPoint (Presentation & Reporting)
- Statistical Distributions (Normal, Beta, Uniform, Empirical)

---

## 👤 Author

**Swas Airee**  
Business Analyst | Decision Modelling | Revenue Optimization  


---

*This project was completed as part of an academic coursework assignment.*
