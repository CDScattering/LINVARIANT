---
layout: page
title: "About"
css: ["about.css", "animate.css", "morphext.css"]
{% js: ["morphext.min.js", "about.js"] %}
---
{% include about.html %}
# LINVARIANT
**LINVARIANT** is a Universal model generator, in the field of computational condensed matter physics. <br />
**INVARIANT** are such objects though we construct with the help of coordinate systems turn out to be independent of coordinates. <br />
**L** is to memorize famous physicist Lev Davidovich Landau (22 January 1908 – 1 April 1968). <br />
- Utilizing the Group Theory, it mathematically modeling physics systems such as Lattice, Electron, Spin and their coupling systems.
- LINVARIANT generates symmetry adapted microscopic or phenomenological models.
- LINVARIANT creates DFT training sets for the model fitting.
- LINVARIANT has numerical solvers running on the model, such as MC, MD, Exact diagnalization, Minimization, and et al..
- For large scale calculations, LINVARIANT exports the symbolic models into FORTRAN/C++ modules together with FORTRAN/C++ solvers, buiding files.
## Features:
- Displacement and magnetic modes analysis
- INVARIANT generator (couplings among distortion, strain and magnetic)
- Modulate modes in supercell, generate initial Domain walls (DWs) structures for Density Functional Theory (DFT) codes
- Landau model builder, Generate DFT training sets by phonon and magnetic frozen-in.
- Heisenberg model with DM model builder
- Tight-Binding model builder
- Finite Element Method (FEM), Minimization, molecular dynamics (MD), Monte Carlo (MC), and Finite Differences nonlinear solver on large scale continuous model
- Generate Fortran source code from mathematica
- openmp parallelization
- dynamics under external electric field
- Jij of Heisenberg model from DFT, in Liechtenstein manner
- Unfolding
- phonon/magnon calculations from DFT input
- X ray diffraction simulation
- Nudged Elastic Bands (NEB) and Growing String Method (GSM) to explore the phase transition, dynamics, and domain wall structures
- Mollwide projection
- Examples: Boracite, Perovskite (To be added: Spinel, Rutile, Pyrochlore)
## Todo:
- implement LLG dynamics
- implement k dot p model builder
- interface to exact diagonalization method
- adding Atomistic Green's Function (AGF) method to study scattering and ultrafast non-equilibrium dynamics
- including electron phonon coupling (EPC) by fitting phonon dependent Tight-Binding (TB) model from DFT molecular dynamics (MD).
## Authors
* **Peng Chen** - peng.chen.iphy@gmail.com
* **Sergey Artyukhin** - sergey.artyukhin@iit.it  <br />
## Contributors
* **Hongjian Zhao** - solidstatezhao@gmail.com
* **Laurent Bellaiche** - laurent@uark.edu

See also the list of [contributors](https://github.com/PaulChern/LINVARIANT/contributors) who participated in this project.
