---
layout: post
title:  "Dynamics"
date: 2016-12-04
categories: Simple-Harmonic-Motion
---

Conservative forces can be described through a potential function. In one-dimension, the relation between the force and kinetic energy is given by,

$$
  F = - \frac{d U(x)}{dx}
$$

The simplest function is \\( U(x) = constant \\), which results in no force.

The next simplest function is a linear function, \\( U(x) = F_c x \\), with \\( F_c \\) some constant with dimensions of Newton. This potential results in a constant force \\( F = -F_c \\), and a constant acceleration \\( a = - F_c / m \\). We have encountered such a potential in the case of gravity near the surface of the earth where \\( F_c = m g \\), and \\( x \\) was a measure of the height from the surface, \\( h \\). In that case the potential energy is simply \\( U(h) = mgh \\).

At the next order of complexity is a quadratic function, \\( U(x) = \frac{1}{2} k x^2 \\), where \\( k \\) is some constant with units of \\( Newton/m \\). This is a very important potential that appears in a wide variety of phenomena. The force associated with such a potential is,

$$
  F = - \frac{d U(x)}{d x} = - k x(t)
$$

You might recognize this force as that of a simple spring with spring constant \\( k \\), namely Hooke's law. This is indeed the case, but it turns out that this force also serves as a good model for many other physical systems. The equation of motion associated with such a force is,

$$
  \frac{d^2 x(t)}{d t^2} = - \frac{k}{m} x(t)
$$

As usual, this is a differential equation whose solution is the position as a function of time, \\( x(t) \\). The general solution to the equation of motion is given by,

$$
  x(t) = A \cos (\omega t + \phi)
$$

where

$$
  \omega = \sqrt{k/m}
$$

is called the angular frequency. It is an intrinsic quantity of the system. \\( A \\) is the amplitude of the oscillations of \\( \phi \\) is the phase, which defines the initial position. Both \\( A \\) and \\( \phi \\) are extrinsic quantities, which vary depending on the initial conditions.

Such a motion is known as simple harmonic motion. It is an extremely important system, not just because of its simplicity, but because it shows up in a countless number of situations in all fields of science.

The motion is periodic with a period of \\( T = 2 \pi / \omega \\). To see this we notes that,

$$
  x(t + T) = A \cos (\omega (t + T) + \phi)
$$
