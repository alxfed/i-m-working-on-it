---
description: The Scikit-Learn flavor of Animal-speak.
---

# Scikit-Learn

## The Dictionary of Scikit-speak

Borrowed mostly from here: , borrowed from:   
[https://scikit-learn.org/stable/tutorial/basic/tutorial.html](https://scikit-learn.org/stable/tutorial/basic/tutorial.html)   
and here: [https://scikit-learn.org/stable/tutorial/statistical\_inference/supervised\_learning.html](https://scikit-learn.org/stable/tutorial/statistical_inference/supervised_learning.html)

## **data -**

the \(pseudo\)**statistical meaning**: a **set** of objects each of which has multiple _individual_ properties \(the realizations of properties that are talked about as classes intrinsic to any and all the objects\). Example: human census is **data**, the set consists of humans, each human has height, weight etc.etc. - the properties \(**features** in Scikit-speak, also "attributes", because of the census, duh!\).

If you are a student of Newtonian dynamics or Mechanics - you need to wrap your head around it here.

## **target** - 

The word that is constantly used in all the functions related to **regression**.   
**The synonyms** of it are: "dependent variable", "response variable", "regressand", "measured variable", "responding variable", "explained variable", "outcome variable", "experimental variable", and "output variable." Also, there are "label", "class", "name of object".   
**The human meaning** of it is: it's the thing you are trying to predict with the help of the "regression analysis".

{% hint style="info" %}
[Supervised learning](https://scikit-learn.org/stable/supervised_learning.html#supervised-learning) consists in learning the link between two datasets: the observed data `X` and an external variable `y` that we are trying to predict, usually called “target” or “labels”. Most often, `y` is a 1D array of length `n_samples`.

All supervised [estimators](https://en.wikipedia.org/wiki/Estimator) in scikit-learn implement a `fit(X, y)` method to fit the model and a `predict(X)`method that, given unlabeled observations `X`, returns the predicted labels `y.`

[http://scikit-learn.org/stable/tutorial/statistical\_inference/supervised\_learning.html](http://scikit-learn.org/stable/tutorial/statistical_inference/supervised_learning.html)
{% endhint %}

