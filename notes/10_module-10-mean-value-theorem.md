# 10 · Module 10 — Mean Value Theorem

> Source: Module 10.txt. This page is searchable, and the checklist state is saved in this browser.

## Learning checks

- [ ] Identify the key terms and explain them without looking.
- [ ] Summarize the main idea in your own words.
- [ ] Work through an example or answer a related question.

## Course notes

Department of Mathematics and Statistics

MODULE 11

COURSE CODE: CSC 114                 COURSE TITLE: Differential and integral Calculus

CHAPTER FIVE

MEAN VALUE THEOREM OF INTEGRAL CALCULUS

5.1 Introduction

The mean value theorem (MVT) for integrals deals with average values. It states that:

If f is continuous on the closed interval [a,b], then there exists a number c in the closed interval [a,b] such that

abf(x)dx=fcb-a.

Notice that the left-hand side of the equation represents the area under the curve with respect to the x-axis on the interval from a to b.

The right-hand side of the equation is the area of a rectangle of height f(c) and width (b-a).

What the theorem basically states is that the area under the curve is the same as the area of a rectangle over the same interval for some specific height, f(c). The x-value of this height, c, is guaranteed to exist under the conditions of the hypothesis.

How to find the value c.

To find c, we need to find f(c) and to do that, we need to solve the above equation by dividing each side by (b-a) or multiplying by 1b-a. That is

1b-aabf(x)dx=fc.

5.2 Average Value of a Function

The value of f(c) has a very special meaning. It is called the average value of f on the interval [a,b]. This means that, if you were to add up every single y-value along the curve from a to b (which is impossible to do, since there are an infinite number of them) and divide the number of y-values you added up (infinity), this would be the number.

To get around the little problem of adding up an infinite number of values and dividing by infinity, the MVT employs a little trick. If we could find the area of the interval (which is height times width) then divide by the width, you would end up with height, and it would be the average height, or y-value.

So, the area of the region under the graph of f is equal to the area of the rectangle whose height is the average value.

Examples

Example 1

Find the average value of fx=3x2-2x on the interval [1,4].

Solution

The average value is given by

fc=1b-aabfxdx=14-1143x2-2x dx

=13x3-x214=1364-16-1-1

=483=16.

So, what is the value of c guaranteed by the theorem?

All what we need to do is to solve the original function for x after we set it equal to 16.

fx=3x2-2x=16

⇒3x2-2x-16=0

⇒3x-8x+2=0

⇒x=83,-2.

Of these two values, only 83 (or 2.667) is in our interval, hence is the desired value of c.

Example 2

The speed of sound s(x) (in metres per second) can be modeled by

sx=-4x+341,  0≤x<11.5;295,                      11.5≤x<22;34x+278.5,  22≤x<32; 32x+254.5,  32≤x<50;-32x+404.5,  50≤x<80.

Where x is the altitude in kilometres.

What is the average speed of sound over the interval [0,80]?

Solution

Notice the question does not mention anything about the integral.

You must discern for yourself that since it is talking about the Average Speed, that this is finding the f(c) from the MVT for integrals.

Begin by Integrating over the 5 subintervals:

011.5sxdx=011.5-4x+341dx=3657;

11.522sxdx=11.522295dx=3097.5;

2232sxdx=223234x+278.5dx=2987.5;

3250sxdx=325032x+254.5dx=5688;

5080sxdx=5080-32x+404.5dx=9210.

By adding the values of the five integrals, you have

080sxdx=24640.

Therefore, the average speed of sound from an altitude of 0 kilometers to 80 kilometers is

180080sxdx=2464080=308 m/s.

Exercises

For each problem, find the average value of the function over the given interval. Then, find the values of c that satisfy the Mean Value Theorem for Integrals.

## Active recall

:::steps
## Retrieval practice
---
Close or cover the notes. Write the key idea, method, or definitions you remember.
---
Reopen the notes and correct your recall in a different color. Add weak points to the progress tracker.
:::