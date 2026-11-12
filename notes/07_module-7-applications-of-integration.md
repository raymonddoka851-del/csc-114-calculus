# 07 · Module 7 — Applications of Integration

![Source illustration from Calculus Module 7](../assets/figures/module-7-image1.png)

> Source: Calculus Module 8. Use integrals to measure area, accumulated quantities, and displacement.

## Area and accumulation

If f(x) ≥ 0 on [a, b], the area under y = f(x) is ∫ₐᵇ f(x) dx. If the curve crosses the axis, split at each crossing and add the absolute areas.

For an upper curve f and lower curve g:

Area = ∫ₐᵇ [f(x) − g(x)] dx.

First solve f(x) = g(x) to find intersection limits; if the curves swap order, split the interval.

## Worked example: area under a curve

Find the area under y = x + 1 from x = 0 to x = 2. Since y is positive:

Area = ∫₀² (x + 1) dx = [x²/2 + x]₀² = 4 square units.

## Accumulated rate

If R(t) is a rate in litres per minute, ∫ₐᵇ R(t) dt is the amount accumulated in litres.

**Worked example:** Water flows at R(t) = 200 − 4t litres/minute. In the first 10 minutes:

∫₀¹⁰ (200 − 4t) dt = [200t − 2t²]₀¹⁰ = 1,800 litres.

## Displacement and distance

For velocity v(t), displacement from a to b is ∫ₐᵇ v(t) dt. Net displacement may be negative. Total distance requires ∫ₐᵇ |v(t)| dt, so split where velocity changes sign.

## Common errors

- Area between curves is top minus bottom (or right minus left for horizontal slices), not simply either function.
- An integral of velocity gives signed displacement, not automatically total distance.
- Check intersections and axis crossings before integrating over the whole interval.
- Attach squared units to area and the proper accumulated units to rate integrals.

## Active recall

1. Find the area under y = 2x on [0, 3].
2. What does integrating a flow rate over time produce?
3. When must a velocity integral be split to calculate total distance?

**Check:** 9 square units; total accumulated volume; at every zero where velocity changes sign.
