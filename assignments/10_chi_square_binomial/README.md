# Assignment 10 — Chi-Square Goodness-of-Fit: Binomial

## Problem
Test whether simulated data follows a Binomial(n=10, p=0.6) distribution
using the Chi-square goodness-of-fit test.

## Parameters
| Parameter          | Value |
|--------------------|-------|
| sample_size (n)    | 30    |
| p(A)               | 0.60  |
| significance level | 0.05  |

## Formula
χ² = Σ (nj - npj)² / npj

## Result
| Statistic       | Value  |
|-----------------|--------|
| χ² statistic    | 50.68  |
| degrees of freedom | 10  |
| critical value  | 18.31  |
| decision        | H rejected — data does not fit Binomial(10, 0.6) |
