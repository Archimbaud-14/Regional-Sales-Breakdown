# 📝 Note: Regional Sales Breakdown and Genre Trends in Video Game Market

## Methodology

### 1. Data Loading & Cleaning
- Loaded `vgsales.csv`: **16,598 games**, 11 columns
- **Dropped 271 rows** with missing `Year` values
- **Filled 58 NaN** in `Publisher` with "Unknown"
- Clean dataset: **16,327 games**

### 2. Multi-Dimensional Aggregation
- Global sales by **Genre** (12 genres), **Platform** (top 10), **Publisher** (top 10)
- Regional sales share calculated as % of Global per genre

### 3. Regional Comparison
- NA, EU, JP sales compared per genre
- Most popular genre identified per region
- Regional percentage breakdown for each genre

### 4. Yearly Trend Analysis
- Industry-wide sales plotted from 1980 to 2016
- Peak year identified with regional breakdown

### 5. Bonus Features
- **Decade analysis**: Which decade (80s, 90s, 2000s, 2010s) had highest avg sales per game
- **Grouped bar**: Top 5 genres compared across NA, EU, JP

---

## Key Findings

| Metric | Value |
|--------|-------|
| Total Games | 16,327 |
| Global Sales | ~$8.8B |
| NA Share | ~49% |
| EU Share | ~27% |
| JP Share | ~14% |
| Top Genre | Action ($1.75B) |
| Top Publisher | Nintendo ($1.78B) |
| Top Platform | PS2 ($1.25B) |
| Best-Selling Game | Wii Sports (82.7M) |
| Peak Year | 2008 ($678M) |

### Regional Preferences
- **NA & EU**: Action > Sports > Shooter
- **Japan**: Role-Playing > Action > Platform (uniquely different!)
- Role-Playing has 33% JP share vs only 7% in most other genres

---

## 💡 4 Regional Market Insights

### 1. NA Dominates but JP Has Unique Tastes
NA = 49% of global sales. Japan uniquely prefers RPGs over Action/Sports.

### 2. Action Is Universal (Except Japan)
Action is #1 in NA ($877M) and EU ($525M), but #3 in Japan where RPGs dominate.

### 3. Nintendo Is the Global King
$1.78B — nearly 2x the nearest competitor. Cross-regional appeal through iconic franchises.

### 4. Industry Peaked in 2008, Physical Sales Declining
Peak at $678M driven by Wii/DS era. Decline reflects shift to digital/mobile, not shrinking market.

---

## Technical Stack
- **Python 3.13**: pandas, matplotlib, seaborn, numpy
- **Dataset**: `vgsales.csv` (16,598 → 16,327 after cleaning)
- **Source**: [Kaggle — Video Game Sales](https://www.kaggle.com/datasets/gregorut/videogamesales)

*Analysis completed April 2026*
