# Statistics Intuition #
Motto: Idea is to provide intuitions around the statistical methods and concepts as a quick reference guide. These concepts are important when dealing with nature of the data and their effect.  
Note: There are numerous articles, blogs, forums and books giving detailed description on each of the topics mentioned here. Instead of making the contributions more redundant, here the assumption is that listeners have good understanding in statistics, this page can be referred as a quick guide.  


## Covariance Vs Correlation ##
Both are mathematical concepts to measure relationship between two random variables.
1. Correlation:
It states if a change in variabe A makes changes in variable B.
2. Covariation:
It states if variables A and B vary or change together. It is similar to variance that says how a single variable changes but covariance says how two variables change together.


What's in common:
1. Variables are positively related if they move in the same direction.
2. Variables are inversely related if they move in opposite directions.
3. Higher the values of covariance and correlation, stronger is the relationship.

Problems with Covariance:
Mathematical formula of covariance does not consider any standard scaling of variables when calculating the relationship. Hence as the scale changes (like from cm to meter to km), the value of covariance changes significantly. And it is difficult to interpret covariance coeficient.

Advantage of Correlation:
To solve the above problem, the covariance is devided by standard deviation to get Correlation coefficient. Unlike covariance, correlation coefficient varies between only -1 and 1. Hence it is independent of scale and gives the correct measure of relationship.

*Reference Links*  
https://www.linkedin.com/pulse/covariance-vs-correlation-kumar-p/  
https://stats.stackexchange.com/questions/18082/how-would-you-explain-the-difference-between-correlation-and-covariance  
http://ci.columbia.edu/ci/premba_test/c0331/s7/s7_5.html  
http://www.statisticshowto.com/covariance/  

### Finding Correlation ###
Correlation is a bivariate analysis that measures the strength of association between two variables and the direction of the relationship.  In terms of the strength of relationship, the value of the correlation coefficient varies between +1 and -1.  A value of ± 1 indicates a perfect degree of association between the two variables.  As the correlation coefficient value goes towards 0, the relationship between the two variables will be weaker.  The direction of the relationship is indicated by the sign of the coefficient; a + sign indicates a positive relationship and a – sign indicates a negative relationship. Usually, in statistics, we measure four types of correlations: Pearson correlation, Kendall rank correlation, Spearman correlation, and the Point-Biserial correlation.  The software below allows you to very easily conduct a correlation.  
Source: https://www.statisticssolutions.com/correlation-pearson-kendall-spearman/  
Code: https://chrisalbon.com/machine_learning/feature_selection/drop_highly_correlated_features/  

## Signal to Noise Ratio ##
Signal-to-noise ratio is defined as the ratio of the power of a signal (meaningful information) and the power of background noise (unwanted signal). If the variance of the signal and noise are known, and the signal and noise are both zero-mean, SNR can be represented as ratio of the variances.  
Source: https://en.wikipedia.org/wiki/Signal-to-noise_ratio  

## Difference between Collinearity and Interaction ##

Source: https://stats.stackexchange.com/questions/113733/what-is-the-difference-between-collinearity-and-interaction  


## N-way Interaction ##
If X1 and X2 are two independent variables and Y is dependent variable, in statistics Interaction says how X1 is predicting Y when it is taken as input combined with X2 and vice verca. In most of the cases X1 and X2 are catergorical values and it is studied by ANOVA. However if any of X1 and X2 is numeric, then moderated multiple regression analsis is used to study Interaction.  

N-way Interaction test: Where we want to study N number of X variables for their interaction.  

* Assumptions of ANOVA *
1. Normality of data  
i) A good way to visually determine if the data are normally distributed is by using a Q-Q plot.  If the
point follow Q-Q line then data follow a normal distribution if there is a lot of deviation from the line then
the data should be inspected further.  
ii)  Shapiro-Wilk test for normality is another good way to identify (using a null hypothesis of normal data) whether or not the data is from a normal distribution.  

2. Homogeneity of variance  
i) It can be determined using the Bartlett Test of Homogeneity of Variances  
ii)  Fligner-Killeen Test of Homogeneity of Variances  
Sources:https://en.wikipedia.org/wiki/Interaction_(statistics)  
https://statistical-research.com/wp-content/uploads/2012/10/2wayanova.pdf

## Laplace ##
https://en.wikipedia.org/wiki/Laplace_distribution  
https://stats.stackexchange.com/questions/224237/what-is-out-of-fold-average  
https://en.wikipedia.org/wiki/Differential_privacy  
https://en.wikipedia.org/wiki/Gumbel_distribution  
https://en.wikipedia.org/wiki/Location_parameter  

