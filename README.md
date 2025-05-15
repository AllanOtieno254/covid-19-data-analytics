# COVID-19 Data Analysis Notebook

This project provides an analysis of the spread of COVID-19 using confirmed case data and investigates its correlation with World Happiness Report indicators. The aim is to understand the pandemic's progression and explore how socio-economic indicators might relate to infection rates.

--

## 📦 Datasets Used

1. **Covid19_Confirmed_dataset.csv**  
   - Contains time series data of confirmed COVID-19 cases globally.
2. **WorldHappinessReport.csv**  
   - Provides various socio-economic indicators such as GDP per capita, social support, and health life expectancy.

# COVID-19 Data Analysis Project

This project analyzes the global spread of COVID-19 using time-series confirmed case data. It also explores how socio-economic factors from the World Happiness Report relate to the maximum infection rates across countries.

---

## 🎯 Project Objectives

- To analyze the time-series progression of COVID-19 across various countries.
- To calculate and visualize the maximum infection rate per country.
- To integrate socio-economic indicators from the World Happiness Report.
- To identify possible correlations between happiness indicators and infection severity.
- To visualize the relationship between different indicators and the infection rate.

---

## 🧰 Tools and Libraries Used

- **Python** – for data processing and analysis.
- **Pandas** – for data manipulation.
- **NumPy** – for numerical operations.
- **Matplotlib** – for plotting and visualizing data.
- **Seaborn** – for advanced visualizations and heatmaps.
- **Scikit-learn** – for correlation analysis and data modeling.

---

## 🚀 How to Run or View the Project

1. Clone or download the repository containing the Jupyter Notebook and datasets.
2. Ensure the following files are in your working directory:
   - `Covid19_Confirmed_dataset.csv`
   - `WorldHappinessReport.csv`
3. Launch the notebook using Jupyter:
   ```bash
   jupyter notebook "covid19 data analysis notebook.ipynb"

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
