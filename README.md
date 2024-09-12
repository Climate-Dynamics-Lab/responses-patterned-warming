# responses-patterned-warming
Analysis code for "Circulation and Cloud Responses to Patterned SST Warming"

Mackie, Byrne, Van de Koot & Williams

Submitted to Geophysical Research Letters, 2024.

The analysis code consists of three notebooks:

1. "calc_entrain_adjust.ipynb" calculates the entrainment adjustment for the instability index, using the zero-buoyancy plume model of Singh & O'Gorman (2013), as detailed in Section 3.2 and Text S1. These are saved and used in the other scripts.
2. "MSE_ascent_frac_framework.iypnb" demonstrates the instability index, motivates the requirement of a dry-air entrainment adjustment in the control simulation to it and shows the improvement when it is included. Also demonstrates that this entrainment-adjusted instability index is able to recreate the changes in (vertical velocity) ascent fraction due to the patterend warming.
3. "joint_histograms.ipynb" produces the joint histograms for the instability space analysis. Also plots the locations of different regimes as defined in the text and changes to mean cloud profiles for these different regions.

Scripts #2 and #3 produce the plots for the script.
