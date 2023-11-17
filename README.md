# Pauline0115.github.io
> [!NOTE]\
> Available ranks are S (top 1%), A+ (12.5%), A (25%), A- (37.5%), B+ (50%), B (62.5%), B- (75%), C+ (87.5%) and C (everyone). This ranking scheme is based on the [Japanese academic grading](https://wikipedia.org/wiki/Academic_grading_in_Japan) system. The global percentile is calculated as a weighted sum of percentiles for each statistic (number of commits, pull requests, reviews, issues, stars and followers), based on the cumulative distribution function of the [exponential](https://wikipedia.org/wiki/exponential_distribution) and the [log-normal](https://wikipedia.org/wiki/Log-normal_distribution) distributions. The implementation can be investigated at [src/calculateRank.js](https://github.com/anuraghazra/github-readme-stats/blob/master/src/calculateRank.js). The circle around the rank shows 100 minus the global percentile.

# 💡💡Experiment
# 1. *_hidden layer formula_
🔎(N_s)/((alpha*(N_i+N_o))+(1-alpha)*(N_i_pre)):<br>
+  Based on 
![Training & Validation Loss over Epochs](./chart/new_formula_1.png)
# 2. *_empirical rule_
🔎(N_s)/(alpha*(N_i+N_o)):<br>
+  Based on the behavior of the loss function, it is suggested to limit the training epochs to 60 to prevent overfitting. 
![Training & Validation Loss over Epochs](./chart/empirical-rule.png)
# 3. *_user defined_
hidden_size1 = 20  # Number of neurons in the first hidden layer<br>
hidden_size2 = 10  # Number of neurons in the second hidden layer
![Training & Validation Loss over Epochs](./chart/user-defined.png)







# 🔦 :flashlight: 做實驗
# 🔎 做實驗
# 🤯 做實驗
