---
content_type: page
description: This section provides the course notes for each session of the course
  along with summaries of the topics covered.
draft: false
learning_resource_types:
- Lecture Notes
ocw_type: CourseSection
title: Course Notes
uid: ed6fbc8c-33fa-352a-e7bd-2b910c318696
---
The course notes linked below serve as the primary textbook. Each chapter corresponds to the content covered in one lecture session. Note that they are © Professor Hutchinson, all rights reserved, and are not covered by the OCW [Creative Commons license](https://ocw.mit.edu/terms/#cc).

The notes have also been adapted and published in book form by [Cambridge University Press](https://www.cambridge.org/):

- Hutchinson, Ian. _A Student's Guide to Numerical Methods_. Cambridge University Press, 2015. ISBN: 9781107479500.

[Course notes home page, preface, & table of contents](http://silas.psfc.mit.edu/22.15/lectures/index.xml)

{{< tableopen >}}{{< theadopen >}}{{< tropen >}}{{< thopen >}}
LEC #
{{< thclose >}}{{< thopen >}}
NOTES
{{< thclose >}}{{< thopen >}}
TOPIC SUMMARIES
{{< thclose >}}{{< trclose >}}{{< theadclose >}}{{< tbodyopen >}}{{< tropen >}}{{< tdopen >}}
1
{{< tdclose >}}{{< tdopen >}}
[Chapter 1: Numerical fitting of data](http://silas.psfc.mit.edu/22.15/lectures/chap1.xml)
{{< tdclose >}}{{< tdopen >}}
1–D least squares fit of a line to a sequence of data. Its representation as a matrix pseudo-inversion problem to determine coefficients.
{{< tdclose >}}{{< trclose >}}{{< tropen >}}{{< tdopen >}}
2
{{< tdclose >}}{{< tdopen >}}
[Chapter 2: Ordinary differential equations (ODEs)](http://silas.psfc.mit.edu/22.15/lectures/chap2.xml)
{{< tdclose >}}{{< tdopen >}}

Ordinary differential equation of order N in one dependent variable is equivalent to N simultaneous first-order ODEs, i.e. a first order vector ODE. The orbit of a field line or an electron in prescribed static EM fields.

Finite difference expressions for derivative. Accuracy and Stability. Implicit and explicit advancing schemes. Runge-Kutta techniques.

Simple Leapfrog scheme as an example of centered time differences.

{{< tdclose >}}{{< trclose >}}{{< tropen >}}{{< tdopen >}}
3
{{< tdclose >}}{{< tdopen >}}
[Chapter 3: Two-point boundary conditions](http://silas.psfc.mit.edu/22.15/lectures/chap3.xml)
{{< tdclose >}}{{< tdopen >}}

Second order ODES. Two point boundary conditions.

Example(s) of two-point problems: Slab charge, cylindrical volumetrically-heated conduction.

Shooting method. Bisection.

Second order differences. Linear ODE: Expression of 2-point problem as a matrix equation. Finite difference boundary condition implementation in matrix. Non-uniform derivatives.

{{< tdclose >}}{{< trclose >}}{{< tropen >}}{{< tdopen >}}
4
{{< tdclose >}}{{< tdopen >}}
[Chapter 4: Partial differential equations (PDEs)](http://silas.psfc.mit.edu/22.15/lectures/chap4.xml)
{{< tdclose >}}{{< tdopen >}}

Examples of partial differential equations of engineering physics.

Fluid flow and derivation of the continuity equation. Diffusion. Waves. Electromagnetism. Poisson's equation.

Classification of PDEs. Elliptic, Parabolic, Hyperbolic. Consequences for boundary conditions. Finite difference representation of partial derivatives. Structured (and unstructured) meshes. Difference stencil.

{{< tdclose >}}{{< trclose >}}{{< tropen >}}{{< tdopen >}}
5
{{< tdclose >}}{{< tdopen >}}
[Chapter 5: Diffusion; parabolic PDEs](http://silas.psfc.mit.edu/22.15/lectures/chap5.xml)
{{< tdclose >}}{{< tdopen >}}

The diffusion equation and boundaries in space and time.

Explicit FTCS scheme for time evolution of multidimensional PDEs first order in time (parabolic). Stability requirement.

Implicit BTCS scheme for time evolution: Unconditionally stable. Crank-Nicholson and θ–implicit schemes.

Expression of the time advance as a matrix equation. Requirement for inversion in implicit schemes. Multidimensional cases leading to non-tridiagonal sparse matrices. The matrix size difficulty for multiple dimensions.

Example of time-dependent diffusive relaxation to a steady state.

{{< tdclose >}}{{< trclose >}}{{< tropen >}}{{< tdopen >}}
6
{{< tdclose >}}{{< tdopen >}}
[Chapter 6: Elliptic problems and iterative matrix solution](http://silas.psfc.mit.edu/22.15/lectures/chap6.xml)
{{< tdclose >}}{{< tdopen >}}

Elliptic equation as steady state of a parabolic equation. Need for matrix inversion. Iteration's equivalence to diffusive relaxation. Solving matrix problem without explicit inversion.

Jacobi, Gauss-Seidel and SOR methods. Convergence.

Nonlinear equations, linearization and iteration.

{{< tdclose >}}{{< trclose >}}{{< tropen >}}{{< tdopen >}}
7
{{< tdclose >}}{{< tdopen >}}
[Chapter 7: Fluid dynamics and hyperbolic equations](http://silas.psfc.mit.edu/22.15/lectures/chap7.xml)
{{< tdclose >}}{{< tdopen >}}

The fluid momentum conservation equation derived. Fluid closure.

The Navier-Stokes equation in conservation form. Hyperbolic equations in advection form. Eigenvalue of the Jacobian and Characteristics.

Finite differences and stability: FTCS unstable. Lax-Friedrichs and CFL condition. Lax Wendroff, second order accuracy.

{{< tdclose >}}{{< trclose >}}{{< tropen >}}{{< tdopen >}}
8
{{< tdclose >}}{{< tdopen >}}
[Chapter 8: Boltzmann's equation and its solution](http://silas.psfc.mit.edu/22.15/lectures/chap8.xml)
{{< tdclose >}}{{< tdopen >}}

The distribution function, and flux-density, energy-density.

Boltzmann's equation derivation as an expression of particle conservation in the presence of collisions and sources.

Integration along orbits / characteristics. Vlasov equation distribution behavior.

The collision term. Simple collision process examples.

{{< tdclose >}}{{< trclose >}}{{< tropen >}}{{< tdopen >}}
9
{{< tdclose >}}{{< tdopen >}}
[Chapter 9: Neutron transport](http://silas.psfc.mit.edu/22.15/lectures/chap9.xml)
{{< tdclose >}}{{< tdopen >}}

The Boltzmann equation in terms of flux. Neutron total loss, scattering and fission source terms. Reduction of Boltzmann equation to a (speed-resolved) diffusion equation.

Groups. Multigroup equations and their numerical representation. Leakage. Diffusive timestep stability.

Eigenvalue nature of the steady problem. Power iteration method to solve for dominant eigenvalue.

{{< tdclose >}}{{< trclose >}}{{< tropen >}}{{< tdopen >}}
10
{{< tdclose >}}{{< tdopen >}}
[Chapter 10: Atomistic and particle-in-cell methods](http://silas.psfc.mit.edu/22.15/lectures/chap10.xml)
{{< tdclose >}}{{< tdopen >}}

Atomistic simulation. Time and space scales. Generic approach. Interparticle force examples: Lennard-Jones, Morse. Computational requirements. Neighbor lists and blocks.

The computational problem of long-range forces. Particle in Cell solution for plasmas. Pseudo-particle representation. Phase space. Direct Simulation Monte Carlo (DSMC) treatment of tenuous gas. Boundary conditions and their implementation.

{{< tdclose >}}{{< trclose >}}{{< tropen >}}{{< tdopen >}}
11
{{< tdclose >}}{{< tdopen >}}
[Chapter 11: Monte Carlo techniques](http://silas.psfc.mit.edu/22.15/lectures/chap11.xml)
{{< tdclose >}}{{< tdopen >}}
Collisions. Random numbers and statistical distributions. Basic introduction to probability (random variables, pdf, cumulative probability) and statistics (mean, variance, standard error). Random sampling from basic distributions used in Monte Carlo simulations (uniform, exponential, …) and rejection sampling technique. Flux weighted injection.
{{< tdclose >}}{{< trclose >}}{{< tropen >}}{{< tdopen >}}
12
{{< tdclose >}}{{< tdopen >}}
[Chapter 12: Monte Carlo radiation transport](http://silas.psfc.mit.edu/22.15/lectures/chap12.xml)
{{< tdclose >}}{{< tdopen >}}

Transport and collisions. Random walk step length; Poisson statistics. Collision-type choice. New particle generation.

Tracking and tallying of collisions. Statistical uncertainty, and tallying methods to reduce it. Importance sampling.

{{< tdclose >}}{{< trclose >}}{{< tropen >}}{{< tdopen >}}
13
{{< tdclose >}}{{< tdopen >}}
[Chapter 13: Next steps, e.g. finite elements](http://silas.psfc.mit.edu/22.15/lectures/chap13.xml)
{{< tdclose >}}{{< tdopen >}}
 
{{< tdclose >}}{{< trclose >}}{{< tbodyclose >}}{{< tableclose >}}