Machine learning is a program that uses data to learn and make predictions and then act on them.






# Key Terms
- **Data table**: rows = examples; columns = features and labels.
- **Features** $x$: what the model gets to see.
- **Label** $y$: what we want to predict.
- **Model** $fθ(x)$: parametric function we can evaluate (and often differentiate).
- **Loss** $l(fθ(x),y)$: how bad a prediction is on one example.
- **Empirical risk**: average loss over training data.
- **Training algorithm**: method that searches for parameters $\hat{\theta}$ with low empirical risk.
- **Metric**: summary of performance on **held‑out** data, chosen to match decisions.

# Supervised Learning
Supervised learning uses labelled data $x$ to train. The labels guide the model to a desired output from the input. Supervised in the sense that the labels given to the model guide it to an result.


> [!Warning] unused labels
> If the data has labels and they go unused the model is unsupervised. 

## 1. Problem and Stakeholders
Decide what the problem is and how to approach it. Decide the cost of errors.  

## 2. Data and Labels
How are $x$ and $y$ measured and what is the data generating process?

## 3. Split Data

# Semi-Supervised Learning
Semi-supervised learning uses two input data sets. A labelled set and an unlabelled set.


# Self-Supervised Learning

# Unsupervised Learning
Supervised learning uses unlabelled data $x$ to 
$x$ will appear as a collection of points and has to discover structure in the data.



# Loss Function for Regression

There are two common choices **Absolute Error (L1)** and **Squared Error (L2)**.

## Absolute Error (L1)
$$l_{AE}(\hat{y},y)=|\hat{y}-y|$$
This function linearly penalizes errors which is **mean absolute error (MAE)**

## Squared Error (L2)
$$l_{SE}(\hat{y},y)=(\hat{y}-y)^2$$
This function aquatically penalizes errors which is **mean squared error (MSE)**




