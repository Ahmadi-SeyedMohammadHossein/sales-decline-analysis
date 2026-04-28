# 📉 Sales Decline Analysis — End-to-End Data Project

> **Tools:** Python · Power BI  
> **Domain:** Retail / Sales Analytics  
> **Type:** End-to-End Personal Portfolio Project

---

## 🎯 Business Problem

A retail business is experiencing consistent sales decline throughout 2024.
This project investigates the root causes across regions, customer segments, and sales channels
to provide data-driven recommendations for recovery.

**Core business questions:**
- Which regions and customer types contribute most to the decline?
- Are returning or new customers driving the drop?
- How do online and offline channels compare during the decline period?

---

## 📌 Key Results

| Metric | Value |
|--------|-------|
| 💰 Total Sales (2024) | $70,400 |
| 🛒 Number of Orders | 354 |
| 📦 Average Order Value | $198.88 |
| 📉 Trend | Consistent decline from ~$8K (Mar) → ~$4K (Dec) |
| 🌍 Dominant Region | East |
| 👥 Highest Churn Segment | Returning customers |

---

## 🔍 Key Insights

### 1 · Consistent Downward Trend Throughout 2024
Sales dropped from approximately **$8,000 in March 2024** to **$4,000 by December 2024**
— a decline of nearly **50% within one year**. The trend shows no recovery period,
indicating a structural issue rather than seasonal fluctuation.

### 2 · Returning Customers Drive the Decline
Returning customers generate higher total sales than new customers (~$40K vs ~$30K),
but their declining loyalty is the core problem.
New customer acquisition is not compensating for the loss of returning customers.

### 3 · East Region Dominates — But Also Declines
The East region accounts for the largest share of sales (~$70K+ when all regions combined),
making it both the most important and most critical region to address.

### 4 · Offline Channel Underperforms Online
Offline sales show weaker performance compared to Online.
This suggests operational inefficiencies or changing customer behaviour
toward digital purchasing.

### 5 · Product Categories
Three product categories — **Electronics, Clothing, Home** — contribute roughly equally,
meaning the decline is not product-specific but systemic across all categories.

> 💡 **Business Recommendation:** Launch a retention campaign targeting returning customers
> in the East region. Shift marketing budget toward online channels and investigate
> why offline sales are underperforming.

---

## 🛠️ Tools & Technologies

| Layer | Tools Used |
|-------|-----------|
| Data Cleaning & EDA | Python · Pandas · NumPy · Matplotlib · Seaborn |
| Dashboard & KPIs | Power BI |
| Data Preparation | Jupyter Notebook · Excel |

---

## 📁 Project Structure

```
sales-decline-analysis/
│
├── data/
│   ├── sales_decline_dataset.csv        # Raw dataset
│   └── sales_cleaned_for_powerbi.csv    # Cleaned & preprocessed data
│
├── notebooks/
│   └── sales_analysis.ipynb             # EDA, feature engineering, visualizations
│
├── media/
│   ├── dashboard_preview.png            # Power BI dashboard screenshot
│   └── python_powerbi_sales_analysis_demo.mp4  # Dashboard walkthrough
│
└── README.md
```

---

## 📊 Dashboard Preview

![Sales Decline Analysis Dashboard](./media/Sales%20Decline%20Analysis%20Dashboard.png)
> 🎬 [Watch Dashboard Demo](./media/python_powerbi_sales_analysis_demo.mp4)

**Dashboard includes:**
- KPI Cards: Total Sales · Average Order Value · Number of Orders
- Monthly Sales Trend (line chart — full 2024)
- Sales by Customer Type (Returning vs New)
- Sales by Region (East · North · South · West)
- Sales by Channel (Online vs Offline)
- Interactive slicers: Region · Year-Month · Channel

---

## 🔄 Analysis Workflow

```
Raw Data → Data Cleaning (Python) → EDA & Visualizations → 
Feature Engineering → Export to Power BI → Interactive Dashboard
```

**Python pipeline steps:**
1. Data loading and inspection (`df.info()`, `df.describe()`)
2. Null value handling and type conversion
3. Feature engineering: month extraction, customer segmentation
4. EDA: trend analysis, regional breakdown, channel comparison
5. Export cleaned data for Power BI

---

## 📂 Dataset

| Field | Detail |
|-------|--------|
| Period | 2024 (full year) |
| Features | order_date · product_category · sales_amount · quantity · customer_type · region · channel |
| Segments | 4 Regions · 2 Customer Types · 2 Channels · 3 Product Categories |

---

## 🚀 How to Run

```bash
git clone https://github.com/Ahmadi-SeyedMohammadHossein/sales-decline-analysis
cd sales-decline-analysis
jupyter notebook notebooks/sales_analysis.ipynb
```

**Power BI Dashboard:**
- Open any `.pbix` file in Power BI Desktop (free)

---

## 👤 Author

**Mohammad Hossein Ahmadi** — Data Analyst | Frankfurt am Main, Deutschland  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?logo=linkedin&logoColor=white)](https://linkedin.com/in/seyed-mohammad-hossein-ahmadi)
[![GitHub](https://img.shields.io/badge/GitHub-Portfolio-black?logo=github)](https://github.com/Ahmadi-SeyedMohammadHossein)
[![Email](https://img.shields.io/badge/Email-Contact-red?logo=microsoft-outlook&logoColor=white)](mailto:s.m.ahmadi@outlook.com)
