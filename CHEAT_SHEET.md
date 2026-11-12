# CSC 114 — Practical Exam Review

Use this as a last-pass method and formula map, not as a substitute for solving problems. Equations are written in plain text and Unicode for quick scanning.

## A reliable exam routine

1. Identify what is being asked: value, derivative, tangent, stationary point, antiderivative, definite accumulation, area, or approximation.
2. Name the rule before using it. Show substitutions and intermediate algebra for method marks.
3. Keep domains and units visible: denominators cannot be zero; logarithm inputs must be positive; trig-calculus formulas use radians.
4. Check the result: differentiate an antiderivative, substitute into an equation, inspect signs, or verify the requested interval and units.
5. If stuck, write the relevant definition/formula and make a valid first step rather than leaving the question blank.

## 1–2 · Foundations

- Rational number: a/b, with integers a, b and b ≠ 0; reduce by common factors.
- Exponent laws: aᵐaⁿ = aᵐ⁺ⁿ; (aᵐ)ⁿ = aᵐⁿ; a⁻ⁿ = 1/aⁿ (a ≠ 0).
- Radians: θ = s/r; degrees to radians: multiply by π/180.
- sin²x + cos²x = 1; sin(−x) = −sin x; cos(−x) = cos x.
- Complex z = a + bi: z̄ = a − bi; |z| = √(a² + b²); i² = −1.
- Line through two points: slope m = (y₂ − y₁)/(x₂ − x₁); then y − y₁ = m(x − x₁).

## 3–5 · Differentiation

- d/dx(c) = 0; d/dx(xⁿ) = n xⁿ⁻¹; differentiate sums term by term.
- Product: (fg)′ = f′g + fg′.
- Quotient: (f/g)′ = (f′g − fg′)/g².
- Chain: d/dx f(g(x)) = f′(g(x))g′(x).
- Trig: (sin x)′ = cos x; (cos x)′ = −sin x; (tan x)′ = sec²x.
- Exponential/log: (eˣ)′ = eˣ; (aˣ)′ = aˣ ln a; (ln x)′ = 1/x.
- Stationary points: solve f′(x) = 0; f″ > 0 suggests minimum, f″ < 0 suggests maximum. If f″ = 0, test further.
- Tangent at x = a: y − f(a) = f′(a)(x − a).
- Newton–Raphson: xₙ₊₁ = xₙ − f(xₙ)/f′(xₙ); stop when estimates agree to the requested precision.

## 6–10 · Integration

- ∫xⁿ dx = xⁿ⁺¹/(n + 1) + C (n ≠ −1); ∫1/x dx = ln|x| + C.
- ∫eᵏˣ dx = eᵏˣ/k + C (k ≠ 0); always include + C for an indefinite integral.
- Definite integral: ∫ₐᵇ f(x) dx = F(b) − F(a), where F′ = f.
- Area between curves: integrate upper − lower; split where curves cross.
- Accumulated rate: integrate rate over time. Displacement is ∫v; distance is ∫|v|.
- Substitution: choose u = inner function and replace du = u′ dx; consistently change or restore limits.
- Parts: ∫u dv = uv − ∫v du.
- Partial fractions: factor denominator, match each factor with a term, solve constants, then integrate.
- Integral average value: f_avg = (1/(b − a))∫ₐᵇ f(x) dx. The theorem guarantees f(c) = f_avg for some c in [a, b] if f is continuous.

## Method chooser

| What the integrand looks like | First method to try |
| --- | --- |
| A sum of powers or standard functions | Integrate term by term |
| A composite function times its inner derivative | Substitution |
| A product such as x eˣ or x sin x | Integration by parts |
| A proper rational function with a factorable denominator | Partial fractions |

## Final checks

- Did you use radians for trig derivatives/integrals?
- Is the denominator nonzero on the interval?
- Did you include + C only when appropriate?
- Did you evaluate upper limit minus lower limit?
- Is area positive, and did you split at crossings?
- Does the answer have the requested units and accuracy?

For worked practice, use the [30-question bank](practice/QUESTION_BANK.md) and its [worked answer key](practice/ANSWER_KEY.md). Record weak topics and next actions in the [progress tracker](PROGRESS_TRACKER.md).
