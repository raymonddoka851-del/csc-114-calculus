# 07 · Module 7 — Applications of Integration

> Source: Module 7.txt. This page is searchable, and the checklist state is saved in this browser.

## Learning checks

- [ ] Identify the key terms and explain them without looking.
- [ ] Summarize the main idea in your own words.
- [ ] Work through an example or answer a related question.

## Course notes

Department of Mathematics and Statistics

MODULE 8

COURSE CODE: CSC 114                   COURSE TITLE: Differential and integral Calculus

CHAPTER THREE

INTEGRAL CALCULUS

Application of Integration to Length, Area, and Volume

Example 1

Find the area of the region bounded by the graph of y=2x2-3x+2, the x-axis, and the vertical lines x=0 and x=2, as shown in the figure below.

Solution

Note that y>0 on the interval [0,2].

Area=022x2-3x+2dx=103.

Example 2

Water flows from a storage tank at the rate of Rt=200-4t litres per minute, where t∈[0,50]. Find the total amount of water that flows out of the tank in the first ten minutes.

Solution

010(200-4t)dt=200t-2t2010=1800.

Therefore, a total of 1,800 litres flow out over the first ten minutes.

Example 3

The velocity of a particle moving along the x-axis is vt=t2-2t-8 metres per second, where t≥0. Find the displacement of the particle over the interval [1,6].

Solution

16(t2-2t-8)dt=13t3-t2-8t16=-103.

The object moved 103 metres to the left.

Area Between Curves

If f(x) is above the x-axis on the interval [a,b], then abf(x)dx gives the area between the function and the axis on that interval, i.e.

The area of the shaded part below is given by abf(x)dx.

Area between two functions can also be found by taking the integral of the difference function, i.e., the area between the functions f(x) and g(x) on the interval [a,b] is

ab[fx-g(x)]dx.

That is, ab[fx-g(x)]dx is the area of the shaded part below.

Example 1

Find the area enclosed by the graphs of y=1+x and y=3+x3.

Solution

Sketch the graph:

Find the points of intersection, i.e., solve for

1+x=3+x3.

This gives x=0 and x=9.

The area between the curves is thus

091+x-3+x3dx=4.5.

Example 2

Find the area below fx=-x2+4x+3 and above gx=-x3+7x2-10x+5 over the interval 1≤x≤2.

Solution

The area needed is the shaded one below:

It is calculated as

12[fx-g(x)]dx=4912.

Example 3

Find the area between fx=-x2+4x and gx=x2-6x+5 over the interval 0≤x≤1.

Solution

Sketch

Since the two curves cross, we need to compute the two areas and add them.

First, we find the intersection point:

-x2+4x=x2-6x+5⟹x=5±152.

The intersection point we want is x=5-152≡a.

0ax2-6x+5--x2+4xdx+a1-x2+4x-x2-6x+5dx=-523+515.

Exercise

Sketch the region bounded by the graphs fx=x+1 and gx=12x+1, hence find the area of the enclosed region.

## Active recall

:::steps
## Retrieval practice
---
Close or cover the notes. Write the key idea, method, or definitions you remember.
---
Reopen the notes and correct your recall in a different color. Add weak points to the progress tracker.
:::