# Adsorption Awesome [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

Awesome list of open source / freely available tools that help simulate, 
treat, understand or disseminate adsorption in porous materials.
Go ahead and submit a PR if you found something interesting!

## Table of Contents
1. [Adsorption data standardization](#Adsorption-data-standardization)
1. [Databases and storage](#Databases-and-storage)
1. [Adsorption simulation](#Adsorption-simulation)
1. [Adsorption data treatment and material characterization](#Adsorption-data-treatment-and-material-characterization)
1. [Multicomponent adsorption](#Multicomponent-adsorption)

## Adsorption data standardization

* [Adsorption Information Format](https://adsorptioninformationformat.com/): A universal file format for gas adsorption experiments, similar to the crystallography CIF file.

## Databases of adsorption data

* [NIST ISODB](https://adsorption.nist.gov): A centralized database of pure and multicomponent adsorption isotherms from experimental published data.
* [Bison 20](https://pubs.acs.org/doi/10.1021/acs.iecr.0c05398?goto=supporting-info): A collection of multicomponent adsorption isotherms. Some has been integrated in the NIST adsorption database.

## Adsorption molecular simulation

* [RASPA](https://github.com/iRASPA/RASPA2): Classical molecular simulation code, particularly geared towards simulating adsorption and diffusion in nanoporous materials.

## Adsorption data treatment and material characterization

* [pyGAPS](https://pygaps.readthedocs.io/): General purpose adsorption data treatment, characterization and isotherm fitting, including specific surface area, pore size distributions, isosteric enthalpy, isotherm model fitting and more. 
* [pyGAPS-gui](https://github.com/pauliacomi/pyGAPS-gui): Python-based graphical user interface to [pyGAPS](https://pygaps.readthedocs.io/).
* [BETSI-gui](https://github.com/fairen-group/betsi-gui): BET Surface Identification, a program that fully implements the rouquerol criteria
* [BEaTmap](https://github.com/PMEAL/beatmap): BET surface area analysis from adsorption data, including a Web App
* [pyPUC](https://github.com/sblanky/pyPUC): pyPUC (Python Porosity Uptake Correlator) calculates the optimum pore size range of some type of material for gas uptake at pressures in a range.

## Multicomponent adsorption 

* [pyIAST](https://github.com/CorySimon/pyIAST): pyIAST predicts mixted-gas adsorption isotherms in a nanoporous material from pure-component gas adsorption isotherms using Ideal Adsorbed Solution Theory (IAST).
* [pyGAPS](https://pygaps.readthedocs.io/) and [pyGAPS-gui](https://github.com/pauliacomi/pyGAPS-gui): integrates functionality of [pyIAST](https://github.com/CorySimon/pyIAST) was integrated.
* [MPTA](https://github.com/RaphaelGervaisLavoie/MPTA): Numerical implementation of the Multicomponent Potential Theory of Adsorption in Python
* [MCIAST](https://github.com/eliasboegel/MCIAST): A numerical code on breakthrough curve modelling for multicomponent gas mixtures based on Ideal Adsorption Theory

