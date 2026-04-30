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

The first equation explores the rate of expansion whereas the second one (also known as Raychadhuri equation) is focused on the accellaration of the exapnsion. A simpler form of the two equations can be written using the equation of state and defining a density parameter:

$$\Omega = \frac{3H_0^2}{8 \pi G}$$

plus the relationship between the density of each element in the universe (Radiation, Matter, Cosmological constant) and the rate of growth of scale factor. Therefore the Friedmann equations will take the following form, respectively:

$$(\frac{\dot a}{a})^2=H_0^2 (\Omega_r a^-4 + \Omega_m a^-3 - \Omega_k a^-2 + \Omega_\Lambda)$$

$$\frac{\ddot a}{a}= H_0^2(\frac{-1}{2}\Omega_m a^-3 + \Omega_\Lambda)$$
