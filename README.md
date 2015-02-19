Machine Leaning 
===============

This is a repository to test some concepts of machine learning according to the Course of [Machine Learning](https://www.coursera.org/course/ml) by Coursera. The course is ministered by [Andrew Ng](http://cs.stanford.edu/people/ang/) from Stanford.

Some concepts of Machine Learning terms are explained bellow, feel free to take a look, and for use these codes you must install Octave([download here](https://www.gnu.org/software/octave/download.html)) or MatLab([download here](http://www.mathworks.com/downloads/web_downloads/?s_tid=hp_ff_s_downloads)).
I prefer Octave because is free, but both works fine.

<h1>Machine Learning Algorithms</h1>
- Supervised learning
- Unsupervised learning

<h2>Supervised Learning</h2>
Given the "right answers" as data to compute, is classified by:
- Regression: Predict continuous valued output (e.g. price);
- Classification: Discrete valued output (e.g. 0 or 1);

<h2>Unsupervised Learning</h2>
This algorithm of machine learning find data structures for us, there is no need to exist labels of the datas.

<h2>Linear Regression</h2>
In statistics, linear regression is an approach for modeling the relationship between a scalar dependent variable y and one or more explanatory variables (or independent variable) denoted X. The case of one explanatory variable is called simple linear regression. For more than one explanatory variable, the process is called multiple linear regression.

<h3>With One Variable or Univariate Linear Regression</h3>
For a feature, the linear regression algorithm needs a training set of the data, the "inputs" and the values of the "outputs", than, we apply these datas in the hipothesis function, 
```h_(theta) (x) = theta_(0) + theta_(1) * x```. 

In others words, if for example, we want to predict the estimated price for a house by its size, you will need a training set of inputs of sizes of many houses and the estimated price of them, and according with these values you represent the hipothesis function, and choose theta0 and theta1 so that htheta(x) is close to y for our training examples (x, y).

<h3>Cost Function</h3>
This function let us figure out how to fit the best possible straight line to our data. The hypothesis function make predictions in this linear function.

<h3>Gradient Descent</h3>

<h3>Normal Equation</h3>

