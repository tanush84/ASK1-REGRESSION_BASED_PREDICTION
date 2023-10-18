END to END ML model for the Regression Based IC50 Values prediction of ASK-1 inhibitors using python script. 

*****

After installing the requirements in an Virtual Environment
or creating a new environment using conda by using "environment_dependencies.yml" file
just open the command prompt or Terminal in the above created virtual environment
run the command given below
### Using KNN regression Algorithm based prediction
python KNN_regression-ASK1.py test.smi

similarly, for any unknown molecule when just use the command by specifying the path
of "*.smi" file.

python KNN_regression-ASK1.py [specify_path]*.smi


The result will be displayed in the terminal as pIC50 value and IC50 value of the Molecule.


###
While testing the script using given test.smi, it will generate below output.

###  pIC50 value for the molecule is  4.970651456824053
###  IC50 value for the molecule is  10699.131939336623 nM

###The image contained in package displays the scatter plot of the ASK1 KNN model built using RDKIT descriptor data.
###KNN model has R-squared value of 0.7029379284599793
