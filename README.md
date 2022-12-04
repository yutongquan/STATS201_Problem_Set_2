# Machine Learning for Time Series Prediction: Daily Return on Investment of Bitcoin
## Project information
- **Author**: Yutong Quan, Political Economy (Economics), Class of 2024, Duke Kunshan University
- **Instructor**: Prof. Luyao Zhang, Duke Kunshan University
- **Disclaimer**: Submissions to the Problem Set 2 for STATS201 Introduction to Machine Learning for Social Science, 2022 Autumn Term (Seven Week - Second) instructed by Prof. Luyao Zhang at Duke Kunshan University.
- **Acknowledgments**: First, I would like to express my deepest gratitude to Prof. Luyao Zhang for her generous and inspiring instrutions on machine learning method for data explanation and prediction. Then, I am also grateful to Jakob Aungiers for his great research on [Time Series Prediction Using LSTM Deep Neural Networks](https://www.altumintelligence.com/articles/a/Time-Series-Prediction-Using-LSTM-Deep-Neural-Networks) which has inspired me on applying machine learning method into financial industry.
- **Project Summary**:Time series forecasting using machine learning methods has been widely used in the financial industry. Aungiers(2018) used LSTM deep neural networks to predict the market volatility of S&P 500 Equity Index. His research inspired me to apply machine learning methods to predict the future market of cryptocurrencies. Since deep neural networks are a complex machine learning method, this project starts with a simpler method provided by Prof. Luyao Zhang in class, including the use of Ridge regression and classification. In general, this project applies machine learning methods to predict the daily return of Bitcoin by using historic time series data (Open, High, Low, Close prices and daily Volume) from March 2020 to November 2022. This project provides a foundation for my future research to explore more machine learning algorithms.

## Part I: Machine Learning for Explanation
[Github Repository: STATS201_Problem_Set_2_Explanation](https://github.com/yutongquan/STATS201_Problem_Set_2_Explanation)

## Part II: Machine Learning for Prediction
### Table of Contents
- [data](https://github.com/yutongquan/STATS201_Problem_Set_2/tree/main/Data)
- [code](https://github.com/yutongquan/STATS201_Problem_Set_2/tree/main/Code)
- [spotlight](https://github.com/yutongquan/STATS201_Problem_Set_2/tree/main/Spotlight)

### Data
- Data Source: https://www.alphavantage.co/documentation/#digital-currency
- [Queried Data](https://github.com/yutongquan/STATS201_Problem_Set_2/tree/main/Data/queried_data)
- [Processed Data](https://github.com/yutongquan/STATS201_Problem_Set_2/tree/main/Data/processed_data)

### Code
- [Process Data](https://github.com/yutongquan/STATS201_Problem_Set_2/blob/main/Code/Process_Data.ipynb)
- [Analyze Data](https://github.com/yutongquan/STATS201_Problem_Set_2/blob/main/Code/Analyze_Data.ipynb)

### Spotlight
![Confusion Matrix](https://github.com/yutongquan/STATS201_Problem_Set_2/blob/main/Spotlight/Confusion%20Matrix_Ridge%20Classfier.png)

*Figure No.1. Source: [Alpha Vantage: Digital & Crypto Currencies/DIGITAL_CURRENCY_DAILY](https://www.alphavantage.co/documentation/#digital-currency), created by [Scikit Learn: Ridge regression and classification](https://scikit-learn.org/stable/modules/linear_model.html#ridge-regression-and-classification)*

## References

### Data Source
[Alpha Vantage: Digital & Crypto Currencies/DIGITAL_CURRENCY_DAILY](https://www.alphavantage.co/documentation/#digital-currency)
### Code Source
[stats201-tutorial-prediction/code](https://github.com/Rising-Stars-by-Sunshine/stats201-tutorial-prediction/tree/main/code)
### Articles
[Time Series Prediction Using LSTM Deep Neural Networks](https://www.altumintelligence.com/articles/a/Time-Series-Prediction-Using-LSTM-Deep-Neural-Networks)
### Literature
Aungiers, Jakob. 2018. “Time Series Prediction Using LSTM Deep Neural Networks.” Www.altumintelligence.com. September 1, 2018. https://www.altumintelligence.com/articles/a/Time-Series-Prediction-Using-LSTM-Deep-Neural-Networks.


