# NYC Airbnb Exploratory Data Analysis (EDA)

## 📋 Project Overview

Comprehensive analysis of **49,000+ NYC Airbnb listings** uncovering pricing trends, neighborhood preferences, room type distributions, and market insights.

## 🎯 Objectives

- 🔧 Data cleaning & preprocessing
- 📊 Descriptive statistics & distributions
- 🗺️ Neighborhood & room type analysis
- 📈 Price trend identification
- 🎨 Publication-quality visualizations
- 💡 Actionable business insights

## 📊 Dataset

| Info | Details |
|------|---------|
| **Source** | [Kaggle NYC Airbnb](https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data) |
| **Size** | ~49,895 listings |
| **Features** | 16 columns |
| **Time** | 2019 NYC listings |

## 📁 Project Structure

NYC-Airbnb-EDA/
├── README.md # 📄 This file
├── requirements.txt # 📦 Dependencies
├── data/
│ ├── raw/AB_NYC_2019.csv # 📥 Original dataset
│ └── cleaned/
├── notebooks/
│ └── EDA_NYC_Airbnb.ipynb # 📓 Analysis notebook
└── visualizations/ # 📊
├── 01_missing_values.png
├── 02_price_distribution.png
├── 03_room_neighbourhood.png
├── 04_correlation_heatmap.png
└── 05_reviews_availability.png


## 🛠️ Tech Stack

| Package | Purpose | Version |
|---------|---------|---------|
| `pandas` | Data analysis | 2.1.4 |
| `numpy` | Math operations | 1.24.3 |
| `matplotlib` | Plotting | 3.8.2 |
| `seaborn` | Stats viz | 0.13.2 |
| `jupyter` | Notebook | 1.0.0 |

## 🚀 Quick Start

```bash
git clone <your-repo-url>
cd NYC-Airbnb-EDA
pip install -r requirements.txt

# Download dataset from:
# https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data
# Place in: data/raw/AB_NYC_2019.csv

jupyter notebook notebooks/EDA_NYC_Airbnb.ipynb
📈 Key Findings

1️⃣ MARKET: 49K+ listings, 37K+ hosts
2️⃣ PRICE: $152 avg ($106 median)
3️⃣ ROOMS: Entire homes 52%, Private 45%
4️⃣ LOCATION: Brooklyn 43%, Manhattan 19%
5️⃣ INSIGHTS: Weak price-review correlation
📊 Visualizations (5 Charts)
Missing Values Analysis

Price Distributions (histograms + box plots)

Neighborhood & Room Type (bar charts)

Correlation Heatmap

Reviews & Availability (scatter plots)

🎓 Skills Demonstrated
text
✅ Data cleaning (missing, outliers, duplicates)
✅ EDA workflow (16 modular cells)
✅ Statistical analysis & correlations
✅ Publication-quality visualizations
✅ Professional GitHub workflows
✅ Data storytelling
💾 Outputs Generated
text
✅ airbnb_cleaned.csv
✅ 5 PNG visualizations (300 DPI)
✅ summary_statistics.csv
✅ Key findings report
📈 Business Insights
For Hosts:

Target Manhattan/Brooklyn

Entire homes = 2x pricing power

Availability > high prices

For Travelers:

Queens = 50% price savings

Reviews ≠ price quality

🎯 3-Day Timeline
Day	Focus	Deliverables
1	Data Cleaning	Clean dataset, Cell 1-4
2	EDA & Analysis	Statistics, Cell 5-9
3	Visuals & Docs	5 charts, README, GitHub
👤 Author
Your Name
[Portfolio] | [LinkedIn] | [GitHub]

📜 License
MIT License
