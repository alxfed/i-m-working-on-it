---
description: >-
  I found a wonderful book of Francois Chollet, the author of Keras, and it's
  exactly what I wanted to read at this point...
---

# Reading Chollet

...a thoughtful overview of the subject with some extra details explained by the actual person who has created something useful for the field.

    Since some point in the not so recent past I started reading books from the last chapter. In this book the last chapter is called: "Conclusions" \(Chapter 9\).

> ...anything that requires reasoning—like programming or applying the scientific method—long-term planning, and algorithmic data manipulation is out of reach for deep-learning models, no matter how much data you throw at them. Even learning a sorting algorithm with a deep neural network is tremendously difficult.
>
>     This is because a deep-learning model is just a chain of simple, continuous geometric transformations mapping one vector space into another. All it can do is map one data manifold X into another manifold Y , assuming the existence of a _learnable_ continuous transform from X to Y . A deep-learning model can be interpreted as a kind of program; but, inversely, most programs can’t be expressed as deep-learning models—for most tasks, either there exists no corresponding deep-neural network that solves the task or, even if one exists, it may not be _learnable_: the corresponding geometric transform may be far too complex, or there may not be appropriate data available to learn it.

    That is good enough. :\) I believe he is talking about the fact that the functions that can be learned are not multi-valued or at least are smooth if they are and because of that can be transformed into single-valued by a continuous transformation. Still it's a kinda' 'cryptic' statement, at least for me; maybe I'm a stupid or something.

    I think it would be worth trying to formulate this problem mathematically and try to solve it. Probably somebody has done that already and everybody knows about that solution, that's why he's speaking so confidently. I will look into it.

    Then, on page 330 there's a peculiar list:

> At a high level, these are the main directions in which I see promise:
>
> * Models closer to general-purpose computer programs, built on top of far richer primi- tives than the current differentiable layers. This is how we’ll get to reasoning and abstraction, the lack of which is the fundamental weakness of current models.
> * New forms of learning that make the previous point possible, allowing models to move away from differentiable transforms.
> * Models that require less involvement from human engineers. It shouldn’t be your job to tune knobs endlessly.
> * Greater, systematic reuse of previously learned features and architectures, such as meta- learning systems using reusable and modular program subroutines.

It is hard to argue. And on the same page:

> Current AI pro- grams that are capable of basic forms of reasoning are all hardcoded by human programmers: for instance, software that relies on search algorithms, graph manipulation, and formal logic. In DeepMind’s AlphaGo, for example, most of the intelligence on display is designed and hardcoded by expert programmers \(such as Monte Carlo Tree Search\); learning from data happens only in specialized sub-modules \(value networks and policy networks\).

The dude has clearly done his homework, but I need to find the source of this information and read it myself.

