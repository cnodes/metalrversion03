# 'metalr': Likelihood ratio meta-analysis package

`R` software package to estimate traditional 95% CIs and 95% intrinsic CIs based on the likelihood ratio meta-analytic approach proposed by [Dormuth et al., 2016](https://www.ncbi.nlm.nih.gov/pubmed/26837056). In the figure below, we present an example of a forest plot showing 95% CIs and 95% ICIs ( of odds ratio) in a random effect meta-analysis. The combined confidence limits of the 9 studies is also shown.

![](man/figures/forest_metalr_eg.png)



## Installation

The dev version of the `metalr` package can be installed from [GitHub](https://github.com/laminjuwara/metalr) using:

```R
if (!require("devtools")) install.packages("devtools")
devtools::install_github("laminjuwara/metalr")
```


## Functionalities

The `metalr` package provide functionalities estimating 95% CIs and ICIs of rate ratio or odds ratio in single studies as well as total effect estimates in meta-analysis. The functions included in the R package are
- ici.or()
- ici.rr()
- metalr_or()
- metalr_rr()
- forest_metalr()

In the [online vignette](https://github.com/LaminJuwara/metalr/blob/master/inst/doc/metalr_document.Rmd), a detailed description of the functions are given. Examples of their usage is also presented.


## Contact

* Pull Requests: <https://github.com/cnodes/metalr/>
* e-mail: <lamin.juwara@mail.mcgill.ca>


