# Mathematical Derivation

### Core Formula

The proposed triadic model is:

$$
\frac{\eta}{s} = \frac{\hbar}{4\pi k_B} \cdot \frac{1}{1 + \varepsilon}
$$

with

$$
\varepsilon = \kappa (\alpha Q_1 + \beta Q_2 + \gamma Q_3), \quad \alpha + \beta + \gamma = 1
$$

where $\kappa$ is a small dimensionless scaling factor ($\sim 0.01$).

### Physical Definition of $Q_2$

$Q_2$ is derived directly from scattering physics:

$$
Q_2 := \frac{\sigma}{\pi d^2}
$$

- $\sigma$ = transport scattering cross-section  
- $d$ = mean interparticle distance $= n^{-1/3}$

This definition connects naturally to the relaxation time $\tau = 1/(n \sigma v)$ and leads to the Planckian dissipation limit $\tau \gtrsim \hbar / k_B T$ when scattering is constrained by quantum unitarity ($\sigma \lesssim \lambda_{dB}^2$).

### Two Regimes

- **Classical regime** ($\Gamma \ll 1$): $\sigma \approx \pi a^2 \exp(\Gamma)$ $\to$ $Q_2$ grows exponentially

- **Strongly quantum regime** ($\Gamma \gg 1$): $\sigma$ saturates at $\sim \lambda_{dB}^2$ $\to$ $Q_2$ saturates at $\sim 1$ to $4$

This reproduces the observed saturation of $\eta/s$ near the KSS bound in strongly correlated systems and the collapse of viscosity in superfluid and topologically ordered phases.
