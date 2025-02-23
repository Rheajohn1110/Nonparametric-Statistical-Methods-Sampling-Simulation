# Nonparametric-Statistical-Methods-Sampling-Simulation
This project applies nonparametric statistical methods, including the Wilcoxon Rank-Sum Test, Kruskal-Wallis Test, bootstrapping, and Monte Carlo simulations, to analyze data without normality assumptions. Using R, it explores sampling techniques, improves parameter estimation, and validates statistical models, ensuring robust data analysis.

# Objectives

Explore nonparametric statistical tests for analyzing datasets without assuming a specific distribution.
Implement sampling and resampling techniques to evaluate statistical significance.
Conduct Monte Carlo simulations to validate statistical models.
Compare parametric and nonparametric approaches to understand their advantages and limitations.

#Statistical Methods Applied

## Nonparametric Hypothesis Testing

**Wilcoxon Rank-Sum Test:** Nonparametric alternative to the t-test, used to compare two independent groups.
**Kruskal-Wallis Test:** Nonparametric equivalent of ANOVA for comparing multiple groups.
**Sign Test:** Determines median differences without assuming normality.

## Sampling & Resampling
Bootstrapping: Repeated random sampling with replacement to improve parameter estimation.
Permutation Tests: Used to test hypotheses by shuffling observed data and analyzing differences.

## Monte Carlo Simulations
Simulated multiple random samples to estimate population parameters.
Evaluated uncertainty in statistical models using iterative sampling techniques.

# Programming Language:

Implemented all analyses in R, leveraging statistical and visualization libraries.

## Key Libraries Used:

library(ggplot2)   -    Data visualization  
library(dplyr)      -   Data manipulation  
library(tidyverse)  -   Data science toolkit  
library(boot)       -   Bootstrapping methods  
library(MASS)       -   Advanced statistical functions  

# Key Findings

## Effectiveness of Nonparametric Tests:
Wilcoxon rank-sum and Kruskal-Wallis tests provided robust results for skewed data.
These tests effectively analyzed datasets with heterogeneous variance where parametric tests fail.

## Bootstrapping & Resampling:
Improved parameter estimation accuracy in small sample datasets.
Showed that increasing bootstrap iterations reduces standard error and enhances confidence intervals.

## Monte Carlo Simulations:
Provided a reliable method for estimating distributions through iterative random sampling.
Helped in assessing model stability under different conditions.
