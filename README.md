# Final-Project-SNP500-Prediction-and-Recommendation
Machine learning model that combines 3 types of data and outputs recommendations to buy/sell/hold the stock.
Each data type was trained as an individual model and we combined the 3 models by implementing Majority vote.

### During the project we used alot of 3rd party API's such as:
* yfinance - S&P500 stock data
* stockstats - Technical indicators
* fundamentalanalysis - fundamental data (companies annual financial reports)
* new york times API for articles
### Modules and libraries used
* NLTK - Natural langauge processing for getting the sentiment from the news articles.
* Sklearn - Building the machine learning models
* Matplotlib - Visualizing the data
* Pandas - Working with data and manipulating it

### Following the model recommendations got us a **17.5%** return on our investment, tested on a 2 year period
* The Model outpreformed the no-actions return (4.4%) from 2020-12-18 to 2022-12-13 , that's 3.98 times that return!

**17.5 / 4.4 = ~ 3.98**

### Let me know if you enjoy and learn from this project! :)
