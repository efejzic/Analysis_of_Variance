# Analysis of Variance

**Introduction**

This analysis will look at a linear model to partition the total variation (variance) for a variable of interest using one categorical variable (one-way ANOVA), or two categorical variables (two-way ANOVA) as the model (explained variation). An SRS of 80 will be drawn independently from three populations based on diet quality (good diet, fair diet, and poor diet) from a total of 350 subjects each and analyzed using **Minitab statistical software**.

**Objectives**

The objective of this analysis is to understand the concept of linear models, the assumptions underlying ANOVA analysis and how to state an ANOVA hypothesis. An experiment in which two or more factors are investigated simultaneously is called a factorial experiment. For the three populations, ANOVA and Tukey testing will be performed. The two measures of quality we will look at is explanatory power of the model given as the ratio of the explained variation to the total variation, and the statistical significance of the model p-value and F test statistic, using hypothesis testing concepts. The objective is to identify whether the researcher can conclude that the three populations differ with respect to mean RBC folate value. 

**Data Description of Variables**

![image](https://github.com/user-attachments/assets/2cf6245a-4bbd-47f5-9a68-5cd8fa3f9bb9)

_**Note**_: Red blood cell is noted as RBC.

**Data**
**File Name**: LDS_CO8_RBCDATA.xlsx

* Variables OBSERV, GOOD, FAIR, POOR represent original data with 350 observations per population, with a total of 1050 observations.

* 3 populations (OBSERV, GOOD), (OBSERV, FAIR), and (OBSERV, POOR)

* Simple Random Sample of 80:

  o (OBSERV, GOOD) → (ID_GOOD_S, GOOD_S)

  o (OBSERV, FAIR) → (ID_FAIR_S, FAIR_S),

  o (OBSERV, POOR) → (ID_POOR_S, POOR_S)

![image](https://github.com/user-attachments/assets/ba935a2b-f771-478a-965f-31a06ef1169b)

![image](https://github.com/user-attachments/assets/c0ef2e33-f9ec-42f2-8153-20ace005c544)

**Results and Discussion** 

Necessary assumptions for this analysis include:

  > Sampled populations will have a normal distribution;

  > Sampled populations will have equal variances;

  > Sampled populations are independently and randomly sampled

_Grubbs Test_

LDS_CO8_RBCDATA

The Grubbs test is used to identify a single outlier within a dataset.

o **G** – the test statistic where a larger value indicates stronger deviation from the mean.

o **U** – critical value based on the significance level of 0.05

  **Outlier Test:** GOOD_S, FAIR_S, POOR_S

  **Method**

  Null hypothesis – All data values come from the same normal population.
  
  Alternative hypothesis – Smallest or largest value is an outlier.
  
  Significance level: α = 0.05

  ![image](https://github.com/user-attachments/assets/79c42a91-ea14-4355-888e-59a139971629)

_**NOTE**_ No outlier at the 5% level of significance


![image](https://github.com/user-attachments/assets/1402340a-cb4d-4c13-ae8a-93ea79b0c57b)


![image](https://github.com/user-attachments/assets/ced567c6-cac6-46b3-90ce-696fa13b17fb)


![image](https://github.com/user-attachments/assets/0fc2c435-e9b3-48a9-bef9-3ebf1b840d30)

* There is no observable outlier in either of the three populations (GOOD_S, FAIR_S, and POOR_S)

_Descriptive Statistics_

LDS_CO8_RBCDATA

![image](https://github.com/user-attachments/assets/951ad7c4-c72a-46cc-ac72-30508353bdfd)

![image](https://github.com/user-attachments/assets/95a47946-8b22-4069-9786-3f4d701450fb)

* For SRS of 80, the maximum for population GOOD_S is 331 (µg/L), while the minimum is 246 (µg/L) with a range of 85 (µg/L).

* For SRS of 80, the maximum for population FAIR_S is 271 (µg/L), while the minimum is 206 (µg/L) with a range of 65 (µg/L).

* For SRS of 80, the maximum for population POOR_S is 233 (µg/L), while the minimum is 165 (µg/L) with a range of 61 (µg/L).

![image](https://github.com/user-attachments/assets/a5d66120-a7e7-4dd8-a9af-0af43cf2da89)

* The skew for variable GOOD_S is -0.159162, a negative number indicating a slight leftward skew, and the kurtosis is 0.489233, indicating a slight peak when compared to a normal distribution. The 95 percent confidence interval of the mean falls between 290.22 and 297.18

![image](https://github.com/user-attachments/assets/4acb4d8b-8989-4151-9854-3670350c7200)

* The skew for variable FAIR_S is 0.095394, indicating a rightward skew and the kurtosis is negative at -0.313563, suggesting lighter tails in the distribution. The 95 percent confidence interval of the mean falls between 234.28 and 240.62.

![image](https://github.com/user-attachments/assets/0a2009fb-516f-4036-90bf-232280b10387)

* The skew for variable POOR_S is 0.045230, indicating a rightward skew and the kurtosis is 0.155582, suggesting a relatively normal distribution with a slight peak. The 95 percent confidence interval of the mean falls between 193.78 and 200.22.
  
_Box Plots_

LDS_CO8_RBCDATA

![image](https://github.com/user-attachments/assets/e5dd0443-a74d-498f-982c-04b9f6f840f4)

* With an SRS of 80 each, we can observe that population with a diet quality of “Good” has a higher RBC folate level with a median of 295 µg/L compared to population “Fair”, median of 237 µg/L and “Poor”, median of 197 µg/L.

![image](https://github.com/user-attachments/assets/ac851904-d6e7-470c-8881-6f6c2efcacae)

_One-way ANOVA Test_
_Equal variance assumed._

LDS_CO8_RBCDATA

**Method**

H0: Null hypothesis – All data values come from the same normal population.

HA: Alternative hypothesis – Smallest or largest value is an outlier.

Significance level: α = 0.05

![image](https://github.com/user-attachments/assets/488354af-d8d7-4e12-b9e3-78b239e6776b)

![image](https://github.com/user-attachments/assets/b8ba215f-089b-42a3-a7e5-0878e4c4409a)

_Pooled StDev = 14.8509_

_Tukey Pairwise Comparisons_

LDS_CO8_RBCDATA

![image](https://github.com/user-attachments/assets/02353559-e526-47c1-a6f5-3d470fcfb29c)

_Tukey Simultaneous CIs_

LDS_CO8_RBCDATA

![image](https://github.com/user-attachments/assets/8f657329-7f37-46c0-a5cb-d0d148b981d6)

![image](https://github.com/user-attachments/assets/f3ddc46b-f9c5-4c38-a61b-3459968da276)

_F Distribution_

Numerator DF = 2

Denominator DF = 237

α = 0.05

Critical F value = 3.03392

Test statistic or F-Value = 851.99

P value = 0.00

* The Tukey simultaneous test for the difference in means produced the 95 percent confidence intervals for quality of diet FAIR_S to GOOD_S as (-61.80, -50.70), for POOR_S - GOOD_S as (-102.03, -90.94) and for POOR_S - FAIR_S as (-45.78, -34.69). The ranges for all populations are in the negative, therefore there is no 0 included which indicates that there is a statistically significant variation in mean between each of the populations. The T-value for FAIR_S - GOOD_S was 23.96, for POOR_S - GOOD_S it was -41.09, and for POOR_S - FAIR_S it was -17.14. All populations had the same p value of 0.000. Since the F statistic is greater than the critical value, we can reject the null hypothesis H0, at the 0.05 level of significance. The difference for all three populations is statistically significant at the 0.05 level of significance.

_Interval Plot_

LDS_CO8_RBCDATA

![image](https://github.com/user-attachments/assets/c984789e-3dde-449b-b66b-269b39f39a52)


* The highest folate level µg/L value for population GOOD_S was 331 µg/L while the lowest value was 246 µg/L. The range is 85 µg/L. The highest value for population FAIR_S was 271 µg/L while the lowest value was 271 µg/L. The range is µg/L. The highest value for population POOR_S was 233 µg/L while the lowest value was 233 µg/L. The range is 68 µg/L.

_Individual Value Plot_

LDS_CO8_RBCDATA

![image](https://github.com/user-attachments/assets/e8596091-2740-42f3-90af-ee73ed23a64e)

* The individual value plot represents the results of the Tukey simultaneous CI test. The means of all three populations are statistically significant, so the distribution will be varied

_Box Plot_

LDS_CO8_RBCDATA

![image](https://github.com/user-attachments/assets/d22b1aa9-9f4b-400f-86f0-6de32b62f081)

* For population diet quality of GOOD_S, the 25th percentile is 283.25 µg/L, 50th percentile is 295 µg/L and 75th percentile is 305 µg/L. For population FAIR_S, the 25th percentile is 228 µg/L, 50th percentile is 237 µg/L, and 75th percentile is 247.75 µg/L. For population POOR_S, the 25th percentile 190 µg/L, the 50th percentile 197 µg/L and the 75th percentile is 208 µg/L. A population with a good diet quality has higher folate levels and a population with a poor diet quality has less folate levels.

_Residual Plots_

LDS_CO8_RBCDATA

![image](https://github.com/user-attachments/assets/adb1a4e0-edf8-448b-bac5-972f720756c0)

* Residual plots are used to test the assumptions of linearity and equal variances in the data (Daniel, 2018). In the normal probability test, the x-axis represents the observed values of residuals from the regression model and the y-axis represents the quantiles of a normal distribution. The plots form a straight line which suggests that the residuals are approximately normally distributed, supporting the assumption of normality.

**Conclusion**

In this study, the quality of diet (good, fair, and poor) was observed by RBC folate value (in μg/liter of red cells). The objective is to identify whether the researcher can conclude that the three populations differ with respect to mean RBC folate value. It is assumed that sampled populations will have a normal distribution, sampled populations will have equal variances, and that sampled populations are independently and randomly sampled. Variables OBSERV, GOOD, FAIR, POOR represent original data with 350 observations per population, with a total of 1050 observations and were simply randomly sampled (SRS) for 80 observations each. The Tukey simultaneous test for the difference in means produced 95 percent confidence intervals for all three populations that do not include the value of 0 (the ranges for all populations were in the negatives). We are rejecting the null hypothesis H0 and concluding that at the 0.05 level of significance, the difference in means is statistically significant.





