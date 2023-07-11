Analysis of Stock Price Data - Data Analytics Project

This repository contains a comprehensive analysis of historical stock price data for multiple companies. The analysis was performed using Python, utilizing libraries such as pandas, numpy, datetime, yfinance, and statsmodels. The following sections provide a detailed breakdown of the analysis.

Dataset

The dataset used for this analysis is stored in the file "stocks.csv". It contains the following columns:

Ticker: The ticker symbol representing the company.
Date: The date of the stock price data.
Open: The opening price of the stock on a given day.
High: The highest price reached by the stock on a given day.
Low: The lowest price reached by the stock on a given day.
Close: The closing price of the stock on a given day.
Volume: The trading volume of the stock on a given day.
Data Cleaning and Preprocessing

The initial steps of the analysis involved data cleaning and preprocessing to ensure data quality and consistency. The following operations were performed:

Descriptive Statistics: Descriptive statistics were calculated to provide an overview of the dataset. This included count, mean, standard deviation, minimum, quartiles, and maximum for each numerical column. The descriptive statistics help identify any outliers or unusual patterns in the data.
Checking for Null Data: The dataset was checked for the presence of null values. It is important to ensure that the dataset does not contain missing values that could impact the accuracy of the analysis. Fortunately, no null values were found in the dataset.
Checking for Duplicates: Duplicate entries in the dataset were identified based on the combination of the "Ticker" and "Date" columns. This step helps ensure the accuracy and uniqueness of the data. No duplicates were found in the dataset.

Graphical Analysis

To gain deeper insights into the stock price data, various graphs were generated using the Plotly Express library. The following graphs were created:

Stock Price Trends

Closing Price Over Time
The line graph depicting the closing price over time for each company reveals the overall movement of the stock prices. Here are the key trends observed:

Apple (AAPL): The stock price of Apple shows a steady upward trend over the analyzed period, indicating consistent growth in value.
Microsoft (MSFT): Microsoft's stock price exhibits a similar upward trend, although with more fluctuations and occasional dips.
Google (GOOG): Google's stock price demonstrates a relatively stable upward trend, with occasional spikes in value.
Netflix (NFLX): Netflix's stock price exhibits significant volatility, with sharp increases and declines throughout the analyzed period.

Moving Averages
Moving averages were calculated for each company to identify potential trends and turning points in the stock prices. The moving average graphs reveal the following:

Apple (AAPL): The moving average lines for Apple indicate an overall upward trend in the stock price. The shorter-term moving average (e.g., 10-day) frequently crosses above the longer-term moving average (e.g., 20-day), indicating potential buy signals.
Microsoft (MSFT): Microsoft's moving average lines also exhibit an upward trend, with occasional crossovers between the short-term and long-term moving averages.
Google (GOOG): Similar to Apple and Microsoft, Google's moving average lines show an overall upward trend, with periodic crossovers between the short-term and long-term moving averages.
Netflix (NFLX): Netflix's moving averages demonstrate significant fluctuations, indicating high volatility and less consistent trends compared to the other companies.

Volatility Analysis
The volatility graph illustrates the degree of price fluctuation for each company. Key observations include:

Apple (AAPL): The volatility of Apple's stock price is relatively low and stable, indicating a more predictable pattern of price fluctuations.
Microsoft (MSFT): Microsoft exhibits moderate volatility, with periods of higher and lower volatility throughout the analyzed period.
Google (GOOG): Google's stock price volatility remains relatively low and consistent, similar to Apple.
Netflix (NFLX): Netflix demonstrates the highest volatility among the analyzed companies, with frequent periods of sharp price fluctuations.

Correlation Analysis
Correlation analysis was conducted to assess the relationship between Apple's stock price and that of other companies. Scatter plots with trendlines were used to visualize the correlation. The following observations were made:

Apple vs. Microsoft: The scatter plot reveals a strong positive correlation between Apple and Microsoft's stock prices. The trendline suggests that as Apple's stock price increases, Microsoft's stock price tends to follow a similar upward trend.
Apple vs. Netflix: The scatter plot indicates a positive correlation between Apple and Netflix's stock prices, although the relationship appears to be less strong than with Microsoft.
Apple vs. Google: The scatter plot shows a positive correlation between Apple and Google's stock prices, but the relationship seems less pronounced compared to Apple and Microsoft.
Analysis of Findings

Based on the analysis of the graphs and data, the following insights and observations can be made:

Stock Price Trends: Apple, Microsoft, Google, and Netflix exhibit overall upward trends in their stock prices, indicating positive growth over the analyzed period. Apple and Google show relatively stable and consistent trends, while Microsoft and Netflix demonstrate higher volatility.
Moving Averages: Moving averages suggest potential trends and turning points in the stock prices. Crossovers between the short-term and long-term moving averages can indicate buy or sell signals. Apple, Microsoft, and Google show relatively consistent upward trends, while Netflix's stock price demonstrates higher volatility and less predictable patterns.
Volatility Analysis: Apple and Google exhibit lower volatility compared to Microsoft and Netflix. Investors with a lower risk tolerance may find Apple and Google more suitable for their portfolios, while those comfortable with higher risk may consider Microsoft and Netflix as potential investment options.
Correlation Analysis: Apple's stock price shows a strong positive correlation with Microsoft, indicating a tendency for the two stocks to move in a similar direction. The correlation with Netflix and Google appears to be positive but relatively weaker. Investors seeking to diversify their portfolios may find value in considering the correlation between these companies when making investment decisions.

Recommendations

Based on the analysis, the following recommendations are proposed:

Investment Opportunities: Apple, Microsoft, and Google exhibit positive growth trends and strong correlations with each other. These companies may present potential investment opportunities. Further analysis, including fundamental analysis and market research, is recommended to validate these findings before making investment decisions.
Risk Assessment: Microsoft and Netflix demonstrate higher volatility compared to Apple and Google. Investors should carefully assess their risk tolerance and diversify their portfolios accordingly. A balanced portfolio can help mitigate risk by including stocks with different risk profiles.
Moving Average Strategies: Moving averages provide insights into potential trends and turning points in stock prices. Investors can explore using moving average crossovers as indicators for buy or sell signals. However, it is important to consider other factors, such as fundamental analysis and market conditions, to make well-informed investment decisions.

Conclusion

The analysis of the stock price data provides valuable insights into stock market trends, company performance, moving averages, volatility, and correlations between different companies. These insights can guide investment decisions, risk assessment, and the development of trading strategies. However, it is essential to note that stock market investments carry inherent risks, and further analysis, research, and consideration of external factors are crucial before making any investment decisions based solely on the provided analysis.

For a detailed report with code snippets and visualizations, please refer to the Jupyter Notebook file in this repository.

*Note: The code and analysis presented in this repositoryare for educational and informational purposes only. The analysis is based on historical stock price data and should not be considered as financial or investment advice. It is always recommended to consult with a qualified financial advisor or conduct thorough research before making any investment decisions.
