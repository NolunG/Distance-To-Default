# Distance-To-Default

Computed Distance do Default for random 250 firms from the COMPUSTAT universe, each year from 1970 to 2020.

Used 3 methods to calculate distance to default. Alll 3 methods and Formuales are added as a picture.

Method 1: Naive Computation using the KMV model 

Method 2: Directly Solving for the Unknowns

Method 3: Distance Default using the KMV model: Iterative Method

Merged COMPUSTAT and CRSP data to get fundamental and market variables respectively.
Computed DD and PD for these firms for each year (as of Jan 1 of each year)
Tabulate the following for the three DD and PD measures
Number of observations
Mean,
, and percentiles and
standard deviation
Minimum and Maximum of the variable
Compute the correlations between these three measures of DD and PD
Plot the mean, , and percentiles of DD for the three measures across time (for
each year). Do you see any trends?
Get NBER recession data https://research.stlouisfed.org/fred2/series/USREC
Compute the descriptive statistics for NBER recession and NBER recession . Plot DD
and PD with the recession data. What do you notice?
Get Moody's BAA-Fed Fund Spread https://research.stlouisfed.org/fred2/series/BAAFFM
Plot DD and PD along with BAA spread. Reflect and comment.
Get Cleveland Financial Stress Index https://research.stlouisfed.org/fred2/series/CFSI. Its not
available for the entire time period. Plot DD and PD along with stress index. Reflect and
comment
