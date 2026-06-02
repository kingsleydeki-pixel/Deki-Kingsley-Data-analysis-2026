HOME-WORK 3-4 SUMMARY

Overview
This comprehensive analysis examines hormone-related variables in a biomedical dataset (data_for_analysis) comparing two independent groups defined by the outcome
variable (0 and 1). The dataset contains 1,148 observations with 9 hormone variables analyzed across both groups.

Key Findings

Sample sizes: Outcome 0 (n=987), Outcome 1 (n=160)

Normality: All hormone variables significantly deviate from normal distribution in both groups (Shapiro-Wilk p < 0.05)

Variance: No consistent evidence of unequal variances across groups (Levene's test p > 0.05 for most variables)

Group differences: Hormone2, hormone5, and hormone8 showed statistically significant differences between outcome groups

Correlation patterns: Spearman correlation matrices revealed different association structures between hormone variables across the two outcome groups

Statistical Methods Applied

Descriptive statistics (mean, SD, median, quartiles) by group

Shapiro-Wilk test for normality assessment

Levene's test for homogeneity of variance


Histograms & Q-Q plots for visual distribution analysis


Brunner-Munzel test (primary), Wilcoxon rank-sum test, and Student's t-test for group comparisons


Spearman correlation heatmaps (selected due to non-normal distributions)

Conclusion
Due to the non-normal distribution of all hormone variables, non-parametric or robust methods (Brunner-Munzel, Wilcoxon) are most appropriate for inference. 
The analysis identified hormone2, hormone5, and hormone8 as showing the strongest evidence of differences between outcome groups, 
while correlation structures among hormones varied by outcome status
