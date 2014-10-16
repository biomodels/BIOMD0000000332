# BIOMD0000000332: model01

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000332.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000332.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000332 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This model is from the article:  
** Modelling thrombin generation in human ovarian follicular fluid **   
Bungay Sharene D., Gentry Patricia A., Gentry Rodney D. _Bulletin of
Mathematical Biology_Volume 68, Issue 8, 12 July 2006, Pages 2283-302
[16838084](http://www.ncbi.nlm.nih.gov/pubmed/16838084),  
**Abstract:**   
A mathematical model is constructed to study thrombin production in human
ovarian follicular fluid. The model results show that the amount of thrombin
that can be produced in ovarian follicular fluid is much lower than that in
blood plasma, failing to reach the level required for fibrin formation, and
thereby supporting the hypothesis that in follicular fluid thrombin functions
to initiate cellular activities via intracellular signalling receptors. It is
also concluded that the absence of the amplification pathway to thrombin
production in follicular fluid is a major factor in restricting the amount of
thrombin that can be produced. Titration of the initial concentrations of the
various reactants in the model lead to predictions for the amount of tissue
factor and phospholipid that is required to maintain thrombin production in
the follicle, as well as to the conclusion that tissue factor pathway
inhibitor has little effect on the time that thrombin generation is sustained.
Numerical experiments to determine the effect of factor V, which is at a much
reduced level in follicular fluid compared to plasma, and thrombomodulin,
illustrate the importance for further experimental work to determine values
for several parameters that have yet to be reported in the literature.


