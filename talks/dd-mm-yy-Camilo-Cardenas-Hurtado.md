# Automatic selection of tuning parameters in Penalised ML estimation for Latent Variable Models

Penalised (a.k.a regularised) maximum likelihood (PML) estimation is often used in applied statistical modelling with the aims of avoiding overfitting and reducing model complexity (in terms of number of estimated parameters). In the Latent Variable Model (LVM) framework, this is of great importance as one would like to obtain "simple" factor loading matrices that are easier to interpret without necessarily recurring to rotation techniques.

Regularisation techniques require to select a (vector of) hyperparameters, called the "tuning parameters", that control for the degree of penalisation that we require on the model coefficients. Selecting the tuning parameters is a critical task. Usually, tuning parameters are selected based on cross-validation criteria or grid-search techniques that are computationally expensive and leave room for subjectivity. We present an automatic, data-driven procedure for selecting the tuning parameters that minimize an approximate AIC.

In this session we will talk about:

The role of PML estimation and a parallel comparison with rotation techniques,
Types of penalties and their (very handy) quadratic approximation,
Automatic selection of the tuning parameters by an approximate AIC minimization
