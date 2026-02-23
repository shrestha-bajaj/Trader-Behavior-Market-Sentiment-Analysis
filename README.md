# Trader-Behavior-Market-Sentiment-Analysis
This quantitative study analyzes sentiment regimes' impact on profitability and directional bias. Through statistical testing, OLS regression, and segmentation, we evaluated trader adaptation to market shifts. Results confirm that behavior varies by regime, providing a robust empirical basis for regime-aware exposure and risk allocation strategies.

# Overview
The project examines the relationship between market sentiment (Fear & Greed Index) and trading outcomes. Using a dataset of historical trades and sentiment classifications, it evaluates whether a trader's performance, frequency, and risk profile adapt dynamically to different market emotional regimes.

# Key Research Features
1. Regime Classification: 
Categorization of market data into five emotional states: Extreme Fear, Fear, Neutral, Greed, and Extreme Greed.
2. Statistical Analysis: Application of One-Way ANOVA and Independent T-Tests to validate the significance of PnL variance and trade frequency.
3. Econometric Modeling: OLS Regression to quantify the impact of specific sentiments (e.g., Greed) on Closed PnL.
4. Predictive Modeling: A Random Forest Classifier used to explore the binary predictability of daily profit based on sentiment features.
5. Behavioral Insights: Analysis of "Long vs. Short" directional bias and trade frequency surges during stress regimes.

# Key Findings
1. Volatility-Accuracy Trade-off: Fear regimes yield high-reward volatility capture, while Extreme Greed offers the highest win-rate reliability.
2. Behavioral Shifts: Statistical evidence ($p < 0.05$) confirms a significant surge in trading frequency during Extreme Fear, indicating reactive hyperactivity.
3. Negative Greed Impact: Regression analysis indicates that "Greed" regimes negatively correlate with the trader's average baseline PnL.

# Setup
To run this project locally:
1. Install Python (3.9+ recommended).
2. Install required libraries:
  * pandas
  * numpy
  * matplotlib
  * seaborn
  * scipy
  * statsmodels
  * scikit-learn
  * jupyter
We can install them using preferred package manager (pip).

# How to run
1. Clone or download the repository.
2. Ensure both datasets are placed in the same directory as the notebook.
3. Open the notebook (project.ipynb) in:
     * Jupyter Notebook, or
     * VS Code (with Python extension).
4. Run all cells sequentially from top to bottom.

