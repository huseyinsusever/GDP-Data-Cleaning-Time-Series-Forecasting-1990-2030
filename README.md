# GDP-Data-Cleaning-Time-Series-Forecasting-1990-2030
This project focuses on the end-to-end processing of global GDP (Gross Domestic Product) data, specifically targeting financial hubs like Singapore and Malaysia. It covers data sanitization, normalization, and Machine Learning (Linear Regression) to predict economic trajectories up to 2030.

🚀 Project Overview
Raw economic datasets are often stored in "Wide Format" and contain noise such as inconsistent quoting and whitespace. This project demonstrates how to transform "messy" data into "tidy" data, followed by a time-series analysis to forecast future growth in strong financial ecosystems.

🛠️ Tech Stack
Python 3.x

Pandas: For advanced data manipulation and "Melt" operations.

Scikit-learn: Implementing the Linear Regression model for forecasting.

Matplotlib & Seaborn: For high-quality data visualization.

🧹 Data Sanitization (The Cleaning Process)
Real-world financial data is rarely perfect. This project handles:

Quote & Whitespace Removal: Systematic stripping of double quotes (") and hidden spaces that disrupt data parsing.

Wide-to-Long Transformation: Converting years from column headers into a single Year variable, making the data compatible with ML algorithms.

Type Casting: Enforcing numeric constraints on GDP values and handling missing values (NaN) to ensure model stability.

🔮 Time Series Forecasting (2030 Projections)
Using Linear Regression, the model analyzes 30 years of historical GDP data to identify growth trends.

Feature (X): Years (1990 - 2019)

Target (y): GDP Per Capita (USD)

Forecast Horizon: 2020 - 2030

Given Singapore's and Malaysia's robust financial systems, the model captures the long-term upward trend while highlighting historical volatility points (e.g., the 1997 Asian Financial Crisis or the 2008 Global Recession).

📊 Key Insights
The output visualization provides:

Historical Trend: Blue scatter points representing actual reported GDP.

The Regression Line: A red dashed line showing the overall economic momentum.

Future Forecast: Green markers indicating the projected GDP values for the year 2030.

📁 Repository Structure
GDP.csv: The raw, unformatted dataset.

cleaning_script.py: Python script for quote removal and reshaping.

forecasting_model.py: The ML script that performs the regression and plots results.

Cleaned_GDP_Analysis.csv: The final processed dataset ready for production.

Developed by Hüseyin as part of a comprehensive Data Science Portfolio.

💡 How to Run
Ensure GDP.csv is in the root directory.

Run the cleaning script to generate the sanitized CSV.

Execute the forecasting script to view 2030 predictions for Singapore/Malaysia.****
