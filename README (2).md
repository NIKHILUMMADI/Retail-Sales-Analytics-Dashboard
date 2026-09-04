# 📊 Online Retail Dataset — Customer Behavior & Sales Analysis

Analysis of large-scale transactional data from a UK-based online retailer to uncover customer purchasing behavior, sales trends, and support data-driven business decisions.

---

## 📁 Dataset

| | |
|---|---|
| **Source** | [UCI Machine Learning Repository – Online Retail Dataset](https://archive.ics.uci.edu/dataset/352/online+retail) |
| **Original size** | 541,909 transactions |
| **Cleaned size** | 392,692 transactions |

*Cleaning removed missing CustomerIDs, cancelled orders, and invalid values.*

---

## 🔍 Approach

1. **Data Cleaning** — Removed missing CustomerIDs, cancelled orders, negative/zero values, and duplicates
2. **Feature Engineering** — Created `TotalPrice`, `Month`, `DayOfWeek`, and `Hour` fields for time-based analysis
3. **Customer Segmentation (RFM Analysis)** — Scored customers on Recency, Frequency, and Monetary value, then segmented into behavioral tiers
4. **Visualization** — Built charts surfacing sales trends, top products, revenue by country, and purchase-time patterns

---

## 📈 Key Findings

| Metric | Value |
|---|---|
| 💰 Total Revenue | **£8,887,208.89** |
| 👥 Total Unique Customers | **4,338** |
| 🛒 Average Order Value | **£479.56** |
| ⭐ Champions Segment | **11.3%** of customers |

**Customer Segments (RFM):**

| Segment | Customers |
|---|---|
| At Risk | 1,504 |
| Potential Loyalist | 1,130 |
| Loyal Customers | 1,034 |
| Champions | 489 |
| Lost | 181 |

---

## 🖼️ Visualizations

| Chart | Description |
|---|---|
| `monthly_sales_trend.png` | Sales trend over time |
| `top_products.png` | Top 10 best-selling products |
| `top_countries.png` | Top 10 countries by revenue |
| `customer_segments.png` | Customer distribution across RFM segments |
| `purchase_heatmap.png` | Purchase activity by day of week and hour |

---

## 🛠️ Tech Stack

`Python` · `Pandas` · `NumPy` · `Matplotlib` · `Seaborn` · `Jupyter Notebook`

---

## 📂 Files

- **`Dataanalysisproject.ipynb`** — Full analysis notebook (code + outputs)
- **`*.png`** — Exported chart images
