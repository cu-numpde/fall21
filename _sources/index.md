# Welcome

Welcome to **CSCI-5636: Numerical Solution of Partial Differential Equations**

:::{admonition} Logistics
* Meeting Time: MWF 11:30-12:20 in ECEE 283
* Office hours:
  * Monday 1:45-3pm
  * Wednesday 9-10am
  * Friday 1-2pm
* [Join in Zoom](https://cuboulder.zoom.us/j/92542412498)
* [Canvas page](https://canvas.colorado.edu/courses/77070/pages/numerical-solution-of-partial-differential-equations)
:::

::::{admonition} Activities
:::{list-table}
:header-rows: 1
:widths: 30 70

* - Name
  - Objectives
* - [2021-08-25-derivatives](https://classroom.github.com/a/Y_75hFL8)
  - Use GitHub classroom and observe two kinds of numerical error: rounding error and discretization (aka. truncation) error.
* - [2021-09-03-boundaries](https://classroom.github.com/a/P7lUsxs_)
  - Implement symmetric Dirichlet and Neumann boundary conditions with at least second order. Show results to demonstrate order of accuracy, constants on coarse grids, and impact of unevenly spaced grids. Discuss the code complexity for handling boundary conditions compared to the complexity interior to the domain.
* - [2021-09-22-multiscale](https://classroom.github.com/a/ofGhdd06)
  - Investigate diffusion problems in which the coefficient structure varies rapidly, typically on a scale finer than the forcing or observation scales.
* - [2021-10-08-plaplace2d](https://classroom.github.com/a/V8nbGCnh)
  - Make discretization choices for staggered grids, Newton methods, and boundary conditions in 2D. Explain methods and verification with words and figures.
* - [2021-community](https://classroom.github.com/a/viyRxqtk)
  - This has three parts: community presentation, contribution, and retrospective presentation about the contribution experience. The goal is to build a deeper understanding of how open source communities function, what metrics and implicit criteria are valued, and the design decisions and norms that went into making libraries and applications successful. In the first stage, you'll survey the community, and in the second, you'll gain experience making a specific contribution of your choosing.
:::
::::

:::{admonition} Resources

* [SIAM Membership](http://www.siam.org/students/memberships.php) is free for CU students (30% discount on SIAM books)
* Books
  * [Driscoll and Braun, *Fundamentals of Numerical Computation*](https://fncbook.github.io/fnc/frontmatter.html) (free, in Julia with demo notebooks)
  * [Myers, Van de Geijn, Van de Geijn], *Linear Algebra: Foundations to Frontiers*](http://www.ulaff.net/downloads.html) (free PDF and videos)
  * [LeVeque, *Finite Difference Methods for Ordinary and Partial Differential Equations*](https://faculty.washington.edu/rjl/fdmbook/) (CU students can [download free from SIAM](http://epubs.siam.org/doi/book/10.1137/1.9780898717839))
  * [LeVeque, *Finite Volume Methods for Hyperbolic Problems*](https://depts.washington.edu/clawpack/book.html) and the [Clawpack software](http://www.clawpack.org/).
  * [Toro, *Riemann Solvers and Numerical Methods for Fluid Dynamics*](https://link.springer.com/book/10.1007%2Fb79761#toc). (CU students can download free)
  * [Logg, Mardal, Wells, *Automated Solution of Differential Equations by the Finite Element Method (The FEniCS Book)*](https://link.springer.com/book/10.1007%2F978-3-642-23099-8). ([free download](https://fenicsproject.org/book/))
  * [Trefethen, *Spectral Methods in MATLAB*](https://people.maths.ox.ac.uk/trefethen/spectral.html). (CU students can [download free from SIAM](http://epubs.siam.org/doi/book/10.1137/1.9780898719598))
  * [Elman, Silvester, Wathen, *Finite Elements and Fast Iterative Solvers with Applications in Incompressible Fluid Dynamics*](https://doi.org/10.1093/acprof:oso/9780199678792.001.0001) (CU students [click "Full Text" to read online](http://libraries.colorado.edu/record=b7826912~S3))
* Papers
  * [Roache, *Code Verification by the Method of Manufactured Solutions*](https://doi.org/10.1115/1.1436090)
:::
