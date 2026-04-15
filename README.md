### Exponentially Fading Memory (EFM) Signature 

This repository reproduces the results of  [Abi Jaber and Sotnikov (2025)](https://arxiv.org/pdf/2507.03700). 

We implement: 
- (EFM-)signature representation of Ornstein–Uhlenbeck and Langevin-type processes, with a comparison of out-of-sample performance (see `demo.ipynb`),
- forecasting of the VIX index and SPX realized volatility, and comparison with HAR in the same spirit as in [Hager, Harang, Pelizzari and Tindel (2026)](https://arxiv.org/pdf/2603.04525) (see `forecasting.ipynb`), 
- computation of conditional moments of Ornstein-Uhlenbeck and CIR processes, multi-factor approximation of completely monotone kernels for the conditional moments of Gaussian Volterra processes $X_t = \int_{-\infty}^t K(t-s)\, dW_s$, for $t\in \mathbb{R}.$ (see `moments_EFM.ipynb`), 
- characteristic function of linear functionals of the EFM-signature of time-augmented Brownian motion, comparison of RK4, Euler and Predictor-Corrector schemes (see `characteristic_function.ipynb`), 
- introduction of a model in which the instantaneous volatility is given by a linear combination of elements of the EFM-signature of time-augmented Brownian motion, pricing of $q$-Volatility swaps and computation of IV via Fourier inversion (see `fourier_EFM.ipynb`).

### Examples of illustrations 

![VIX](assets/forecast_vix.png)

![OU](assets/comparison_OU.png)

![REG](assets/regression_langevin.png)

![VOLSWAP](assets/vol_swaps_SteinStein_EFM.png)

### Disclaimer 
Source code is available upon request. Please contact me directly. 