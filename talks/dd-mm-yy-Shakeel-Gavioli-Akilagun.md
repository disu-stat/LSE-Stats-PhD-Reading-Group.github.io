# Testing for changepoints using the multi-resolution norm

The multi-resolution norm of a vector is given by the largest absolute standardized sum over all (contiguous) subsets of elements. Recently, the norm has been used to test for multiple *changepoints* in a linear model by checking whether the norm of empirical residuals exceed a given threshold.  

When testing many possibly overlapping regions of a signal for changepoints the multi-resolution norm gives easy control over the family-wise error of any collection of tests. However, not much is known about the power of changepoint tests based on the multi-resolution norm.

In this talk I will briefly review the multiple changepoint detection problem and discuss some strategies for analyzing the power of changepoint tests based on the multi-resolution norm.
