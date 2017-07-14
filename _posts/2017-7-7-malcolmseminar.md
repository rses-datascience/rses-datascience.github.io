---
layout: post
title: The Story of Nothing
description: Data Science news
image:
---

Malcolm Sambridge, the leader of the RSES Data Science theme, gave a seminar on the 6th of July at RSES about his latests thoughts and findings on using sparsity in geoscience data to gather more information about them. His talk briefly charted the history of nothing, and showed the power of nothing through a series of novel examples.

The concept of zero, sparsity, emptiness, or nothing has a long history in the development of civilizations, and our understanding of the world about us. Grappling with what is not, can have surprising benefits for understanding what is. Recently it has been discovered that exploiting the concept of sparsity or emptiness leads to powerful new ways to make physical measurements in the field or lab, and also solve previously intractable problems in fitting parameters to data. The solution of such inverse problems is of considerable interest in the Earth Sciences because many Earth properties and processes are not directly observable and so to constrain them one must rely on indirect measurements. An example is estimating properties of the inner Earth mantle and core from surface geophysical observables, or constraining past or hidden Earth processes from geochemical signatures.

During his talk, Malcolm highlighted the various abilities of algorithms exploiting data sparsity. He showed how sparse [matrix completion](https://en.wikipedia.org/wiki/Matrix_completion), as also known as the ["Netflix Problem"](https://en.wikipedia.org/wiki/Netflix_Prize) amongst data scientists, can be used to find missing values in sparse matrix. Using most recent sparse matrix completion algorithms, excellent recovery of sparse matrix can be obtained with using only a fraction of the existing data, as shown in Figure 1. 

![Figure 1](https://rses-datascience.github.io/rses-datascience.github.io/assets/images/Malcolm_post_072017_PastedGraphic-2.png)

*Figure 1: An example of reconstructing missing entries of a table of data (matrix) by maximizing the sparsity of its eigenvalue spectrum. The left panel shows the original 40x40 matrix and the middle panel the recovered matrix recovered using just 31% of its entries randomly chosen. The right hand panel shows a plot of the true versus recovered value of the unseen 69% of entries. The matrix can be recovered near perfectly because it has a low rank (of 4) which means a sparse eigenvalue spectrum.*

Such approach may be very interesting, for instance, in the case of image reconstruction for [tomography](https://en.wikipedia.org/wiki/Seismic_tomography) analysis, a well-knwon problem in geophysics. As a "toy" case, an example of the reconstruction of the logo of the Australian National University is shown in Figure 2. We see that, compared to previous methods such as the Tikhonov algorithm, sparse matrix completion leads to an excellent reconstruction of the ANU logo with only using 5238 random strainghts transverse of the original image.

![Figure 2](https://rses-datascience.github.io/rses-datascience.github.io/assets/images/Malcolm_post_072017_PastedGraphic-1.png)

*Figure 2: Example "X-ray" tomography. The left panel shows a 194x194 binary pixel image (black =0, white=1). Our data is the sum of the pixel values along just 5238 random straight paths across the image. The middle panel shows a classic reconstruction using standard `Tikhonov’ algorithm. The right panel shows a sparsity maximized solution with fewer artefacts. Because the true image is sparse it can be nearly perfectly recovered with many fewer data than there are unknowns.*

The approaches presented by Malcolm highlight a turning point in using mathematics for solving Earht science problems. Exploiting the sparsity of existing and new geoscience datasets may lead to observations that were previously impossible. As a result, new discoveries related to the exploitation of sparsity can be expected, particularly in domains such as, for instance, seismic tomography or geochemistry.

*Post written by Charles Le Losq.*