# Constraining Cosmological Parameters

## Part 1

## <em> Constraining CMB Parameters </em>

(Power Spectrum data can be found in \Data_part1)

This notebook accomplishes the following:

1. Plot Plank Power Spectrum Data against theoretical model

2. Constrain cosmological parameters $H_0$, $\Omega_b$, $h^2$, $\Omega_c$, $h^2$, $n_s$, $10^9A_s$, and $\tau$ using various techniques including Gauss-Newton optimization, SVD (Linear Alegra approach), etc.

3. Computle the covariance matrix $\big(J(\vec{\theta})^TJ(\vec{\theta})\big)^{-1}$ to plot 1-D and 2-D constraints on these parameters, with the 68% and 95% confidence ellipses for each parameter pair.

4. Implementation of simple gradient descent, gradient descent with momentum, and ADAM Optimization.

## Part 2

## <em> Optimization, Markov chain Monte Carlo, pocoMC </em>

This notebook accomplishes the following:

1. Load and analyze Supernova Type Ia data from the Union2.1 compilation to study cosmic expansion.

2. Derive luminosity distance and distance modulus relations for cosmological parameter inference.

3. Apply optimization and MCMC methods to constrain cosmological parameters from Supernova data.

4. Use the `pocoMC` framework to sample parameter space and evaluate model likelihoods.

5. Demonstrate MCMC parameter constraints for galaxy clustering via Halo Occupation Distribution (HOD) modeling.

6. Infer HOD parameters such as $\log M_{\mathrm{min}}$, $\sigma_{\log M}$, $\log M_0$, $\log M_1$, $\alpha$, $A_{cen}$, and $A_{sat}$.
