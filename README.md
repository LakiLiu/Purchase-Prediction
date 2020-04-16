# Purchase-Prediction
---

Retail Company want to suggest consumers products they are interested to buy. We track all user's acitivites across the wesite. The data includes the last purhcase time
as well as other features. C1 to C10 is the categorical features, and N1-N9 are numercial features. For the privacy, all the data is hashed.

From the collected data, we want to predict the probability that a specific user will make a purchase.

Attention: This dataset is highly imbalanced, with less than 1% case to purchase compared to not purchase

With a baseline model (**0.4 F1 score**), we successfully improve to **0.9** after dealing with imbalanced classes by applying both undersampling and oversampling.
