# 04 · Module 4 — Methods of Differentiation

![Source illustration from Calculus Module 4](../assets/figures/module-4-image1.png)

> Source: Calculus Module 4. Identify the structure of an expression before choosing a rule.

## Product, quotient, and chain rules

For differentiable f and g:

- **Product:** (fg)′ = f′g + fg′
- **Quotient:** (f/g)′ = (f′g − fg′)/g², where g ≠ 0
- **Chain:** if y = f(u) and u = g(x), then dy/dx = (dy/du)(du/dx)

The chain rule handles a function inside another function: differentiate the outer function first, keep the inner expression, then multiply by the inner derivative.

## Worked example: product

Differentiate y = x² sin x.

y′ = (2x)sin x + x² cos x.

## Worked example: quotient

For y = (x + 1)/(x − 1), x ≠ 1:

y′ = [(1)(x − 1) − (x + 1)(1)]/(x − 1)² = −2/(x − 1)².

## Worked example: chain

For y = (x² − 5)⁴, let u = x² − 5. Then dy/du = 4u³ and du/dx = 2x, so:

dy/dx = 8x(x² − 5)³.

## Choosing a method

1. A sum of terms? Use linearity and the basic rules on each term.
2. A product? Use the product rule.
3. A quotient? Use the quotient rule, or simplify first if possible.
4. A nested expression? Use the chain rule. Products and chains may appear together.

## Common errors

- The derivative of a product is not f′g′.
- In the quotient rule, the numerator order is f′g − fg′; reversing it changes the sign.
- Do not forget the square on the denominator.
- For a chain, omitting the inner derivative loses a factor.

## Active recall

1. Differentiate y = (3x + 1)(x² − 2).
2. Differentiate y = (2x − 1)³.
3. State one way to check a quotient-rule result.

**Check:** y′ = 9x² + 2x − 6; y′ = 6(2x − 1)²; differentiate the result independently or test with a numerical slope.
