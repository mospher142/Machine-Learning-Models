
# Batch Gradient Descent for Linear Regression

## Linear Regression

Linear Regression is the relation between a dependent variable and an independent variable or more.\
The goal is to find a linear equation that best describes the relationship between the input features and the output variable.

**Linear Regression Equation** \
$\hat{y} = {w*x} + {b}$ \
$\hat{y}$ - **dependent variable**\
${w}$ - **coefficient/slope/weight**\
${x}$ - **independent variable** \
${b}$ - **y-intercept** / **bias**
** **
## Gradient Descent

Its an optimized algorithm used to find the optimal values of the **coefficients** and for **y-intercept**. \
The goal is to iteratively update the values of ${w}$ and ${b}$ in a way that minimizes the **loss function**.\
By minimizing the loss function the algorithm finds the best-fit that passes throught the data points allowing the model to make accurate predictions for new data points.

**Batch Gradient Descent**\
It uses all the data points of the feature

**Calculate the Gradient Descent**
1º - chose a random value for weight and bias
2º - chose a loss function in this case will be the MSE
3º - 
