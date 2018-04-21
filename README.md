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
