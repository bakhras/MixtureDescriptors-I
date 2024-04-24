# MixtureMetrics
This project calculates additive scheme for mixture descriptors for multi-component materials. The algorithm takes input from two .csv files, first one containing individual descriptors of each component and the second one containing the mole fraction values of each component of each mixtures.
The main function "mixture_descriptors_to_csv" gets three arguments 1- descriptors file path 2- mole fraction file path and 3- output directory (to store the 12 .csv output files)
This code computes 12 different mixture descriptors based on 12 different metrics and returns 12 .csv files for each one. 
Download the code and extract it, change the directory to that, and then install the package using "pip install . " and then use "from  MixtureMetrics import mixture_descriptors_to_csv" to run the function.

