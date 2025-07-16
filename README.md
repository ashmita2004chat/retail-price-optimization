# 🧠 Retail Price Optimization Project

Welcome to the **Retail Price Optimization** project, where we act as a **Pricing Analyst** or **Product Manager** with the goal of identifying optimal price points for a product that balance:

- ✅ Profitability  
- ✅ Customer demand  
- ✅ Conversion potential

This data analytics project uses **regression analysis**, **segmentation**, and **profit simulations** to arrive at actionable pricing strategies.

---

## 📌 Objective

To model and analyze how customers respond to price changes and provide strategic pricing recommendations using:

- 📉 **Price Elasticity Modeling** (Log-Log OLS Regression)
- 🔍 **Customer Segmentation** (via KMeans Clustering)
- 🧮 **Profit Simulations** at multiple cost margins (60%, 70%, 80%)
- 📊 **Visualization Dashboards** for demand, revenue, and pricing behavior
- 📈 **Interactive HTML Report** with custom styling & floating Table of Contents

---

## 🗂️ Dataset Used

- **File:** `retail_price.csv`
- **Source:** Synthetic retail dataset adapted for elasticity analysis
- **Key Columns:**
  - `unit_price`
  - `qty` (quantity sold)
  - `total_price` / `revenue`
  - `category`
  - `month_year` / `datetime`

Newly engineered features include:
- `log_price`, `log_qty` 
- `profit_60pct`, `profit_70pct`, `profit_80pct`
- `segment` (via clustering)

---

## 🔍 Techniques & Tools

| Technique | Description |
|----------|-------------|
| **Log-Log Regression** | To model demand elasticity |
| **Segment-Level Regression** | To analyze elasticity by product category |
| **Profit Curve Simulation** | To find profit-maximizing price points |
| **Customer Segmentation** | KMeans clustering based on sales and pricing behavior |
| **Visualizations** | Seaborn, Matplotlib, Heatmaps, and Trend Charts |
| **HTML Report Styling** | Custom CSS for UI polish, floating TOC |

---

## 📂 Project Files

| File | Description |
|------|-------------|
| `retailprice.ipynb` | Main Jupyter notebook with analysis, models, and visualizations |
| `retailprice.html` | Interactive, styled version of notebook with Table of Contents |
| `retail_price.csv` | Cleaned dataset used for modeling |


---

## 📊 Key Outputs

- 📉 **Elasticity estimates** by category with p-values and R²
- 📈 **Monthly revenue trends** and pricing shifts
- 🧮 **Profit maximization curves** for key categories
- 🔥 **Heatmap** of quantity sold by category & month
- 🎯 **Customer segmentation** clusters and profiling
- 💰 **Revenue breakdown by segment**

---

## 🌐 Live Preview (HTML Report)

> You can open the polished report offline in your browser:
>
> 🔗 `retailprice.html` → right-click → open in browser

Includes:
- Floating Table of Contents  
- Custom gradient background  
- Clear headers, smooth scrolling, and emojis for readability 😄

---

## 🧰 Tech Stack

- **Python 3.x**
- **Jupyter Notebook**
- Libraries:
  - `pandas`, `numpy`
  - `statsmodels`
  - `matplotlib`, `seaborn`
  - `scikit-learn` (KMeans)
- **HTML/CSS** for report customization
- (Optional) Visual Studio Code for HTML design

---

## 📈 Sample Visualizations

> (Add screenshots here if uploading images folder)

- Elasticity by category bar chart
- Profit curve with optimal pricing marker
- Monthly revenue line chart
- Heatmap of quantity sold
- Cluster profiling bar plots

---

## 💡 Final Recommendations

- For **bed_bath_table**, the optimal price point was found to be approximately **X.XX** yielding maximum profit.
- Categories like **garden_tools** showed negative elasticity — lowering price improves demand and revenue.
- Segment 0 contributes over 40% of total revenue and should be prioritized in targeted pricing strategy.

---

## 🤝 Author

**Ashmita Chatterjee**  
Data Science & Analytics Enthusiast  
[GitHub Profile](https://github.com/ashmita2004chat) 


---

## ⭐ If you found this useful...

Feel free to ⭐ star this repo or use it as inspiration for your own analytics portfolio!

