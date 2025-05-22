# Digital-Equity-Insights-in-Kenya

This project tackles the **digital divide** in Kenya by analyzing key indicators of **digital exclusion** at the **constituency** and **county** levels.

## 💡 Project Goal
Highlight areas most affected by digital inequality.

## 🗃️ Datasets Used

| Dataset                        | Description                                 |
|--------------------------------|---------------------------------------------|
| `kenya_internet_usage.csv`     | Internet usage rates by constituency        |
| `full_kenya_constituency_poverty_rates.csv` | Poverty levels by constituency        |
| `electricity_access.csv`       | Electricity availability by county          |
| `constituencies.geojson`       | Constituency boundaries for Kenya           |

## 📈 Features & Methods

- **Data Cleaning & Normalization**: Resolved naming inconsistencies in county and constituency names.
- **Feature Engineering**: Computed a **Digital Exclusion Score** from:
  - Low internet access
  - High poverty rates
  - Low electricity availability
- **Data Visualization**:
  - Bar chart: Top 10 most digitally excluded constituencies
  - Heatmap/Choropleth: Kenya colored by exclusion scores

## 🚀 How to Use

1. Open the notebook in Google Colab:  
   👉 [Digital_Equity_Insights_in_Kenya_.ipynb](https://colab.research.google.com/github/Athman-Dodoe/Digital-Equity-Insights-in-Kenya/blob/main/Digital_Equity_Insights_in_Kenya_.ipynb)

2. Upload or mount the dataset files (`CSV`, `GeoJSON`).

3. Run all cells to:
   - Clean and merge datasets
   - Calculate Digital Exclusion Score
   - Generate visualizations
