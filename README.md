
# COVID-19 Policy Impact on U.S. Housing Markets

This project analyzes how COVID-19 government response policies influenced U.S. housing price growth from 2020 to 2023.  
It combines public health indicators with economic variables to uncover how lockdown stringency, unemployment, GDP growth, interest rates, and pandemic severity reshaped housing markets across U.S. states.

##  Project Overview
During the COVID-19 pandemic, U.S. housing markets behaved in unexpected ways. Despite economic disruption and rising unemployment, housing prices surged in many states. This project explores **why**.

Using state-level, quarterly data, the analysis examines:
- Government policy stringency (lockdowns, travel restrictions)
- Housing price growth trends
- Unemployment rates
- GDP growth
- Mortgage interest rates
- COVID-19 deaths per million

The findings highlight how policy restrictions, low interest rates, and migration patterns interacted to drive housing market dynamics during the pandemic.

##  Interactive Dashboard
An interactive Tableau dashboard was built to visualize trends, compare states, and explore relationships between variables.

 **Live Dashboard:**  
https://public.tableau.com/app/profile/sana.ambreen/viz/Coviddashboard_17673930866780/Dashboard1

## Analysis & Methodology
- Data merged from multiple public sources (Zillow, OxCGRT, FRED, OWID)
- Extensive Exploratory Data Analysis (EDA)
- Outlier detection and normalization
- Multiple Linear Regression (OLS) to quantify relationships
- Model evaluation using R², RMSE, MAE, and residual diagnostics
  ##  Tools & Technologies
- Python (Pandas, NumPy, Matplotlib, Seaborn, Statsmodels)
- Jupyter Notebook
- Tableau Public
- Public economic & health datasets

##  Key Insights
- States with lower policy stringency generally experienced faster housing price growth
- Low mortgage interest rates played a major role in sustaining demand
- High unemployment and rising rates slowed growth in later phases
- Migration patterns amplified suburban and Sunbelt housing demand

The regression results show statistically significant relationships between housing price growth and policy stringency, interest rates, unemployment, GDP growth, and COVID severity.


