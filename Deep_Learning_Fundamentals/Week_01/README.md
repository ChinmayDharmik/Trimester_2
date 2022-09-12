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


** High-dimensional datasets**

>The size of a dataset is measured by the number of data samples it contains, and also the number of dimensions per sample. For example, the housing dataset you will use in this week’s exercise has 10 features per property, so it is a 10-dimensional dataset. Visualising 10-dimensional data using 2D or 3D plots is a challenge that has been addressed by unsupervised learning methods. Richer data types used in machine learning (for example, images or genetic data) may contain thousands or millions of dimensions per sample.

***
***
***

### What Isn’t Machine Learning Good For?

#### 1. Problems with data

**Quantity of data**

On the other hand, a task like image classification requires millions of images, with thousands of examples per class to be identified.This is because an image is much more complex than a 2D data point.

**Range or domain of data**

For successful generalisation, it is critical not only to have enough data, but also data that is representative of future data points. For example, if you want to classify images of cats vs. dogs, it is important that you do not only have images of ginger cats. Otherwise, you will fail to accurately model what an average cat looks like, and therefore your solution will likely fail when applied to general images of cats and dogs.

**Noise, outliers and errors**

In most real-world sources of data, whether it originates from a sensor or from human annotations, noise and errors are inevitably present. Fortunately, there are several steps you can take to detect errors, and to reduce their impact on generalisation error, or even remove them from the data. You will encounter some examples of these in this week’s exercises.

**Redundancy**

Not all data is created equal. A common problem with large datasets is that only a small part of it is actually related to the output you want to predict. You have seen several techniques in previous courses to identify this and focus on useful data, such as:

* dimension reduction, e.g. principal component analysis (PCA),
* correlation with the target value.
