# Randomization-Post-Hoc-Test

This code was developed by Montgomery College student, Adi V. (2022) 

This code creates a function for a dataset such that the input "treatment" a long-format categorical variable and the input "outcome" is a long-format quantitative variable. It should be used as a post hoc test to a non-parametric analysis of variance or an alternative to the two-sample t-test.

The format for performing the test is as follows:
adi_saidi.RPT(<data$treatment_variable>, <data$outcome_variable>, <n = number of times to resample>, <plot_dist = "TRUE/FALSE">)
the plot_dist variable will plot all distributions of differences in pairwise means.


