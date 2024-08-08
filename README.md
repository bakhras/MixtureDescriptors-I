# MixtureMetrics : Mixture Descriptors Calculator



This Python project calculates an additive scheme for mixture descriptors of multi-component materials. The algorithm processes input from two .csv files and computes various mixture descriptors.

Overview
The project is designed to compute 12 different mixture descriptors based on 12 distinct metrics. The results are saved as 12 separates .csv files, each corresponding to one of the metrics.

Getting Started
Prerequisites
Ensure you have Python 3.x installed. You will also need pip to install the package.

Installation
1.	Download the Package:

•	Clone the repository or download the ZIP file from GitHub.
•	Extract the contents of the ZIP file.
2.	Install the Package:

•	Open a command-line interface (CLI).
•	Navigate to the directory containing the extracted package files.
•	Run the following command to install the package:
pip install .

Usage
After installing the package, you can use it in your Python code. Here’s a basic example of how to use the main function:

from MixtureMetrics import mixture_descriptors_to_csv

# Define file paths
descriptors_file_path = 'path/to/descriptors.csv'
mole_fraction_file_path = 'path/to/mole_fraction.csv'
output_directory = 'path/to/output_directory'

# Call the function
mixture_descriptors_to_csv(descriptors_file_path, mole_fraction_file_path, output_directory)


Arguments
descriptors_file_path: Path to the .csv file containing individual descriptors for each component.
mole_fraction_file_path: Path to the .csv file containing mole fraction values for each component in each mixture.
output_directory: Directory where the 12 output .csv files will be saved.
Output
The code computes and saves 12 different mixture descriptors, each in its own .csv file within the specified output directory.

Contributing
Contributions are welcome! Please open an issue or submit a pull request if you have suggestions or improvements.
   
License
This project is licensed under the GNU General Public License - see the LICENSE file for details.


