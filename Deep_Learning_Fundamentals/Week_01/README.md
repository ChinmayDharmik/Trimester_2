# WEEK 1: Introduction to Machine Learning

##### What is Machine Learning?

> Using **Data** to uncover **unknown** Underlying process

##### Components of Machine Learning

--- Metaphor --> Problem statement or The Issue that the Model works on

--- Decision --> The Outcomes that are expected from the ML model

--- Formulation -->

1. inputs (features) 
2. outputs (label)
3. underlying process (unknown)(blackbox process): f: X->Y
4. Data : (Historic Data) : set of data {x_i,y_i} where i is from 1 to N
5. Decision function g : X ->y such that g is equivalent to f(the actual function)

--> for a new x' predict y' = g(x')

***

### Machine Learning Terminology

#### Supervised Learning

--> The data includes Two elements

----> **Features** --> values that describe the data --> The compenents that that Model uses to develop its "BlackBox" Logic

----> **Target/Labels** --> The Desired outcome for the set of Features 



##### Types of supervised Models that we might encounter

1. ***Regression*** :  Estimate a continuous target value for a feature, given target values for other features.

2. ***Classification***  :  Estimate a discrete value (e.g. a class) for a feature given the target class of the other feature values.

#### Unsupervised Learning

--> Data **does not** have target or labels

--> the aim of this perticular model is to find a pattern in the data

##### Types of Unsupervised Models that we might encounter

1. ***Clustering*** : Detect related sub-groups within a dataset.
2. ***Dimension Reduction*** : Reduce a complex dataset by combining correlated features.
3. ***Anamaly Detection*** : Identify unusual or outlier data points within a dataset.