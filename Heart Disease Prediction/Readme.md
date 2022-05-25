# Logistic Regression
#### In this project we will implement logistic regression model to predict whether a person has heart disease, or not.
#### Dataset Info.
This database contains 76 attributes, but all published experiments refer to using a subset of 14 of them. In particular, the Cleveland database is the only one that has been used by ML researchers to
this date. The "goal" field refers to the presence of heart disease in the patient. It is integer valued from 0 (no presence) to 4.<br/>
**Creators:**<br/>
Hungarian Institute of Cardiology. Budapest: Andras Janosi, M.D.<br/>
University Hospital, Zurich, Switzerland: William Steinbrunn, M.D.<br/>
University Hospital, Basel, Switzerland: Matthias Pfisterer, M.D.<br/>
V.A. Medical Center, Long Beach and Cleveland Clinic Foundation: Robert Detrano, M.D., Ph.D.
Donor:<br/>
David W. Aha (aha '@' ics.uci.edu) (714) 856-8779

#### Introduction:
Logistic Regression is a type of regression that estimates the probability of an event occurred. For example, an email is spam or not, sentiment is positive or negative etc. The goal of logistic regression in the context of machine learning is to develop a model capable of predicting a categorical output ( y ) given a set of input features ( X ). Like linear regression, the training of this model involves determining a set of parameters (or weights)  θ  that linearly map the input features to the output of the model. Choosing these parameters is an optimization problem where we are looking for a minimum of a loss or cost function ( J(θ) ) in the  θ  parameter space. The basic way to approach this problem numerically is to implement the batch gradient descent algorithm.

Below are the vectorized forms of the logistic regression hypothesis  hθ(X) , cost function  J(θ) , and the gradient descent algorithm. Logistic regression aims to classify samples based on a categorical or discrete output variable  y∈{0,1} . Thus the hypothesis maps our  θTX  to a number between 0 and 1. This value is treated as the probability that the sample has the output value 1. Usually a decision boundary of 0.5 is used, thus when  hθ(X)≥0.5→y=1  and <br/>

![1222](https://user-images.githubusercontent.com/50455870/132582095-0b0d7fc5-9da9-412b-8db6-3a45a93415d6.JPG)

Hypothesis:<br/>

![1222](https://user-images.githubusercontent.com/50455870/132581943-cdb612e9-5f63-4d01-ada0-f49b941c245e.JPG)

Cost function:<br/>

![1222](https://user-images.githubusercontent.com/50455870/132581453-befb3874-7ff0-46df-ae76-94f409ba51bb.JPG)

Gradient descent:<br/>

![1222](https://user-images.githubusercontent.com/50455870/132581707-9e3d7149-7ca0-45ac-8576-9032a2a82d98.JPG)

Where  X  is the feature matrix containing  m  examples,  θ  is a column vector of model parameters,  y⃗   is the column vector of outputs, and  α  is the learning rate

#### Precedure:
* Dataset Visualization<br/>
* Hypothesis and Cost Function<br/>
* Training the model from scratch<br/>
* Model evaluation<br/>
* Scikit-learn implementation<br/>
