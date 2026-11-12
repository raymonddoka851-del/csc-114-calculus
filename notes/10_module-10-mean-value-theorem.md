# 10 · Module 10 — Mean Value Theorem for Integrals

> Source: Calculus Module 11. The theorem connects accumulated area with the average height of a continuous function.

![Source illustration from Calculus Module 10](../assets/figures/module-10-image1.png)

## The theorem and average value

If f is continuous on [a, b], there is at least one c in [a, b] such that:

∫ₐᵇ f(x) dx = f(c)(b − a).

The average value is therefore:

f_avg = (1/(b − a)) ∫ₐᵇ f(x) dx.

To find c, first calculate f_avg, then solve f(c) = f_avg and retain solutions in [a, b]. There may be more than one such c.

## Worked example

Find the average value of f(x) = 3x² − 2x on [1, 4], then find c.

f_avg = (1/3)∫₁⁴(3x² − 2x)dx = (1/3)[x³ − x²]₁⁴ = 48/3 = 16.

Set 3c² − 2c = 16. Then 3c² − 2c − 16 = 0 = (3c − 8)(c + 2), giving c = 8/3 or −2. Only c = 8/3 lies in [1, 4].

## Piecewise functions

For a piecewise rate or speed, integrate separately on each segment and add the results. Divide by the total interval length to obtain the average value.

## Common errors

- Divide by interval width b − a, not by the function’s endpoint values.
- Apply the theorem only when f is continuous on the closed interval.
- A solution to f(c) = f_avg outside [a, b] is not the required c.
- Average value is not generally f((a + b)/2).

## Active recall

1. Find the average value of f(x) = 2x on [0, 3].
2. State the continuity condition for the integral mean value theorem.
3. If f(c) = f_avg has two solutions, what do you do?

**Check:** (1/3)∫₀³2x dx = 3; f must be continuous on [0, 3]; keep every solution in the interval.
