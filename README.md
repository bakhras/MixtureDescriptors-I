# MixtureMetrics
This project calculates additive scheme for mixture descriptors for multi-component materials. The algorithm processes input from two .csv files. The first file includes individual descriptors for each component, while the second file contains mole fraction values for each component in each mixture.
The main function "mixture_descriptors_to_csv" gets three arguments 1- descriptors file path 2- mole fraction file path and 3- output directory (to store the 12 .csv output files)
This code computes 12 different mixture descriptors based on 12 different metrics and returns 12 .csv files for each one. 
To install the package, begin by downloading the ZIP file from the GitHub repository and extracting its contents. Then, navigate to the extracted directory using the command line interface. Once in the directory containing the package files, install it using "pip install .". After successful installation, you can import and utilize the package's functions in your Python code using " from MixtureMetrics import mixture_descriptors_to_csv” 

