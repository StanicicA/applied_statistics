## Applied_Statistics

This repository contains my assessment submission for the Applied Statistic module in the following three notebooks: 

## 1. tasks.ipynb

Four answers to the following list of tasks can be found in this notebook:

1. Permutations and Combinations
2. numpy's Normal Distribution
3. t-Test Calculation
4. ANOVA

## 2. project.ipyb
In this notebook, I have analysed the Plant Growth dataset using the T test and ANOVA statistical test.

A t-test is an inferential statistic used to determine if there is a statistically significant difference between the means of two population samples. It is used in statistics for hypothesis testing and can indicate whether differences between two populations are meaningful or random.

The t-test calculation uses three data: the difference between the mean values from each data set, the standard deviation of each group, and the number of data values. There are different variations of the t-test formula. Which one to use depends on factors such as the similarity of the sample records, the size of each data set, and the variance of each set. However, each variation of the t-test is used to investigate the same statistical question.

In this case, I performed a t-test to compare the means of the treatment groups ‘trt1’ and ‘trt2’. The results have shown that there is a significant difference in the mean weights of plants between treatment groups trt1 and trt2.

When performing using ANOVA statistical test to determine whether there is a significant difference between the three treatment groups ctrl, trt1, and trt2, the results have shown that the p-value is less than 0.05, so we can reject the null hypothesis meaning there is a significant difference in the mean weights of plants among the three groups (ctrl, trt1, and trt2).

## 3. mywork.ipynb

GitHub repository containing additional exercises made in this module

## Literature:
1. https://docs.python.org/3/library/math.html#math.comb
2. https://peps.python.org/pep-0008/
3. https://en.wikipedia.org/wiki/Normal_distribution
4. https://docs.python.org/3/tutorial/datastructures.html#sets
5. https://docs.python.org/3.12/library/math.html#math.factorial
6. https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.ttest_rel.html#ttest-rel
7. https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.f_oneway.html
8. https://statistics.laerd.com/spss-tutorials/one-way-anova-using-spss-statistics.php
9. https://en.wikipedia.org/wiki/F-test#One-way_analysis_of_variance
10. https://www.jstor.org/stable/2331554
11. https://www.scirp.org/reference/referencespapers?referenceid=2056938
12. https://vincentarelbundock.github.io/Rdatasets/doc/datasets/PlantGrowth.html
13. https://www.scribbr.com/statistics/t-test/#:~:text=A%20t%20test%20is%20a,are%20different%20from%20one%20another.
14. https://datatab.net/tutorial/t-test
15. https://en.wikipedia.org/wiki/Student%27s_t-test
16. https://www.investopedia.com/terms/t/t-test.asp
17. https://www.scribbr.com/statistics/t-test/#:~:text=A%20t%20test%20is%20a,are%20different%20from%20one%20another.
18. https://www.agrowtronics.com/plant-growth-stages-an-overview/