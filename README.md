# Time-series-Analysis/ML-for-price-action-prediction
Using time series analysis, this research is to evaluate how different ML models perform in predicting stock market. The code uses several ML models, some are blind to temporal patterns (such as KNN, RF, SVM and NN) and some are developed particularly for time series (LSTM and 1D-CNN). 
## Method:
Data get stationary by differencing. Feature engineering is applied to extract features (mainly simple and exponential moving averages and their ratios and distances from spot price and spot volume) that could help predicting the direction of market. 

## Outcome:
1-Results show that all models perform badly for regression problem (predicting direction and extent of price action), but classification problem (predicting the direction) could be performed with a precision better than flipping a coin or always longing or shorting the market.

2- 1D-CNN performed best among the used models, nonetheless, surprisingly, models as simple as SVM or RF also could fit in a way that they showed predictability is attainable to some degree for out of sample test.

## Disclaimer and Final Conclusion: 
Although this work shows the importance of proper feature engineering and statistical analysis to help timing the market, the whole code is intended for educational purposes and no trade is recommended based on this reserach.
