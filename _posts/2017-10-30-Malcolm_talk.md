---
layout: post
title: Fitting lines and curves to data… Its like running with scissors.
description: Data Science news
image:
---

On Monday the 30th of October, Malcolm Sambridge (RSES-ANU) gave a talk about fitting curves to data. According to him (and he is an expert on this topic!), it is like running with scissors... Malcolm introduced the best practices in order to let the data decide which model is best supported by them (and avoid falling with the scissors). This goes against the traditional least square approch, which relies on the user deciding the number of parameters for the model that he assumes fit his data.

A good illustration of the approach presented by Malcolm is given in Figure 1, where data points are represented and fitted with polynomials functions with orders = 0, 1, 2 and 3 (constant, linear, quadratic, cubic). It is difficult to decide, only on the basis of the fits, which model is best supported by the data.

<img src="https://rses-datascience.github.io/rses-datascience.github.io/assets/images/RJ_MCMC_curves.png" alt="Drawing" style="width: 800px;"/>

*Figure 1: An example of arbitrary datapoints fitted by constant (k=1), linear (k=2), quadratic (k=3) and cubic (k=4) polynomial models. Source: Sambridge et al., Geophys. J. Int. (2006) 167, 528–542.*

To solve such kind of problem, we can used the approach described by Malcolm is called Trans-Dimentional Markov-Chain Monte Carlo (MCMC) inversion. It can be applied to fit a line to a set of points, or very complex models with hundreds of dimensions. Practically speaking, the user provides a set of possible models to the Trans-D MCMC algorithm. This approach will provide an answer regarding the critical question: which model is best supported by the data? The MCMC approach samples a range of possible solutions (Fig. 2), rather than providing a unique best fit. At first, this may seem awkward to those used to perform the tranditional least-square approach, but, in turns, this is a robust method that provides reliable uncertainties on estimated parameters.

<img src="https://rses-datascience.github.io/rses-datascience.github.io/assets/images/RJ_MCMC_models.png" alt="Drawing" style="width: 800px;"/>

*Figure 2: MCMC fits of the data with (a) a constant model, (b) a linear model, (c) a quadratic model, (d) a cubic model, (e) their combination, and (f) the Reversible-Jump MCMC approach that test different models while performing the MCMC run. Source: Sambridge et al., Geophys. J. Int. (2006) 167, 528–542.*

On the example illustrated above, the RJ-MCMC approach provides a posterior distribution that best support the linear (k=2) models in Figure 1. The important point is that this approach does not support a single, best model, but rather provides a range of possible solutions supported by the data. This allows to draw probability density distributions that can be used to estimate what the most probable model parameters are.

The Trans-D MCMC approach is key to sample the solutions of complex problems that can be described by several possible models, either empirical or based on physical equations. It already is used in geophysical models, and, aside of Geophysics, such approach may, in turn, be critical to revisite old problems. For instance, in geochemistry, peak fitting spectroscopic data (infrared or raman, for instance) always relied on the user defining a certain number of peaks as well as choosing a peak shape. With a Trans-D MCMC approach, this wall can be destroyed, and the data will determine which model is best supported by them. As such, this approach will allow pushing further the interpretation of existing and upcoming data.

To illustrate the principle of the Trans-D MCMC approach, we prepared a [Jupyter Notebook in Python](https://nbviewer.jupyter.org/github/rses-datascience/GeneralResources/blob/master/Notebooks/RJMCMC_example.ipynb) illustrating a example of fitting a curve to a dataset. Is it linear, quadratic, cubic... ? Let's let the code decide! Figure 3 shows a few example of possible models and how they fit the data.

![](https://rses-datascience.github.io/rses-datascience.github.io/assets/images/MCMC_example.gif)

*Figure 3: Example of MCMC fits of noisy data with polynomial functions with the Reversible-Jump MCMC algorithm.*

The code being the example is based on the Reversible-Jump MCMC library available on iEarth and developped at the RSES. The talk of Malcolm will further be available online soon, for those who missed it and would like to catch up with this cutting edge technic developped at the Research School of Earth Sciences!

*Post written by Charles Le Losq, posted 9/11/2017*
