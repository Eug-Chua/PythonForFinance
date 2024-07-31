# Stock Analysis & Data Visualization with Pandas, NumPy, and Matplotlib
## Introduction
In the era of rapidly advancing natural language processing (NLP) and artificial intelligence (AI), technologies like ChatGPT are transforming industries across the globe. This project takes a deep dive into the landscape of companies driving this transformation and those poised to be affected by it. We explore a curated selection of stocks with the potential to thrive in the age of ChatGPT and other groundbreaking NLP innovations.

Our analysis leverages the power of pandas to dissect crucial data, including vital metrics such as value, risk, and returns. We focus on major tech players who are making significant shifts towards AI, including:
- Nvidia
- Google
- Microsoft
- Amazon
 
Within this notebook, we aim to uncover answers to compelling questions, shedding light on the dynamics of these tech giants and their potential in the AI-driven landscape:
- How has the stock price of these companies evolved over time?
- What insights can we gain from examining moving averages of their stock prices?
- What do daily returns reveal about individual stock performance, and how are these returns correlated across different companies?
- What level of risk is associated with each investment, and how can we quantify it?

## Project Overview
### Libraries Used
- Pandas
- NumPy
- Matplotlib
- Seaborn
- yfinance

### Data
We analyze and compare the performance of the selected stocks over the period from January 2022 to October 2023. To provide context for their performance in the broader tech sector, we also obtain historical price data for S&P 500 (SPY) and the NASDAQ 100 (QQQ), both of which are key market benchmark indexes.

### Key Sections
1. Import Libraries: We start by importing the necessary libraries.
2. Fetch Stock Data: Using yfinance to download historical stock data.
3. Data Preprocessing: Normalizing stock prices for meaningful comparison.
4. Stock Performance Comparison: Visualizing and analyzing stock performance.
5. Risk Analysis: Evaluating daily returns and associated risks.

## Usage
To run the notebook, you will need to install the required Python libraries. You can install them using pip:

```
pip install pandas numpy matplotlib seaborn yfinance
```

Once the libraries are installed, you can run the notebook using Jupyter Notebook or any other compatible environment.

## Visualizations
### Stock Price Evolution
We normalize each stock price to 100 on January 1, 2022, to facilitate a relative performance comparison.

### Moving Averages
Analyzing moving averages helps us understand the trends and price movements of each stock over time.

### Daily Returns
We calculate and visualize daily returns to assess the volatility and risk associated with each stock.

### Correlation Analysis
Examining the correlation of daily returns between different stocks provides insights into their interconnected performance.

## Conclusion
This analysis provides valuable insights into the stock performance of major tech companies in the context of the rapidly evolving AI landscape. By leveraging data visualization and statistical analysis, we can make informed predictions and investment decisions.

