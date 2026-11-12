# 08 · Module 8 — Integration by Substitution and Parts

![Source illustration from Calculus Module 8](../assets/figures/module-8-image1.png)

> Source: Calculus Module 9. Choose substitution for a nested expression and integration by parts for a product that simplifies after differentiating one factor.

## Substitution

This reverses the chain rule. Set u equal to an inner expression and replace its differential consistently:

u = g(x), du = g′(x) dx.

If the integral is definite, either convert both limits to u-values or return to x before applying the original limits.

**Worked example:** ∫2x cos(x²) dx. Set u = x², du = 2x dx:

∫cos u du = sin u + C = sin(x²) + C.

## Integration by parts

This reverses the product rule:

∫u dv = uv − ∫v du.

Choose u so its derivative is simpler, and dv so it can be integrated. A useful heuristic is to choose a logarithm or algebraic factor for u.

**Worked example:** ∫x sin x dx. Choose u = x, dv = sin x dx; then du = dx and v = −cos x:

∫x sin x dx = −x cos x + ∫cos x dx = −x cos x + sin x + C.

For ∫x² sin x dx, apply parts twice:

∫x² sin x dx = −x² cos x + 2x sin x + 2 cos x + C.

## Common errors

- Substitution must replace both the expression and its differential; do not leave mixed x and u variables.
- With definite substitution, change both limits or change back to x—not one without the other.
- The parts formula has a minus sign: uv − ∫v du.
- Check by differentiating the final antiderivative.

## Active recall

1. Evaluate ∫3x² eˣ³ dx.
2. Choose u and dv for ∫x eˣ dx, then evaluate.
3. What are the two consistent ways to handle definite-integral limits after substitution?

**Check:** eˣ³ + C; u = x, dv = eˣ dx, giving eˣ(x − 1) + C; convert both limits to u or convert the antiderivative back to x before using x-limits.
