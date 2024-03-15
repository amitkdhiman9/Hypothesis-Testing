# Hypothesis-Testing
Hypothesis Testing is basically to check whether the difference between the means (or ratio) of two samples is statistically significant. But what do we mean by "statistically significant"? It means that there is definitely some significant amount of difference between the two means (or ratios) and this difference is not by chance/luck, this difference has some statistical significance to it.
For Hypothesis Testing I will work on Environmental Protection Agency's Air Quality Index Data. I will leverage AQI data to help America's government to prioritize their strategy for improving air quality.

I will consider the following activities. For each, I will construct a hypothesis test and use my results of that test to make a recommendation: <br>
1. I will consider a metropolitan-focused approach. Within California, I want to know if the mean AQI in Los Angeles County is statistically different from the rest of California. <br>
2. I will check between New York and Ohio which has a better AQI and check whether there's a statistical significance between their means? <br>
3. I will check if Michigan has a mean AQI of 10 or higher? <br>

Notes:

1. For this analysis, I'll default to a 5% level of significance. <br>
2. Throughout the lab, for two-sample t-tests, use Welch's t-test (i.e., setting the equal_var parameter to False in scipy.stats.ttest_ind()). This will account for the possibly unequal variances between the two groups in the comparison.
