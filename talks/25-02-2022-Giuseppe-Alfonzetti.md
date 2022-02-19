# Composite likelihood methods and surroundings

When the joint likelihood of your data is intractable or too complex, maximum likelihood estimation may be 
overly computationally expensive to be of practical use. One possible strategy to deal with the problem is to 
build a surrogate likelihood by composing together several lower dimensional margins of the original likelihood. 
The maximizer of the resulting composite likelihood function will still be consistent and asymptotically normally distributed. The price you agree to pay is to make inference under a model misspecified by 
construction. Thanks to their flexibility, composite likelihood methods have been applied on several statistical 
problems, but many computational challenges still remain and prevent an even wider use.

In this talk we are going to deal with:
* A review of composite likelihood estimation and classical inferential results
* Applications across different areas of the statistical literature
* Strategies to select and combine the low-dimensional contributions considered
