# 05 · Module 5 — Applications of Differentiation

> Source: Module 5.txt. This page is searchable, and the checklist state is saved in this browser.

## Learning checks

- [ ] Identify the key terms and explain them without looking.
- [ ] Summarize the main idea in your own words.
- [ ] Work through an example or answer a related question.

## Course notes

Department of Mathematics and Statistics

MODULE 6

COURSE CODE: CSC 114                   COURSE TITLE: Differential and integral Calculus

CHAPTER TWO

DIFFERENTIATION

2.8 Newton-Raphson Method for Solving Equations

A method for finding the roots of an “arbitrary” function that uses the derivative was first circulated by Isaac Newton in 1669. John Wallis published Newton’s method in 1685, and in 1690 Joseph Raphson (1648–1715) published an improved version, the form we use today.

The idea is as follows:

We are given a function, say fx=x3-4x2-x+2. A graph of this function shows that the function has three roots: near -1, 1, and 4 as shown in the figure below.

Those are not the exact values of the roots.

We us an iterative procedure that gets us progressively closer to the root.

If xk is our guess and neither f(xk) nor f'(xk) is zero, then the next approximation will be

xk+1=xk-fxkf'xk.

Now, suppose in the above f(x) we want to find the solution close to -1. The successive iterations (with ten-digit accuracy) are

x2=-0.8;

x3=-0.7628415301;

x4=-0.7615586962;

x5=-0.7615571818;

x6=-0.7615571818.

This is a very good approximation to the root as it is given up to 10 decimal places. This is the Newton-Raphson Method.

To find the other two roots, we start closer to them.

If the initial guess is not very accurate, it takes more iterative steps.

Example 1

Use the Newton-Raphson method, with 3 as starting point, to find a solution that is within 10-8 of 10.

Solution

The number 10 is the unique positive solution of the equation fx=0 where fx=x2-10.

Let x0 be our initial estimate of the root and let xn be the n-th improved estimate.

Note that f'x=2x.

The Newton method recurrence is therefore,

xn+1=xn-fxnf'xn=xn-xn2-102xn=xn-xn2+102xn=12xn+10xn.

Starting with x0=3:

x1=12x0+10x0=3.166666667;

x2=12x1+10x1=3.162280702;

x3=12x2+10x2=3.16227766;

x4=12x3+10x3=3.16227766.

We see that x3=x4 to 8 decimal places.

Example 2

Newton’s equation y3-2y-5=0 has a root near y=2. Starting with y0=2, compute y1, y2, and y3, the next three Newton-Raphson estimates for the root.

Solution

Let fy=y3-2y-5. Then f'y=3y2-2.

Newton-Raphson method thus produces the recurrence:

yn+1=yn-fynf'yn=yn-yn3-2yn-53yn2-2=2yn3+53yn2-2.

Starting with y0=2, we have y1=2.1, y2=2.094568121, and y3=2.094551482.

Example 3

Find all solutions of e2x=x+6, correct to 4 decimal places. Use the Newton method.

Solution

Let fx=e2x-x-6.

We want to find where fx=0.

Note that f'x=2e2x-1. So, the Newton method iteration is

xn+1=xn-e2xn-xn-62e2xn-1=2xn-1e2xn+62e2xn-1.

We need to choose an initial estimate x0.

Let x0=0.97. We then see that x1=0.970870836 and x2=0.97087002.

Since x1 and x2 agree to 5 decimal places, then to 4 decimal places, the solution is 0.9709.

Exercise

Let fx=x2-a. Show that the Newton method leads to a recurrence

xn+1=12xn+axn.

## Active recall

:::steps
## Retrieval practice
---
Close or cover the notes. Write the key idea, method, or definitions you remember.
---
Reopen the notes and correct your recall in a different color. Add weak points to the progress tracker.
:::