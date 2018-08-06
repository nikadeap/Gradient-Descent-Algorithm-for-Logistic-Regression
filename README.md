### Gradient-Descent-Algorithm-for-Logistic-Regression

Implement  a gradient descent algorithm for logistic regression .This data are taken from a larger dataset, described in Rousseauw et al, 1983, South African Medical Journal.

**Dataset: Use the following dataset for the implementation.**

Data is available at: http://statweb.stanford.edu/~tibs/ElemStatLearn/datasets/
And header information is available at: http://statweb.stanford.edu/~tibs/ElemStatLearn/datasets/SAheart.info.txt

#### Description
A retrospective sample of males in a heart-disease high-risk region of the Western Cape, South Africa. There are roughly two controls per case of CHD. Many of the CHD positive men have undergone blood pressure reduction treatment and other programs to reduce their risk factors after their CHD event. In some cases, the measurements were made after these treatments. These data are taken from a larger dataset, described in Rousseauw et al, 1983, South African Medical Journal.
 
### Steps to implement

*	Encode the categorical variables.
*	Normalize the numerical variables
*	Randomly initialize beta values
*	Define a sigmoid function to predict Y
* Define a function for calculating binary cross entropy loss function 
* Define a function for updating beta values. The derivative term is same as derivative term for the linear regression as discussed in the class.
* Write the code for gradient descent iterations.
* Plot the cost function for different alpha (learning parameters) values. E.g. 0.01, 0.001, 0.0001 
* Use sklearn logistic regression API and compare the estimation of beta values.

