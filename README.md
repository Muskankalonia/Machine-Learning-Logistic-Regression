# Machine-Learning-Logistic-Regression

This is example 2 of andrew Ng Machine learning course giving a vectorized implemntation of logistic regeression and also the optimised solution of linear gradient and logistic regression.

#Details of the files included:

- Data1.mlx file includes the training sets that contains exam scores of 2 tests as parameters and on their bases the parameter y tells whether the person is admitted to the university or not
- After loading the data in Matlab plotData.m contains the plotData function to visualise the data
- The sigmoid function implements the sigmoid for the logistic regression
- CostFunction.m implements the actual logistic regression function and gives cost function as well as the gradient
- The data1finalimplementation file will walk you through the sequence of all the steps once you are done with the above files. It also contains the implemntation of fminunc function.

***********
- Data2.mlx file contains the data of microchips Test 1  and test 2 and output is whether the chips are accepted or not
- As done earlier first plot the data then there is addition work to map the fearture (mapFeature.m) so as to set a degree 6 equation of the 2 parameters to fit the training data 
- Now costFunctionReg.m would give a regularized cost func and gradient.
- plotDesicionBoundary will plot a fit boundary accross the plot.
- The data2finalimplemntation file will walk you through all the sequence of steps once done with the above files.
