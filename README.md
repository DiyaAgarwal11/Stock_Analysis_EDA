# Stock Market Analysis

## Project Overview
This project analyzes stock market data to extract valuable financial insights, identify statistical patterns, and compare stock performances. The study is structured into several key sections:

- **Single Stock Performance Analysis** – Examining how a specific company’s stock has evolved over time using time-series analysis.
- **Comparative Multi-Stock Evaluation** – Comparing multiple stocks to identify correlations, trends, and market movements.
- **Outlier Detection and Data Adjustments** – Identifying and addressing anomalies in the data to enhance analytical accuracy.
- **Data Visualization** – Leveraging Seaborn and Matplotlib to create clear and informative financial visualizations.

---
## Dataset Information
- **Part1_data.csv** – Contains data for an individual company’s stock, including Date, Open, High, Low, Close, and Volume.
- **Part2_data.csv** – Includes closing prices for multiple stocks, facilitating comparative analysis across different companies.

---
## Key Findings
### Single Stock Analysis (Amazon)
- **Trend Analysis**: The stock’s closing price demonstrated a consistent upward trajectory, indicating strong long-term growth.
- **30-Day Moving Average**: This smoothing technique highlighted long-term price trends while filtering out short-term fluctuations.
- **Outlier Detection**: Unusual spikes in trading volume suggested instances of significant market activity, likely driven by institutional investors.
- **Log Transformation**: Applied to volume data to mitigate the impact of extreme values, improving data distribution for analysis.

### Multi-Stock Comparative Analysis
- **Correlation Analysis**: Stocks within the technology sector exhibited strong positive correlations, moving in similar directions.
- **Stock Price Volatility**: Certain stocks displayed heightened price volatility, indicating greater investment risk.
- **Price Distribution Patterns**: Stock prices were not normally distributed, suggesting that traditional statistical models might require adjustments for accurate analysis.

---
## Recommendations
- **Diversify Investments**: A balanced portfolio with both stable and high-growth stocks can help mitigate risk.
- **Monitor Market Activity**: Identifying significant price movements early can support more informed investment decisions.
- **Enhance Predictive Analysis**: Incorporating external economic factors such as inflation and interest rates could improve forecast accuracy.

---

## How to Run the Project
1. Clone the project repository:  
   ```bash
   git clone https://github.com/DiyaAgarwal11/Stock_Analysis_EDA.git
   cd Stock_Analysis_EDA
   ```
2. Install the necessary Python libraries:  
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```
3. Run the Jupyter Notebook to perform data analysis and generate visualizations.
   
---
## License
This project is intended for educational purposes. Users are encouraged to modify and expand upon it while adhering to ethical data practices.
