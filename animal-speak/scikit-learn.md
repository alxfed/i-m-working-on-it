---
description: The Scikit-Learn flavor of Animal-speak.
---

# Scikit-Learn

## The Dictionary of Scikit-speak

Borrowed mostly from here: , borrowed from:   
[https://scikit-learn.org/stable/tutorial/basic/tutorial.html](https://scikit-learn.org/stable/tutorial/basic/tutorial.html)   
and here: [https://scikit-learn.org/stable/tutorial/statistical\_inference/supervised\_learning.html](https://scikit-learn.org/stable/tutorial/statistical_inference/supervised_learning.html)

## **data -**

a **set** of objects \(**individuals** in Stats-speak\) each of which has multiple properties, **variables** \(or **features** in Scikit-speak\).  
  
**Example:** human census is **data**, the set consists of humans-_individuals_ , each human has height, weight etc.etc. - the **features** which are also called "attributes" \(because of the census, duh!\). Notice that a human must have height and weight, \(s\)he can not _not_ have them. The complete set of data is sometimes called **population** \(as opposed to sample which is a sub-set of it\).

a subset of data is called **sample** \(see below\). It is just what I've just said  a subset picked out of the data according to a criterion \(including a 'random' selection\).

**Human language**: If you are a student of Newtonian dynamics or Mechanics or, God forbid, Electrodynamics - you need to wrap your head around it here. Everything is totally static, there is only a set of pieces on the chessboard and of course all the Animal-speak is created for the sole purpose of being able to joggle the super-expensive to acquire numbers and answers to questions as the 'researcher' wants in order to obtain the desired 'prediction' that will sell well. Sorry for being cynical but that's what it is and nothing more, - the Census data collection as any other 'field research' required in the past a lot of money. Now you can probably surveil each human in an industrialized country in real time and work with that 'data'. :\)

## sample -

a subset of data from the **population**/\(all of\) **data** selected by a predefined procedure \(including a 'random' selection\). The elements of a sample are known as "sample points", "sampling units" or "observations".  
  
**Example**: a subset of humans in the same age group taken from the census data \(the population\).

{% hint style="info" %}
**Descriptive statistics** is the branch of statistics that includes methods for organizing and summarizing data. **Inferential statistics** is the branch of statistics that involves generalizing from a sample to the population from which the sample was selected and assessing the reliability of such generalizations.
{% endhint %}

## **feature -**

the Scikit-speak for **variable** of Stat-speak. It's a variable in a very broad sense of the word, because it can be an object representing a complex phenomenon \(like a histogram of a noise\), but it's a variable \(or at maximum a 'representation of a variable'\) none the less. Seriously, there is no need in this meaningless \(in this context\) word "feature".

{% hint style="info" %}
In [machine learning](https://en.wikipedia.org/wiki/Machine_learning) and [pattern recognition](https://en.wikipedia.org/wiki/Pattern_recognition), a **feature** is an individual measurable property or characteristic of a phenomenon being observed. Choosing informative, discriminating and independent features is a crucial step for effective algorithms in [pattern recognition](https://en.wikipedia.org/wiki/Pattern_recognition), [classification](https://en.wikipedia.org/wiki/Classification_%28machine_learning%29) and [regression](https://en.wikipedia.org/wiki/Regression_analysis). Features are usually numeric, but structural features such as [strings](https://en.wikipedia.org/wiki/String_%28computer_science%29) and [graphs](https://en.wikipedia.org/wiki/Graph_%28discrete_mathematics%29) are used in [syntactic pattern recognition](https://en.wikipedia.org/wiki/Syntactic_pattern_recognition). The concept of "feature" is related to that of [explanatory variable](https://en.wikipedia.org/wiki/Explanatory_variable) used in [statistical](https://en.wikipedia.org/wiki/Statistics) techniques such as [linear regression](https://en.wikipedia.org/wiki/Linear_regression).
{% endhint %}

## **target** - 

The word that is constantly used in all the functions related to **regression**.   
**The synonyms** of it are: "dependent variable", "response variable", "regressand", "measured variable", "responding variable", "explained variable", "outcome variable", "experimental variable", and "output variable." Also, there are "label", "class", "name of object".   
**The human meaning** of it is: it's the thing you are trying to predict with the help of the "regression analysis".

{% hint style="info" %}
[Supervised learning](https://scikit-learn.org/stable/supervised_learning.html#supervised-learning) consists in learning the link between two datasets: the observed data `X` and an external variable `y` that we are trying to predict, usually called “target” or “labels”. Most often, `y` is a 1D array of length `n_samples`.

All supervised [estimators](https://en.wikipedia.org/wiki/Estimator) in scikit-learn implement a `fit(X, y)` method to fit the model and a `predict(X)`method that, given unlabeled observations `X`, returns the predicted labels `y.`

[http://scikit-learn.org/stable/tutorial/statistical\_inference/supervised\_learning.html](http://scikit-learn.org/stable/tutorial/statistical_inference/supervised_learning.html)
{% endhint %}

