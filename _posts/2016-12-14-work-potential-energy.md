---
layout: post
title:  "Work and Potential Energy"
date: 2016-12-14
categories: Energy
---

When the forces acting on an object are conservative, there exists a very simple relation between the work done and the potential energy. For simplicity I will illustrate it to you in one dimension, but the proof in any number of dimensions is very similar. I remind you that in one dimension a conservative force can be written in terms of some potential function \\( U(x) \\), namely \\( F = - dU(x) / dx \\). Using the definition of work given in the previous section, we find that:

$$
  W = \int^{x_f}_{x_i} F dx = \int^{x_f}_{x_i} \left( - \frac{d U(x)}{dx} \right) dx = - ( U(x_f) - U(x_i) )
$$

where the fundamental theorem of calculus was used in that last step. This says that the work is equal to the change between the initial potential energy and the final potential energy. It does not matter what happened in between!

To better appreciate how powerful this relation is, let us consider for example hydropower. The basic principle of hydropower is to utilize the speed water gains as they drop from a height in order to drive turbines. What is the maximal amount of work that can be extracted from a certain amount of water dropping a given height? The force acting on the water as they drop is that of gravity and so the potential energy is given by,

$$
  U(h) = m g h
$$

If the hydro plant is constructed such that water drops from a height \\( h_2 \\) to a lower height \\( h_1 \\), then the work done by the water on the turbines is at most the work they gained by falling under gravity (neglecting their initial speed),

$$
  W = - (mg h_1 - mg h_2) = mg(h_2 - h_1)
$$

Now, the actual amount of work extracted is always lower because machines are not perfectly efficient. But, think how impressive this relation is. With all its simplicity, it is giving us a very sharp upper limit on how much energy we can hope to extract from a given power source. With the ever-increasing demand for energy in the world, it is important to be able to clearly identify and analyzed the different energy resources and their potential output.

Suppose that there is now both a conservative force \\( F_{cons} \\), as well as another unspecified external force, \\( F_{ext} \\). The external force may or may not be conservative. We can arrive at an important relation between the amount of work done by the external force and the change in potential and kinetic energies. From the definitions of work, we have:

$$
  W = \Delta K
$$

Where \\( \Delta K \\) is the difference in kinetic energy. From the discussion above we have:

$$
  W = \int^{x_f}_{x_i} (F_{ext} + F_{cons}) dx = W_{ext} - \Delta U
$$

Where \\( \Delta U \\) is the difference in potential energy. Combining the above equations, we have"

$$
  W_{ext} = \Delta K + \Delta U
$$
