# 09 · Module 9 — Integration by Partial Fractions

> Source: Calculus Module 10. Decompose a rational function into simpler fractions, then integrate logarithmic forms.

![Source illustration from Calculus Module 9](../assets/figures/module-9-image1.png)

## When and how

A rational function is a polynomial divided by a polynomial. If its numerator degree is at least the denominator degree, perform polynomial division first. Then:

1. Factor the denominator completely.
2. Write a partial-fraction form matching its factors.
3. Clear denominators and solve for the unknown constants.
4. Integrate each term; check by recombining or differentiating.

For distinct linear factors (x − a)(x − b), write A/(x − a) + B/(x − b). For a repeated factor (x − a)², include A/(x − a) + B/(x − a)². Irreducible quadratics need a linear numerator.

## Worked example: distinct factors

Decompose 1/[(x + 1)(x − 2)]:

1 = A(x − 2) + B(x + 1).

Setting x = 2 gives B = 1/3; setting x = −1 gives A = −1/3. Therefore:

1/[(x + 1)(x − 2)] = −1/[3(x + 1)] + 1/[3(x − 2)].

So its integral is (1/3)ln|x − 2| − (1/3)ln|x + 1| + C.

## Logarithm check

∫1/(x − a) dx = ln|x − a| + C. Absolute values are needed on intervals that do not cross the singularity.

## Common errors

- Factor the denominator fully before choosing the decomposition.
- Include every power for repeated linear factors.
- Solve for constants carefully; substitution at roots is a quick check.
- Keep absolute values in logarithms, and exclude points where the denominator is zero.

## Active recall

1. What is the correct form for A/[(x − 1)(x + 3)]?
2. Decompose 1/[(x − 1)(x + 1)].
3. Why do we use ln|x| rather than only ln x when integrating 1/x?

**Check:** A/(x − 1) + B/(x + 3); 1/2·1/(x − 1) − 1/2·1/(x + 1); the antiderivative is defined on either side of zero, with zero excluded.
