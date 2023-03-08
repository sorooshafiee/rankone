# Constrained Optimization of Rank-One Functions with Indicator Variables

This folder contains the source code for the implementation and all the experiments in the paper.

## Dependencies
To use the code, use python3.9 and install Gurobi 9.5 and the following packages in python as follows

```
conda create --name rankone 
conda activate rankone
conda install -c conda-forge julia
conda install -c conda-forge numpy
conda install -c conda-forge pandas
conda install -c conda-forge matplotlib
```
The following Julia packages are required as well

```
> Using Pkg
> Pkg.add.(["JuMP", "MosekTools", "ArgParse", "Distributions",
            "LinearAlgebra", "Combinatorics", "MathOptInterface"])
```

## Reference
S. Shafieezadeh-Abadeh, F. Kılınç-Karzan. [Constrained Optimization of Rank-One Functions with Indicator Variables](https://arxiv.org/pdf/xxx.xxx.pdf). arXiv preprint arXiv:xxxx.xxxxx (2023).
