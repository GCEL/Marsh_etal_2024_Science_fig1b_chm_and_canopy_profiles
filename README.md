# Marsh_etal_2024_Science_fig1b_chm_and_canopy_profiles
Code to reproduce figure 1b from Marsh et al., 2024, Science: "Logging alters tropical forest structure, while conversion reduces biodiversity and functioning"

The repository contains the following:
- lidar_canopy_profiles_adaptive_for_synthesis.npz -> data file with the canopy profiles from the forest plots
- lidar_canopy_profiles_adaptive_OP_for_synthesis.npz -> data file with the canopy profiles for oil palm plantation
- CHM_50cm_Belian.npy -> data file with canopy height model for old growth plot 
- CHM_50cm_BNorth.npy -> data file with canopy height model for heavily logged plot
- CHM_50cm_E.npy -> data file with canopy height model for moderately logged plot
- CHM_50cm_OP.npy -> data file with canopy height model for oil palm
- canopy_structure_across_gradient.png -> example figure
- GPS_points_file.csv -> plot coordinates
- least_squares_fitting.py -> python script with some auxilliary functions used
- synthesis_figure.py -> python script to produce the figure

Note that to run the script requires python v3 with the following packages:
- numpy
- matplotlib
- scipy
- seaborn
