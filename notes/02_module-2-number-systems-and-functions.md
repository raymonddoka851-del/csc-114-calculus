# 02 · Module 2 — Number Systems and Functions

> Source: Module 2.txt. This page is searchable, and the checklist state is saved in this browser.

## Learning checks

- [ ] Identify the key terms and explain them without looking.
- [ ] Summarize the main idea in your own words.
- [ ] Work through an example or answer a related question.

## Course notes

Department of Mathematics and Statistics

MODULE 3

COURSE CODE: CSC 114                  COURSE TITLE: Differential and integral Calculus

CHAPTER ONE

BASIC MATHEMATICS

1.2 Functions

A function is an association which to each number associates another number.

In other words, a function is a rule which maps a number to another unique number.

If we denote a function by f, then this association is denoted by x↦f(x).

We call f(x) the value of the function at x, or the image of x under f.

Examples

The association f:x→x2 is a function called the square. We have f2=4, f3=9, f-1=1, etc.

The association g:x→x+1 is a function. We have g1=2, g2=3, etc.

The association which to each number x associates a constant value, say c, is called the constant function with value c, i.e. f:x→c for all numbers x.

Let f,g be functions defined on the same set S. We can define the sum f+g of the two functions to be the function whose value at an element x of S is fx+g(x).

Associativity for addition of numbers gives us associativity for addition of functions; namely, for any functions f,g,h defined on S, we have f+g+h=f+(g+h).

Similarly, for commutativity, we have f+g=g+h.

Example

Let fx=x2 and gx=sin(x). Then

f+gx=fx+gx=x2+sin(x).

We also have the zero function, whose value at every element x of S is 0.

If f is a function defined on S, then we can define minus f, written -f to be the function whose value at an element x of S is -f(x).

Thus, we see that functions satisfy the same basic rules for addition as numbers.

The same is true for multiplication. If f,g are functions defined on the same set S, we define their product fg to be the function whose value at an element x of S is the product f(x)g(x).

Thus, we have, by definition, fgx=f(x)g(x). This product is commutative and associative.

Also, multiplication is distributive with respect to addition, because

f+ghx=f+gx∙hx

=fx+gxhx

=fxhx+gxhx

=fhx+ghx

=fh+ghx.

Thus, f+gh=fh+gh.

A function is said to be an even function if fx=f(-x) for all numbers x. It is said to be odd function if fx=-f(-x) for all x.

1.3 Trigonometry

Radian Measure

In a sense, the measurement of angles by degrees is not a natural measurement. It is much more reasonable to take another measure as described below.

Let π be the numerical value of the area of a disc of radius 1. The approximate value for π is 3.14159 . . . .

Let A be an angle with vertex at P and let S be the sector determined by A in the disc D of radius 1 centered at P. Let x be a number between 0 and 2π. We say that A has x radians to mean that

Area of SArea of D=x2π.

Examples of Angles with Radian Measure

Degrees are related to radians. For instance, 3600=2π radians; 1800=π radians; 600=π3 radians, etc.

In general,

x degrees=π180x radians.

Observe that the length of the circle of radius 1 is 2π.

The angle A determines an arc on this circle, and radian measure is so adjusted that

Length of this arcTotal length of circle=x2π.

Thus x is the length of arc determined by A.

Exercise

Give the following values of angles in radians:

150.

750.

1050.

1500.

Give the following values of angles in degrees:

-π4.

-89π.

143π.

Sine and Cosine

Consider a right-angled triangle:

Then,

sinA=Opposite sideHypotenuse=ac,

And

cosA=Adjacent sideHypotenuse=bc.

For any n∈Z and for any angle x,

sin(x+2nπ)=sin(x),

cos(x+2nπ)=cos(x).

Sine and cosine satisfy a basic relation:

sin2x+cos2x=1.

For all angles x,

sin-x=-sinx;

cos-x=cosx.

Example

A boat B starts from a point P on a straight river and moves down the river. An observer O stands at a distance of 1,000 ft from P, on the line perpendicular to the river passing through P. After 10 minutes, the observer finds that the angle θ formed by P, himself, and the boat, is such that cos(θ)=0.7. What is the distance between the observer and the boat at that time?

Solution

cosθ=0.7=Adjacent sideHypotenuse=1000c

⇒1000c=0.7⇒c=10000.7≈1428.6 ft.

1.4 Complex Numbers

Every complex number can be written in the form a+bi where a,b are real numbers.

