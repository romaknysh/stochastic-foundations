# Assignment 07 — Binomial Distribution

## Problem
Model a Bernoulli process with n=9 trials and p=0.4 success probability.
Compute the PDF and simulate outcomes for multiple participants.

## Parameters
| Parameter    | Value |
|--------------|-------|
| n_trials     | 9     |
| p_success    | 0.40  |
| p_failure    | 0.60  |
| sample_size  | 224   |

## Formula
P(K=k) = C(n,k) * p^k * (1-p)^(n-k)

## Result
PDF peaks at k=3 with P(K=3) ≈ 0.281
