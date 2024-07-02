# housing-trend-predictor

We are using an SVM (support vector machine) trained on time-series data found on Kaggle on US housing trends to predict average home value over time. The dataset contains the average home value by city by month from 2000-2024, and from 2018-2024 it includes monthly data about average time on market and price cuts. 

*The dataset being used here is too limited for a model to make meaningful predictions. The model, trained on data 2000-2019, makes a reasonable prediction based on the limited data that a bust will occur in 2021 comparable to the 2008 bust, because it predicts a wave-like pattern with a period of 12 years. (In reality, housing prices have almost monotonically increased since 2008.) Would be better to analyze correlations to # of divorces, retirees, etc., any number of other factors. Might return to this later.*

![predicted housing values][predictedhomevalues.png]
*A reasonable guess, but no.*
