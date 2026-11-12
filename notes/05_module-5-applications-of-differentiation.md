# 05 · Module 5 — Applications of Differentiation

![Source illustration from Calculus Module 5](../assets/figures/module-5-image1.png)

> Sources: Calculus Modules 5–6. This module covers standard derivative families, curve behaviour, extrema, and Newton–Raphson approximation.

## Standard derivative families

Use the chain rule when the input is not simply x.

- Trigonometric: (sin x)′ = cos x; (cos x)′ = −sin x; (tan x)′ = sec²x
- Also: (cot x)′ = −csc²x; (sec x)′ = sec x tan x; (csc x)′ = −csc x cot x
- Exponential/logarithmic: (eˣ)′ = eˣ; (aˣ)′ = aˣ ln a; (ln x)′ = 1/x for x > 0
- Inverse trig: (arcsin x)′ = 1/√(1 − x²); (arccos x)′ = −1/√(1 − x²); (arctan x)′ = 1/(1 + x²); (arccot x)′ = −1/(1 + x²)
- Also: (arcsec x)′ = 1/(|x|√(x² − 1)); (arccsc x)′ = −1/(|x|√(x² − 1))
- Hyperbolic: (sinh x)′ = cosh x; (cosh x)′ = sinh x; (tanh x)′ = sech²x
- Also: (coth x)′ = −csch²x; (sech x)′ = −sech x tanh x; (csch x)′ = −csch x coth x
- Inverse hyperbolic: (arcsinh x)′ = 1/√(1 + x²); (arccosh x)′ = 1/√(x² − 1); (arctanh x)′ = 1/(1 − x²)
- Variable powers: for x > 0, (xʳ)′ = r xʳ⁻¹ and (xˣ)′ = xˣ(ln x + 1)

For example, d/dx[sin(3x)] = 3 cos(3x); d/dx[eˣ²] = 2x eˣ².

## Stationary points and classification

A stationary point satisfies f′(x) = 0. Find its coordinates by solving f′ = 0 and substituting each x into f. At a stationary point:

- f″(x) > 0: local minimum
- f″(x) < 0: local maximum
- f″(x) = 0: test inconclusive; inspect higher derivatives or the sign of f′ on each side.

**Worked example:** f(x) = x² − 4x + 2. Then f′ = 2x − 4 = 0 gives x = 2; f(2) = −2. Since f″ = 2 > 0, (2, −2) is a minimum.

## Newton–Raphson method

To approximate a root of f(x) = 0, start with a reasonable x₀ and iterate:

xₙ₊₁ = xₙ − f(xₙ)/f′(xₙ).

Stop when consecutive values agree to the required accuracy and verify that f(xₙ) is small. The method can fail if f′(xₙ) = 0 or the starting value is poor.

**Worked example:** For √10, solve f(x) = x² − 10 = 0. Then xₙ₊₁ = (xₙ + 10/xₙ)/2. Starting x₀ = 3 gives x₁ = 3.166667 and x₂ ≈ 3.162281, so √10 ≈ 3.1623.

## Common errors

- In a composite function, multiply by the derivative of the inner expression.
- f″ = 0 alone does not prove a point of inflection or classify a stationary point.
- Newton–Raphson requires a nonzero derivative at each iterate; do not round too early.

## Active recall

1. Differentiate y = ln(2x + 1).
2. Classify the stationary point of y = −x² + 6x.
3. Write one Newton step for f(x) = x³ − 2 starting at x₀ = 1.

**Check:** 2/(2x + 1); a maximum at (3, 9), since y″ = −2; x₁ = 1 − (−1)/3 = 4/3.
