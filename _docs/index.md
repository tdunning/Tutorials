---
title: Welcome!
permalink: /docs/home/
redirect_from: /docs/index.html
---

## Getting started with SU2

Rather than writing a long manual on all available (and constantly evolving) configuration options available in SU2, the approach has been taken to teach the various aspects of the SU2 code through a range of tutorials. If you would like to see all of the available config options, we keep a configuration file template in the root directory of the source distribution (see [config_template.cfg](https://github.com/su2code/SU2/blob/master/config_template.cfg)).

The tutorials are numbered roughly in order of their complexity and how experienced with the code the user may need to be, noting that the more advanced tutorials may assume the user has already worked through the earlier ones. Each tutorial attempts to present new features of SU2 and contains explanations for the key configuration file options. More information on the exact learning goals of a tutorial can be seen at the beginning of each.

You can get all the mesh and config files either by cloning or downloading the [Tutorials repository](https://github.com/su2code/Tutorials) or by downloading them separately using the provided links on each tutorial page.

**Note:** Before beginning with the tutorials, please make sure to check out the information on how to [download](https://github.com/su2code/SU2/wiki/Download) and [install](https://github.com/su2code/SU2/wiki/Installation) SU2 in the official [wiki](https://github.com/su2code/SU2/wiki).

## Summary of tutorials
------

#### Basic Features

* [Inviscid Bump in a Channel](/Tutorials/docs/Inviscid_Bump/)   
A simulation of internal, inviscid flow through a 2D geometry.
* [Inviscid Supersonic Wedge](/Tutorials/docs/Inviscid_Wedge/)    
Get familiar with supersonic flows.
* [Inviscid OneraM6](/Tutorials/docs/Inviscid_OneraM6/)   
Simulation of external, inviscid flow around a 3D geometry.
* [Laminar Flat Plate](/Tutorials/docs/Laminar_Flat_Plate/)   
Simulation of external, laminar flow over a flat plate.
* [Laminar Cylinder](/Tutorials/docs/Laminar_Cylinder/)    
Simulation of external, laminar flow around a 2D cylinder.
* [Turbulent Flat Plate](/Tutorials/docs/Turbulent_Flat_Plate/)    
Simulation of external, turbulent flow over a flat plate.
* [Transitional Flat Plate](/Tutorials/docs/Transitional_Flat_Plate/)    
Simulation of external, transitional flow over a flat plate.
* [Turbulent OneraM6](/Tutorials/docs/Turbulent_OneraM6/)     
Simulation of external, viscous flow around a 3D geometry using a turbulence model.

#### Shape Design

* [Unconstrained shape design of a transonic inviscid airfoil](/Tutorials/docs/NACA0012_Design)
Perform an optimal shape design of a 2D geometry without constraints.
* [Constrained shape design of a transonic turbulent airfoil at a cte. C<sub>L</sub>](/Tutorials/docs/RAE2822_Design)
Perform an optimal shape design of a 2D geometry with flow and geometrical constraints.
* [Constrained shape design of a transonic inviscid wing at a cte. C<sub>L</sub>](/Tutorials/docs/ONERAM6_Design)
Perform an optimal shape design of a 3D geometry with geometrical constraints.
