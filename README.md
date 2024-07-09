Calculating the absorbance, transmittance and reflectance of each layer of a material stack of arbitrary numbers and layers taking into account their optical constants.

This code models analytically an material of arbitrary materials and thicknesses using the transfer matrix method described in 
Centurioni, E. "Generalized Matrix Method for Calculation of Internal Light Energy Flux in Mixed Coherent and Incoherent Multilayers."
Appl. Opt. 2005, 44 (35), 7532. https://doi.org/10.1364/AO.44.007532.

The model is developed in Matlab and should be self-contained meaning that it should contain in itself all the information to understand this modelling.
An outline with the most important capability can be found in "CalcOfOpticalPowerDensity".

The name of the file containing the code "CalcOfOpticalPowerDensity" should be updated using Git (GitHub) versioning system.

The optical constants are sources for material parameters and are included in various txt files whose name denote the material. The columns are from left to right: wavelength (either in μm or nm), n, and k.

Credits: S. A. Svatek (initial development) C. Bueno-Blanco, E. Antolín

Instituto de Energía Solar Universidad Politécnica de Madrid Spain
