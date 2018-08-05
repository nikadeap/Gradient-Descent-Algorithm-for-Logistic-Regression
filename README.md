# Gradient-Descent-Algorithm-for-Logistic-Regression
Implement  a gradient descent algorithm for logistic regression .This data are taken from a larger dataset, described in Rousseauw et al, 1983, South African Medical Journal.

Implement a Gradient Descent Algorithms for Logistic Regression. 
Use the following dataset for the implementation.
Data is available at: http://statweb.stanford.edu/~tibs/ElemStatLearn/datasets/
And header information is available at: http://statweb.stanford.edu/~tibs/ElemStatLearn/datasets/SAheart.info.txt
A retrospective sample of males in a heart-disease high-risk region of the Western Cape, South Africa. There are roughly two controls per case of CHD. Many of the CHD positive men have undergone blood pressure reduction treatment and other programs to reduce their risk factors after their CHD event. In some cases, the measurements were made after these treatments. These data are taken from a larger dataset, described in Rousseauw et al, 1983, South African Medical Journal.
 Steps to implement
a)	Encode the categorical variables.
b)	Normalize the numerical variables
c)	Randomly initialize beta values
d)	Define a sigmoid function to predict Y

 

e)	Define a function for calculating binary cross entropy loss function 
 

f)	Define a function for updating beta values. The derivative term is same as derivative term for the linear regression as discussed in the class.
g)	Write the code for gradient descent iterations.
h)	Plot the cost function for different alpha (learning parameters) values. E.g. 0.01, 0.001, 0.0001 
i)	Use sklearn logistic regression API and compare the estimation of beta values.

