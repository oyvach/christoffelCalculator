# christoffelCalculator

sympy code to calculate the linearised Christoffel symbols of perturbed FLRW spacetimes

User is able to choose between
* No perturbations (FLRW)
* Only $\Psi$ and $\Phi$
* $\Psi,\Phi,B^i$
* $\Psi,\Phi,B^i,h_{ij}$
The choice can also be made of whether to use conformal or cosmic time coordinates.
Furthermore the order to which the perturbations should be solved is a free parameter, but runtime is large for higher orders.

The code should be easy to modify for other metrics.
