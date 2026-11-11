# Maths

## Process

1. Intrinsic Value per Share
    - PV of future earnings / Number of Shares
    - It will tell you what the actual value of the share is, then compare it with the current market price
2. Calculate CAGR (Compound Annual Growth Rate)
    - Reverse the Compounding formula
    - (Final Amount / Initial Investment) ^ (1 / Number of years) - 1
    - It will tell you expected returns per year

## Appendix

### Future Value When Average Growth Rate is known

```text
Future Value = Current Value * (Average rate of growth for the next N years) ^ N years
```

Derivation:

- Let current Value = 1.5
- N = 5 years
- Average growth rate for the next 5 years = 6%

(B) Growth rate during the year (in %) = 6%

| Year | Value at the start of the year (A) | Value at the end of the year (A * B / 100) |
|:----:|:----------------------------------:|:------------------------------------------:|
|  1   |                1.5                 |                 1.5 * 1.06                 |
|  2   |             1.5 * 1.06             |            (1.5 * 1.06) * 1.06             |
|  3   |           1.5 * (1.06)^2           |           1.5 * (1.06)^2 * 1.06            | 
|  4   |           1.5 * (1.06)^3           |           1.5 * (1.06)^3 * 1.06            | 
|  5   |           1.5 * (1.06)^4           |           1.5 * (1.06)^4 * 1.06            | 

```text
The final Value at the start of the 6th year = 1.5 * (1.06) ^ 5
                                             = Current Value * (Average Growth Rate for the next N years) ^ N years
```
