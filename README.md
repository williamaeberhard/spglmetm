spglmetm: an R package for fitting of semi-parametric GLMs based on exponentially tilted mixtures
-------------------------------------------------------------------------------------------------

This R package provides functions for fitting semi-parametric generalized linear models for response variables with continuous support whose distribution is not fully specified. Rather, only a mean equation is specified and the baseline (carrier) distribution of the exponential family is approximated by a mixture of basis density functions.

Package updates can be found at https://github.com/williamaeberhard/spglmetm.

Any requests/comments/bug reports should be sent to william.aeberhard@gmail.com.

### Contents

Files contained in this repository:

* spglmetm_0.5.tar.gz, a tarball containing the R package to be installed from R, see below;
* a LICENSE file;
* this README file.

### Version History

This is spglmetm version 0.5. This is the initial release.

Tested and compiled on R version 3.2.2. R CMD check returned all ok.

### Package Installation

1. Open R.
2. Make sure your working directory contains the file spglmetm_0.5.tar.gz.
3. Run install.packages('spglmetm_0.5.tar.gz',repos=NULL,type='source').
4. Load the package by running library(spglmetm).
5. Check out the main help page by running help(spglmetm).

### References

Aeberhard, W. H. and Hannay, M. (2016) Semi-Parametric Generalised Linear Models based on Exponentially Tilted Mixtures. Working Paper.
