# BIOMD0000000080: Model_1

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000080.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000080.git@20140916`


# Model Notes


This model reproduces figure 5 and figure 4(B)of the paper, with Kinh
represented by [G-GTP]. We arbitrarily chosed to set the initial concentration
of D to 31 micorMolar based on legend of figure 4. [R] was not given anywhere
in the paper and was chosen to calibrate the sigmoid response to an increased
[GTP]. THe figure 5 in the model was successfully simulated on COPASI 4.0 ,the
figure 4(B) was sucessfully simulated on both COPASI and SBML_odeSolver.

There are two curves for Kinh in the absence and presence of NaCl in the
figure obtained from simulations of the model using parameters of set C and
set D.Here in the model the initial value given is from set D.The parameters
in set C :k7=0.5, k10=1.0,k5=0.1,the others are the same with set D.


