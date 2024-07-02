# housing-trend-predictor

*The dataset being used here is too limited for a model to make meaningful predictions. The model, trained on data 2000-2019, makes a reasonable prediction based on the limited data that a bust will occur in 2021 comparable to the 2008 bust, because it predicts a wave-like pattern with a period of 12 years. (In reality, housing prices have almost monotonically increased since 2008.) Would be better supplemented by data about number of divorces, retirees, etc., any number of things. Might return to this later.*

We are using time-series data found on Kaggle on US housing trends to analyze correlations between average home values, average time on market, and average price cuts. The dataset contains the average home value by city by month from 2000-2024, and from 2018-2024 it includes monthly data about average time on market and price cuts. We also use a support vector machine (SVM) to predict housing prices.

The dataset can be found here, or otherwise in this repository: https://www.kaggle.com/datasets/clovisdalmolinvieira/us-housing-trends-values-time-and-price-cuts