There exists a complex number i such that i2=1.

Thus, in the complex numbers we can take a square root of -1.

Operations of Complex Numbers

Let z=x+yi and w=u+vi be complex numbers. Then

z+w=x+u+y+vi.

zw=x+yi u+vi

=xu+xvi+uyi-yv

=xu-yv+xv+uyi.

Example

Find zw given that z=2+3i and w=1-i.

Answer: zw=5+i.

Complex Conjugate

Let z=a+bi be a complex number. We define its complex conjugate (or simply its conjugate) to be the complex number z=a-bi.

Thus if z=2+3i, then z=2-3i. Similarly, if z=2-3i, then z=2+3i.

Exercise

Verify that if z=a+bi, then zz=a2+b2.

Theorem:

Let z,w be complex numbers. Then

zw=zw;

z+w=z+w;

z=z.

Proof

Left as an exercise.

Real and Imaginary Parts of a Complex Number

Let z=x+iy be a complex number with real x,y. We call x the real part of z, and y the imaginary part of z. These are denoted as Re(z) and Im(z), respectively.

Absolute Value of a Complex Number

We define the absolute value of a complex number z=x+iy to be z=x2+y2.

Thus, the absolute value of z is simply the distance from the origin to the point (x,y) in the plane.

1.5 Analytic Geometry

Equation of a Straight Line

Consider an equation y=3x or simply y-3x=0. Its graph is given by

If we consider y=4x, we will see that it is a line which slants more steeply.

In general, the graph of the equation y=ax, where a is a number, represents a straight line.

If a is positive, then the line slants to the right. If a is negative, then the line slants to the left.

Let a,b be numbers. The graph of the equation y=ax+b is also a straight line, which is parallel to the graph of the equation y=ax.

Examples

Draw the graph of y=2x+1.

Solution

Draw the graph of y=-2x-5.

Solution

If a line L is the graph of the equation y=ax+b, then we call the number a the slope of the line. For instance, the slope of the line whose equation is y=-4x+7 is -4. The slope determines how the line is slanted.

Let y=ax+b be the equation of a line. The slope of this line can be obtained from two distinct points on the line.

Let (x1, y1) and (x2, y2) be the two points. By definition, we know that

y1=ax1+b,

y2=ax2+b.

Subtracting, we find y2-y1=a(x2-x1).

If the two points are distinct, x2≠x1, and we can divide by (x2-x1) to find

a=y2-y1x2-x1≡∆y∆x.

This formula gives us the slope in terms of the coordinates of two distinct points.

Examples

Consider the line defined by the equation y=2x+5. The two points (1,7) and (-1,3) lie on the line. The slope is equal to 2. Notice that,

2=7-31-(-1)=42=2.

Find the equation of the line passing through the points (1,2) and (2,-1).

Solution

We first find the slope. It must be the quotient, y2-y1x2-x1 which in this case is equal to

-1-22-1=-3.

Thus, we know that our line is the graph of the equation y=-3x+b for some number b, which we must determine.

We know that the line passes through the point (1,2). Hence

2=-3∙1+b ⟹b=5.

Thus, the equation of the line is y=-3x+5.

Find the equation of the line having slope -7 and passing through the point (-1,2).

Solution

The equation must be of the form y=-7x+b with some number b.

Furthermore, when x=-1, the corresponding value of y must be 2. Hence

2=-7-1+b ⇒b=-5.

Hence the equation of the line is y=-7x-5.

Find the points of intersection of the line and the circle given by the following equations:

y=3x+2 and x2+y2=1.

Solution

To do this, note that a point (x,y) lies on the intersection if and only if y=3x+2 and x2+(3x+2)2=1.

Thus, we must solve for x in this last equation, which is equivalent to

x2+9x2+12x+4=1 ⇒10x2+12x+3=0.

Using quadratic formula,

x=-12±144-(4×10×3)20=-6±610.

These two possible values for x give us the two points of intersection.

The y-coordinates can be found by the expression y=3x+2, and hence the points of intersection are

-6+610,2+3610 and -6-62,2-3610.

Exercise

Find the points of intersection (if any) of the line and the circle given by the following equations:

y=x+5 and x2+y2=1.

## Active recall

:::steps
## Retrieval practice
---
Close or cover the notes. Write the key idea, method, or definitions you remember.
---
Reopen the notes and correct your recall in a different color. Add weak points to the progress tracker.
:::