### Exponentially Fading Memory Signature 

This repository reproduces the results of  [Abi Jaber and Sotnikov (2025)](https://arxiv.org/pdf/2507.03700). 

We implement: 
- (see `demo.ipynb`)
- (see `forecasting.ipynb`) 
- computation of conditional moments of Ornstein-Uhlenbeck and CIR processes, multi-factor approximation of completely monotone kernels for the conditional moments of Gaussian Volterra processes $X_t = \int_{-\infty}^t K(t-s) dW_s$. (see `moments_EFM.ipynb`), 
- (see `characteristic_function.ipynb`) 

### Examples of illustrations 

![VIX](assets/forecast_vix.png)

![OU](assets/comparison_OU.png)

![REG](assets/regression_langevin.png)

![MOMENTS](assets/conditional_OU_EFM_2.png)

### Disclaimer 
Source code is available upon request. Please contact me directly. 