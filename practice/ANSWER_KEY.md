# CSC 114 — Worked Answer Key

Use these solutions to check reasoning, not just final values. If a method differs, verify by substitution, differentiation, or a numerical check.

## Module 1 — Basic Mathematics

### M01-Q1

Use denominator 8: 3/4 − 5/8 = 6/8 − 5/8 = 1/8. It is rational because it is a ratio of integers with nonzero denominator.

### M01-Q2

Multiply coefficients and add exponents: (2x³)(−3x²) = −6x⁵. A negative exponent means reciprocal: 2⁻² = 1/2² = 1/4.

### M01-Q3

Sixty years contains 60/20 = 3 doubling periods. Population = 300,000 × 2³ = 2,400,000.

## Module 2 — Number Systems and Functions

### M02-Q1

f(−x) = (−x)² − 2 = x² − 2 = f(x), so f is even.

### M02-Q2

150° × π/180° = 5π/6. This is in quadrant II with reference angle π/6, so sin(150°) = 1/2 and cos(150°) = −√3/2.

### M02-Q3

(a) Expand and use i² = −1: (2 + 3i)(1 − i) = 2 − 2i + 3i − 3i² = 5 + i.

(b) Slope m = (−1 − 2)/(2 − 1) = −3. Through (1, 2): y − 2 = −3(x − 1), hence y = −3x + 5.

## Module 3 — Introduction to Differentiation

### M03-Q1

By the power rule, f′(x) = 20x³ − 6x + 7. Thus f′(1) = 20 − 6 + 7 = 21.

### M03-Q2

y′ = 2x, so the slope at x = 2 is 4. The point is (2, 5). Point-slope form gives y − 5 = 4(x − 2), or y = 4x − 3.

### M03-Q3

V′(5) = −2.4 L/min means that at minute 5, the volume is decreasing instantaneously at 2.4 litres per minute.

## Module 4 — Methods of Differentiation

### M04-Q1

Product rule: y′ = (2x)sin x + x² cos x.

### M04-Q2

For x ≠ 1, quotient rule gives y′ = [(1)(x − 1) − (x + 1)(1)]/(x − 1)² = −2/(x − 1)². The original function and derivative are undefined at x = 1.

### M04-Q3

Outer derivative times inner derivative: y′ = 4(3x² + 1)³(6x) = 24x(3x² + 1)³.

## Module 5 — Applications of Differentiation

### M05-Q1

Chain rule: d/dx ln(2x + 1) = 2/(2x + 1), and d/dx sin(3x) = 3 cos(3x). Therefore y′ = 2/(2x + 1) + 3 cos(3x).

### M05-Q2

y′ = −2x + 6 = 0 gives x = 3; y(3) = 9. Since y″ = −2 < 0, the stationary point (3, 9) is a maximum.

### M05-Q3

Newton’s formula is x₁ = x₀ − f(x₀)/f′(x₀). Here f(1) = −1 and f′(x) = 3x², so f′(1) = 3. Thus x₁ = 1 − (−1)/3 = 4/3 ≈ 1.3333.

## Module 6 — Integral Calculus

### M06-Q1

Integrate term by term: ∫(6x² − 4x + 3) dx = 2x³ − 2x² + 3x + C. Differentiating gives 6x² − 4x + 3, as required.

### M06-Q2

An antiderivative of 2x is x². Therefore ∫₁³ 2x dx = [x²]₁³ = 9 − 1 = 8.

### M06-Q3

An antiderivative of e²ˣ is e²ˣ/2. Thus ∫₀¹ e²ˣ dx = [e²ˣ/2]₀¹ = (e² − 1)/2.

## Module 7 — Applications of Integration

### M07-Q1

The curve is above the axis, so area = ∫₀²(x + 1)dx = [x²/2 + x]₀² = 2 + 2 = 4 square units.

### M07-Q2

Volume = ∫₀¹⁰(200 − 4t)dt = [200t − 2t²]₀¹⁰ = 2,000 − 200 = 1,800 litres.

### M07-Q3

Displacement = ∫₀⁴(t − 2)dt = [t²/2 − 2t]₀⁴ = 0 m. Velocity changes sign at t = 2, so total distance is ∫₀²(2 − t)dt + ∫₂⁴(t − 2)dt = 2 + 2 = 4 m.

## Module 8 — Substitution and Integration by Parts

### M08-Q1

Let u = x³, so du = 3x² dx. Then ∫3x²eˣ³ dx = ∫eᵘ du = eᵘ + C = eˣ³ + C.

### M08-Q2

Choose u = x and dv = eˣdx; then du = dx and v = eˣ. By parts, ∫xeˣdx = xeˣ − ∫eˣdx = eˣ(x − 1) + C.

### M08-Q3

Set u = x²; du = 2x dx. When x = 0, u = 0; when x = 1, u = 1. Therefore ∫₀¹2x cos(x²)dx = ∫₀¹cos u du = [sin u]₀¹ = sin 1.

## Module 9 — Partial Fractions

### M09-Q1

Set 1/[(x − 1)(x + 1)] = A/(x − 1) + B/(x + 1). Clearing denominators gives 1 = A(x + 1) + B(x − 1). At x = 1, A = 1/2; at x = −1, B = −1/2. Thus the decomposition is 1/[2(x − 1)] − 1/[2(x + 1)].

### M09-Q2

Using M09-Q1, integrate term by term:

∫dx/(x² − 1) = (1/2)ln|x − 1| − (1/2)ln|x + 1| + C.

### M09-Q3

The denominator has a repeated linear factor and a distinct linear factor, so include each power of x − 2 and the x + 3 term:

(2x + 1)/[(x − 2)²(x + 3)] = A/(x − 2) + B/(x − 2)² + C/(x + 3).

All three terms are needed to represent a general numerator over that denominator.

## Module 10 — Mean Value Theorem for Integrals

### M10-Q1

Average value = (1/(4 − 1))∫₁⁴(3x² − 2x)dx = (1/3)[x³ − x²]₁⁴ = 48/3 = 16. Solve 3c² − 2c = 16: (3c − 8)(c + 2) = 0, so c = 8/3 or −2. Only c = 8/3 lies in [1, 4].

### M10-Q2

Average value = (1/3)∫₀³2x dx = (1/3)[x²]₀³ = 9/3 = 3.

### M10-Q3

The interval width is 8 − 2 = 6, so continuity and the theorem give ∫₂⁸ f(x)dx = 5 × 6 = 30. To find c, solve f(c) = 5 and retain a solution in [2, 8].
