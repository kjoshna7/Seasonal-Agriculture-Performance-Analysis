# Seasonal Agriculture Performance Analysis

## Project Overview

This project analyzes agricultural performance across different seasons using data analysis and visualization techniques.

The analysis focuses on identifying seasonal patterns in crop yield, environmental conditions, resource usage, economic performance, regional differences, and disease/pest risk.

## Problem Statement

Agricultural performance varies across seasons due to differences in environmental conditions, farming practices, resource usage, and economic factors.

This project analyzes these variations to identify meaningful patterns, trends, relationships, and insights that can support better agricultural planning and decision-making.

## Objectives

- Analyze agricultural performance across Kharif, Rabi, and Zaid seasons.
- Compare crop yield and profitability across seasons.
- Study rainfall, temperature, and soil moisture.
- Analyze water usage and water efficiency.
- Compare crop performance across seasons.
- Analyze irrigation, fertilizer, and pesticide usage.
- Examine regional differences in agricultural performance.
- Identify relationships between agricultural factors and crop yield.
- Perform correlation and ANOVA analysis.
- Provide data-driven agricultural recommendations.

## Dataset

The dataset contains **4,000 records and 28 variables**.

Important variables include:

- Farm ID
- State
- District
- Crop
- Season
- Farm Area
- Rainfall
- Temperature
- Humidity
- Sunlight
- Soil pH
- Soil Moisture
- Nitrogen
- Phosphorus
- Potassium
- Irrigation Method
- Fertilizer Usage
- Pesticide Usage
- Seed Quality
- Crop Yield
- Production
- Market Price
- Total Cost
- Revenue
- Profit
- Water Usage
- Water Efficiency
- Disease/Pest Risk

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Google Colab
- Jupyter Notebook
- GitHub

## Analysis Performed

### 1. Seasonal Analysis

Compared agricultural records, crop yield, and profit across Kharif, Rabi, and Zaid seasons.

### 2. Environmental Analysis

Analyzed:

- Rainfall
- Temperature
- Soil moisture
- Water usage
- Water efficiency

### 3. Crop Performance Analysis

Compared crop yield across different seasons and identified high-performing crops.

### 4. Resource and Farming Analysis

Analyzed:

- Irrigation methods
- Fertilizer usage
- Pesticide usage
- Seed quality
- Water consumption

### 5. Regional Analysis

Compared crop yield and profitability across different states.

### 6. Disease and Pest Risk Analysis

Analyzed disease and pest risk across seasons and crops.

### 7. Statistical Analysis

Performed:

- Correlation analysis
- One-way ANOVA

## Key Findings

- **Kharif** recorded the highest average crop yield of approximately **5.63 tonnes/ha**.
- Kharif also recorded the highest average profit of approximately **₹178,914.65**.
- **Rabi** recorded an average profit of approximately **₹87,689.47**.
- **Zaid** recorded a negative average profit of approximately **₹24,804.82**.
- Kharif had the highest average rainfall and soil moisture.
- Zaid had the highest average water usage.
- Kharif had the highest water efficiency.
- Water usage showed the strongest positive correlation with yield among the analyzed factors, with a correlation of approximately **0.386**.
- One-way ANOVA produced a p-value of approximately **0.212**, indicating that the difference in mean yield across seasons was not statistically significant at the 5% significance level.

## Recommendations

- Prioritize suitable crop planning during high-performing seasons.
- Improve water management during Zaid season.
- Use efficient irrigation methods to reduce unnecessary water consumption.
- Strengthen disease and pest management during high-risk periods.
- Select crops according to seasonal and regional suitability.
- Investigate the factors responsible for low profitability during Zaid season.
- Use regional agricultural performance data for better planning.

## Future Scope

- Machine learning-based crop yield prediction.
- Seasonal crop forecasting.
- Real-time weather data integration.
- Soil and satellite data integration.
- Interactive agricultural dashboards.
- AI-based crop recommendation.
- Agricultural resource optimization.
- Multi-year agricultural trend analysis.

## Project Files

- `Seasonal_Agriculture_Performance_Analysis.ipynb` — Complete analysis notebook.
- `seasonal_agriculture_performance_dataset (1).csv` — Dataset used for analysis.
- `README.md` — Project documentation.

## Conclusion

The project provides a data-driven analysis of seasonal agricultural performance by examining environmental conditions, resource usage, crop performance, economic outcomes, regional differences, and disease/pest risk.

The analysis indicates that Kharif performed strongest overall, while Zaid showed lower yield, lower water efficiency, and negative average profitability.

The findings can support better crop selection, water management, resource planning, and seasonal agricultural decision-making.
