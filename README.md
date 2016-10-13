Multiscale Multiphase Modelling of Granular Flows
=================================================
> A PhD thesis submitted to the Department of Engineering, University of Cambridge (January, 2015).

[![Build Status](https://api.travis-ci.org/kks32/phd-thesis.svg)](https://travis-ci.org/kks32/phd-thesis)
[![License CC 4.0](https://img.shields.io/badge/license-CC--4.0-brightgreen.svg)](license.md)


[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.160339.svg)](https://doi.org/10.5281/zenodo.160339)



## Author
*   Krishna Kumar

## Supervisor
*   Prof. Kenichi Soga

## Abstract
Geophysical hazards usually involve multiphase flow of dense granular solids and water.
Understanding the mechanics of granular flow is of particular importance in predicting the
run-out behaviour of debris flows. The dynamics of a homogeneous granular flow involve
three distinct scales: the microscopic scale, the meso-scale, and the macroscopic scale.
Conventionally, granular flows are modelled as a continuum because they exhibit many
collective phenomena. Recent studies, however, suggest that a continuum law may be unable
to capture the effect of inhomogeneities at the grain scale level, such as orientation of force
chains, which are micro-structural effects. Discrete element methods (DEM) are capable of
simulating these micro-structural effects, however they are computationally expensive. In the
present study, a multi-scale approach is adopted, using both DEM and continuum techniques,
to better understand the rheology of granular flows and the limitations of continuum models.

The collapse of a granular column on a horizontal surface is a simple case of granular
flow; however, a proper model that describes the flow dynamics is still lacking. In the present
study, the generalised interpolation material point method (GIMPM), a hybrid Eulerian –
Lagrangian approach, is implemented with the Mohr-Coloumb failure criterion to describe
the continuum behaviour of granular flows. The granular column collapse is also simulated
using DEM to understand the micro-mechanics of the flow. The limitations of MPM in
modelling the flow dynamics are studied by inspecting the energy dissipation mechanisms.
The lack of collisional dissipation in the Mohr-Coloumb model results in longer run-out
distances for granular flows in dilute regimes (where the mean pressure is low). However, the
model is able to capture the rheology of dense granular flows, such as the run-out evolution
of slopes subjected to lateral excitation, where the inertial number I < 0.1.

The initiation and propagation of submarine flows depend mainly on the slope, density,
and quantity of the material destabilised. Certain macroscopic models are able to capture
simple mechanical behaviours, however the complex physical mechanisms that occur at the
grain scale, such as hydrodynamic instabilities and formation of clusters, have largely been
ignored. In order to describe the mechanism of submarine granular flows, it is important to
consider both the dynamics of the solid phase and the role of the ambient fluid. In the present
study, a two-dimensional coupled Lattice Boltzmann LBM – DEM technique is developed to understand the micro-scale rheology of granular flows in fluid. Parametric analyses are
performed to assess the influence of initial configuration, permeability, and slope of the
inclined plane on the flow. The effect of hydrodynamic forces on the run-out evolution is
analysed by comparing the energy dissipation and flow evolution between dry and immersed
conditions.
