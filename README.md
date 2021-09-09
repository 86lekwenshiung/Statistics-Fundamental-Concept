# Statistic Concept

## 1.0 Introduction

Typical flow for choosing a Statistical Test.

[Source : Rebecca Bevans](https://www.scribbr.com/statistics/statistical-tests/)
<p>
<img src = '/images/flowchart.png'>
<p>

**Comparison Test**
 
Parametric statistical procedures rely on assumptions about the shape of the distribution (i.e., assume a normal distribution) in the underlying population and about the form or parameters (i.e., means and standard deviations) of the assumed distribution. 
  
Nonparametric statistical procedures rely on no or few assumptions about the shape or parameters of the population distribution from which the sample was drawn. 
  
|Analysis Type|Paramatric Procedure|Nonparametric Procedure|Example Question|
|---|---|---|---|
|Compare 2 independant group|Two-sample t-test / Independant t-tests|Wilcoxon ranksum test|Is the mean systolic blood pressure (at baseline) for patients assigned to placebo different from the mean for patients assigned to the treatment group?|
|Compare 2 quantitative measurement taken from same individual|Paired t-test|Wilcoxon signedrank test|Was there a significant change in systolic blood pressure between baseline and the six-month followup measurement in the treatment group? |
|Compare 2 or more independant groups|Analysis of Variance (ANOVA)|Kruskal-Wallis test| Was there a significant difference in the systolic blood mean pressure between the 3 groups|  
|Correlation between 2 quantitative variables|Pearson coefficient of correlation |Spearman’s rank correlation| Is systolic blood pressure associated with the patient’s age? |
  


## 2.0 Method Dictionary

|Notebook|Description|Notebook Key Feature|
|---|---|---|
|[2 Sample T-test](https://github.com/86lekwenshiung/Statistics-Fundamental-Concept/blob/master/Two-Sample%20T-Test.ipynb)| A/B Testing on Mobile Game's Level : Is there difference in Retention Rate at Level 30 and Level 40?| Levene Test <br> Shapiro Test <br> Wilcoxon ranksum test|

  
  ## 3.0 Credits and Resources
  
  - [Parametric vs Non - parametric](https://www.mayo.edu/research/documents/parametric-and-nonparametric-demystifying-the-terms/doc-20408960)
