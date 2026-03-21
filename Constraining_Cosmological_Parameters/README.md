# Constraining Cosmological Parameters

## Part 1

(Power Spectrum data can be found in \Data_part1)

1. We plot the Plank Power Spectrum Data against the theoretical model

2. We constrain the cosmological parameters $H_0$, $\Omega_b$, $h^2$, $\Omega_c$, $h^2$, $n_s$, $10^9A_s$, and $\tau$ using various techniques. These include Gauss-Newton optimization, SVD (Linear Alegra approach), etc.

3. We Computle the covariance matrix $\big(J(\vec{\theta})^TJ(\vec{\theta})\big)^{-1}$ to plot 1-D and 2-D constraints on these parameters, with the 2-D plot showing the 68% and 95% confidence ellipses for each parameter pair.

4. We practice implementation of simple gradient descent, gradient descent with momentum, and ADAM Optimization.