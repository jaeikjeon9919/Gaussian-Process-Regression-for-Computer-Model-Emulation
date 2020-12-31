# Gaussian-Process-Regression-for-Computer-Model-Emulation
Jaeik Jeon
## Abstract

We consider a full Bayesian approach for the estimation of the parameters of a
Gaussian process and its application to Computer model emulation. Gu et al. (2017)
suggests certain parameterizations of the covariance structure that have certain advantages when finding the posterior modes. However it turns out that such parametrization
may not be appropriate for sampling from the posterior of range parameters using the
Metropolis-Hasting algorithm, especially when there are inert inputs. In this paper,
we present one possible parametrization of correlation structure for the full Bayesian
approach, and the method is applied to an emulator of Multiphase Flow with Interphase eXchanges (MFIX) which is a computational fluid dynamics model of a bubbling
fluidized bed.
