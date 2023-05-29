# Adsorption Awesome [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

Awesome list of open source / freely available tools that help treat,
understand, disseminate or simulate adsorption and adsorption-based processes in
porous materials.

What it does NOT contain:

- Proprietary / closed source programs or datasets
- Databases of structures of adsorbent materials
- General atomistic simulation software and related tools
- Stuff that you know and use but have not yet added here!

Go ahead and submit a PR if you found something interesting!

**Disclaimer**: I am the main maintainer of the pyGAPS package.

## Table of Contents

- [Free resources for learning about adsorption](#free-resources-for-learning-about-adsorption)
- [Adsorption data standardization](#adsorption-data-standardization)
- [Databases of adsorption data](#databases-of-adsorption-data)
- [Adsorption data treatment and material characterization](#adsorption-data-treatment-and-material-characterization)
- [Multicomponent adsorption](#multicomponent-adsorption)
- [Process design](#process-design)
- [Adsorption-specific molecular simulation](#adsorption-specific-molecular-simulation)
- [Interfaces with adsorption devices](#interfaces-with-adsorption-devices)

## Free resources for learning about adsorption

- [Interactive Module](https://learncheme.com/quiz-yourself/interactive-self-study-modules/adsorption/adsorption-introduction/) 
  from University of Colorado Boulder: excellent resource containing videos of
  annotated lecture slides, simple equilibrium simulations and multiple choice questions.

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
- [pyGAPS-gui](https://github.com/pauliacomi/pyGAPS-gui): Graphical user
  interface for [pyGAPS](https://pygaps.readthedocs.io/), offering interactive
  simple-to-use access to all its functionality.
- [BETSI-gui](https://github.com/fairen-group/betsi-gui): BET Surface
  Identification, an interactive graphical program for determining BET
  area using a statistical multiple region fit approach in combination with
  the Rouquerol criteria.
- [BEaTmap](https://github.com/PMEAL/beatmap): BET surface area analysis from
  adsorption data implementing the Rouquerol criteria and offering useful
  visualisations. An interactive Web App version exists allowing for easy use.
- [SESAMI](https://pubs.acs.org/doi/10.1021/acs.jpcc.9b02116), a script
  to estimate surface areas of porous materials using either/both the BET and
  excess sorption work model and later extended with machine learned (ML) estimations of monolayers as
  [SESAMI ML](https://pubs.acs.org/doi/10.1021/acs.jpclett.0c01518).
  One may find the interfaces from the Kulik group useful for the
  [web](https://github.com/hjkgrp/SESAMI_web) and for a
  [GUI](https://github.com/hjkgrp/SESAMI_GUI).
- [Micromeritics](https://github.com/Micromeritics/micromeritics)-provided
  various adsorption calculations and other support tools for their instruments.
- [pyPUC](https://github.com/sblanky/pyPUC): pyPUC (Python Porosity Uptake
  Correlator) determines the optimum pore size range of some type of material
  for gas uptake in a pressure range. The calculation uses experimental data
  and a brute force first principles calculation.

## Multicomponent adsorption

- [pyIAST](https://github.com/CorySimon/pyIAST): predicts mixed-gas adsorption
  isotherms in a nanoporous material from pure-component gas adsorption
  isotherms using the Ideal Adsorbed Solution Theory (IAST).
- [pyGAPS](https://pygaps.readthedocs.io/) and
  [pyGAPS-gui](https://github.com/pauliacomi/pyGAPS-gui): integrate
  functionality of [pyIAST](https://github.com/CorySimon/pyIAST) and alongside
  providing other IAST functions, like selectivity vs. pressure and bulk to
  adsorbed fractional composition graphs.
- [IASTpp](https://github.com/Sangwon91/IASTpp): graphical software written in
  C++ for Ideal Adsorbed Solution Theory Calculations.
- [MPTA](https://github.com/RaphaelGervaisLavoie/MPTA): Numerical implementation
  of the Multicomponent Potential Theory of Adsorption in Python
- [MCIAST](https://github.com/eliasboegel/MCIAST): A numerical code on
  breakthrough curve modelling for multicomponent gas mixtures based on Ideal
  Adsorption Theory.
- [GraphIAST](https://github.com/ORC-WUR/GraphIAST): Graphical User Interface 
  Software for the pyIAST Ideal Adsorption Solution Theory code.
- [RUPTURA](https://github.com/iRASPA/RUPTURA): Command-line simulation package to 
  fit pure component isotherms, then compute breakthrough curves and IAST mixture 
  predictions.

## Process design

- [CADET](https://github.com/modsim/CADET): A modular, fast, and accurate
  simulation framework for (column) liquid chromatography breakthrough curves.
- [MAPLE](https://github.com/ArvindRajendran/MAPLE) (Machine-assisted Adsorption
  Process Learner and Emulator) and
  [PANACHE](https://github.com/ArvindRajendran/PANACHE) (Physics-based
  artificial neural network framework for adsorption and chromatography
  emulation), two neural network based codes that assist in simulating
  adsorption processes with and without requiring isotherm parameters.

## Adsorption-specific molecular simulation

- [RASPA](https://github.com/iRASPA/RASPA2): Classical molecular simulation
  code, particularly geared towards simulating adsorption and diffusion in
  nanoporous materials.
- [PorousMaterials.jl](https://github.com/SimonEnsemble/PorousMaterials.jl) A
  pure-Julia package for classical molecular modeling of adsorption in porous
  crystals.

## Interfaces with adsorption devices

- [NuMAT 3flex driver](https://github.com/numat/threeflex): a python package for
  interfacing with the Micromeritics 3Flex.
