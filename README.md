# NYC Airbnb Exploratory Data Analysis (EDA)

## 📋 Project Overview

Comprehensive analysis of **49,000+ NYC Airbnb listings**, uncovering pricing trends, neighborhood preferences, room type distributions, and market insights.

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
| **Source** | [Kaggle — NYC Airbnb Open Data](https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data) |
| **Size** | ~49,895 listings |
| **Features** | 16 columns |
| **Time period** | 2019 NYC listings |

## 📁 Project Structure

```
NYC-Airbnb-EDA/
├── README.md                       # 📄 This file
├── requirements.txt                # 📦 Dependencies
├── data/
│   ├── raw/
│   │   └── AB_NYC_2019.csv         # 📥 Original dataset
│   └── cleaned/
│       └── airbnb_cleaned.csv      # ✅ Cleaned dataset
├── notebooks/
│   └── EDA_NYC_Airbnb.ipynb        # 📓 Analysis notebook
└── visualizations/                 # 📊
    ├── 01_missing_values.png
    ├── 02_price_distribution.png
    ├── 03_room_neighbourhood.png
    ├── 04_correlation_heatmap.png
    └── 05_reviews_availability.png
```

## 🛠️ Tech Stack

| Package | Purpose | Version |
|---------|---------|---------|
| `pandas` | Data analysis | 2.1.4 |
| `numpy` | Math operations | 1.24.3 |
| `matplotlib` | Plotting | 3.8.2 |
| `seaborn` | Statistical visualization | 0.13.2 |
| `jupyter` | Notebook environment | 1.0.0 |

## 🚀 Getting Started

```bash
# Clone the repo
git clone https://github.com/<your-username>/NYC-Airbnb-EDA.git
cd NYC-Airbnb-EDA

# Install dependencies
pip install -r requirements.txt

# Launch the notebook
jupyter notebook notebooks/EDA_NYC_Airbnb.ipynb
```

## 📈 Key Findings

| # | Category | Finding |
|---|----------|---------|
| 1️⃣ | **Market** | 49K+ listings across 37K+ hosts |
| 2️⃣ | **Price** | Average price $152, median $106 |
| 3️⃣ | **Room Types** | Entire homes/apts 52%, Private rooms 45% |
| 4️⃣ | **Location** | Brooklyn 43% of listings, Manhattan 19% |
| 5️⃣ | **Reviews** | Weak correlation between price and review activity |

## 📊 Visualizations

1. **Missing Values Analysis** — heatmap of null/missing data across features
2. **Price Distributions** — histograms and box plots (raw and log-transformed)
3. **Neighborhood & Room Type** — bar charts comparing boroughs and room categories
4. **Correlation Heatmap** — relationships between numeric features
5. **Reviews & Availability** — scatter plots exploring review counts vs. availability

## 🎓 Skills Demonstrated

- ✅ Data cleaning (missing values, outliers, duplicates)
- ✅ Structured EDA workflow (16 modular notebook cells)
- ✅ Statistical analysis & correlation studies
- ✅ Publication-quality visualizations
- ✅ Professional GitHub workflow & documentation
- ✅ Data storytelling

## 💾 Outputs Generated

- ✅ `airbnb_cleaned.csv` — cleaned dataset
- ✅ 5 PNG visualizations (300 DPI)
- ✅ `summary_statistics.csv`
- ✅ Key findings report

## 📈 Business Insights

**For Hosts**
- Target Manhattan or Brooklyn for higher-demand markets
- Listing an entire home/apt commands roughly 2x the pricing power of a private room
- Availability drives bookings more than aggressively high prices

**For Travelers**
- Queens offers up to ~50% price savings compared to Manhattan
- More reviews doesn't necessarily mean better value — review count and price show little correlation

## 🗂️ Project Workflow

| Phase | Focus | Notebook Cells |
|-------|-------|-----------------|
| 1 | Data Cleaning | Cells 1–4 |
| 2 | EDA & Statistical Analysis | Cells 5–9 |
| 3 | Visualizations & Documentation | 5 charts, README, GitHub |

## 📜 License

This project is licensed under the [MIT License](LICENSE).
