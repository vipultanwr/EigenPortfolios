# EigenPortfolio

Researching on the portfolios made by taking weights as the eigenvectors of stock return matrix

# Getting EigenPortfolio: Multiple methods

We train the trading model on previous month's returns for our stock universe and use the resulting eigenweights as the current portfolio weights. 
However since there are many eigenvectors, choosing the correct vector is essentially the problem. Following are the methods so far tried:
1) Choose by cross validation on the some part of unseen data 
2) Choose the vector with largest eigen values or a group of N large eigenvalues
3) Choose the vector with smallest eigen values or a group of N small eigenvalues for the inverse cov matrix (As suggested by Irine Aldridge in her paper)


#TODO:
1) Try on different time scales
2) Make the portfolio less volatile by using trailing stop losses or some other methods of finding the best unidirectional eigenportfolio 

