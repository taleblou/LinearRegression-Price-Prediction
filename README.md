# **SVR Model for Financial Predictions**

This repository contains an implementation of an Linear Regression model, specifically designed for predicting the prices of financial instruments such as currencies, stocks, and cryptocurrencies. The Linear Regression algorithm leverages gradient boosting techniques, enabling it to capture intricate patterns in price movements and handle various dataset characteristics effectively. This approach enhances the accuracy and robustness of price forecasts across various datasets.

This is the original code sample for the Linear Regression model. Explore my GitHub repository for additional models and implementations that cater to different financial prediction needs.

## **Performance Metrics**

### 

### **BTC-USD (Bitcoin)**

| Metric | Open | High | Low | Close |
| :---- | :---- | :---- | :---- | :---- |
| Mean Squared Error | 0.000824 | 0.000706 | 0.000892 | 0.000830 |
| Mean Absolute Error | 0.0213 | 0.0190 | 0.0226 | 0.0215 |
| R-squared | 0.9642 | 0.9699 | 0.9609 | 0.9650 |
| Median Absolute Error | 0.0160 | 0.0141 | 0.0181 | 0.0164 |
| Explained Variance Score | 0.9648 | 0.9704 | 0.9615 | 0.9656 |

### **![][image1]**

### **GC=F (Gold Futures)**

| Metric | Open | High | Low | Close |
| :---- | :---- | :---- | :---- | :---- |
| Mean Squared Error | 0.000840 | 0.000801 | 0.000778 | 0.000842 |
| Mean Absolute Error | 0.0233 | 0.0224 | 0.0220 | 0.0231 |
| R-squared | 0.9587 | 0.9602 | 0.9619 | 0.9583 |
| Median Absolute Error | 0.0183 | 0.0195 | 0.0182 | 0.0204 |
| Explained Variance Score | 0.9595 | 0.9608 | 0.9625 | 0.9590 |

### **![][image2]**

### **EURUSD (Euro/US Dollar)**

| Metric | Open | High | Low | Close |
| ----- | ----- | ----- | ----- | ----- |
| Mean Squared Error | 0.000428 | 0.000405 | 0.000388 | 0.000428 |
| Mean Absolute Error | 0.0163 | 0.0155 | 0.0155 | 0.0163 |
| R-squared | 0.9023 | 0.9097 | 0.9132 | 0.9024 |
| Median Absolute Error | 0.0135 | 0.0129 | 0.0120 | 0.0135 |
| Explained Variance Score | 0.9028 | 0.9102 | 0.9136 | 0.9029 |

 

### **![][image3]**

### **GSPC (S\&P 500 Index)**

| Metric | Open | High | Low | Close |
| :---- | :---- | :---- | :---- | :---- |
| Mean Squared Error | 0.000586 | 0.000480 | 0.000578 | 0.000604 |
| Mean Absolute Error | 0.0174 | 0.0158 | 0.0177 | 0.0183 |
| R-squared | 0.9568 | 0.9663 | 0.9573 | 0.9576 |
| Median Absolute Error | 0.0142 | 0.0121 | 0.0136 | 0.0141 |
| Explained Variance Score | 0.9578 | 0.9671 | 0.9583 | 0.9588 |

### **![][image4]**


## **Related Websites**

### [**Predict Price**](https://predict-price.com/)

Free AI-powered short-term (5/10/30 days) and long-term (6 months/1/2 years) forecasts for cryptocurrencies, stocks, ETFs, currencies, indices, and mutual funds.

### [**Magical Prediction**](https://magicalprediction.com/)

Get free trading signals generated by advanced AI models. Enhance your trading strategy with accurate, real-time market predictions powered by AI.

### [**Magical Analysis**](https://magicalanalysis.com/)

Discover free trading signals powered by expert technical analysis. Boost your forex, stock, and crypto trading strategy with real-time market insights.

## **About This Project**

This Linear Regression model is an initial implementation, released for public use. The project demonstrates the potential of deep learning models for financial predictions. While this repository focuses on Linear Regression, I have also utilized other models, the code for which is available on my GitHub[https://github.com/taleblou/].

## **How to Use**

1. Clone this repository.  
2. Install the required libraries: `pip install -r requirements.txt`  
3. Prepare your dataset and follow the instructions in the notebook or script.  
4. Run the model and evaluate its performance using the provided metrics.

## **License**

This project is open-source and available for public use under the MIT License. Contributions and feedback are welcome\!

[image1]: <https://raw.githubusercontent.com/taleblou/LinearRegression-Price-Prediction/refs/heads/main/Plot/LinearRegression_BTC-USD.png>
[image2]: <https://raw.githubusercontent.com/taleblou/LinearRegression-Price-Prediction/refs/heads/main/Plot/LinearRegression_GC%3DF.png>
[image3]: <https://raw.githubusercontent.com/taleblou/LinearRegression-Price-Prediction/refs/heads/main/Plot/LinearRegression_EURUSD%3DX.png>
[image4]: <https://raw.githubusercontent.com/taleblou/LinearRegression-Price-Prediction/refs/heads/main/Plot/LinearRegression_%5EGSPC.png>