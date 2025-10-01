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
The course notes linked below serve as the primary textbook. Each chapter corresponds to the content covered in one lecture session. Note that they are © Professor Hutchinson, all rights reserved, and are not covered by the OCW {{% resource_link "b61ad850-201d-4631-a501-e9a19dc473a2" "Creative Commons license" %}}.

The notes have also been adapted and published in book form by {{% resource_link "9db5980e-920e-433d-8b83-28a927e8bc62" "Cambridge University Press" %}}:

- Hutchinson, Ian. _A Student's Guide to Numerical Methods_. Cambridge University Press, 2015. ISBN: 9781107479500.

{{% resource_link "d6de212d-3daa-43b5-a9d5-ae4eebf40ca3" "Course notes home page, preface, & table of contents" %}}

{{< tableopen >}}{{< theadopen >}}{{< tropen >}}{{< thopen >}}
LEC #
{{< thclose >}}{{< thopen >}}
NOTES
{{< thclose >}}{{< thopen >}}
TOPIC SUMMARIES
{{< thclose >}}{{< trclose >}}{{< theadclose >}}{{< tbodyopen >}}{{< tropen >}}{{< tdopen >}}
1
{{< tdclose >}}{{< tdopen >}}
{{% resource_link "071690ad-e753-47d3-b417-8006ed79f954" "Chapter 1: Numerical fitting of data" %}}
{{< tdclose >}}{{< tdopen >}}
1–D least squares fit of a line to a sequence of data. Its representation as a matrix pseudo-inversion problem to determine coefficients.
{{< tdclose >}}{{< trclose >}}{{< tropen >}}{{< tdopen >}}
2
{{< tdclose >}}{{< tdopen >}}
{{% resource_link "d6805fcb-48be-4deb-bc29-ded98443a87c" "Chapter 2: Ordinary differential equations (ODEs)" %}}
{{< tdclose >}}{{< tdopen >}}

Ordinary differential equation of order N in one dependent variable is equivalent to N simultaneous first-order ODEs, i.e. a first order vector ODE. The orbit of a field line or an electron in prescribed static EM fields.

Finite difference expressions for derivative. Accuracy and Stability. Implicit and explicit advancing schemes. Runge-Kutta techniques.

Simple Leapfrog scheme as an example of centered time differences.

{{< tdclose >}}{{< trclose >}}{{< tropen >}}{{< tdopen >}}
3
{{< tdclose >}}{{< tdopen >}}
{{% resource_link "32477355-7b68-4cf1-a4ca-9921c4c84246" "Chapter 3: Two-point boundary conditions" %}}
{{< tdclose >}}{{< tdopen >}}

Second order ODES. Two point boundary conditions.

Example(s) of two-point problems: Slab charge, cylindrical volumetrically-heated conduction.

Shooting method. Bisection.

Second order differences. Linear ODE: Expression of 2-point problem as a matrix equation. Finite difference boundary condition implementation in matrix. Non-uniform derivatives.

{{< tdclose >}}{{< trclose >}}{{< tropen >}}{{< tdopen >}}
4
{{< tdclose >}}{{< tdopen >}}
{{% resource_link "3899480a-7769-455d-ac62-253a5ab5d19e" "Chapter 4: Partial differential equations (PDEs)" %}}
{{< tdclose >}}{{< tdopen >}}

Examples of partial differential equations of engineering physics.

Fluid flow and derivation of the continuity equation. Diffusion. Waves. Electromagnetism. Poisson's equation.

Classification of PDEs. Elliptic, Parabolic, Hyperbolic. Consequences for boundary conditions. Finite difference representation of partial derivatives. Structured (and unstructured) meshes. Difference stencil.

{{< tdclose >}}{{< trclose >}}{{< tropen >}}{{< tdopen >}}
5
{{< tdclose >}}{{< tdopen >}}
{{% resource_link "ebef2f8e-9ab0-4e30-80f2-295582a8fa4a" "Chapter 5: Diffusion; parabolic PDEs" %}}
{{< tdclose >}}{{< tdopen >}}

The diffusion equation and boundaries in space and time.

Explicit FTCS scheme for time evolution of multidimensional PDEs first order in time (parabolic). Stability requirement.

Implicit BTCS scheme for time evolution: Unconditionally stable. Crank-Nicholson and θ–implicit schemes.

Expression of the time advance as a matrix equation. Requirement for inversion in implicit schemes. Multidimensional cases leading to non-tridiagonal sparse matrices. The matrix size difficulty for multiple dimensions.

Example of time-dependent diffusive relaxation to a steady state.

{{< tdclose >}}{{< trclose >}}{{< tropen >}}{{< tdopen >}}
6
{{< tdclose >}}{{< tdopen >}}
{{% resource_link "bb6d0b27-a315-4803-95e8-3ad60b20f708" "Chapter 6: Elliptic problems and iterative matrix solution" %}}
{{< tdclose >}}{{< tdopen >}}

