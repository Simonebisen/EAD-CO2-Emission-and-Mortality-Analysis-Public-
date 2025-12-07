# CO2 Emissions and Mortality Rate Analysis

## Project Overview
This project explores the hypothesis that higher CO2 emissions correlate with increased death rates due to environmental health impacts. The research merges multiple carbon emission datasets for a comprehensive analysis of the relationship between various sources of CO2 emissions and mortality rates across different countries.

## Research Hypothesis
Higher CO2 emissions correlate with increased death rates due to environmental health impacts.

## Data Sources
The project utilizes several datasets:
- Annual CO2 emissions per country
- Annual CO2 emissions growth percentage
- Annual CO2 emissions including land-use change
- CO2 emissions by source (coal, oil, gas, cement, flaring)
- Global Burden of Disease results

## Methodology
1. **Data Preprocessing**: Cleaning, merging, and normalizing data from various sources
2. **Feature Engineering**: Creating additional features like mortality rates, emissions per death, and relative risk metrics
3. **Statistical Analysis**: Performing correlation analysis between CO2 emissions and death rates
4. **Predictive Modeling**: Implementing Bayesian models and SARIMA for forecasting
5. **Visualization**: Creating various visualizations to represent findings

## Key Findings
- Strong correlation found between certain CO2 emission sources and mortality rates
- Coal emissions emerged as the primary contributor to the negative health impacts
- India showed the highest projected mortality rates related to CO2 emissions
- Cement sector is one of the major contributors to coal consumption in India

## Models Used
- **Bayesian Linear Regression**: For emissions-mortality relationship analysis
- **Bayesian Hierarchical Models**: For estimating future trends
- **SARIMA (Seasonal ARIMA)**: For detailed time series forecasting
- **Linear Regression**: For sector-specific analysis

## Visualizations
The project includes various visualizations:
- Correlation heatmaps
- Time series plots
- Geospatial maps
- Animated bubble charts
- Source contribution analysis

## Requirements
The project uses various Python libraries:
```
pandas
numpy
matplotlib
seaborn
scipy
plotly
scikit-learn
statsmodels
pymc
arviz
```

## How to Run
1. Clone the repository
2. Install required packages: `pip install -r requirements.txt`
3. Run the Jupyter notebooks in sequence

## Future Work
- Incorporate additional environmental factors into the analysis
- Develop more sophisticated predictive models
- Expand the country-specific analysis to more regions
- Investigate potential mitigation strategies

## References
- Land Use: Annual CO₂ Including Land Use (https://ourworldindata.org/grapher/annual-co2-including-land-use)
- Annual CO₂ Emissions Per Country (https://ourworldindata.org/grapher/annual-co2-emissions-per-country)
- CO₂ by Source (https://ourworldindata.org/grapher/co2-by-source)
- Global Burden of Disease Results (https://vizhub.healthdata.org/gbd-results/)
