## Machine Learning Specialization
### https://www.coursera.org/specializations/machine-learning-introduction
### What is Machine Learning? 
###  Answer: From Wiki(the Term ML was used 1959 by Arthur Samuel), Machine learning algorithms build a model based on sample data, known as training data, in order to make predictions or decisions without being explicitly programmed to do so. ML is part of AI.  Applications on Machine Learning: Medicine, email filtering, speech recognition, computer vision...Machine Learning is referred as Predictive Analytics. Algorithms learn from examples. 
***
## Course 1: Supervised Machine Learning: Regression and Classification  
(According to Prof. Andrew NG,  99% of economic values produced today by Machine Learning is Supervised ML)
(https://www.coursera.org/learn/machine-learning?specialization=machine-learning-introduction)
* #### Supervise means to observe and direct the excution of a task, project or an activity. " Supervise" a ML model  is by " teaching " the model-train it with data from the labeled dataset. (https://learning.edx.org/course/course-v1:IBM+ML0101EN+3T2018/)
* #### Supervised machine learning or more commonly, supervised learning, refers to algorithms that learn x to y or input to output mappings. The key characteristic of supervised learning is that you give your learning algorithm examples to learn from, 
* #### Examples: input x-> output y->Application: Email->Spam( 0/1)-> Eamil Spam Filter; Audio->Text Transcript->Speech Recognition; English->Spanish(Chinese etc)->Mechine Translation; Ad, User info->Click( 0/1)-> Online Advertising;  image radar info-> positions of other cars->Self Driving cars; Image of phones->Defect( 0/1)->Visual inspection
***
### Regression: the rocess of predicting a continuous value
( dealing with numerical data, to predict a number): Using the provided dataset, the learning algorithm is trying to produce a right answer (y) on different inputs( x). Regression analysis is a statistical technique for determining the relationship between a single dependent (criterion) variable and one or more independent (predictor) variables.
* #### Examples for regression:1Housing price prediction is the particular type of supervised learning called regression. By regression, the learning algorithm is  trying to predict a number from infinitely many possible numbers such as the house prices;2Use regression to predict the Co2 emission of a new car by
using other fields, such as Engine size or number of Cylinders

* #### Types of Regression: Simple regression and multi-Value regression
* #### Visualization for regression: Regression line, curve 
***
### Linear Regression Model, cost function and Gradient Descent: 
```
Linear Regression model:
Cost Function:
Gradient Descent: Gradient descent is an algorithm for finding values of parameters w and b that minimize the cost function J.  What does this update statement do? (Assume \alphaα is small.) 
![image](https://user-images.githubusercontent.com/51423887/178381263-bd8c1100-4e02-4cd5-96d7-cf496cf630ed.png)

 w=w−α(d/dJ (w,b) )

​Updates parameter ww by a small amount
```
*** 
###  Classification: the process of predicting a discrete class label or category
( a predctive modeling to analyze categorical data not numerical data): Classification is a task that requires the use of machine learning algorithms that learn how to assign a class label to examples from the problem domain. An easy to understand example is classifying emails as “spam” or “not spam.”
 * #### 4 types of classifications: 
  https://machinelearningmastery.com/types-of-classification-in-machine-learning/#:~:text=In%20machine%20learning%2C%20classification%20refers,one%20of%20the%20known%20characters.
  * #### Examples of Classifications: Cancer 
  
 ***
 ## Course 2: Unsupervised Mechine Learning 
 #### Unsupervised Learning does  not supervise the model, but we let the model work on its own to discover information
that may not be visible to the human eye.It means, The Unsupervised algorithm trains on the dataset, and draws conclusions on UNLABELED
data. ( IBM ML course)
#### Types of Unsupervised ML:  Dimension reduction, Density estimation, Market basket analysis and Clustering are the most
widely used unsupervised machine learning techniques.
