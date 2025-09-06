# Trends and Forecasts of Indian Economy Through Statistical Insights and Machine Learning Techniques (1960–2020)

## 📚 Project Overview

This project presents a comprehensive analysis of the Indian economy from 1960 to 2020 using both statistical and machine learning approaches. It applies Exploratory Data Analysis, Ridge Regression, K-Means Clustering, and ARIMA Time Series Forecasting to real macroeconomic indicators, drawing actionable insights that can aid in policy, research, and business applications. The work was completed as part of a B.Sc. in Statistics, under the mentorship of Mr. N. Rakesh and in collaboration with Codegnan IT Solutions, Vijayawada.

---

## ⚡ Table of Contents

- [Project Overview](#-project-overview)
- [Dataset](#-dataset)
- [Features](#-features)
- [Technologies Used](#-technologies-used)
- [Methodology](#-methodology)
- [Key Results & Insights](#-key-results--insights)
- [How to Run](#-how-to-run)
- [Key Visualizations](#-key-visualizations)
- [Acknowledgements](#-acknowledgements)
- [Contact](#-contact)

---

## 🗃️ Dataset

- **Source:** [Kaggle: Indian Economy 1960–2020](https://www.kaggle.com/datasets/nejilee/indian-economy-from-1960-to-2020)
- **Rows:** 61 (each year from 1960–2020)
- **Columns:** Year, GDP, GDP per capita, GDP growth, Imports, Exports, Total Reserves, Inflation, Population, Population Growth, Life Expectancy

---

## 🚩 Features

- `Year`: Reporting year  
- `GDP (current US$)`: Total GDP in current US dollars  
- `GDP per capita (current US$)`: GDP per person  
- `GDP growth (annual %)`: Annual GDP growth rate  
- `Imports`/`Exports (% of GDP)`: Trade as a share of GDP  
- `Total reserves`: Includes gold, in US dollars  
- `Inflation (annual %)`: Consumer price inflation  
- `Population, total`: Total population  
- `Population growth (%)`: Annual population growth  
- `Life expectancy at birth (years)`: Average life expectancy

---

## 🛠️ Technologies Used

- **Languages:** Python, R  
- **Libraries:** pandas, numpy, matplotlib, seaborn, scikit-learn, statsmodels  
- **Tools:** Jupyter Notebook, RStudio, Excel

---

## 📈 Methodology

### Exploratory Data Analysis (EDA)
- Summarized key variable trends, checked for missing values, and visualized data with boxplots, bar charts, histograms, and heatmaps.

### Ridge Regression
- Built a regularized linear model to predict GDP using all economic variables; addressed multicollinearity and identified most significant predictors.
- Model fit: \( R^2 = 0.9674 \)

### K-Means Clustering
- Used Elbow Method to choose 3 optimal clusters.
- Segmented economic periods into Stable, Volatile (high inflation), and Downturn regimes based on GDP growth and inflation.

### ARIMA Time Series Forecasting
- Performed Dickey-Fuller tests and ACF/PACF analysis.
- Modeled GDP with ARIMA(1,1,1) (after log/difference transformation) and inflation with ARIMA(1,0,1).
- Produced 5-year forecasts with strong accuracy (\( \text{MAPE} \approx 2.36\% \)).

---

## 🏆 Key Results & Insights

- **Consistent GDP Growth:** GDP grew from \$37B to \$2.83T (1960–2020).
- **Impactful Variables:** GDP per capita, population, life expectancy, and population growth are most influential for GDP prediction.
- **Economy Clusters:** Identifiable phases—stable growth, high-inflation volatility, and slowdowns.
- **Reliable Forecasts:** Models indicate continued GDP growth and stable inflation barring major external shocks.

---

## ▶️ How to Run

1. Clone this repository.
2. Download the dataset from Kaggle and place in the `/data/` folder.
3. Open and run analysis scripts in [notebooks/](notebooks/) (Python) or [scripts/](scripts/) (R).
4. Install requirements:  
    - Python: `pip install -r requirements.txt`  
    - R: See `packages.R` for packages  
5. Outputs (plots, stats) will be saved to `/results/` or displayed inline.

---



## 📊 Key Visualizations

- Time evolution of GDP and GDP per capita (line/bar graphs)
- Correlation heatmap of economic indicators
- K-Means cluster assignment plots (GDP vs Inflation)
- Actual vs Predicted plots and ARIMA forecast graphs

---

## 🙏 Acknowledgements

- **Mentor:** Mr. N. Rakesh, Department of Statistics, PBS College
- **Industry Partner:** Codegnan IT Solutions, Vijayawada
- **Academic:** Parvathaneni Brahmayya Siddhartha College of Arts and Science

---

## 📬 Contact

**Author:** Mudili Pradeep  
**Degree:** B.Sc. (Statistics), 2025 
**Phone:**+91 9014628229
**Email:** pradeepmudili4@gmail.com
**LinkedIn:**https://linkedin.com/in/pradeep-mudili-0bbaba248

---


