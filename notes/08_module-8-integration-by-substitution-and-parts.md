# 08 · Module 8 — Integration by Substitution and Parts

> Source: Module 8.txt. This page is searchable, and the checklist state is saved in this browser.

## Learning checks

- [ ] Identify the key terms and explain them without looking.
- [ ] Summarize the main idea in your own words.
- [ ] Work through an example or answer a related question.

## Course notes

Department of Mathematics and Statistics

MODULE 9

COURSE CODE: CSC 114                  COURSE TITLE: Differential and integral Calculus

CHAPTER FOUR

TECHNIQUES OF INTEGRATION

We have so far encountered simple problems of integration such as x10dx, cos(x)dx, e2xdx, etc.

In this topic, we study various techniques of integrating some more advanced problems.

4.1 Integration by Substitution

Example 1

Find 2xcosx2dx.

Solution

This is not a simple problem, but a little thought reveals that it must have come from an application of the chain rule.

We proceed as follows:

Let u=x2, then dudx=2x or du=2xdx.

Since we have exactly 2xdx in the original integral, we can replace it by du, i.e.,

2xcosx2dx=cos(u)du=sin(u)+c=sinx2+c.

Example 2

Evaluate ax+bndx assuming that a and b are constants, a≠0 and n is a positive integer.

Solution

Let u=ax+b. So, dudx=a⟹du=adx OR dx=dua. Then

ax+bndx=1aundu=1a(n+1)un+1+c=1a(n+1)(ax+b)n+1+c.

Example 3

Evaluate sinax+bdx, assuming that a and b are constants and a≠0.

Solution

Again, we let u=ax+b. So, dudx=a⟹du=adx OR dx=dua. Thus,

sinax+bdx=1asin(u)du=1a-cos(u)+c=-1acosax+b+c.

Example 4

Evaluate 24xsinx2dx.

Solution

Let u=x2, so du=2xdx OR xdx=du2.

Thus,

xsinx2dx=12sin(u)du=12-cos(u)+c=-12cosx2+c.

Now,

24xsinx2dx=-12cosx224=-12cos16+12cos4.

Another alternative is to change the original limits to match the variable u.

Since u=x2; when x=2, u=4; when x=4, u=16. So, we can write

24xsinx2dx=41612sin(u)du=-12cosu416=-12cos16+12cos4.

Example 5

Evaluate

1/41/2cos(πt)sin2(πt)dt.

Solution

Let u=cos(πt). So,

dudt=πcos(πt) OR du=πcos(πt)dt OR duπ=cos(πt).

We change the limits of integration as follows:

When t=14, u=sinπ4=22. When t=12, u=sinπ2=1.

1/41/2cos(πt)sin2(πt)dt=2/211π1u2du=2/211πu-2du=1πu-1-12/21=-1π+2π.

4.2 Integration by Parts

Start with the product rule:

ddxfxgx=f'xgx+fxg'x.

We can rewrite this as:

fxgx=f'xgxdx+fxg'xdx.

And then,

fxg'xdx=fxgx-f'xgxdx.

It turns out that, in many cases, we have an integral of the form fxg'xdx but f'xgxdx is easier.

This technique for turning one integral into another is called integration by parts.

If we let u=f(x) and v=g(x), then du=f'xdx and dv=g'xdx. Thus

udv=uv-vdu.

To use this technique, we need to identify likely candidates for u=f(x) and dv=g'xdx.

Example 1

Evaluate xlnxdx.

Solution

Let u=lnx. So, du=1xdx.

Then we must let dv=xdx. So, v=x22.

And thus,

xlnxdx=udv=uv-vdu

=x2lnx2-x2dx

=x2lnx2-x24+c.

Example 2

Evaluate xsinxdx.

Solution

Let u=x. So, du=dx.

Then we must let dv=sinxdx. So, v=-cosx.

And thus,

xsinxdx=udv=uv-vdu

=-xcosx+cosxdx

=-xcosx+sinx+c.

Example 3

Evaluate x2sinxdx.

Solution

Let u=x2 and let dv=sinxdx.

Then du=2xdx and v=-cosx.

Now,

x2sinxdx=uv-vdu

=-x2cosx+2xcosxdx.

This is better than the original integral, but we need to do integration by parts again.

Let u=2x, dv=cosxdx.

Then, du=2 and v=sinxdx.

Thus,

2xcosxdx=uv-vdu

=2xsinx-2sinxdx

=2xsinx+2cosx+c.

Hence,

x2sinxdx=-x2cosx+2xsinx+2cosx+c.

## Active recall

:::steps
## Retrieval practice
---
Close or cover the notes. Write the key idea, method, or definitions you remember.
---
Reopen the notes and correct your recall in a different color. Add weak points to the progress tracker.
:::