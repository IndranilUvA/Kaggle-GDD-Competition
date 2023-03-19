Another forecasting competition within Kaggle.
The official link of this competition is: https://www.kaggle.com/competitions/godaddy-microbusiness-density-forecasting
Forecasting period is March, April and May of 2023 and we did not have January and Febryary data.
This notebook is just to explore the weird pattern of SMAPE metric. This metric is a ratio based metric, meaning the SMAPE of (1,1.1) would be exactly equal to SMAPE(100, 110). This makes SMAPE a unique forecasting metric. Moreover, there is a weird pattern, we usually are safe if we over-predict than if we under-predict. Mostly, if we use a linear model, this pattern persists. I was wondering if Jensen's inequality plays a role here or not. Happy to be answered. 
