### Overview

The **ldbod** package provides flexible functions for computing local density-based outlier scores. Functions included in this package can be used for computing local density-based outlier scores in the unsupervised and semi-supervised setting. Two functions are included ldbod() and ldbod2(). Function ldbod(X,k,...) computes outlier scores referencing random subamples of the input data, X. Fucntion ldbod2(X,Y,k,...) computes outlier scores based on a reference data set, Y. Y can be a set of "normal" data points for semi-supervised outlier detection.

Nearest neighbor search is carried out using k-d tree with option for approximate nearest negibhors. Refer to **RANN** package for more details on how nearest neighbors are computed.

and includes two functions ldbod() and ldbod2(), which allow for random subsampling and

### Installation

To install the package in R use the following command:

``` r
install.packages("devtools")
devtools::install_github("kwilliams83/ldbod")
```

<!-- README.md is generated from README.Rmd. Please edit that file -->
