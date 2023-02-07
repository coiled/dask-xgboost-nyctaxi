XGBoost + Dask + HPO with Optuna
================================

This repository contains a sequence of notebooks that progressively train a
large model on tabular data using ...

-   [XGBoost](https://xgboost.readthedocs.io/en/stable/) for gradient boosted trees
-   [Dask](https://dask.org) for parallel computing
-   [Optuna](https://optuna.org/) for hyper-parameter-optimization

We find that this combination is pragmatic in large scale machine
learning problems.

Notebooks
---------

The notebooks in this repository are progressively more sophisticated.  We
start with just looking at the data, and then we train with XGBoost and Dask,
then we train with XGBoost and Dask and Optuna, then we train many models in
parallel with XGBoost and Dask and Optuna.  This progression can help to make
it clear what each tool does, and how best to combine them.

We hope that these notebooks serve as a prototype for others to adapt to their
needs.
