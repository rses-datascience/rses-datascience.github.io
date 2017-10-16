---
layout: post
title: What is machine learning?
description: Data Science news
image:
---

Andrew Valentine (ANU-RSES) presented today a talk about machine learning (subsequently abreviated ML), what it consists in and how we can use it. 

Andrew presented the two caterogies of problems in machine learning: ["supervised"](https://en.wikipedia.org/wiki/Supervised_learning) and ["unsupervised"](https://en.wikipedia.org/wiki/Unsupervised_learning) learning problems. After distinguishing those two different categories, he presented three different types of generic problems encountered in Earth Science for which ML can be handy: 

- classification problems
- regression
- clustering and dimensionality reduction

After highlighting a few examples from each caterogy, he visually introduced a few algorithms to perform those tasks (clic on names to reach some usefull documentation/description pages):

- ["decision tree"](http://scikit-learn.org/stable/modules/tree.html) - ["random forest"](http://scikit-learn.org/stable/modules/ensemble.html#forests-of-randomized-trees), used in the discussed example for supervised classification
- ["K-mean algorithm"](http://scikit-learn.org/stable/auto_examples/cluster/plot_cluster_iris.html), used in the discussed example for unsupervised clustering
- ["Gaussian processes"](http://scikit-learn.org/stable/modules/gaussian_process.html), used in the discussed example for supervised regression
- ["Neural networks"](http://neuralnetworksanddeeplearning.com/), which can be used in many different supervised and unsupervised problems

During the discussion time, the ["SciKit Learn documentation"](http://scikit-learn.org/stable/index.html) was mentioned as a good starting point to read about those algorithm and to learn how we can use them. SciKit Learn even provide a visual chart that suggests whcih algorithm may be handy to solve a particular problem, as shown in the figure 1.

![Figure 1](https://rses-datascience.github.io/rses-datascience.github.io/assets/images/ml_map_skl.png)

*Figure 1: Visual flowchart suggesting interesting algorithms that can be used for particular problems. See the ["SciKit Learn website"](http://scikit-learn.org/stable/tutorial/machine_learning_map/index.html) for an interactive version of this chart. Image reproduced from http://scikit-learn.org/stable/tutorial/machine_learning_map/index.html.

This Data Science Research Forum was thus a success, with so many people showing up that we had to switch to a bigger room. We invite anybody from RSES and ANU to come and discuss Data Science with us about Machine Learning. In two weeks, Malcolm Sambridge will discuss interpolation and related problems. See you there!

*Post written by Charles Le Losq.*