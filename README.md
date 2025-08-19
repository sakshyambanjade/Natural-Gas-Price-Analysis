# Natural-Gas-Price-Analysis

---

````markdown
# 📊 Natural Gas Price Analysis (2020–2024)

## 📂 Dataset
We used a manually compiled dataset of monthly natural gas prices from October 2020 to September 2024.  
The dataset contains two columns:  

- `Dates` → Last day of each month (e.g., `2020-10-31`)  
- `Prices` → Natural gas price for that month  

Example:

| Dates      | Prices |
|------------|--------|
| 2020-10-31 | 10.1   |
| 2020-11-30 | 10.3   |
| 2020-12-31 | 11.0   |
| ...        | ...    |
| 2024-09-30 | 11.8   |

---

## 🛠️ What We Did
This project aims to analyze and visualize natural gas price patterns and the factors influencing them:

1. 📈 Time Series Visualization  
   - Plotted natural gas prices from 2020–2024.  
   - Observed seasonal cycles (higher in winter, lower in summer).  
   - Identified an overall upward trend with fluctuations.

2. 🔎 Seasonal Decomposition  
   - Used `statsmodels` seasonal decomposition to break prices into:  
     - Trend (long-term direction)  
     - Seasonality (repeating cycles by month)  
     - Residuals (random noise)  

3. 📅 Monthly Seasonality Analysis  
   - Grouped data by month to find average seasonal effects.  
   - Confirmed winter peaks (Nov–Feb) and summer dips (May–Aug).

4. 🗓️ Event Impact Overlay  
   - Annotated the price chart with key global and policy events:  
     - 🔶 Oct 2021: Global energy crisis begins  
     - 🔴 Feb 2022: Russia invades Ukraine → LNG demand surge  
     - 🔵 Dec 2022: EU gas price cap announced  
     - 🟢 Jul 2023: U.S. supply glut lowers summer prices  
     - 🟣 Jan 2024: U.S. LNG export pause  
     - 🟤 Jun 2024: Warm winter & storage glut keeps prices low  

   - Events were plotted directly inside the chart box for clarity.

---

## 📊 Technologies Used
- Python  
- `pandas` → data wrangling  
- `matplotlib` → visualization  
- `statsmodels` → seasonal decomposition  

---

## 🚀 How to Run
1. Clone this repo:  
   ```bash
   git clone https://github.com/yourusername/natural-gas-analysis.git
   cd natural-gas-analysis
````

2. Install dependencies:

   ```bash
   pip install pandas matplotlib statsmodels
   ```

3. Run the analysis script:

   ```bash
   python analysis.py
   ```

This will generate:

* A line chart of natural gas prices
* A seasonal decomposition plot
* A monthly average seasonality chart
* A timeline with key global events marked inside the chart

---

## 📌 Key Insights

* Natural gas prices follow strong seasonal cycles.
* Prices spike in winter (heating demand) and dip in summer.
* Major geopolitical events (Ukraine war, EU policy, U.S. LNG pause) align with observed price shifts.
* Recent (2024) lows were due to mild winters and high storage inventories.

---

## 📜 License

Open-source for educational and analytical purposes.

---

```

---

👉 Do you want me to also include a ready-to-use folder structure (`/data`, `/notebooks`, `/scripts`) so your GitHub repo looks polished and professional?
```
