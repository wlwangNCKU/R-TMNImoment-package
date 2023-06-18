# R-TMNImoment-package
Multivariate Normal/Independent Distributions with Double Truncation
This package provides functions related to the multivariate normal/independent (MNI) distributions with double truncations considered in Lin and Wang (2023). The considered MNI distributions contain the multivariate normal (MVN), multivariate t (MVT), multivariate slash (MSL), multivariate contaminated normal (MCN) and multivariate variance-gamma (MVG) distributions. The ‘dmni’ and ‘pmni’ functions calculate the probability density and distribution functions for the MNI distributions.  The ‘dtmni’ and ‘ptmni’ calculate the probability density and distribution functions for the truncated MNI distributions, and the ‘rtmni’ function generates random number (vector) from the truncated MNI distributions. The ‘TMNI.moment’ function computes the first two moments of doubly truncated MNI distributions theoretically.

Note: The cubature, mvtnorm, tmvtnorm, invgamma, and Bessel R packages are required. 
