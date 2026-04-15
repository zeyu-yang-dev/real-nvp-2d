# RealNVP 2D

A study of **RealNVP (Real-valued Non-Volume Preserving)**, 
a normalizing flow model that learns invertible transformations between complex data distributions and simple latent distributions, 
enabling exact density estimation and sampling, demonstrated in two dimensions.

This repository contains two Jupyter notebooks:


## RealNVP: Modeling, Training, Density Estimation, and Sampling

`real_nvp_2d.ipynb`

Includes:
- RealNVP model construction and training
- forward and inverse transformations
- density estimation and outlier detection
- sampling and data generation


## Interactive Demo: Data-to-Latent Transformation

`real_nvp_2d_interactive_demo.ipynb`

Interactively move a point in the data space and observe how it is mapped to the latent space by the trained RealNVP model.

Run in browser: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/zeyu-yang-dev/real-nvp-2d/HEAD?urlpath=%2Fdoc%2Ftree%2Fnotebooks%2Freal_nvp_2d_interactive_demo.ipynb)




