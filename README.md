🚀 #Trader Behavior Analysis Using Market Sentiment (Fear & Greed Index)
📌 Project Overview

This project analyzes the relationship between market sentiment (Fear & Greed Index) and trader performance using real-world trading data.
The goal is to uncover hidden patterns in trader behavior and provide insights that can support smarter trading strategies.

🎯 Objective
Analyze how Fear & Greed sentiment affects trading performance
Understand risk-taking behavior of traders
Identify patterns in profit and loss across market conditions
Generate actionable insights from data
📊 Datasets Used
🔹 1. Sentiment Dataset (sentiment.csv)
Columns:
date
classification (Fear, Greed, Extreme Fear, Extreme Greed, Neutral)
value

👉 Represents daily market sentiment

🔹 2. Trader Dataset (trader_data.csv)
Columns include:
Account
Execution Price
Size
Side (Buy/Sell)
Closed PnL
Timestamp
Fee

👉 Represents real trading activity and performance

🛠️ Tools & Technologies
Python
Pandas
NumPy
Matplotlib
Seaborn
Jupyter Notebook

⚙️ Methodology

1. Data Cleaning
Standardized column names
Converted date formats
Removed missing values
2. Data Integration
Merged both datasets using Date column
3. Feature Engineering
Created:
Profit/Loss categories
Absolute PnL (volatility)
4. Exploratory Data Analysis
Average PnL by sentiment
Total profit analysis
Trade frequency analysis
Profit distribution
5. Visualization
Bar charts
Time-series plots
Distribution graphs

📈 Key Insights

Extreme Greed shows the highest average profit, indicating high-risk, high-reward behavior.
Fear phase generates the highest total profit due to consistent trading activity.
Extreme Fear leads to the lowest trading activity and weakest performance.
Majority of traders incur losses across all sentiment conditions.
A small group of traders consistently achieves high profitability → indicating skill-based advantage.

🧠 Conclusion

Market sentiment plays a significant role in influencing trader behavior and performance.
While Greed-driven markets can offer higher returns, they also introduce higher risk and volatility.
Fear-based markets provide more stable and consistent trading conditions.

👉 Successful trading depends more on strategy, discipline, and risk management rather than emotional reactions to market sentiment.

📂 Project Structure
├── data/
│   ├── sentiment.csv 
│   ├── trader_data.csv 
│
├── notebook/
│   └── Trader_Behavior.ipynb
│
├── report/
│   └── Crypto_Trading_Sentiment_Analysis_Report.docx 
│
└── README.md


🚀 How to Run
Clone the repository:
git clone https://github.com/syed-sadain/Crypto-Trader-Sentiment-Analysis.git
Navigate to the project folder:
cd Crypto-Trader-Sentiment-Analysis
Open the notebook:
notebook/Trader_Behavior.ipynb
Run all cells to reproduce the analysis

📊 Output
Visualizations of sentiment vs trader performance
Insights on trading patterns
Identification of high-performing traders
👤 Author
Syed Sadain

⭐ Final Note

This project highlights how combining data analysis with behavioral insights can provide a deeper understanding of financial markets and improve decision-making.

💬 Optional Improvements (Future Scope)
Add Machine Learning models for prediction
Build interactive dashboards (Power BI / Tableau)
Real-time sentiment integration
