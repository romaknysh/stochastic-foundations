# Lab 01 — Binary Combinations

## Problem
Find all 8-bit binary numbers that contain exactly 3 ones.

## Approach
Enumerate all integers from 1 to 2^8 = 256, convert to binary,
and check if the count of 1-bits equals the target.

## Formula
C(n, k) = n! / (k! * (n-k)!)
where n = bit_count = 8
      k = ones_count = 3

Total valid numbers: C(8, 3) = 56
