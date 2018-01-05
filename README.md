* [Inviscid Bump](Inviscid_Bump/Inviscid_Bump) - A simulation of internal, inviscid flow through a 2D geometry
  - Steady, 2D Euler equations 
  - Multigrid
  - JST numerical scheme in space
  - Euler implicit time integration
  - Inlet, Outlet, and Euler Wall boundary conditions
* [Inviscid Wedge](Inviscid_Wedge/Inviscid_Wedge) - Get familiar with supersonic flows 
  - Steady, 2-D Euler equations 
  - Multigrid
  - HLLC numerical scheme in space
  - Euler implicit time integration
  - Supersonic Inlet, Outlet, and Euler Wall boundary conditions
  - CGNS to SU2 mesh conversion
* [Inviscid OneraM6](Inviscid_OneraM6/Inviscid_OneraM6) - Simulation of external, inviscid flow around a 3D geometry
  - Steady, 3D Euler equations 
  - Multigrid
  - JST numerical scheme in space
  - Euler implicit time integration
  - Euler Wall, Symmetry, and Far-field boundary conditions
  - Code parallelism 
* [Laminar Cylinder](Laminar_Cylinder/Laminar_Cylinder) - Simulation of external, laminar flow around a 2D cylinder
  - Steady, 2D Laminar Navier-Stokes equations 
  - Multigrid
  - Roe (Second-order) numerical scheme in space and slope limiter
  - Euler implicit time integration
  - Navier-Stokes wall and far-field boundary conditions
* [Laminar Flat Plate](Laminar_Flat_Plate/Laminar_Flat_Plate) - Simulation of external, laminar flow over a flat plate
  - Steady, 2D, Laminar Navier-Stokes equations 
  - Multigrid
  - Roe (Second-Order) numerical scheme in space
  - Euler implicit time integration
  - Inlet, Outlet, Symmetry, and Navier-Stokes Wall boundary conditions
  - Cauchy convergence criteria
* [Turbulent Flat Plate](Turbulent_Flat_Plate/Turbulent_Flat_Plate) - Simulation of external, turbulent flow over a flat plate
 - Steady, 2D RANS Navier-Stokes equations 
 - Spalart-Allmaras turbulence model
 - Roe 2nd-order numerical scheme in space
 - Euler implicit time integration
 - Inlet, Outlet, and Navier-Stokes Wall boundary conditions
* [Transitional Flat Plate](Transitional_Flat_Plate/Transitional_Flat_Plate) - Simulation of external, transitional flow over a flat plate
  - Steady, 2D, incompressible RANS equations
  - Spalart-Allmaras (S-A) turbulence model with Bas-Cakmakcioglu (B-C) transition model
  - Roe 2nd-order numerical scheme in space
  - Inlet, Outlet, Symmetry and No-Slip Wall boundary conditions
* [Turbulent OneraM6](Turbulent_OneraM6/Turbulent_OneraM6) - Simulation of external, viscous flow around a 3D geometry using a turbulence model
  - Steady, 3D RANS equations 
  - Spalart-Allmaras turbulence model
  - Roe 2nd-order numerical scheme in space
  - Euler implicit time integration
  - Navier-Stokes Wall, Symmetry, and Far-field boundary conditions
  - Code parallelism (optional)
* [Optimal Shape Design](Optimal_Shape_Design/Optimal_Shape_Design) - Perform an optimal shape design of a 2D geometry
  - Direct and adjoint flow simulation
  - Optimal shape design Options
  - Hicks-Henne parameters
* [Constrained Optimal Shape Design](Constrained_Optimal_Shape_Design/Constrained_Optimal_Shape_Design) - Perform an optimal shape design of a 3D geometry
  - Direct and adjoint flow simulation
  - Optimal shape design options
  - Free-Form deformation method
  - Geometrical constraints (thickness)
