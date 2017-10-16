---
layout: post
title: What is machine learning?
description: Data Science news
image:
---

Andrew Valentine (ANU-RSES) presented today a talk about machine learning (subsequently abreviated ML), what it consists in and how we can use it. Andrew highlighted the two caterogies of problems in machine learning: ["supervised"](https://en.wikipedia.org/wiki/Supervised_learning) and ["unsupervised"](https://en.wikipedia.org/wiki/Unsupervised_learning) learning problems. After distinguishing those two categories, he introduced the three different types of generic problems encountered in Earth sciences for which ML can be handy: 

- classification problems;
- regression;
- clustering and dimensionality reduction.

After highlighting a few examples from each category, he visually introduced a few algorithms to perform those tasks (clic on names to reach some usefull documentation/description pages):

- [Decision tree](http://scikit-learn.org/stable/modules/tree.html) - [random forest](http://scikit-learn.org/stable/modules/ensemble.html#forests-of-randomized-trees);
- [K-mean algorithm](http://scikit-learn.org/stable/auto_examples/cluster/plot_cluster_iris.html), used in the example depicted in Figure 1 for unsupervised clustering;
- [Self-organizing maps](https://en.wikipedia.org/wiki/Self-organizing_map), used in the example presented in Figure 2 for unsupervised regression;
- [Gaussian processes](http://scikit-learn.org/stable/modules/gaussian_process.html), for performing supervised regression with error estimations;
- [Neural networks](http://neuralnetworksanddeeplearning.com/), a domain in itself that can be applied in many different supervised and unsupervised problems.

![Figure 1](https://rses-datascience.github.io/rses-datascience.github.io/assets/images/cluster.png)

*Figure 1: Illustration of the process of unsupervised K-mean clustering. The example contains 3 different classes (blue, green, red circles). The first step consists in setting 3 points randomly (dark square in b), then to calculate the closest boundaries (black lines) that will delimite sectors in which the means are calculated. It then moves the centers (new grey square in c), performs again the boundary and mean calculations. The process is repeated until convergence (e): the distances between the points in each cluster should be minimal. In other terms, the distance of the points to their mean in each cluster should be minimal.*

![Figure 2](https://rses-datascience.github.io/rses-datascience.github.io/assets/images/som.png)

*Figure 2: Illustration of the process of unsupervised self-organizing maps on a dataset (blue circles in a). 5 random points are first defined. Then, the three closest points to a particular datapoint (surrounded by green in b-d) are moved in the direction of this datapoint. The process is reapeated iteratively until convergence (e).*

As Andrew highlighted, these ideas are potentially powerful in data-rich research fields such as the geosciences, and the underlying mathematical ideas are helping provide new insight into how we process and understand our datasets. A number of different packages are available for performing those tasks in various programming languages. In particular, the [SciKit Learn package](http://scikit-learn.org/stable/index.html) was mentioned during the discussion time as a good starting point for anyone without knowledge on machine learning, because of an excellent documentation about ML algorithms and the good way to use them. SciKit Learn even provide a visual chart that suggests which algorithm may be handy to solve a particular problem, as shown in the Figure 3. For further details on packages, please see our [ressource webpage](https://rses-datascience.github.io/rses-datascience.github.io/resources.html).

![Figure 3](https://rses-datascience.github.io/rses-datascience.github.io/assets/images/ml_map_skl.png)

*Figure 3: Visual flowchart suggesting interesting algorithms that can be used for particular problems. See the [SciKit Learn website](http://scikit-learn.org/stable/tutorial/machine_learning_map/index.html) for an interactive version of this chart. Image reproduced from http://scikit-learn.org/stable/tutorial/machine_learning_map/index.html.*

This Data Science Research Forum was thus a success, with many people showing up, leading us to move to a bigger room. We invite anybody from RSES and ANU to come and discuss Data Science with us about Machine Learning. In two weeks, Malcolm Sambridge will discuss interpolation and related problems. See you there!

*Post written by Charles Le Losq.*