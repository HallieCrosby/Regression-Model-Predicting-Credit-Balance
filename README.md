# Regression Model Predicting Credit Balance
#### Apache Spark: Model building with Scala

Using the `Credit.csv` dataset from [ISLR](http://www-bcf.usc.edu/~gareth/ISL/data.html), I built a regression model to predict the credit balance (`Balance`) given the following features:

- Income
- Limit
- Rating
- Cards
- Age
- Education
- Gender*
- Student*
- Married*
- Ethnicity**

*Indexed with `StringIndexer`

**Indexed with `StringIndexer` and one-hot encoded with `OneHotEncoder`


## Train/Test split
1. The data was split into an 80/20 train/test split.
2. The R2 score from the test set was 0.97


## Published  Notebook
** DataBricks Notebook URL: https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/4542248418852910/500774070814786/4051759718773976/latest.html**