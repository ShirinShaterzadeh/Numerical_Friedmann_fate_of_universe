# Numerical_Friedmann_fate_of_universe
Numerical integration of the Friedmann equations to simulate cosmic evolution across different density parameters. Assessing the role of each element in the geometry and dynamics of the universe.
## The Physics
The whole cosmos can be described as an evolving system using two equation named the Friedmann equations followed as:

$$(\frac{\dot a}{a})^2 = \frac{8\pi G}{3} \rho - \frac{k}{a^2} + \frac{\Lambda}{3} $$

$$\frac{\ddot a}{a} = \frac{-4\pi G}{3} (\rho + 3P) + \frac{\Lambda}{3}$$

where

a = scale factor

$$\rho$$ = energy density

p = pressure

k = curvature

$$\Lambda$$ = cosmological constant (also known as the dark energy)

The first equation explores the rate of expansion whereas the second one (also known as Raychadhuri equation) is focused on the accellaration of the exapnsion. While integrating these equations seems easy at first sight, one must keep in mind that $$\rho=\rho(t)$$, so integrating is not possible unless we know the dependancy of energy density on time. A simpler form of the two equations can be written using the equation of state and defining a density parameter:


$$\Omega =\frac{\rho}{\rho_c}=\frac{3H_0^2 \rho}{8 \pi G}$$

plus the relationship between the density of each element in the universe (Radiation, Matter, Cosmological constant) and the rate of growth of scale factor. Therefore the Friedmann equations will take the following form, respectively:

$$(\frac{\dot a}{a})^2=H_0^2 (\Omega_r a^{-4} + \Omega_m a^{-3} - \Omega_k a^-{2} + \Omega_\Lambda)$$

$$\frac{\ddot a}{a}= H_0^2(\frac{-1}{2}\Omega_m a^-3 + \Omega_\Lambda)$$

These two equations can be used to assess the change of scale factor of the universe, or in another words, its fate. The amount of the $$\Omega_{total}$$ gives us the geometry of universe as:

$$\Omega_{total} < 1 :$$ Open Universe

$$\Omega_{total} = 1 :$$ Flat Universe

$$\Omega_{total} > 1 :$$ Closed Universe

Though as we see in further calculation, the total density parameter only has a role in determining the geometry, while the real fate of universe (big crunch, big rip, etc) is depending on the individual contributions of each component to the total density. Meaning, the ratio of matter, cosmological constant and curvature specifies the ultimate fate of the universe. In the following project, we are first going to take a deeper insight into the role of each element and then plot the fate of universe for hypothetical cosmological models.

## Domination of Elements

Each component based on its equation of state, scales differently with respect to a:

$$\rho_r\propto a^{-4}$$

$$\rho_m\propto a^{-3}$$

$$\rho_c\propto a^{-2}$$

$$\rho_\Lambda=const$$

Therefore, one can plot the normalized density parameter equation vs the scale factor to see the domination era of each component. As the first step, we use Planck 2018 cosmological parameters [(Aghanim et al. 2018)](https://arxiv.org/abs/1807.06209) :

$$\Omega_r = 9.24\times10^{-5}$$

$$\Omega_m = 0.315$$

$$\Omega_k = 0$$

$$\Omega_\Lambda = 0.685$$

to have the plot that is found in the standard textbooks. Keep in mind that the plot is in logarithmic scales:
