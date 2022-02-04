# Gaussian Process BART.
Implementation of GP-BART algorithm in R language, from the article entitled " GP-BART: a novel Bayesian Additive Regression Treesapproach using Gaussian Processes" by Mateus Maia and Andrew Parnell.

To run all functions necessary, it's just necessary to source the codes and require the libraries from the code snippet below:

```{r}
# Importing libraries and function
rm(list=ls())
library(mlbench)
library(Rcpp)

source("gpbart.R")
source("bart.R")
source("tree_manipulation_objects.R")
sourceCpp("dist_matrix.cpp")
source("fast_gp_multiple_tau.R")

```
