---
title: Machine Learning Journal Library
keywords: machine_learning
summary: "My personal list of journals I use for my research and projects where I wrote one-sentence summaries."
sidebar: ml_sidebar
permalink: /machine-learning/journals-library/
folder: machinelearning
tags: [machine_learning]
---
### Deep Reinforcement Learning
- [Deep Q-Networks for Accelerating the Training of Deep Neural Networks](https://arxiv.org/abs/1606.01467)
- [Playing Atari with Deep Reinforcement Learning](https://arxiv.org/abs/1312.5602)
- [Continuous Control with Deep Reinforcement Learning](https://arxiv.org/abs/1509.02971)
- [Deterministic Policy Gradient Algorithms](http://jmlr.org/proceedings/papers/v32/silver14.pdf)
- [Actor-Critic Methods](https://webdocs.cs.ualberta.ca/~sutton/book/ebook/node66.html)
    - Summary: an actor neural network would determine the actions (student) while the critic neural network would evaluate the actor's actions (teacher)
- [Progressive Neural Network, Reinforcment Learning Context](https://arxiv.org/pdf/1606.04671.pdf)
    - Summary: adding columns for each new task results in better transfer learning compared to partial or complete fine-tuning which causes catastrophic forgetting

### Deep Convolutional Neural Networks
- [Wide Residual Networks](https://arxiv.org/abs/1605.07146)
    - Summary: a variation of residual networks where width over depth has shown better performance

### Deep Neural Networks
- [A shared neural ensemble links distinct contextual memories encoded close in time](http://www.nature.com/nature/journal/v534/n7605/full/nature17955.html)
    - Summary: spatial memories that are acquired near in time are associated with overlapping neuronal ensembles in the brain’s hippocampus
- [Memories linked within a window of time](http://www.nature.com/nature/journal/v536/n7617/full/536405a.html)
    - Summary: a theory called temporal context memory (TCM) explains why people have a better memory for words that occur close together in a list than for words that are further apart
- [Learning Step Size Controllers for Robust Neural Network Training](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/04/daniel2016stepsizecontrol.pdf)
    - Summary: identifying informative states, using the states for learning step size and showing generalization to different tasks
- [Weight Features for Predicting Future Model Performance of Deep Neural Networks](http://www.ijcai.org/Proceedings/16/Papers/318.pdf)
    - Summary: using statistics of weights instead of actual weights
- [Compete to Compute](http://papers.nips.cc/paper/5059-compete-to-compute.pdf)
    - Summary: using competing linear units to outperform non-competing nonlinear units and avoid catastrophic forgetting when training sets change over time
- [HyperNetworks](https://arxiv.org/pdf/1609.09106v3.pdf)
    - Summary: using a HyperLSTMCell over BasicLSTM cell by using a small number of parameters (small LSTM) to generate a large number of parameters (larger LSTM)

### Hyper-parameter Optimization
- [Learning to learn by gradient descent by gradient descent](https://arxiv.org/abs/1606.04474)
    - Summary: learning an optimization algorithm that works on a class of optimization problems by parameterizing the optimizer
- [Direct Feedback Alignment Provides Learning in Deep Neural Networks](https://arxiv.org/abs/1609.01596)
    - Summary: an alternative to error backpropagation by propagating the error through fixed random feedback connections directly from the output layer to each hidden layer
- [DrMAD: Distilling Reverse-Mode Automatic Differentiation for Optimizing Hyperparameters of Deep Neural Networks](https://arxiv.org/abs/1601.00917)
    - Summary: using a convex combination of the starting and ending points to accelerate convergence
