Repository for the submission of the course project for the Johns Hopkins Statistical Inference course.

Overview
In this is the project for the statistical inference class we will use simulation to explore inference and do some simple inferential data analysis. The project consists of two parts:

1. A simulation exercise.
2. Basic inferential data analysis.

Project Summary

The following is a summary description of the project instructions
In this project you will investigate the exponential distribution in R and compare it with the Central Limit Theorem. The exponential distribution can be simulated in R with rexp(n, lambda) where lambda is the rate parameter. The mean of exponential distribution is 1/lambda and the standard deviation is also 1/lambda. Set lambda = 0.2 for all of the simulations. You will investigate the distribution of averages of 40 exponentials. Note that you will need to do a thousand simulations.

Illustrate via simulation and associated explanatory text the properties of the distribution of the mean of 40 exponentials.  You should
1. Show the sample mean and compare it to the theoretical mean of the distribution.
2. Show how variable the sample is (via variance) and compare it to the theoretical variance of the distribution.
3. Show that the distribution is approximately normal.

In point 3, focus on the difference between the distribution of a large collection of random exponentials and the distribution of a large collection of averages of 40 exponentials. 

As a motivating example, compare the distribution of 1000 random uniforms
hist(runif(1000))
and the distribution of 1000 averages of 40 random uniforms

mns = NULL
for (i in 1 : 1000) mns = c(mns, mean(runif(40)))
hist(mns)
This distribution looks far more Gaussian than the original uniform distribution!

This exercise is asking you to use your knowledge of the theory given in class to relate the two distributions.  
Confused?  Try re-watching video lecture 07 for a starter on how to complete this project.

Additional Information
I have created a report to answer the questions. The reports have been uploaded in pdf format.
