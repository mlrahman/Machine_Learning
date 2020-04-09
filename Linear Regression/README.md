# Linear Regression

It's a statistical model and a famous machine learning algorithm. The inventor of regression is <b>Francis Galton, 1822-1911</b>).
Linear regression basically deals with the relationship between <b>dependent and independent variable</b>. If we change the independent variable by 1 unit then how much changes will occur in dependent variable, the process of estimating this result is known as linear regression.  
<b>Note:</b> The result may not be 100% equal but it will be nearest one.</br></br>
Now let us begin with the <b>numerical analysis</b>. If we try to sketch a graph where x-axis represent the independent variable and y-axis represent the dependent variable then it is observable that the relation between few points can be easily explained by a <b>straight line</b>. We have to find out a straight line which intersects all the points. For any case if we failed to find out such straight line which intersects all the points then we need to find the closet one where the points and line distance will be minimum.</br></br>
The equation of a straight line is:  
<b>y=mx+c</b>  
Here, <b>x</b> is a independent variable, <b>m</b> is the slope: the tangent value of the degree angle with the positive side of x-axis. It indicates the direction of the straight line, <b>c</b> is the value of intercept: that means the intersecting point of the straight line to the y-axis.</br></br>
So we have to find out the value of <b>m</b> and <b>c</b> for which the straight line will interesct all the points or pass through the points with minimum distance. Here the expected <b>m</b> and <b>c</b> with the mentioned equation will create our <b>hypothesis</b>. The accurate straight line is known as <b>regression line</b> or <b>best fit line</b>.</br></br>
To find out the best value for <b>m</b> and <b>c</b> we can use two formulas,  
<b>m = ((avg(x) * avg(y)) - avg(x * y)) / (avg(x)^2 - avg(x^2))</b>  
<b>c = avg(y) - m * avg(x)</b>  
<a href="https://github.com/mlrahman/Machine_Learning/blob/master/Linear%20Regression/Linear%20Regression%20Using%20Formula.ipynb" target="_blank">Go to the code..</a></br></br>
We can check the performance of our linear regression hypothesis by using <b>R-Squared Value</b>. The possible R-Squared Value is betwen 0% to 100%. Higher value indicate hypothesis high accuracy for training data or in other words best fit with features.</br>
R-Squared value can be found using the following formula,</br>
<b>r_square=(sum of i=1 to n: (predicted_y_i-avg(y))^2) / (sum of i=1 to n: (actual_y_i-avg(y))^2)</b>  
<a href="https://github.com/mlrahman/Machine_Learning/blob/master/Linear%20Regression/Linear%20Regression%20with%20R-Squared%20Value%20Using%20Formula.ipynb" target="_blank">Go to the code..</a></br></br>
