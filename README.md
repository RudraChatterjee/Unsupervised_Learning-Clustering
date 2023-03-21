# Unsupervised_Learning-Clustering_Stocks_and_Personalized-Portfolio-Recommender

## Summary
<p align="justify"> This project explores and analyzes financial data of a number of securities using EDA and visualization. Following data scaling, K-means clustering is applied to this dataset and optimum no of clusters are selected using the elbow method and silhouette visualizer. Next, hierarchical clustering is applied to the dataset for different distance metrics and linkage methods. Optimal no of clusters is selected by examining dendograms and cophenetic correlation values. Cluster profiles obtained from the two different types of clustering are compared and contrasted and different portfolios of stocks depending on different investment strategies (long-term vs short-term, risk on vs conservative) are recommended for clients.</p>

## Context

<p align="justify"> The stock market has consistently proven to be a good place to invest in and save for the future. There are a lot of compelling reasons to invest in stocks. It can help in fighting inflation, create wealth, and also provides some tax benefits. Good steady returns on investments over a long period of time can also grow a lot more than seems possible. Also, thanks to the power of compound interest, the earlier one starts investing, the larger the corpus one can have for retirement. Overall, investing in stocks can help meet life's financial aspirations.</p>

<p align="justify"> It is important to maintain a diversified portfolio when investing in stocks in order to maximise earnings under any market condition. Having a diversified portfolio tends to yield higher returns and face lower risk by tempering potential losses when the market is down. It is often easy to get lost in a sea of financial metrics to analyze while determining the worth of a stock, and doing the same for a multitude of stocks to identify the right picks for an individual can be a tedious task. By doing a cluster analysis, one can identify stocks that exhibit similar characteristics and ones which exhibit minimum correlation. This will help investors better analyze stocks across different market segments and help protect against risks that could make the portfolio vulnerable to losses.</p>


## Objective

<p align="justify"> A financial consultancy firm provides their customers with personalized investment strategies. Financial data comprising of stock prices and other financial indicators for a no of companies listed under the New York Stock Exchange have been provided. The broad object is to perform data analysis, group stocks based on the various financial attributes, and share insights about the characteristics of each group.</p>

## Data Dictionary

- Ticker Symbol: An abbreviation used to uniquely identify publicly traded shares of a particular stock on a particular stock market
- Company: Name of the company
- GICS Sector: The specific economic sector assigned to a company by the Global Industry Classification Standard (GICS) that best defines its business operations
- GICS Sub Industry: The specific sub-industry group assigned to a company by the Global Industry Classification Standard (GICS) that best defines its business operations
- Current Price: Current stock price in dollars
- Price Change: Percentage change in the stock price in 13 weeks
- Volatility: Standard deviation of the stock price over the past 13 weeks
- ROE: A measure of financial performance calculated by dividing net income by shareholders' equity (shareholders' equity is equal to a company's assets minus its debt)
- Cash Ratio: The ratio of a  company's total reserves of cash and cash equivalents to its total current liabilities
- Net Cash Flow: The difference between a company's cash inflows and outflows (in dollars)
- Net Income: Revenues minus expenses, interest, and taxes (in dollars)
- Earnings Per Share: Company's net profit divided by the number of common shares it has outstanding (in dollars)
- Estimated Shares Outstanding: Company's stock currently held by all its shareholders
- P/E Ratio: Ratio of the company's current stock price to the earnings per share 
- P/B Ratio: Ratio of the company's stock price per share by its book value per share (book value of a company is the net difference between that company's total assets and total liabilities)
