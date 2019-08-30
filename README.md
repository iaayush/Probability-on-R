# Probability on R
 Using R to perform some probability calculations and imputation. There are plots included as well.

# RMD or *R Markdown* file
The code for calculating the probabilities along with comments to explain each step. Use this file to knit html/pdf (packages maybe be required).

# Task 1: calculate conditional probability of an event
Tossing a fair die 7 times. Consider the following events, A = “each value appears at least once” and B = “the outcome is alternate in numbers (i.e., no two values are adajacent)”. What is p(A|B)? Solve this analytically (a formula) and experimentally by simulation, in each case printing the value found. 

# Task 2: Entropy
Given the Boolean dataset “FIT5197 2018 S1 Assignment1 Q2 data.csv” which contains 2 discrete random variables X and Y, and 100 samples with missing values (NA). Do the following:
1. handle NAs by mode imputation, and plot indivdual variables in a histogram with proper axis labels and title.
2. calculate and report full tables for p(X), p(Y), p(X, Y), p(X|Y), p(Y|X).
3. calculate and report H(X), H(Y), H(X|Y) and H(Y|X)   

# Task 3: Correlations and Covariance
Assume X and Y are two independent standard Gaussian random variables, U = X − Y and V = 2X + 3Y. What is the correlation and covariance between U and V? Solve the questions analytically, then confirm your analytical results using 1, 000, 000 simulation.

# Task 4: maximum likelihood estimation of parameters
You are told the following data [4,3,2,4,6,3,4,0,5,6,4,4,4,5,3,3,4,5,4,5]
comes from a Poisson distribution with unknown parameter λ. Solve the MLE of a Poisson parameter analytically and numerically without using existing mle functions in R. Hint: you should first define a log likelihood function. Then use the optimize() function in R to find the optimal parameters for the given dataset.

# Task 5: central limit theorem
Consider sampling a sequence of 10 i.i.d. random variables from a Poisson distribution with λ = 10. For this, experimentally justify the central limit theorem using simulation with sample size 100, 1000, 10000 and 100000. You should compute both theoretical and sample mean and sd. In addition, plot each result in a histogram with the theoretical Gaussian curve. In the first instance (sample size 100), this means you generate 100 such samples of size 10, and compute their means to get 100 means. Then plot the 100 means in a histogram and report the sample mean and sample standard deviation of the 100 values. Compare these with the theoretical values. Then repeat for the other sizes.
