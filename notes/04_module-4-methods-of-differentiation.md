# 04 · Module 4 — Methods of Differentiation

> Source: Module 4.txt. This page is searchable, and the checklist state is saved in this browser.

## Learning checks

- [ ] Identify the key terms and explain them without looking.
- [ ] Summarize the main idea in your own words.
- [ ] Work through an example or answer a related question.

## Course notes

Department of Mathematics and Statistics

MODULE 5

COURSE CODE: CSC 114                   COURSE TITLE: Differential and integral Calculus

CHAPTER TWO

DIFFERENTIATION

2.3 Derivatives of Trigonometric Functions

ddxsin(x)=cos(x),

ddxcos(x)=-sinx,

ddxtanx=ddxsinxcosx=cosxcosx-sinx-sinxcosx2

=cos2x+sin2(x)cos2x=1cos2x=sec2x.

Also note that

ddxcotx=-csc2x,

ddxsecx=secxtanx,

ddxcsc(x)=-cscxcotx.

Examples

Differentiate each of the following functions:

gx=3sec(x)-10cot(x).

hw=3w-4-w2tanw.

y=5sin(x)cos(x)+4csc(x).

pt=sin(t)3-2cos(t).

Solution

g'x=3sec(x)tan(x)-10-csc2x=3secxtanx+10csc2x.

h'w=-12w-5-2wtanw+w2sec2w

=-12w-5-2wtanw-w2sec2w.

y'=5cosxcosx+5sinx-sinx-4cscxcotx

=5cos2x-5sin2x-4cscxcotx.

p't=cos(t)3-2cos(t)-sin(t)2sin(t)3-2cos(t)2=3cos(t)-2cos2t-2sin2(t)3-2cos(t)2=3cos(t)-23-2cos(t)2.

2.4 Derivatives of Exponential and Logarithmic Functions

ddxex=ex.

ddxlnx=1x.

Note that lnx=loge(x) is called the natural logarithm.

ddxln-x=1-x-1=1x.

What about ddxax and ddxloga(x) ?

Note that a=eln(a). Then,

ax=eln(a)x=exln(a),

and we can compute the derivative using the chain rule.

ddxax=ddxeln(a)x=ddxexln(a)=lnaexlna=lnaax.

Likewise, we can compute the derivative of the logarithmic function loga(x).

Since x=eln(x), we can take the logarithm base a of both sides to get

logax=logaeln(x)=lnxlogae.

Then

ddxlogax=1xlogae.

The above is a perfectly good answer, but we can improve it slightly.

Since a=eln(a),

logaa=logaeln(a)=lnalogae⟹1=lnalogae⟹1lna=logae,

and hence,

ddxlogax=1xlogae=1xlna.

Example 1

Compute the derivative of fx=2x.

Solution

ddx2x=ddxeln(2)x=ddxexln(2)=ln2exln2=2xln2.

Example 2

Compute the derivative of fx=2x2.

Solution

ddx2x2=ddxex2ln(2)=2xln2ex2ln2=2ln2x2x2.

Example 3

Compute the derivative of fx=xx.

Solution

At first, this appears to be a new kind of function, but it is not harder than the previous examples.

Note that

ddxxx=ddxexln(x)=ddxxln(x)exln(x)=x×1x+ln(x)xx=1+ln(x)xx.

Example 4

Compute the derivative of fx=xr.

Solution

ddxxr=ddxerln(x)=ddxrln(x)erln(x)=x×1xxr=rxr-1.

Exercise

Find the derivatives of

3x2.

x2ex.

ex2.

xcos(x).

esin(x).

xln(x).

2.5 Derivatives of Inverse Trigonometric Functions

ddxsin-1(x)=11-x2.

ddxcos-1(x)=-11-x2.

ddxtan-1(x)=11+x2.

ddxcot-1(x)=-11+x2.

ddxsec-1(x)=1xx2-1.

ddxcsc-1(x)=-1xx2-1.

Alternative Notation

sin-1x=arcsinx.

cos-1(x)=arccosx.

tan-1(x)=arctanx.

cot-1(x)=arccotx.

sec-1(x)=arcsecx.

csc-1(x)=arccscx.

Examples

Differentiate the following functions

ft=4 cos-1t-10 tan-1(t).

y=z sin-1z.

Solution

f't=-41-t2-101+t2.

y'=12z-1/2 sin-1z+z1-z2.

2.6 Derivatives of Hyperbolic Functions

In many physical situations, combinations of ex and e-x arise often.

Because of this, these combinations are given names.

There are six hyperbolic functions and they are defined as follows:

sinhx=ex-e-x2.

coshx=ex+e-x2.

tanh(x)=sinh(x)cosh(x).

