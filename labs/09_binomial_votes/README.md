# Lab 09 — Binomial Distribution: Voting Simulation

## Problem
Model an election where each voter independently votes for A with p=0.6.
Compute the Binomial PDF for n=10 and n=100 voters.

## Parameters
| Parameter | Value |
|-----------|-------|
| p(A)      | 0.60  |
| p(B)      | 0.40  |

## Sheets
| Sheet         | Description                        |
|---------------|------------------------------------|
| n_10          | PDF for 10 voters + custom p=0.7   |
| n_100_custom  | PDF for 100 voters                 |

## Formula
P(X=k) = C(n,k) * p^k * (1-p)^(n-k)

## Result
For n=10: P(A wins majority) = P(X≥6) ≈ 0.666
Distribution shifts right and narrows as n increases
