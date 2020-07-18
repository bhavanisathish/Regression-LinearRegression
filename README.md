# Regression-LinearRegression

Regression is used to predict the values in continuous varaiables

Linear regression is a linear relationship between input and output.

We can split our implementation into 2 modules.1 Forward Propagation 2. Backward propagation

Forward Propagation
    Its is simpyy based on Line equation y=mx+c. it can be written as Y_Output = theta * Inuput + Bias
    Then we compute the cost using mean square error i.e error between the actualand predicted.
    
Backward Propagation
    Replacing the theta and bias value to minimise the cost
    theta -=alpha(learning_rate) * theta_derivative / numberof_training_example
    
Compute the test and train accuracy,to determine our model bestfit,overfit or underfit.
    
 
