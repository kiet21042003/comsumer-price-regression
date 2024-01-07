# Consumer Spending Analysis Project

## Introduction
The data set includes data from a direct marketer who sells his products only via direct mail. He sends catalogs with product characteristics to customers who then order directly from the catalogs. The marketer has developed customer records to learn what makes some customers spend more than others.

The objective of this predictive modeling exercise is to predict the amount that will be spent in terms of the provided customer characteristics for a direct marketer who sells his products via mail. This analysis will be useful for the marketer to make strategic decisions about advertising and targetting a selected group of potential customers based on the amount that they are predicted to spend in the future.

## Dataset Description
[Dataset link](https://github.com/user/repo/blob/branch/other_file.md)
The dataset DirectMarketing.csv contains 1000 records and 18 attributes. But only the first 10 columns are significant, 8 remaining columns are just one-hot encoded attributes from the first 10 row. As one-hot encoding is only used for linear regression part, so we decided to remove 8 last rows in Exploratory Data Analysis part for better speed.

## Conclusion:
- The data is great for linear regression exercises but the encoded attributes is not good enough, and there are some missing values in `History` attributes.
- Data analysis is the most interesting part when we could get the insights of the data set
- Some simple resgression are built but the results are quite good.
- Some machine learning algorithms could be used in further works like: KNN, SVR, Random Forests,...
