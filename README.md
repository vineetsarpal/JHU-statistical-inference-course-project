## Introduction
The project consists of two parts:
* A simulation exercise
* Basic inferential data analysis

### Part 1: Simulation Exercise Instructions 
In this project we will investigate the exponential distribution in R and compare it with the Central Limit Theorem. The exponential distribution can be simulated in R with rexp(n, lambda) where lambda is the rate parameter. The mean of exponential distribution is 1/lambda and the standard deviation is also 1/lambda. Set lambda = 0.2 for all of the simulations. We will investigate the distribution of averages of 40 exponentials by doing a thousand simulations.
Illustrate via simulation and associated explanatory text the properties of the distribution of the mean of 40 exponentials. We will:
* Show the sample mean and compare it to the theoretical mean of the distribution
* Show how variable the sample is (via variance) and compare it to the theoretical variance of the distribution
* Show that the distribution is approximately normal

### Part 2: Basic Inferential Data Analysis Instructions 
Now in the second portion of the project, we're going to analyze the ToothGrowth data in the R datasets package.
* Load the ToothGrowth data and perform some basic exploratory data analyses
* Provide a basic summary of the data
* Use confidence intervals and/or hypothesis tests to compare tooth growth by supp and dose
* State your conclusions and the assumptions needed for your conclusions
