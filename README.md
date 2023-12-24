# Hypothesis-testing_Non-parametric-test_Sports

**Description**

This project leverages the pingouin package and hypothesis testing to answer the following question:

_Are more goals scored in women's international soccer matches than men's?_

H0 (null hypothesis): the mean number of goals scored in women's international soccer matches is the same as men's.
H1 (alternative hypothesis): the mean number of goals scored in women's international soccer matches is greater than men's.

After cleaning and merging the datasets, we determine the most suitable type of hypothesis test. We calculate the p-value and compare it to a pre-determined significance threshold (10%) to assert whether the hypothesis should be rejected or not. 

**Datasets**

We use two datasets containing the results of every official men's and women's international football match since the 19th century.This data is stored in two CSV files: women_results.csv and men_results.csv.

As the sport has changed over the years and performances likely depending on the tournament, we limit the data to FIFA World Cup matches (excluding qualifiers) since 2002-01-01.
