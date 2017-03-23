---
layout: reading
title: "Axial Symmetry Breaking in Self-Induced Neutrino Flavor Conversions"
date: 2017-02-27
modified: 2017-02-27 #2014-08-27T11:57:41-04:00
author: Lei Ma
comments: true
sidebar:
  title: "All Readings"
  nav: sidebar-reading
categories:
  - collective oscillations
tags:
  - collective oscillations
  - axial symmetry breaking
summary: Local symmetry can be broken by a mult-azimuth-angle instability.
ref:
  - title: "Axial Symmetry Breaking in Self-Induced Flavor Conversion of Supernova Neutrino Fluxes"
    link: http://link.aps.org/doi/10.1103/PhysRevLett.111.091101
published: true
---





The authors consider collision less neutrino propagation. The convention for Hamiltonian is

$$
\mathrm H = \frac{\mathrm M^2}{2E} + \sqrt{2}G_F\left( \mathrm N_l +\int_{-\infty}^\infty dE' \int \frac{d\mathbf v'}{(2\pi)^3} \rho' (1-\mathbf v \cdot \mathbf v') \right)
$$

The idea is that axial symmetry can be spontaneously broken in multiangle approach or continuous angle distribution. That is to say, even we start from a axial symmetric configuration, the axial symmetric for flavor instabilities can be broken locally.

> Comment: This result seems to be weird. We have axial symmetry of initial conditions. Meanwhile the equation of motion preserves the axial symmetry.

## Notations

Here is a list of all the definitions and notations.

1. The vacuum Hamiltonian

   $$
   \mathrm M^2
   $$

2. Matter contribution to Hamiltonian

   $$
   \mathrm N_l
   $$

3. $\theta_R$ position of emission point on neutrino sphere.
4. $u=\sin^2\theta_R$ is a parameter that is used to work out the radial velocity $v_{r,u}=\sqrt{1-u R^2/r^2}$ and transverse velocity $\beta_{r,u}=\sqrt{u}R/r$.
5. Flux matrix is related to density matrix

   $$
   \frac{\mathrm F(r,E,u,\phi)}{4\pi r^2} \frac{d E du d\phi}{v(u,r)} = \rho(r,\mathbf p) \frac{d^2\mathbf p}{(2\pi)^3}.
   $$

   Flux matrix can be used instead of density matrix to describe the dynamics,

   $$
   \partial_r \mathbf F = -i[\mathrm H,\mathrm F]
   $$

6. Coherent scattering becomes

   $$
   \mathrm H_{\nu\nu} = \sqrt{2}G_F \int d\Gamma' \mathrm F' \frac{1 - v v' - \boldsymbol \beta \cdot \boldsymbol \beta'}{v v'}.
   $$

7. Linearization is done using flux matrix

   $$
   \mathrm F = \frac{\mathrm{Tr}\mathrm F}{2} + \frac{F_{ee}-F_{xx}}{2} \begin{pmatrix} s & S \\ S^* & -s \end{pmatrix}.
   $$

8. Matter potential

   $$
   \lambda = \sqrt{2}G_F ( n_e - n_{\bar e} ) \frac{R^2}{2r^2},
   $$

   and

   $$
   \bar \lambda = \lambda + \epsilon \mu.
   $$

9. Normalized self-interaction potential

   $$
   \mu = \frac{\sqrt{2}G_F (F_{\bar \nu_e} (R ) -  F_{\bar \nu_x}(R) ) }{4\pi r^2} \frac{R^2}{2r^2}.
   $$


## Linearized Equation of Motion

Assuming the solution to perturbation $S$ has the form $S = Q_\Omega e^{i\Omega r}$, where $\Omega=\gamma + i \kappa$.

$$
(\omega + \mu \bar \lambda-\Omega) Q _ \Omega=\mu \int d\Gamma' (u + u' -2\sqrt{u u'} \cos(\phi - \phi') ) g' Q'_ \Omega.
$$


<div class="notes--warning" markdown="1">

Question: What happens if
  $$
  \omega + \mu \bar \lambda -\Omega =0?
  $$

Then the equation of motion becomes the rhs integral being 0. Either the integrand is zero, or the integrand has positive and negative regions and they sum up to zero.

I don't think we can solve this equation.

</div>

The integral on the right hand side should have the form

$$
a + b u + \sqrt{u}(c\cos \phi + d\sin\phi).
$$

The solution to $Q_\Omega$ should be of the form

$$
Q _ \Omega= \frac{a + b u + \sqrt{u}(c\cos \phi + d\sin\phi)}{ \omega + \mu \bar\lambda - \Omega }.
$$

Then we plug this result back into the equation of motion and find out a matrix equation for the unknown coefficients $a,b,c,d$. We require that the equation has nontrivial solutions. So the problem becomes an eigenvalue problem.




## Axial Symmetric Emission

The spectrum $g$ doesn't depend on $\phi$. But the solution to frequency can depend on $\phi$.

## Single Energy Model

Energy spectrum is

$$
g(\omega) = - \delta(\omega + \omega_0) + (1+\epsilon) \delta(\omega-\omega_0).
$$

The author solved system

1. Inverted hierarchy ($\omega_0>0$), bimodal instability.
2. NH ($\omega_0<0$), MZA & MAA instability.


## Matter Effect

At large matter density, instability occurs at larger $\sim\lambda/\lvert q_j\rvert\sim \lambda$. Matter suppression of instability.
