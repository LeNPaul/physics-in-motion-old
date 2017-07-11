---
layout: post
title:  "Fluid Dynamics"
date: 2016-11-10
categories: Fluids
---

There are many aspects of fluid dynamics that can be understood by simply applying the notions of particle mechanics such as energy, forces, and work. For incompressible fluids in particular, there is a simple relation between the pressure on the fluid, its height, and its velocity. Let us consider a small amount of mass entering a tube on one end and exiting on the other. The two ends are not necessarily at the same height, nor do they necessarily have the same area. The work done on the fluid b the external pressure as it enters is

$$
  W_1 = A_1 p_1 dx_1
$$

Where \\( A_1 \\) is the area of the entrance, \\( p_1 \\) is the inward pressure, and \\( d x_1 \\) is the distance the fluid was pushed through by the pressure. Similarly, the work done by the external pressure upon exit is,

$$
  W_2 = - A_2 p_2 d x_2
$$

Where the minus sign accounts for the opposite direction of the velocity (outwards) as compared with the pressure (inwards). The total work done on the fluid is then,

$$
  W_{ext} = W_1 + W_2 = A_1 p_1 d x_1 - A_2 p_2 d x_2
$$

$$
  W_{ext} = (p_1 - p_2) V
$$

Conservation of volume flow rate implies that over the same time the volume flowing inwards in equal to the volume flowing outwards and thus \\( A_1 d x_2 = A_2 d x_2 = V \\). As this work is done, there are changes in the fluid's kinetic and potential energies. These changes are,

$$
  \Delta K = \frac{1}{2} m v^2_2 - \frac{1}{2} m v_1^2,
$$

$$
  \Delta U = m g h_2 - m g h_1
$$

The relation between the external work done and the changes in kinetic and potential energy informs us that,

$$
  W_{ext} = \Delta K + \Delta U \rightarrow (p_1 - p_2) V = \frac{1}{2} m (v^2_2 - v^2_1) + mg (h_2 - h_1)
$$

Dividing through by the volume and rearranging, we arrive at a relation among the pressure, velocity, and height upon entrance and exit,

$$
  p_1 + \frac{1}{2} \rho_l v^2_1 + \rho_l g h_1 = p_2 + \frac{1}{2} \rho_l v^2_2 + \rho_l g h_2
$$

In other words, the quantity on both sides is unchanged throughout the motion,

$$
  p + \frac{1}{2} \rho_l v^2 + \rho_l g h = constant
$$

This relation is known as Bernoulli's equation.
