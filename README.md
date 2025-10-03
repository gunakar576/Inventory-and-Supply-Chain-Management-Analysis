# Inventory-and-Supply-Chain-Management-Analysis


# 📊 Supply Chain & Inventory Dashboard

This project presents a **Supply Chain & Inventory Analysis Dashboard** built using **SQL & Power BI**.  
It tracks **warehouse utilization, transportation costs, sales growth, lead times, backorders, and inventory levels** to identify inefficiencies and support data-driven decisions.  

---

## 🔹 Key Performance Indicators (KPIs)

- **Warehouse Utilization:** **34.08%** → Warehouses are operating at only one-third of their total capacity.  
- **Days Sales of Inventory (DSI):** **15.56 days** → On average, inventory is sold within ~16 days.  
- **Inventory Turnover:** **23.47** → Inventory is turned over 23 times per year, indicating strong movement.  

---

## 🔹 Transportation Cost by Region & Category (Updated)

### North Region
- Accessories: **0.57M**  
- Clothing: **0.57M**  
- Electronics: **0.63M**  
- Furniture: **0.72M** (highest in North)  

### West Region
- Accessories: **0.45M** (lowest overall)  
- Clothing: **0.57M**  
- Electronics: **0.67M**  
- Furniture: **0.75M** (highest overall)  

### East Region
- Accessories: **0.54M**  
- Clothing: **0.59M**  
- Electronics: **0.61M** (highest in East)  
- Furniture: **0.53M**  

### South Region
- Accessories: **0.41M** (lowest in South)  
- Clothing: **0.59M** (highest in South)  
- Electronics: **0.53M**  
- Furniture: **0.53M**  

**Insight:**  
- **West Region – Furniture (0.75M)** has the **highest transportation cost overall**.  
- **South Region – Accessories (0.41M)** has the **lowest transportation cost overall**.  
- Furniture consistently drives the **highest transportation expenses** across regions.  

---

## 🔹 Units Sold by Year

- **2020:** ~55K units  
- **2021:** ~10K units (drop)  
- **2022:** **182K units** (sharp rise)  
- **2023:** ~195K units  
- **2024:** **198K units (peak)** → **260% growth from 2020 to 2024**  

---

## 🔹 Average Lead Time by Category

- **Accessories:** 16.60 days (highest)  
- **Electronics:** 15.68 days  
- **Furniture:** 15.50 days  
- **Clothing:** 15.29 days (lowest)  

---

## 🔹 Backorders by Order Status

- **Fulfilled Orders:** 838 backorders  
- **Pending Orders:** 248 backorders  
- **Cancelled Orders:** 114 backorders  

👉 **77% of all backorders (838/1200)** occur in fulfilled orders → signals supply chain inefficiency.  

---

## 🔹 Inventory Level by Category & Region (Updated)

### Clothing
- East: **185K**  
- North: **202K**  
- South: **232K** (highest in Clothing)  
- West: **201K**  

### Electronics
- East: **168K**  
- North: **228K**  
- South: **171K**  
- West: **234K** (highest in Electronics)  

### Furniture
- East: **167K**  
- North: **213K** (highest in Furniture)  
- South: **148K** (lowest overall)  
- West: **206K**  

### Accessories
- East: **173K**  
- North: **181K** (highest in Accessories)  
- South: **161K**  
- West: **166K**  

**Insight:**  
- **Clothing & Electronics dominate inventory (~200K+ each region)** → risk of overstocking.  
- **Furniture** shows **regional imbalance (148K–213K)**.  
- **Accessories** remain the lowest (161K–181K), more balanced across regions.  

---

## 🔹 Business Insights

- Warehouses are **underutilized (34%)**, leaving room for optimization.  
- **Transportation cost peaks in West (0.75M)**, lowest in South Accessories (0.41M).  
- Sales recovered massively after 2021 → **260% growth (55K → 198K units, 2020–2024)**.  
- **Accessories** face the longest lead times (16.6 days) → supplier reliability needs improvement.  
- **Backorders highest in fulfilled orders (77%)** → poor inventory planning.  
- **Clothing & Electronics (~200K+ each)** dominate stock → risk of excess storage costs.  

---

## 🚀 Tools & Tech Used
- **SQL** → Data extraction & transformation.  
- **Power BI** → Dashboard development & visualization.  

---