coth(x)=cosh(x)sinh(x)=1tanh(x).

sech(x)=1cosh(x).

csch(x)=1sinh(x).

We also have the following facts about the hyperbolic functions:

sinh(-x)=-sinhx.

cosh-x=cosh(x).

cosh2x-sinh2x=1.

1-tanh2x=sech2x.

You will note that these are similar, but not quite the same, to some of the more common trigonometric identities.

Because the hyperbolic functions are defined in terms of exponential functions finding their derivatives is simple.

With ddxex=ex and ddxe-x=-e-x, I hereby do the derivative for hyperbolic sine and leave the rest as an exercise:

ddxsinh(x)=ddxex-e-x2=ex-(-e-x)2=ex+e-x2=cosh(x).

For the rest, we can either use the definition of the hyperbolic function and/or the quotient rule.

All the six derivatives are as below:

ddxsinh(x)=cosh(x).

ddxcoshx=sinhx.

ddxtanh(x)=sech2x.

ddxcoth(x)=-csch2x.

ddxsech(x)=-sechxtanhx.

ddxcsch(x)=-cschxcothx.

Examples

Differentiate each of the following functions:

2x5coshx.

ht=sinh(t)t+1.

Solution

f'x=10x4coshx+2x5sinhx.

h't=t+1cosht-sinh(t)(t+1)2.

Derivatives of Inverse Hyperbolic Functions

ddxsinh-1(x)=1x2+1;

ddxcosh-1(x)=1x2-1;

ddxtanh-1(x)=11-x2;

Etc.

Let me show only the first one in the example below.

Example

Show that ddxarcsinhx=11+x2.

Solution

Let y=arcsinhx=sinh-1(x).

So, sinhy=x.

Then, ddxsinhy=coshy×y'=1, and so

y'=1coshy=11+sinh2(y)=11+x2.

Exercise

Use chain rule to differentiate the following

Rz=5z-8.

fx=sin3x2+x.

ft=2t3+cos(t)50.

hw=ew4-3w2+9.

gx=ln(x-4+x4).

y=sec(1-5x).

pt=cos4t+cos(t4).

Differentiate each of the following:

Tx=tan-1(2x)31-3x2.

y=x3+451-2x23.

2.7 Maximum and Minimum Points

You need to be able to find a stationary/critical point on a curve and decide whether it is a turning point (maximum or minimum) or a point of inflexion.

When dydx=0, the gradient is zero and so you have a stationary point.

Second Order Differentiation

The 2nd differential measures the change in gradient and can help you decide whether a

stationary point is a maximum, minimum or point of inflexion.

If dydx=0 and d2ydx2>0, then you have a minimum point.

If dydx=0 and d2ydx2<0, then you have a maximum point.

If dydx=0 and d2ydx2=0, then you have a point of inflection.

Example 1

Find the stationary point on the curve y=x2-4x+2.

Solution

dydx=2x-4.

We need to solve for dydx=0:

2x-4.=0⟹x=2.

Next, we find the value of y when x=2:

y=x2-4x+2=22-42+2=-2.

So, the stationary point is (2,-2).

Next decide whether the stationary point is a maximum, minimum or point of inflexion:

d2ydx2=2>0.

Hence the turning point is a minimum.

Example 2

Find the stationary point(s) on the curve f(x)=x3-3x2+4.

Solution

f'x=3x2-6x.

Now,

3x2-6x=0⇒3xx-2=0⇒x=0 or x=2.

Next, we find the y-values.

When x=0, y=4. Hence the stationary point is at (0,4).

When x=2, y=0. Hence the stationary point is at (2,0).

Next decide whether the stationary points are maximum, minimum or point of inflexion:

f''x=6x-6.

When x=0, f''x=-6<0. Hence (0,4) is a maximum point.

When x=2, f''x=6>0. Hence (2,0) is a minimum point.

Example 3

Find the stationary point on the curve y=x3.

Solution

f'x=3x2.

Now,

3x2=0⇒x=0.

The stationary point is thus at (0,0).

d2ydx2=6x.

The d2ydx2 is zero when x=0.

Thus (0,0) is a point of inflection.

Exercise

Find the stationary points and determine whether they are maximum, minimum, or points of inflection for the following curves:

y=-2x2+8x+7.

y=3x2-12x+2.

y=x2+8x-7.

fx=13x3+3x2+9x-3.

y=23x3-x2-12x+1.

fx=x3-12x.

y=-x3.

fx=x3-6x2+12x.

y=x3-32x2-18x+5.

## Active recall

:::steps
## Retrieval practice
---
Close or cover the notes. Write the key idea, method, or definitions you remember.
---
Reopen the notes and correct your recall in a different color. Add weak points to the progress tracker.
:::