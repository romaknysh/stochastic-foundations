# Lab 06 — Network Reliability

## Problem
Calculate the reliability of a complex network with 11 nodes
connected in series and parallel combinations.

## Setup
All individual node reliability: 0.9

## Network Structure
| Subsystem | Nodes       | Type     |
|-----------|-------------|----------|
| p1        | leaf node   | series   |
| p2        | leaf node   | parallel |
| p3–p4     | subgroup    | parallel |
| p5–p6     | subgroup    | series   |
| p7–p8     | subgroup    | parallel |
| p9–p11    | final chain | series   |

## Intermediate Results
| Node | Reliability |
|------|-------------|
| p1   | 0.19        |
| p2   | 0.171       |
| p3   | 0.19        |
| p4   | 0.1539      |
| p5   | 0.9737      |
| p6   | 0.729       |
| p7   | 0.81        |
| p8   | 0.271       |
| p9   | 0.2439      |
| p10  | 0.8222      |
| p11  | **0.8006**  |

## Result
system_reliability ≈ 0.8006
