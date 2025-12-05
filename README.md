# HDB Resale Flat Market Analysis (Power BI Dashboard)

This project analyzes Singapore's HDB resale market using publicly available transaction data.
The goal is to uncover trends in resale pricing, transaction volume, buyer behavior, and the relationship between key housing attributes such as flat type, size, town, model, and remaining lease.


## Business Questions Addressed

This dashboard was designed to answer:

1. How have HDB resale prices changed year over year?
2. Which flat types are most frequently sold and which are most expensive?
3. How do resale prices vary by location (town)?
4. Does remaining lease impact resale price?
5. Are there seasonal trends in monthly transaction volumes or pricing?
6. How does floor size affect pricing patterns?
7. Which flat models are most in-demand and which have the highest resale value?


## Preview
<img width="1144" height="725" alt="image" src="https://github.com/user-attachments/assets/e7796d75-fde0-4e3e-9478-14ad8023376d" />
<img width="1153" height="730" alt="image" src="https://github.com/user-attachments/assets/a80ed348-11a2-47c7-9f68-a01e958391f4" />



## 🧠 Key Metrics Summary

| Metric | Value |
|--------|-------|
| **Average Resale Price** | ~$415K |
| **Total Transactions** | ~92,000 |
| **Average Remaining Lease** | ~74 years |
| **Average Property Size** | ~97.77 sqm |


### **1️ Yearly Price Trend (2017–2021)**

<img width="436" height="262" alt="image" src="https://github.com/user-attachments/assets/ed17efb0-5d3d-4dcb-ba4a-98ca7b50299e" />

- Resale prices **declined** from **2017 to 2019** (from ~$444K → ~$432K).
- Starting **2020**, prices began to **increase significantly**, reaching the **highest level in 2021 (~$490K)**.
- This shift likely reflects a tightening housing supply, changes in buyer demand, and pandemic-related behavior where buyers preferred ready-to-move-in flats over waiting for BTO construction.


### **2️ Monthly Seasonality**

<img width="509" height="255" alt="image" src="https://github.com/user-attachments/assets/29298398-2d96-4c46-b83a-937cc45ec402" />

This chart shows how the resale housing market fluctuated throughout the year in terms of both pricing and demand. Average resale prices peaked in January and February, then gradually declined and remained relatively stable mid-year before rising again in December. This year-end increase may indicate renewed buyer confidence, seasonal demand, or limited supply entering the market.

Transaction volume followed a different pattern: it started strong at around 8.2K in January but declined through May. From June to November, activity stabilized around 8K transactions before dropping to 7.3K in December. The decline at the end of the year may reflect seasonal slowdowns or affordability challenges as prices increased.

Meanwhile, total transactions begin at around 8.2K in January and decrease consistently through February to May. From June to November, transaction volume stabilizes around the 8K range. In December, transactions drop further to approximately 7.3K.



### **3️ Flat Type Distribution**

<img width="955" height="230" alt="image" src="https://github.com/user-attachments/assets/74eb9ade-8691-4954-968f-87389394d9b6" />

- **4-room flats dominate the resale market (~41% of transactions)**, indicating this size best fits the needs and affordability range of majority buyers.
- **Executive and multi-generation units** show **higher average resale prices**, driven by their significantly larger size and scarcity.
- **1-room and 2-room flats** record lower transaction counts and lower price ranges, consistent with subsidized or elderly-focused flat supply.



### **4️ Geographic Price Variation**

<img width="601" height="283" alt="image" src="https://github.com/user-attachments/assets/cfcb536a-0b0f-484c-ac13-e378a8d1d1e0" />

- The map visualization shows towns closer to the central region and transportation hubs tend to have **higher resale values**.
- Location remains a strong price driver independent of flat type or size.



### **5️ Remaining Lease vs Price**

<img width="487" height="278" alt="image" src="https://github.com/user-attachments/assets/8e3ec682-1cbb-4ec4-b30f-bacea17721e1" />

- There is a clear **positive correlation** between remaining lease and resale value.
- Prices generally remain strong until around **60–70 years of remaining lease**, after which a **visible decline** occurs, likely due to:
  - Financing restrictions,
  - Depreciation perception,
  - Limited long-term usage of older leasehold flats.

### **6️ Floor Area and Price**

<img width="955" height="359" alt="image" src="https://github.com/user-attachments/assets/d67b704d-3649-4063-8e16-1364632ad39e" />

- Larger units typically have higher prices, but the relationship is **not perfectly linear**.
- This implies that **location, model type, and lease duration** influence value beyond just size.

### **7️ Flat Model Distribution**
- Flat models such as **Type S, Premium Apartment Loft, and Maisonette** achieve the highest average prices (one above **$1M**).
- Meanwhile, Model A shows the highest number of resale transactions, indicating strong demand and wide availability in the market. Improved flats also appear frequently, though not as high as Model A, suggesting they remain a popular mid-range choice. Other models have significantly fewer transactions, likely due to limited supply, niche layouts, or smaller buyer segments.


## Tools & Techniques

- **Power BI Desktop**
- **Power Query** for data cleaning and transformation
- **DAX Measures** for analytical calculations
- Visuals: KPI Cards, Clustered Column Chart, Line Chart, Donut Chart, Scatter Plot, and Filled Map



