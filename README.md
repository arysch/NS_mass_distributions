# NS_mass_distributions

This notebook accompanies the publication: LINK and INFO. If you use this work in your own research, please cite CITATION.

# Overview
This project performs a statistical comparison of neutron star mass distributions between two populations:

Gaia Neutron Stars: Single neutron stars identified by the Gaia space telescope \
Recycled Double Neutron Stars (rDNS): The recycled component from double neutron star binary systems \
The analysis uses Bayesian inference with MCMC sampling to fit double Gaussian mixture models and compare the underlying mass distributions using statistical divergence measures.

# Features
Bayesian Model Fitting: Double Gaussian mixture models with uniform priors \
MCMC Sampling: No-U-Turn Sampler (NUTS) for efficient posterior exploration \
Statistical Comparison: Jensen-Shannon divergence and Wasserstein distance calculations \

# Dependencies
jax \
jaxlib \
numpyro \
arviz \
matplotlib \
numpy \
scipy \
corner \
pandas \
seaborn \
