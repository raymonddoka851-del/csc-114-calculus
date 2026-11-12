# 03 · Module 3 — Introduction to Differentiation

> Source: Module 3.txt. This page is searchable, and the checklist state is saved in this browser.

## Learning checks

- [ ] Identify the key terms and explain them without looking.
- [ ] Summarize the main idea in your own words.
- [ ] Work through an example or answer a related question.

## Course notes

Department of Mathematics and Statistics

MODULE 4

COURSE CODE: CSC 114                  COURSE TITLE: Differential and integral Calculus

CHAPTER TWO

DIFFERENTIATION

2.1 Introduction

Formulas

If fx=c, then f'x=ddxc=0, i.e., the derivative of a constant is zero.

If fx=xn, then f'x=ddxxn=nxn-1, where n is any number. This method is called the power rule.

Properties

f(x)±g(x)'=f'x+g'x OR ddxf(x)±g(x)=dfdx±dgdx.

cf(x)'=cf'x OR ddxcf(x)=cdfdx, where c is a constant.

Examples

Differentiate each of the following functions

fx=15x100-3x12+5x-46.

gt=2t6+7t-6.

y=8z3-13z5+z-23.

Tx=x+93x7-25x2.

hx=xπ-x2.

y=3x22x-x2.

ht=2t5+t2-5t2.

Some Interpretations of Derivatives

Example 1

Is fx=2x3+300x3+4 increasing, decreasing, or not changing at x=-2?

Solution

Note that the rate of change of a function is given by the function’s derivative. Thus

fx=2x3+300x-3+4⟹f'x=6x2-900x-4=6x2-900x4.

Therefore,

f'-2=6(-2)2-900-24=-32.25.

So, at x=-2, the derivative is negative and so the function is decreasing at x=-2.

Example 2

Find the equation of the tangent line to fx=4x-8x at x=16.

Solution

The slope of the tangent line is given by the derivative of the function. Thus

fx=4x-8x12⇒f'x=4-4x-12=4-4x12=4-4x.

Therefore,

f'x=4-416=4-1=3.

Note that at x=16, fx=416-816=64-84=32.

Therefore, the line passes through (16,32).

Let (x,y) be another point on the line, then

Slope=∆y∆x=y-32x-16=3⟹y-32=3x-16

⟹y=3x-48+32

⇒y=3x-16,

which is the equation of the tangent line.

2.2 Methods of Differentiation

Product Rule

If two functions f(x) and g(x) are differentiable (i.e. the derivative exist), then the product is differentiable and,

(fg)'=f'g+fg'.

Quotient Rule

If two functions f(x) and g(x) are differentiable (i.e. the derivative exist), then the quotient is differentiable and,

fg'=f'g-fg'g2.

Examples

Differentiate each of the following functions:

y=3x22x-x2.

fx=6x3-x10-20x.

wz=3z+92-z.

hx=4xx2-2.

Chain Rule

If y is a function of u, i.e. y=f(u), and u is a function of x, i.e. u=g(x), then the derivative of y with respect to x is

dydx=dydu×dudx.

Example

Differentiate y=(x2-5)4.

Solution

Let u=x2-5, therefore y=u4.

Thus,

dudx=2x  and dydu=4u3.

Using chain rule, we get

dydx=dydu×dudx=4u3×2x=8xu3=8x(x2-5)3.

Application Problem on Derivatives

Suppose that the amount of air in a balloon at any time t is given by Vt=63t4t+1. Determine if the balloon is being filled with air or being drained of air at t=8.

Solution

Note that if the balloon is being filled with air, then the volume is increasing (value of the derivative is positive at that time) and if it being drained of air, then the volume is decreasing (value of the derivative is negative at that time).

On differentiation and substituting for t=8, V'8=-632178.

Hence the volume is decreasing.

## Active recall

:::steps
## Retrieval practice
---
Close or cover the notes. Write the key idea, method, or definitions you remember.
---
Reopen the notes and correct your recall in a different color. Add weak points to the progress tracker.
:::