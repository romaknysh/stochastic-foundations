# Lab 11 — Chi-Square Goodness-of-Fit: Uniform Distribution

## Problem
Test whether 30 die rolls follow a uniform distribution
across 6 faces using the Chi-square test.

## Parameters
| Parameter          | Value |
|--------------------|-------|
| n_rolls            | 30    |
| n_faces            | 6     |
| significance_level | 0.05  |
| p(each face)       | 1/6 ≈ 0.167 |

## Formula
χ² = Σ (nj - npj)² / npj

## Result
| Statistic          | Value       |
|--------------------|-------------|
| χ² statistic       | 28.8        |
| degrees of freedom | 5           |
| p-value            | 2.54e-05    |
| decision           | H rejected — die is not fair |
