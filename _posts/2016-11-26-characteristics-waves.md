---
layout: post
title:  "Characteristics of Waves"
date: 2016-11-26
categories: Waves
---

When studying simple harmonic motion, we have considered one or two bodies that may feel external forces, or may exert forces on each other. The motion of the sysetm was found by analyzing the objects individually, writing down the different forces that act on each object separately, using Newton's Second Law to arrive at the equations of motion, and finally solved these equations. Ultimately, we were after the position as a function of time, \\( x(t) \\).

What happens if we have many bodies, all interacting with each other? Writing down a position function of each body would be too difficult, with an uncountable number of equations associated with all the different bodies. Many important and interesting systems in nature are like this.

If the number of bodies is so large that they can be treated collectively as some sort of medium, then indeed there is much we can learn about the medium. It turns out that such systems often exhibit collective behaviour that can be analyzed and understood without having to understand all the internal interactions between the different bodies making up the medium.

For example, a tight string is composed of many atoms, but we may just want to describe its displacement away from its stretched position. In that case, we can do so with a function \\( y(x,t) \\), where \\( x \\) denotes the position along the string, \\( t \\) is the time, and \\( y(x,t) \\) denotes the displacement at position \\( x \\) and at time \\( t \\). To solve for the explicit form of \\( y(x,t) \\).

When dealing with a single body, in order to solve for the explicit form of \\( x(t) \\), we drew a force diagram, used Newton's Second Law to write down the equation of motion for \\( x(t) \\), and finally solved the equation of motion. It is possible to follow similar steps, applying Newton's laws to every point in the medium, to arrive at the equation of motion for \\( y(x,t) \\). The resulting equation for the case of a string takes the form,

$$
  T \frac{\partial^2 y(x,t)}{\partial x^2} = \mu \frac{\partial^2 y(x,t)}{\partial t^2}
$$

Where \\( T \\) is the string's tension, and \\( \mu \\) is the mass density of the string (mass density if equation to the mass of the string divided by the length of the string). You can think of the right hand side as the usual \\( m d^2 x(t) / d t^2 \\) term in Newton's Second Law, and the left hand side is the force, that is, \\( F = m a \\). But, this is now applied at every point along the string, \\( x \\). This equation is known as the wave equation and it finds application in many fields of science and technology. The solutions of these are known as waves.

### Characteristics of Waves

There are many types of media that support waves, and what is "waving" in each one could be different. Waves are disturbances that propagate through the medium about some unperturbed state. Water waves are disturbances in the height of the water's surface. Sound waves are disturbances in the local density of materials. Waves in a string are disturbances in the local strength of the electromagnetic field. In each of these cases, the function \\( y(x,t) \\) represents something different, such as height, displacement, density, and so on, but the mathematical description is the same.

The most general solution to the wave equation is:

$$
  y(x,t) = f(x - v_w t) + g(x + v_w t)
$$

where \\( f(x - v_w t) \\) is any continuous function of the single variable \\( x - v_w t \\) and \\( g(x + v_x t) \\) is any continuous function of the variable \\( x + v_w t \\). The constant \\( v_w \\) has units of velocity and it is given by,

$$
  v_w = \sqrt{t / \mu}
$$
