# MARCF
Codes and data for article: A Hybrid Framework Combining Autoregression and Common Factors for Matrix Time Series Modeling


## Introduction

This repository provides the implementation of all algorithms, simulation experiments, real data analysis, data, and outputs in our paper ***A Hybrid Framework Combining Autoregression and Common Factors for Matrix Time Series Modeling***. 



## Repository Structure

.<br>
├── Simulation/<br>
│&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;├──simulation.Rmd&nbsp;&nbsp;&nbsp;&nbsp;# implementation of  Simulations 1 and 2<br>
│&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;└── simulation1&nbsp;&nbsp;&nbsp;&nbsp;# results and figures of Simulation 1<br>
│&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;└── simulation2&nbsp;&nbsp;&nbsp;&nbsp;# results and figures of Simulation 2<br>
├── RealData/&nbsp;&nbsp;&nbsp;&nbsp;# real data, code for data analysis, and figures<br>
├── functions.Rmd&nbsp;&nbsp;&nbsp;&nbsp;# implementation of algorithms and other methods<br>
├── README.md&nbsp;&nbsp;&nbsp;&nbsp;# this file



- **functions.Rmd:** provides the implementation of our gradient descent algorithm, initialization, rank selection and common dimension selection. The codes for data generalization and functions for simulations are also provided.



## Dependencies

This project was developed and tested using R version **4.4.2** .

#### Required R Packages 

| Package  | Version |
| -------- | ------- |
| purrr    | 1.0.2   |
| dplyr    | 1.1.4   |
| tidyr    | 1.3.1   |
| pheatmap | 1.0.12  |
| Matrix   | 1.7-1   |
| reshape2 | 1.4.4   |
| ggplot2  | 3.5.2   |
| MASS     | 7.3-61  |
| tensorTS | 1.0.2   |
