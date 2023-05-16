# The code is broken into two parts: Data.ipynb and Algorithm.ipynb

###################################################################

Directories:

report/             report (report.pdf)
script/             espn.R
data/               data
Data.ipynb          okay to run this on laptop
Algorithm.ipynb     run this on Colab
README.md

###################################################################

Data.ipynb --

simply set GLOBAL = PRESET ... to choose the way the tabular data
should be generated, and run the script to generate the file, e.g.

    ./tabular-100-100-original.csv for example

Algorithm.ipynb --

Look for "Specification", and change the following according, and
then run.

TABULAR_CSV = './tabular-100-100-original.csv'
GLOBAL_PCA = False

###################################################################
