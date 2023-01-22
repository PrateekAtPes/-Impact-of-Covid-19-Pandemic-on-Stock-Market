# -Impact of Covid-19 Pandemic and other global economic factors on the Indian Stock Market

Using Machine learning models like LSTM, KNN, RMSE, and Linear Regression, we produce an exceptionally accurate output in predicting the stock index.


Stock trading is one of the most significant financial activities in this dynamically expanding
economy. Stock price prediction is the act of finding the future worth of the firm stock and other
financial assets traded on a marketplace. With economic uncertainty and a number of other
dependent and independent variables that predict the rise and fall of the market, anticipation of
stock price is one of the hardest tasks to do. Numerous models have been used since the advent of
artificial intelligence to forecast the movement of the equities market.The effects of many elements
in India, such as the festival season, changes in oil prices, the impact of an increase in gold prices, the
covid-19 pandemic, and many other factors that affect stock values are compared using several
machine learning modeling techniques in this study. Stock price forecasting will be done based on
the examination of these elements. This paper presents the thorough investigation of the stock price
forecast using yearly and historical data and an analysis of how Covid-19 pandemic, Oil Prices and
Gold Prices impacted the Indian Stock Market.


# -Introduction
Due to the large global epidemic of the coronavirus disease (COVID-19), which had a
substantial impact on many nations in different ways, the year 2020 was marked by many
uncertainty. Public health declined, governments were overthrown, the global economy collapsed,
inflation peaked, the price of gold and other commodities skyrocketed, etc. Behavioral patterns,
trade and exchange, education, the economy, and other sectors all underwent changes. Since the
epidemic, there has been a significant transformation in many areas of the world.
Similar to other stock markets throughout the world, the Indian stock market experienced
significant volatility during the pandemic. The market fell by around 38\% following the pandemic's
onset. The market's decline during this period was the most significant since the 2008 Global
Economic Crisis. All of the world's major stock markets experienced this influence. It was anticipated
that it would take at least a few years to recover from such a significant fall.
In this study, we shall observe how the market performed in the pre-covid era, covid
pandemic era and post-pandemic era. We will also examine how the market performed during the
pandemic era and how factors affecting the global economy, such as the price of gold and oil,
affected that performance.

# -Proposed Methodology
Dataset
The Covid-19 Indian data, the Brent-oil Indian price data, the Gold price Indian data, and the
NSE 500 index data have all been utilised in this study.
The top 500 NSE-listed firms are included in the Nifty 500. The Nifty 50 data has been used
in a number of research. However, the Nifty 500 index data was used in this analysis primarily
because it accounts for about 96.1\% of the free float market capitalization and roughly 96.5\% of all
trading on the NSE. The primary elements of the dataset are the following: Date, Open, High, Low,
Close, Shares Traded (Volume), Turnover. The study's consideration period spans 5 fiscal years, from
03 April 2017 to 31 March 2022.
The World Health Organization (WHO) website is where the Covid-19 data for India was
gathered. Date, New Cases, Cumulative Cases, New Deaths, and Cumulative Deaths are the
attributes that make up the dataset. The study's consideration period is from January 1, 2020, until
March 31, 2022.
Data on gold prices were taken into account from 02 March 2020 to 30 March 2022. Data on
the price of Brent oil was taken into account from 02-03-2020 to 26-08-2022.
The paper is organized into five sections. Following this introduction, Section 2 explains
significant concepts through a literaturereview of related work. We put forth the proposed
methodology in Section 3 and provide results in Section 4. Ultimately, we’ve encapsulated our
research with a conclusion in Section 5, followed by a list of references.

# -Models
Traditional Machine Learning Techniques
RMSE - Root Mean Square Error is one of the most commonly used measures for evaluating the
quality of predictions.
Linear Regression - It is a supervised learning algorithm used for performing a regression task in
predicting an output.
K-Nearest Neighbours - It is a non-parametric, supervised learning classifier, which uses proximity to
make classifications or predictions about the grouping of an individual data point.
RNN / Time Series
LSTM - Long Short-Term Memory (LSTM) networks are a type of recurrent neural network capable of
learning order dependence in sequence prediction problems.


# -Analysis
Datasets of price movements for the NIFTY-500, OIL, GOLD, and COVID-19 Total Deaths and
Cases Worldwide were extracted. The dataset for Brent has also been used because the conflict over
oil prices between Saudi Arabia and Russia has had an effect on the market.
 We have implemented price changes between the beginning of the financial year in 2020
and the conclusion of the financial year in 2022 in order to obtain an analysis of the impact of
COVID-19. Thus, the actions of the Indian Stock Market during these times and their effects from
COVID-19, the Oil Price War between Russia and Saudi Arabia, COVID-19- lockdowns, and other
significant events that occurred during the time have been examined.
Along with the extraction of pricing actions, the datasets' normalization requires the
extraction of necessary information, such as Covid case information for India and other name
conventions and date formats.

# -Results
The results obtained were exactly as expected. The RMSE, Linear Regression and KNN model
fail to provide an accurate output in predicting the stock index as seen in fig.. However, the LSTM
model provides an exceptionally accurate output in predicting the stock index as seen in fig.4,5,6,7.
While KNN model works fairly well in problem statements that require multiclass classifications, a
Linear Regression model helps in understanding the relation between only 2 variables. However, a
LSTM model is a time series based that can be used in sequential prediction of data and thereby,
works perfectly for the problem statement in predicting the stock index over the timeframe.



# -Conclusion
Relevant studies have focused on various methodologies and implementations to predict the
stock prices and indexes based on the time series models. In this study, we have demonstrated how
a sequential model clearly outperforms traditional Machine Learning techniques in a problem
statement that involves time sequence. LSTM model outperforms and provides an exceptionally
accurate prediction when compared to the RMSE, Linear Regression and KNN model.
Further, we've also concluded some of the results based on the Analysis obtained after
various careful observations, mentioned below:
• Oil Prices see a rapid increase in the months of April-July 2020 while the stock market sees a
slow recovery.
• Gold Prices drastically increased in the months of March - May 2020 while the Market hits
low. This is primarily because, due to the uncertainty in the market conditions, investors
would prefer in switching over to safer investing options like Gold or Government Bonds.
• Again, Gold Prices see a drastic drop as the Market condition improves during June - Nov
2020.
• It can be observed that whenever there has been an increase in the Oil prices, the Market
has gone down (Jan - Mar 2022)
We can conclude that Covid lockdowns during Mar-May 2020 brought a major impact to the market
than the lockdowns during April-June 2021. One primary reason can be said due to the fear of
outbreak of a pandemic which was observed in March 2020 by WHO (World Health Organization).


For more Details refer to the research paper.
