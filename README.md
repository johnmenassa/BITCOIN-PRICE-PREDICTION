
Based on the detailed project information you've provided and the content of your PowerPoint presentation, I'll create a README file that encompasses the essence of your project. This README aims to showcase your work on predicting Bitcoin price fluctuations using various data science and machine learning techniques. Here's how it could look:

Decoding Bitcoin's Future: A Data Science Approach to Price Prediction
Team Members
Jake Schuler
Praveen Rajendran Nair
Rakshit Vastrad
Overview
In the volatile market of cryptocurrency, predicting Bitcoin's price movement remains a significant challenge. Our project, "Decoding Bitcoin's Future," aims to address this challenge through a classification-based approach. By utilizing sophisticated data cleaning, feature engineering, and time series analysis, we strive to forecast the price fluctuations of Bitcoin accurately.

Problem Statement
Bitcoin's price volatility poses a significant challenge for investors and traders alike. Our objective is to predict Bitcoin price movements (up or down) by analyzing historical price data alongside various financial indicators, thus providing insights that could aid in making informed investment decisions.

Data Sources
Federal Reserve Economic Data (FRED): Federal Funds Rate
Yahoo Finance API (yFinance): Historical Bitcoin price data
Additional data includes price and volume information for Ethereum (ETH) and USD Coin (USDC) to enrich our analysis.
Methodology
Our project involved several key steps:

Data Gathering: Utilized FRED API and yFinance API to collect historical data.
Data Processing and Feature Engineering: Applied Simple Moving Average (SMA) and Exponential Moving Average (EMA) techniques to the collected data. We also created features like price change classification and incorporated financial indicators from other cryptocurrencies.
Model Development: Explored several machine learning models, including Random Forest, SVM, Gradient Boosted Classifier, Logistic Regression, LSTM, and Naive Bayes, to predict Bitcoin's price movement.
Evaluation: Assessed the models based on accuracy, precision, recall, and F1-score, along with other metrics like confusion matrices.
Key Findings
Logistic Regression provided the best balance between simplicity and predictive performance, achieving an accuracy score of 68%.
While LSTM showed promise due to its ability to handle sequential data, its performance was hindered by the limited dataset.
Gradient Boosting Machine (GBM) showed notable improvement after hyperparameter tuning, underscoring the importance of model optimization.
Challenges Encountered
Managing false positive and negative rates.
The necessity of a balanced dataset.
Variability in model performance based on the train-test split.
Future Directions
Incorporating more features and external data sources to improve model accuracy.
Conducting extensive research on profit models.
Real-world testing with a futures trading account.
Conclusion
Our exploration into using data science for Bitcoin price prediction has shown potential, particularly in leveraging machine learning algorithms. While challenges remain, there is promising groundwork for further development and application in the finance sector.
