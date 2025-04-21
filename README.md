# 🚚 Fleet Management & Cost Analyzer Dashboard

## 📌 Overview  
This Power BI dashboard offers a comprehensive analysis of fleet performance and transportation costs. It focuses on tracking freight revenue, fleet operating expenses, vehicle utilization, and financial impact, helping logistics or B2B companies make strategic, data-driven decisions.

The project supports What-If analysis to simulate cost fluctuations, fuel pricing, and vehicle maintenance scenarios, ensuring flexible financial planning and performance tracking.

---

## 🔍 Key Features  
- **Fleet-Wise Cost Breakdown** for efficient maintenance and operation tracking  
- **Advanced DAX Calculations** for freight revenue, cost per kilometer, vehicle profitability, and fuel impact  
- **What-If Analysis** to test various cost/revenue inputs  
- **Dynamic Filters** for driver, vehicle, and route-level analysis  
- **Utilization Metrics** including distance traveled, cost per km, and vehicle downtime  
- **KPI Cards** highlighting revenue, operating costs, fuel efficiency, and profitability  

---

## 📊 Page 1: Fleet Overview  

### 🔑 Key Insights:  
- **Vehicle Performance**: Monitor each vehicle's revenue, cost, and trips.  
- **Fuel & Maintenance Costs**: Break down expenses by type and vehicle.  
- **Operational KPIs**: Visualize active fleet count, total km traveled, and average revenue per km.

### 📈 Visualizations:  
- **Fleet KPI Summary (Card Visuals)**  
- **Revenue & Cost by Vehicle (Bar Chart)**  
- **Fuel vs Maintenance Breakdown (Donut Chart)**  
- **Monthly Activity Tracker (Line Chart)**  
  - *DAX Measure*: `MonthlyDistanceVsRevenue`

---

## 📊 Page 2: Financial Performance  

### 🔑 Key Insights:  
- **Freight Revenue Trends**  
- **Cost Structure Analysis (fixed vs variable)**  
- **Profitability by Vehicle & Driver**  

### 📈 Visualizations:  
- **Revenue & Expense Trends (Stacked Column Chart)**  
  - *DAX Measure*: `FreightRevenueVsCost`  
- **Profitability Table by Vehicle**  
  - *DAX Measure*: `VehicleProfitability`  
- **Driver Performance Scorecard**  
  - *DAX Measure*: `DriverEfficiencyScore`  
- **Cost per KM Heatmap**  
  - *DAX Measure*: `CostPerKmByVehicle`

---

## 📊 Page 3: What-If Analysis & Simulator  

### 🔑 Key Insights:  
- **Scenario Planning for Fuel, Repair, and Revenue Changes**  
- **Instant Impact on Net Profitability**  
- **Optimize Route/Vehicle Mix Based on Simulation Results**  

### 📈 Visualizations:  
- **Fuel Price Impact (Line Chart)**  
  - *DAX Measure*: `FuelImpactSimulation`  
- **Cost & Revenue Sensitivity (Clustered Column Chart)**  
  - *DAX Measure*: `ScenarioCostRevenueChange`  
- **Simulation Table: Net Income by Scenario**  
  - *DAX Measure*: `SimulatedFleetProfit`  

