# BitcoinTradingStrategy

The problem of predicting a buy or sell signal for a trading strategy is defined in the
classification framework, where the predicted variable has a value of 1 for buy and 0
for sell.

**Conclusion:**

We showed that framing the problem is the first priority and we address it by engi‐ neering the features and transforming the labels according to the investment objective.

We demonstrated the efficiency of using feature engineering that leads to creation of intuitive features related to the trend and momentum of the price movement and increases the predictive power of the model.

In terms of the evaluation metrics for a classification-based trading strategy, accuracy or auc are appropriate, but in case the strategy is focusing to be more accurate while going long, the metric recall which focuses on less false positive can be preferred as compared to accuracy.

Finally, we demonstrated the backtesting framework which allows us to simulate a trading strategy using historical data to generate results and analyze risk and profita‐ bility before risking any actual capital.

