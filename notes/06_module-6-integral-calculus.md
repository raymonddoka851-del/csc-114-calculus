# 06 · Module 6 — Integral Calculus

![Source illustration from Calculus Module 6](../assets/figures/module-6-image1.png)

> Source: Calculus Module 7. Integration reverses differentiation; a definite integral accumulates signed change over an interval.

## Indefinite integrals

An antiderivative F of f satisfies F′(x) = f(x). All antiderivatives differ by a constant:

∫ f(x) dx = F(x) + C.

Core rules:

- ∫ k dx = kx + C
- ∫ xⁿ dx = xⁿ⁺¹/(n + 1) + C, for n ≠ −1
- ∫ 1/x dx = ln|x| + C
- ∫ eˣ dx = eˣ + C; ∫ eᵏˣ dx = eᵏˣ/k + C (k ≠ 0)
- Integrals distribute over sums and constant factors.

## Worked example: reverse the power rule

∫(6x² − 4x + 3) dx = 2x³ − 2x² + 3x + C.

Differentiate the answer to check: 6x² − 4x + 3.

## Definite integrals

If F′ = f, the Fundamental Theorem gives:

∫ₐᵇ f(x) dx = F(b) − F(a) = [F(x)]ₐᵇ.

The integration constant cancels, so do not add + C to a definite-integral answer.

**Worked example:** ∫₁³ 2x dx = [x²]₁³ = 9 − 1 = 8.

## Interpretation

A definite integral is signed accumulation: area above the axis contributes positively; area below contributes negatively. Units are “output units × input units.”

## Common errors

- For powers, divide by the new exponent n + 1; the formula excludes n = −1.
- Keep + C for indefinite integrals.
- Evaluate upper limit minus lower limit, not the reverse.
- ∫ₐᵇ f can be negative, even though geometric area is nonnegative.

## Active recall

1. Find ∫(4x³ + 2/x) dx.
2. Evaluate ∫₀² (3x² + 1) dx.
3. Why is there no + C in a definite integral?

**Check:** x⁴ + 2 ln|x| + C; [x³ + x]₀² = 10; the constants cancel when F(b) − F(a) is formed.
