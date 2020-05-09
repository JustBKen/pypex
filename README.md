# pypex
Python for Physics Experiments, idea based on [adouge/octapex](https://github.com/adouge/octapex "octapex")

## todo
* Define purpose, desired functionality/documentation

**It seems, no extra code is necessary** - all the applications one would need in physics lab courses are already there.
However, it takes time to find - so a short (10 pages?) guide on which packages to use, how to use them, and where to look for further info, would be much more beneficial.

One could even keep the  name of the repo, and adapt it to a short pdf brochure.



* ~Port existing octapex code to Python~ nothing to port.
* ~Data read Function
 Read csv,tsv or spreadsheet into usable data~ pandas
* ~Linear Algebra
LU Decomp for solving Linear equations~ already exists; wrapper?
* $\chi^2$-test, $\frac{\chi^2}{dof}$-test + learn theory
* ~Fit-Function with custom function~ exists (scipy). Wrapper?
* pdf manual + tips for what to use for what
* error calculation methods - ~see old octapex code~ potential replacement found - Python package **uncertainties**.