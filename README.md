# Graphical model estimation
Implmentation of Node-wise Lasso and Graphical Lasso models in R.

## Aim
The graphical model is used to depict the conditional dependence structure among a set of random variables, represented by the nodes. The edges connected the nodes describe the conditional dependence (covariance) structure of the random variables. The set of such edges is defined as the edge set.

The aim is to implement a Node-wise Lasso approach and a Graphical Lasso approach for a simulated dataset with the aforementioned structure.

## Specification
Implement the node-wise lasso and graphical lasso approaches in R:
1. Conduct simulations to compare the sample performance of different approaches in recovering the edge set
2. Produce ROC curves to compare the overall performance on recovering the true edge set
3. Develop methods to select optimal tuning parameters of each method, and compare the sample performance in terms of support recovery

## Remarks
This group project is submitted as part of assessed coursework.

## Files
- `graphical_lasso.Rmd` contains all R code and elementary analysis.
- `report.pdf` is the written report summarising the findings.
