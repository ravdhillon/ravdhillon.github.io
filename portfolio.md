### [Home](/index) | [Blog](/blog) | [Resume](/resume) | Portfolio
---

<span class="portfolio-title">Linear Regression</span>
<span class="portfolio-summary">
Linear Regression is type of Supervised Learning where the model assumes a linear relationship between input variable(s) and single output variable.
<div class="portfolio-container">
    <div class="portfolio-content">
        Idea of Linear Regression model is to estimate the values of the coefficients used in the representation. Estimating the coefficients help us in understanding how the regression line fits the data during model training.
    
        <div class="equation">
            Simple Linear Regression  y = β0 + β1 x    
            Multiple Linear Regression    y = β0 + β1 x1 + β2 x2 + … + βn xn
        </div>

        Single input variable – simple linear regression à represented by simple line equation. 
        Multiple input variables – multi linear regression (multi variable regression)  The line equation is called a plane or hyper-plane. 

        Coefficient: b0, b1, b2, … bn, 
        Features: x1, x1, x2, … xn, 

        The coefficient estimates for the Ordinary Least Square rely on the feature independence. Multi collinearity is one of the situations that can arise with data. 

        <div class="portolfio-content-sub-heading">MATH BEHIND LINEAR REGRESSION</div>

        Discuss about the Slope and Intercept and how to calculate for the best fit line and use those to make predictions. 

        <div class="portolfio-content-sub-heading">TRAINING LINEAR MODEL</div>

        Learning a linear regression means estimating the values of the coefficients used in the representation. Different methods are used to train or fit the linear model. 

        Ordinary Least Squares or Least Square Regression 

        The idea here is to minimize the sum of squared residuals (left after).  
        

        Minimize  (yactual  − ypredicted)2 

        This technique treats the data as matrix and uses linear algebra operations to estimate the optimal values for the coefficients. This means that all the data has to fit into memory to perform matrix operation. 

        Steps: 

        Given a regression line through data, 

        1.     First, we calculate the distance from each point to the regression line, 

        2.     Then square the distance from the point to the line.  

        3.     Finally sum up all the data points. (This is something model should try to minimize) 

        Q1: Why are we squaring the distance between the line and the point ?  

        A: If we don’t do this but just sum the distances, we may end up getting 0 because there will be +ve and –ve distances and thus never able to find the best line. 

        Q2: Then why not using absolute value of the distance ?  

        A: Well, we want to penalize the outliers. So using the squared distance we can penalize the outliers more. 

        Limitations: 

        Collinearity between x-variables leads to misinterpretation of the coefficients. 

        <div class="portolfio-content-sub-heading">GRADIENT DESCENT</div>

        Gradient Descent is an optimization algorithm which is used to minimize some function (cost function) by iteratively descending as defined by the negative of the gradient. Gradient Descent is used to update the parameters (coefficient in Linear Regression and weights in Neural Network). 

        Steps: 

        1.     First, assign zero values or random values for each coefficient. 

        2.     Then, we calculate sum of the squared error for each pair of input and output values. 

        3.     Using learning rate, we update the coefficients in direction to minimize the error. 

        

        We repeat this process until a minimum sum squared error is achieved. 

        Useful when we have huge dataset which can’t fit into memory 

        

        <div class="portolfio-sub-heading">REGULARIZED LINEAR REGRESSION</div>

        These techniques address some of the issues (like multi collinearity) of the Ordinary Least Squares. They train the model in same way as OLS, but also penalize the coefficients to reduce model complexity. 

        Ridge Regression (L2 regularization): Modifies the OLS method to minimize the squared absolute sum of the coefficients. This is also called L-2 Norm of regression coefficients, because the coefficients are raised to power of 2. 

        Lasso (Least Absolute Shrinkage and Selection Operator) Regression (L1 regularization): Modifies the OLS method to minimize the absolute sum of the coefficients. This can actually bring the coefficient all the way to 0, thus avoiding that feature completely (In which case it becomes Ordinary Least Square Regression) . It reduces the number of features. Called L-1 Norm of coefficients. 

        

        The complexity parameter Alpha (hyperparameter) controls the amount of shrinkage. 

        Large Alpha means More Shrinkage implies coefficients more robust (able to withstand) to collinearity. 

        

        <div class="portolfio-content-sub-heading">MODEL EVALUATION</div>

        Calculating the R2 is the first step in determining how good the guess will be. R2 measures how much change in the output variable (y) is explained by change in input variable(s). In other words it's measure of how well the regression model captures the variances in underlying data. 

        It is a metric of correlation or coefficient of determination. 

        (uJ)na-(u-Dazu)1D'1 
        What should be the value of R2 ? Should it be high or low ? => Higher R2 means better model. 

        RMSE => gives us the average values with which our predictions vary with output.
    </div>
    <div class="portfolio-highlight">
        <div class="portolfio-sub-heading">MAIN IDEA</div>

        Idea of Linear Regression model is to estimate the values of the coefficients used in the representation. Estimating the coefficients help us in  understanding how well the regression line fits the data during model training. 

        

        <div class="portolfio-sub-heading">COST (LOSS) FUNCTION</div>

        Mean Squared Error 

        Root Mean Squared Error 

        

        <div class="portolfio-sub-heading">TRAINING LINEAR MODEL</div>

        Ordinary Least Squares or Least Square Regression 

        Gradient Descent 

        Regularized Linear Regression 

        

        <div class="portolfio-sub-heading">REGULARIZATION OF LINEAR MODEL</div> 

        L1 (Lasso) Regularization 

        L2 (Ridge) Regularization 

        

        <div class="portolfio-sub-heading">MODEL PERFORMANCE</div> 

        R2 =>Metric of correlation or coefficient of determination 
    </div>
</div>
<!-- Estimating the coefficients ...[Read More](/sample_page) -->
<!-- <img src="images/dummy_thumbnail.jpg?raw=true"/> -->

---
[Logistic Regression](/pdf/sample_presentation.pdf)
<img src="images/dummy_thumbnail.jpg?raw=true"/>

---
[Decision Tree & Random Forest](http://example.com/)
<img src="images/dummy_thumbnail.jpg?raw=true"/>

---
[K Nearest Neighbors](http://example.com/)
<img src="images/dummy_thumbnail.jpg?raw=true"/>

---
[SVM - Support Vector Machines](http://example.com/)
<img src="images/dummy_thumbnail.jpg?raw=true"/>

---
