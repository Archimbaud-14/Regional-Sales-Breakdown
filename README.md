# 🎮 Regional Sales Breakdown and Genre Trends in Video Game Market

> Analyze global video game sales to understand platform, genre and publisher dominance across NA, EU and JP markets.

![Python](https://img.shields.io/badge/Python-3.13-3776AB?logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-2.3-150458?logo=pandas&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![Level](https://img.shields.io/badge/Level-Intermediate-orange)

---

## 📋 Table of Contents
- [About](#-about-the-project) · [Dataset](#-dataset-overview) · [Structure](#-project-structure) · [Getting Started](#-getting-started)
- [Key Findings](#-key-findings) · [Visualizations](#-visualizations) · [Insights](#-4-regional-market-insights) · [Bonus](#-bonus-features)

---

## 📖 About the Project
Analysis of **16,327 video games** across 12 genres, 31 platforms and 578 publishers. Compares NA vs EU vs JP market preferences and tracks industry evolution from 1980–2016.

---

## 📊 Dataset Overview

| Property | Detail |
|----------|--------|
| **File** | `vgsales.csv` |
| **Records** | 16,598 → 16,327 (after cleaning) |
| **Columns** | 11 features |
| **Year Range** | 1980–2016 |
| **Cleaning** | Dropped 271 NaN Year rows; filled 58 Publisher NaN |

### Columns
`Rank` · `Name` · `Platform` · `Year` · `Genre` · `Publisher` · `NA_Sales` · `EU_Sales` · `JP_Sales` · `Other_Sales` · `Global_Sales`

---

## 📁 Project Structure
```
Regional Sales Breakdown and Genre Trends in Video Game Market/
├── 📓 VideoGame_Regional_Analysis.ipynb
├── 📝 note.md
├── 📄 README.md
├── 📊 vgsales.csv
├── 🖼️ chart1_stacked_regional_genre.png    # Stacked bar: Regional sales by genre
├── 🖼️ chart2_yearly_trend.png              # Line: Industry trend 1980–2016
├── 🖼️ chart3_top10_publishers.png          # Bar: Top 10 publishers
└── 🖼️ chart4_top5_genres_regional.png      # ⭐ Grouped bar: Top 5 genres × regions
```

---

## 🚀 Getting Started
```bash
cd "Regional Sales Breakdown and Genre Trends in Video Game Market"
pip install pandas matplotlib seaborn jupyter
jupyter notebook VideoGame_Regional_Analysis.ipynb
```

---

## 🔍 Key Findings

| Metric | Value |
|--------|-------|
| 💰 **Global Sales** | ~$8.8B |
| 🇺🇸 **NA Share** | ~49% |
| 🇪🇺 **EU Share** | ~27% |
| 🇯🇵 **JP Share** | ~14% |
| 🏆 **Top Genre** | Action ($1.75B) |
| 👑 **Top Publisher** | Nintendo ($1.78B) |
| 🎮 **Top Platform** | PS2 ($1.25B) |
| 📅 **Peak Year** | 2008 ($678M) |

---

## 📈 Visualizations

| # | Chart | Description |
|---|-------|-------------|
| 1 | Stacked Bar | Regional sales (NA+EU+JP) by genre |
| 2 | Line Chart | Industry sales trend 1980–2016 with peak annotation |
| 3 | Horizontal Bar | Top 10 publishers by global sales |
| 4 | ⭐ Grouped Bar | Top 5 genres compared across NA, EU, JP |

---

## 💡 4 Regional Market Insights

1. **🇺🇸 NA Dominates (49%) but 🇯🇵 JP Is Unique** — Japan prefers RPGs over Action
2. **⚔️ Action Is Universal (Except Japan)** — #1 in NA & EU, #3 in JP where RPGs rule
3. **👑 Nintendo = Global King** — $1.78B, nearly 2× the nearest competitor
4. **📉 Industry Peaked in 2008** — Physical sales declined; market shifted to digital

---

## ⭐ Bonus Features
- **Decade Analysis**: Highest avg sales per game by decade (80s/90s/2000s/2010s)
- **Top 5 Genres Grouped Bar**: Side-by-side NA vs EU vs JP comparison

---

## ✅ Deliverables
- [x] Jupyter notebook with full regional analysis
- [x] `note.md` with methodology and insights
- [x] Stacked bar chart of regional sales by genre
- [x] Yearly trend line chart
- [x] Top 10 publishers bar chart
- [x] 4 regional market insights
- [x] ⭐ Decade avg sales analysis
- [x] ⭐ Grouped bar: top 5 genres across regions

---
<p align="center"><i>Built with 🐍 Python | 📊 pandas | 🎨 matplotlib + seaborn</i></p>
