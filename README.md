# COVID-19 Data Analysis Notebook

This project provides an analysis of the spread of COVID-19 using confirmed case data and investigates its correlation with World Happiness Report indicators. The aim is to understand the pandemic's progression and explore how socio-economic indicators might relate to infection rates.

---

## 📦 Datasets Used

1. **Covid19_Confirmed_dataset.csv**  
   - Contains time series data of confirmed COVID-19 cases globally.
2. **WorldHappinessReport.csv**  
   - Provides various socio-economic indicators such as GDP per capita, social support, and health life expectancy.

---

## 🔧 Tools and Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 🔍 Project Workflow

### 1. Data Loading and Preprocessing
- Loaded COVID-19 confirmed cases dataset.
- Removed unnecessary columns.
- Aggregated data at the country level.

### 2. Visualization
- Visualized COVID-19 spread over time.
- Plotted data for specific countries (e.g., China) to analyze trends.

### 3. Infection Rate Calculation
- Calculated the first derivative (rate of change) of COVID-19 spread.
- Identified maximum infection rates for each country.
- Created a simplified dataframe with maximum infection rates.

### 4. Merging with World Happiness Data
- Loaded and cleaned World Happiness Report data.
- Selected relevant features: GDP per capita, social support, health life expectancy, freedom to make life choices, generosity, and perceptions of corruption.
- Merged with infection rate data.

### 5. Correlation Analysis
- Analyzed correlation between happiness indicators and infection rates.
- Produced a correlation matrix and visualized it using a heatmap.

### 6. Final Visualization
- Plotted relationships between variables such as GDP vs. infection rate and health expectancy vs. infection rate.

---

## 📈 Key Insights

- The maximum infection rate varied widely by country.
- Some socio-economic factors showed potential correlation with the spread of COVID-19.
- Visualization and analysis provided meaningful insights into the global dynamics of the pandemic.

---

## 📌 Conclusion

This notebook demonstrates the power of data analysis in understanding complex global phenomena. By combining pandemic data with socio-economic indicators, we uncover patterns that can inform future public health and policy decisions.
