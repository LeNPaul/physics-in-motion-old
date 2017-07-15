---
layout: post
title:  "Calculus"
date: 2016-11-06
categories: Mathematics
---

### Functions

Functions are a mapping from some sets of numbers to another set of numbers. This simplest type of functions are ones that take a single variable, like \\( f(x) \\). This function, \\( f(x) \\), takes as argument a single number and returns a single number. For example,

$$
  f(x) = \frac{1}{2} k x^2
$$

Where \\( k \\) is some constant. The independent variable \\( x \\) may have many different meanings and symbolic representations. Similarly, the function \\( f(x) \\) my be represented by many other symbols. But, the meaning is always the same: you give it some number \\( x \\) and it will give you some other number \\( f(x) \\). A few examples are,

Some function of time \\( t \\)

$$
  f(t)
$$

Some function of the velocity along the x-direction, \\( v_x \\)

$$
  f(v_x)
$$

Some function of the position \\( x \\)

$$
  f(x)
$$

### Derivatives

The notion of derivatives will be introduced by discussing a function of time \\( f(t) \\), but everything below applies equally well to functions of other variables.

The derivative of a function \\( f(t) \\) is defined as

$$
  \frac{ d f }{ d t } = \lim_{\epsilon\ to 0\ } \frac{f(t + \epsilon) - f(t)}{\epsilon}
$$

Practically, what you care about is the result, so let's see some simple cases that will be useful for you:

$$
  f(t) = A t^n \rightarrow \frac{d f}{d t} = (A n) t^{n-1}
$$

$$
  f(t) = A \cos(\omega t + \phi) \rightarrow \frac{d f}{d t} = - A \omega \sin(\omega t + \phi)
$$

$$
  f(t) = A \sin(\omega t + \phi) \rightarrow \frac{d f}{d t} = A \omega \cos(\omega t + \phi)
$$

Finally, maybe the prettiest function of all, the exponential,

$$
  f(t) = A e^{\lambda t} \rightarrow \frac{d f}{d t} = \lambda A e^{\lambda t}
$$

Notice that for \\( \lambda = 1 \\) this function is its own derivative!

In all the expressions above, all the symbols which are not \\( t \\) or the function itself are some constants (eg. the amplitude \\( A \\), the angular frequency \\( \omega \\), the phase \\( \phi \\), etc.).

### Integrals


The fundamental theorem of calculus states that if a function \\( f(t) \\) i the derivative of another so that \\( f(t) = dg(t) / dt \\), the its definite integral is given by:

$$
  \int^{b}_{a} f(t) dt = g(b) - g(a)
$$

Here are some indefinite integrals:

$$
  \int (A t^n) dt = \frac{A}{n + 1} t^{n + 1} , \ n \ne -1
$$

When \\( n = -1 \\) we arrive at the beautiful natural logarithm function:

$$
  \int \left( \frac{A}{t} \right) dt = A \ln t
$$

For trigonometric functions the integrals can be easily guessed from the derivatives above

$$
  \int A \cos(\omega t + \phi) dt = \frac{A}{\omega} \sin (\omega t + \phi)
$$

$$
  \int A \sin(\omega t + \phi) dt = - \frac{A}{\omega} \cos (\omega t + \phi)
$$

Finally, the integral of the exponential function is,

$$
  \int A e^{\lambda t} dt = \frac{A}{\lambda} e^{\lambda t}
$$

If you know the indefinite integral, then you can always evaluate the definite integral. For example, we see that the definite integral of a power is

$$
  \int^{b}_{a} (A t^n) dt = \frac{A}{n+1} b^{n+1} - \frac{A}{n+1} a^{n+1}, \ n \ne -1
$$
