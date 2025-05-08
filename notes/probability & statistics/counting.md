# Counting & Sets

#### Probability Theorem:
Probability of a desirable outcome given $k$ desirable outcomes and $n$ total possible outcomes, where each outcome is equally probable, is $k/n$.

## Counting:
#### Inclusion-Exclusion principle:
```math
|{A}\cup{B}|=|{A}|+|{B}|-|{A}\cap{B}|
```
#### Rule of product / multiplication rule:
If there are m ways to perform action 1 and n ways to perform action 2 then there are ${m}\cdot{n}$ ways to perform action 1 followed by action 2.

### Permutations:
**Ordering** of elements. It is a **list** of $k$ distinct elements from a set of size $n$.
```math
_{n}P_{k}=\frac{n!}{(n-k)!}
```
permutations of a multiset:
```math
\frac{n!}{n_1!n_2!...}
```
### Combinations:
Ordering does not matter. It is a subset of $k$ distinct elements from a set of size $n$.
```math
_{n}C_{k}=\binom{n}{k}=\frac{n!}{k!(n-k)!}=\frac{_{n}P_{k}}{k!}
```
#### Permutations vs Combinations
```math
\begin{aligned}
\text{Permutations:} & \quad abc, acb, bac, bca, cab, cba \quad \\
                     & \quad abd, adb, bad, bda, dab, dba \quad \\
                     & \quad acd, adc, cad, cda, dac, dca \quad \\
                     & \quad bcd, bdc, cbd, cdb, dbc, dcb \quad \\
\end{aligned}
```
```math
\begin{aligned}
\text{Combinations:} & \quad \{a, b, c\} \\
                     & \quad \{a, b, d\} \\
                     & \quad \{a, c, d\} \\
                     & \quad \{b, c, d\} \\
\end{aligned}
```
