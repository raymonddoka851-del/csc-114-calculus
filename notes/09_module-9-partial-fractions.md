# 09 · Module 9 — Partial Fractions

> Source: Module 9.txt. This page is searchable, and the checklist state is saved in this browser.

## Learning checks

- [ ] Identify the key terms and explain them without looking.
- [ ] Summarize the main idea in your own words.
- [ ] Work through an example or answer a related question.

## Course notes

Department of Mathematics and Statistics

MODULE 10

COURSE CODE: CSC 114                 COURSE TITLE: Differential and integral Calculus

CHAPTER FOUR

TECHNIQUES OF INTEGRATION

4.3 Integration of Rational Functions by Partial Fractions

A rational function is a fraction with polynomials in the numerator and denominator. For example, x3x2+x-6, 1x-32, x2+1x2-1, etc., are all rational functions.

There is a general technique called partial fractions that allows us to integrate any rational function.

Example 1

Integrate

xdxx-1x-2.

Solution

First, we write:

xx-1x-2=Ax-1+Bx-2=Ax-2+B(x-1)(x-1)(x-2).

The above implies:

x=Ax-2+Bx-1=A+Bx-2A-B.

From which we obtain the following system of equations:

A+B=1;

-2A-B=0.

Solving the above simultaneous equations, we obtain A=-1 and B=2.

Therefore,

xdxx-1x-2=-1x-1dx+2x-2dx

=-1x-1dx+21x-2dx

=-lnx-1+2lnx-2+c

=lnx-22x-1+c.

Example 2

Integrate

x2-3(x2-1)(x-3)dx.

Solution

Note that

x2-3x2-1x-3=x2-3x+1x-1x-3=Ax+1+Bx-1+Cx-3

=Ax-1x-3+Bx+1x-3+C(x+1)(x-1)(x+1)(x-1)(x-3).

The above leads to

x2-3=Ax-1x-3+Bx+1x-3+Cx+1x-1.

Solving the above equation, we obtain: A=-14; B=12; and C=34.

Therefore,

x2-3x2-1x-3dx=-141x+1dx+121x-1dx+341x-3dx

=-14lnx+1+12lnx-1+34lnx-3+c.

Example 3

Evaluate

dxx2-4x-5.

Solution

Here, we can factor x2-4x-5=(x+1)(x-5), so we can write:

1x2-4x-5=1(x+1)(x-5)=Ax+1+Bx-5,

And solve for A and B as above, to obtain: A=1/6 and B=-1/6.

So, we have:

dxx2-4x-5=161x+1dx-161x-5dx

=16lnx+1-16lnx-5+c

=16lnx+1-lnx-5+c

=16lnx+1x-5+c.

## Active recall

:::steps
## Retrieval practice
---
Close or cover the notes. Write the key idea, method, or definitions you remember.
---
Reopen the notes and correct your recall in a different color. Add weak points to the progress tracker.
:::