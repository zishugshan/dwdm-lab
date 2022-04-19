Assignment Problem:
* First of all fill all missing values in Age and Fare with mean values. 
Q. 1: Using the data for age and fare attribute given in Titanic dataset, 
a. WAP to Plot histogram using singleton bucket. 
b. WAP to Plot an equal-width histogram of width 10. 
Q. 2: Using the data for age attribute given in Titanic dataset, WAP to perform following sampling techniques (Select 30% samples with following methods) 
a. Simple Random Sampling With Replacement. 
b. Simple Random Sampling Without Replacement.
c. Stratified Sampling. (use three intervals as per the range of attribute) 
d. Calculate mean and standard deviation after sampling and compare it with mean and standard deviation of original data. 
Q. 3: Using the data for age and fare attribute given in Titanic dataset, 
a. WAP for min-max normalization onto the range [0, 1]. 
b. WAP for z-score normalization. 
c. WAP to perform decimal scaling. 
d. Calculate mean and standard deviation after all types of normalization and compare it with mean and standard deviation of original data.
Approach Used:
The pyplot hist function is used to plot histograms with different bin values as required by the question.
For sampling we are using the secrets library which actually gives a random value each time it is run (for cryptographic purposes). For sampling with no replacement, we first make a set of all the indexes until it reaches a length of 30% of the total. After which, the sampled data is returned from those indexes. For stratified, the question asks us to make 3 strata. So, we divide into intervals, and pass each interval in the random sampling function with no replacement. The results are then appended and returned.
For normalization, we simply use the mathematical function and iterate over all the values to get the normalized values of the given data points.

Outputs:
Outputs attached after each code part, as in a Jupyter file.
