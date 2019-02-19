---
description: The Scikit-Learn flavor of Animal-speak.
---

# Scikit-Learn

## The Dictionary of Scikit-speak

Borrowed mostly from here: , borrowed from:   
[https://scikit-learn.org/stable/tutorial/basic/tutorial.html](https://scikit-learn.org/stable/tutorial/basic/tutorial.html)   
and here: [https://scikit-learn.org/stable/tutorial/statistical\_inference/supervised\_learning.html](https://scikit-learn.org/stable/tutorial/statistical_inference/supervised_learning.html)

## **data -**

a **set** of objects each of which has multiple _individual_ properties \(**features** in Scikit-speak\), the realizations of properties that are talked about as classes of any and all the objects in the set.   
**Example:** human census is **data**, the set consists of humans-_individuals_ , each human has height, weight etc.etc. - the **features** which are also called "attributes" \(because of the census, duh!\).

If you are a student of Newtonian dynamics or Mechanics or, God forbid, Electrodynamics - you need to wrap your head around it here. Everything is totally static, there is only a set of pieces on the chessboard and of course all the Animal-speak is created for the sole purpose of being able to joggle the super-expensive to acquire numbers and answers to questions as the 'researcher' wants in order to obtain the desired 'prediction' that will sell well. Sorry for being cynical but that's what it is and nothing more.

## **target** - 

The word that is constantly used in all the functions related to **regression**.   
**The synonyms** of it are: "dependent variable", "response variable", "regressand", "measured variable", "responding variable", "explained variable", "outcome variable", "experimental variable", and "output variable." Also, there are "label", "class", "name of object".   
**The human meaning** of it is: it's the thing you are trying to predict with the help of the "regression analysis".

{% hint style="info" %}
[Supervised learning](https://scikit-learn.org/stable/supervised_learning.html#supervised-learning) consists in learning the link between two datasets: the observed data `X` and an external variable `y` that we are trying to predict, usually called “target” or “labels”. Most often, `y` is a 1D array of length `n_samples`.

All supervised [estimators](https://en.wikipedia.org/wiki/Estimator) in scikit-learn implement a `fit(X, y)` method to fit the model and a `predict(X)`method that, given unlabeled observations `X`, returns the predicted labels `y.`

[http://scikit-learn.org/stable/tutorial/statistical\_inference/supervised\_learning.html](http://scikit-learn.org/stable/tutorial/statistical_inference/supervised_learning.html)
{% endhint %}

