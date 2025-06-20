# Tableau-Dashboard-on-Parking-Lot-Data
Parking Usage Analysis with Tableau &amp; Python - where I analyzed a large-scale parking transaction dataset (~5 million rows) to uncover trends, forecast usage, and build interactive dashboards.

## Dataset Summary
- ~5 million rows of parking transaction data
- Included timestamps, card numbers, access groups, and lot locations

## Tools & Platforms
- **Python**: Data cleaning, transformation, and CSV generation (Google Colab)
- **Tableau**: Interactive dashboarding and forecasting (Mac Desktop)

## Data Cleaning & Processing (Python)
- Removed ~9.5% rows with invalid `EffectiveGroupNumber = -1`
- Filled missing entry/exit times based on instructions
- Parsed datetime into year, month, day, week
- Calculated parking duration (in hours, rounded to 2 decimals)


## Peak Usage & Forecasting
- Calculated simultaneous usage per lot and identified peak hours/day
- Due to memory limitations, restricted peak usage analysis to 2024 data
- Forecasted usage for the remaining months of 2025 using trends from April 2024–April 2025

## Tableau Dashboards
- Visualized:
  - Peak parking times (7–8am and 11am–1pm)
  - Seasonal usage (highest in October; lowest May–July)
  - Access group & lot-level usage patterns
- Dashboards reveal:
  - Lot 56 = longest parked durations; Lot 60 = shortest
  - Access Group 81 = highest number of card assignments

## Contextual Insights (Public Info)
  - Classes begin around 7:30am, supporting peak usage patterns
  - October events correlate with highest parking usage
  - May–August = summer semester → low usage trends

## Key Insights
- **Peak hours**: 7–8am and 11am–1pm weekdays
- **Busiest month**: October (2021–2024)
- **Lowest usage**: May–July (summer semester)
- **Weekend peak**: 7–8am
- **Group 81**: Most active access group
- **Lot 56**: Longest average parking duration

---
