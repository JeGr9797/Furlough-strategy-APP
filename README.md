# Furlough strategy in aggregate production planning with uncertainty in labour capacity
This repository contains the instances, as well as the codes of the mathematical formulation used for the article "A furlough-based framework for aggregate production planning with stochastic labor production capacity".

In order to solve the matemathical model, it is necesary to have a Gurobi license (https://www.gurobi.com/academia/academic-program-and-licenses/), gurobipy (https://pypi.org/project/gurobipy/), matplotlib (https://matplotlib.org/stable/) and numpy (https://numpy.org/).

## Install the library gurobipy

```
   python -m pip install gurobipy
```
## Install the library matplotlib

```
   python -m pip install -U matplotlib
``` 
## Install the library numpy

```
   pip install numpy
```

## The codes provided has the following characteristics:
  - Both scripts are in jupyter notebook.
  - The instances were originally run using Gurobi 11.
  - The first script runs the sample average approximation with 10 replicates and for each replicate generates KPIs.
  - The second script is utlized in order to generate visualization of the results, KPIs, etc.
