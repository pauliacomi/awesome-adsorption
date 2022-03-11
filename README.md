# Adsorption Awesome [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

Awesome list of open source / freely available tools that help treat,
understand, disseminate or simulate adsorption in porous materials. Go ahead and
submit a PR if you found something interesting!

## Table of Contents

- [Adsorption Awesome ![Awesome](https://github.com/sindresorhus/awesome)](#adsorption-awesome-)
  - [Table of Contents](#table-of-contents)
  - [Adsorption data standardization](#adsorption-data-standardization)
  - [Databases of adsorption data](#databases-of-adsorption-data)
  - [Adsorption data treatment and material characterization](#adsorption-data-treatment-and-material-characterization)
  - [Multicomponent adsorption](#multicomponent-adsorption)
  - [Adsorption simulation](#adsorption-simulation)
  - [Interfaces with adsorption devices](#interfaces-with-adsorption-devices)

## Adsorption data standardization

- [Adsorption Information Format](https://adsorptioninformationformat.com/): A
  universal file format for gas adsorption experiments, similar to a
  crystallographic CIF file.

## Databases of adsorption data

- [NIST ISODB](https://adsorption.nist.gov): A centralized database of pure and
  multicomponent adsorption isotherms from experimental published data.
- [Bison 20](https://pubs.acs.org/doi/10.1021/acs.iecr.0c05398?goto=supporting-info):
  A collection of multicomponent adsorption isotherms. Some has been integrated
  in the [NIST ISODB](https://adsorption.nist.gov).

## Adsorption data treatment and material characterization

- [pyGAPS](https://pygaps.readthedocs.io/): General purpose adsorption data
  treatment, characterization and isotherm fitting, including specific surface
  area, pore size distributions, isosteric enthalpy, isotherm model fitting and
  more.
- [pyGAPS-gui](https://github.com/pauliacomi/pyGAPS-gui): Python-based graphical
  user interface to [pyGAPS](https://pygaps.readthedocs.io/).
- [BETSI-gui](https://github.com/fairen-group/betsi-gui): BET Surface
  Identification, a program that fully implements the Rouquerol criteria.
- [BEaTmap](https://github.com/PMEAL/beatmap): BET surface area analysis from
  adsorption data, including a Web App.
- [pyPUC](https://github.com/sblanky/pyPUC): pyPUC (Python Porosity Uptake
  Correlator) calculates the optimum pore size range of some type of material
  for gas uptake at pressures in a range.
- [Micromeritics](https://github.com/Micromeritics/micromeritics) software
  adsorption calculations and other support tools.

## Multicomponent adsorption

- [pyIAST](https://github.com/CorySimon/pyIAST): pyIAST predicts mixed-gas
  adsorption isotherms in a nanoporous material from pure-component gas
  adsorption isotherms using Ideal Adsorbed Solution Theory (IAST).
- [pyGAPS](https://pygaps.readthedocs.io/) and
  [pyGAPS-gui](https://github.com/pauliacomi/pyGAPS-gui): integrates
  functionality of [pyIAST](https://github.com/CorySimon/pyIAST) and other IAST
  functions.
- [IASTpp](https://github.com/Sangwon91/IASTpp): Graphical software written in
  C++ for Ideal Adsorbed Solution Theory Calculations.
- [MPTA](https://github.com/RaphaelGervaisLavoie/MPTA): Numerical implementation
  of the Multicomponent Potential Theory of Adsorption in Python
- [MCIAST](https://github.com/eliasboegel/MCIAST): A numerical code on
  breakthrough curve modelling for multicomponent gas mixtures based on Ideal
  Adsorption Theory

## Adsorption simulation

- [RASPA](https://github.com/iRASPA/RASPA2): Classical molecular simulation
  code, particularly geared towards simulating adsorption and diffusion in
  nanoporous materials.
- [PorousMaterials.jl](https://github.com/SimonEnsemble/PorousMaterials.jl) A
  pure-Julia package for classical molecular modeling of adsorption in porous
  crystals.

## Interfaces with adsorption devices

- [NuMAT 3flex driver](https://github.com/numat/threeflex): a python package for
  interfacing with the Micromeritics 3Flex