Elliptic equation as steady state of a parabolic equation. Need for matrix inversion. Iteration's equivalence to diffusive relaxation. Solving matrix problem without explicit inversion.

Jacobi, Gauss-Seidel and SOR methods. Convergence.

Nonlinear equations, linearization and iteration.

{{< tdclose >}}{{< trclose >}}{{< tropen >}}{{< tdopen >}}
7
{{< tdclose >}}{{< tdopen >}}
{{% resource_link "d9fbc946-d589-40f1-b5ca-efcf1ef3de16" "Chapter 7: Fluid dynamics and hyperbolic equations" %}}
{{< tdclose >}}{{< tdopen >}}

The fluid momentum conservation equation derived. Fluid closure.

The Navier-Stokes equation in conservation form. Hyperbolic equations in advection form. Eigenvalue of the Jacobian and Characteristics.

Finite differences and stability: FTCS unstable. Lax-Friedrichs and CFL condition. Lax Wendroff, second order accuracy.

{{< tdclose >}}{{< trclose >}}{{< tropen >}}{{< tdopen >}}
8
{{< tdclose >}}{{< tdopen >}}
{{% resource_link "96576f93-b82d-4a8e-8497-2573b6cc671d" "Chapter 8: Boltzmann's equation and its solution" %}}
{{< tdclose >}}{{< tdopen >}}

The distribution function, and flux-density, energy-density.

Boltzmann's equation derivation as an expression of particle conservation in the presence of collisions and sources.

Integration along orbits / characteristics. Vlasov equation distribution behavior.

The collision term. Simple collision process examples.

{{< tdclose >}}{{< trclose >}}{{< tropen >}}{{< tdopen >}}
9
{{< tdclose >}}{{< tdopen >}}
{{% resource_link "a88cb9d2-2591-4014-9d17-6c882cbf7b89" "Chapter 9: Neutron transport" %}}
{{< tdclose >}}{{< tdopen >}}

The Boltzmann equation in terms of flux. Neutron total loss, scattering and fission source terms. Reduction of Boltzmann equation to a (speed-resolved) diffusion equation.

Groups. Multigroup equations and their numerical representation. Leakage. Diffusive timestep stability.

Eigenvalue nature of the steady problem. Power iteration method to solve for dominant eigenvalue.

{{< tdclose >}}{{< trclose >}}{{< tropen >}}{{< tdopen >}}
10
{{< tdclose >}}{{< tdopen >}}
{{% resource_link "83abab03-4684-4070-adfa-4906f576e98d" "Chapter 10: Atomistic and particle-in-cell methods" %}}
{{< tdclose >}}{{< tdopen >}}

Atomistic simulation. Time and space scales. Generic approach. Interparticle force examples: Lennard-Jones, Morse. Computational requirements. Neighbor lists and blocks.

The computational problem of long-range forces. Particle in Cell solution for plasmas. Pseudo-particle representation. Phase space. Direct Simulation Monte Carlo (DSMC) treatment of tenuous gas. Boundary conditions and their implementation.

{{< tdclose >}}{{< trclose >}}{{< tropen >}}{{< tdopen >}}
11
{{< tdclose >}}{{< tdopen >}}
{{% resource_link "42308a09-10a0-43aa-b451-cd4eeebf972f" "Chapter 11: Monte Carlo techniques" %}}
{{< tdclose >}}{{< tdopen >}}
Collisions. Random numbers and statistical distributions. Basic introduction to probability (random variables, pdf, cumulative probability) and statistics (mean, variance, standard error). Random sampling from basic distributions used in Monte Carlo simulations (uniform, exponential, …) and rejection sampling technique. Flux weighted injection.
{{< tdclose >}}{{< trclose >}}{{< tropen >}}{{< tdopen >}}
12
{{< tdclose >}}{{< tdopen >}}
{{% resource_link "3158ddc2-6340-4c99-b89c-fb088bad1bc8" "Chapter 12: Monte Carlo radiation transport" %}}
{{< tdclose >}}{{< tdopen >}}

Transport and collisions. Random walk step length; Poisson statistics. Collision-type choice. New particle generation.

Tracking and tallying of collisions. Statistical uncertainty, and tallying methods to reduce it. Importance sampling.

{{< tdclose >}}{{< trclose >}}{{< tropen >}}{{< tdopen >}}
13
{{< tdclose >}}{{< tdopen >}}
{{% resource_link "d9122520-3974-4905-8485-162b73cda5c7" "Chapter 13: Next steps, e.g. finite elements" %}}
{{< tdclose >}}{{< tdopen >}}
 
{{< tdclose >}}{{< trclose >}}{{< tbodyclose >}}{{< tableclose >}}