# [Forecasting Sticker Sales](https://www.kaggle.com/competitions/playground-series-s5e1)

For this challenge, you will be predicting multiple years worth of sales for various Kaggle-branded stickers from different fictitious stores in different (real!) countries. This dataset is completely synthetic, but contains many effects you see in real-world data, e.g., weekend and holiday effect, seasonality, etc.

___

I use a combination of XGBoost regressor and linear regression - the first for the prediction of daily and monthly patterns and the second for yearly trends. I also use boosting regression to fill the missing values in the dataset. The model is rather simplistic, however results in the mean absolute percentage error of 0.1386 (top 27% of results in the corresponding Kaggle competetion). 
