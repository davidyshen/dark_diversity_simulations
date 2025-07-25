# Dark diversity simulations

This repository contains the notebooks and data used in the simulation study for testing how dark diversity can be modelled and spatially interpolated.

The basis for the experiments relies on the R DarkDiv package published by [Carmona and Pärtel (2020)](https://onlinelibrary.wiley.com/doi/full/10.1111/geb.13203).

Simply, dark diversity can be easily measured at point locations, but it is difficult to then extrapolate and interpolate this information across space. This study aims to test different methods for doing so.

The first notebook `dark_diversity_PoC.ipynb` is the initial exploration of the methods, simulating only 3 species over 2 environmnetal variables.

The second notebook `dark_diversity_methods_testing.ipynb` is an extension of the first, building on the learnings and identified limitations of the first notebook. This notebook simulates 25 species over 5 environmental variables, and 3 different driver variables of dark diversity.

The third notebook `assumed_absence.ipynb` is a test of a new method for estimating dark diversity. This method has proved to be by far the most accurate than previous methods, and is able to reproduce the spatial patterns of pre-defined dark diversity patterns.
