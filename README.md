<p align="center">
<img width="150" align = "center" src="./graphics/UR_Logo.jpg" >


</p>


# Quantifying terms from the bias-variance decomposition using metalog distributions

## Abstract.

The bias-variance decomposition (BVD) serves as a key guidepost in machine-learning practice. Com- paring model scores for training, validation, and test data provide qualitative indications of possible model overfitting. Explicit calculation of BVD terms is generally problematic, absent assumptions about convenient probability distributions.

Metalog distributions, an emerging technique from the Decision-Analysis community, provide a mechanism for explicit calculation of BVD terms. Metalogs fit arbitrary empirical distributions to closed-form, multiply-differentiable, continuous functions rep- resented as series.

The bias and variance terms result from metalog-distribution fits to prediction-model training- and test- data residual errors employing a method resembling Locally Weighted Scatterplot Smoothing (LOWESS). In- stead of calculating means as is done with LOWESS, metalog-fit probability-density functions are instead obtained. This allows for some statistical inference using machine-learning results, including estimates of prediction and confidence intervals. Applying Kolmogorov-Smirnov or other tests to the resulting bias and variance distributions leads to a quantitative characterization of prediction-model overfitting.

Metalog distributions can similarly be employed to estimate Cramer-Row Lower Bounds (CRLB) on estimation-error variance. This occurs from fitting orthogonal-transform-space representations of the explanatory variables to metaled distributions. The CLRB offers a proxy for the irreducible-variance term in the BVD. Explicit calculation of BVD terms using metalog distributions affords the opportunity to extend Analysis of Variance (ANOVA) methods from classical statistics into the machine-learning realm.

## Introduction.

<a href="#Hamlett2020">[Hamlet2020]</a> contains an abstract proposal for the 2021 Symposium on Statistics and Data Science (SDSS).



## References.

<a id="Hamlett2020">[Hamlett2020]</a> N. A. Hamlett (2020).  Quantifying terms from the bias-variance decomposition using metalog distributions. (Refereed-paper abstract proposal).  Symposium on Statistics and Data Science, Saint Louis, MO, June 2-5, 2021, https://bityl.co/521K.
