---
layout: post
title:  "Elastic Collisions"
date: 2016-12-08
categories: Momentum
---

Bodies, especially microscopic ones, can collide and recoil off each other without losing energy to heat or other internal degrees of freedom. Such collisions are known as elastic collisions. Many collisions are approximately elastic, that is to say the energy lost is a small fraction of the kinetic energy and does not affect the dynamics. When no external forces are present we can use conservation of energy and momentum to solve for the motion of the bodies involved.

We begin with one-dimension. Since no forces are present before the collision, Galileo's principle informs us that the two particles move with constant velocities, which we denote with \\( v_{1i} \\) and \\( v_{2i} \\). Similarly, since no forces are present after the collision the two particles again move with constant velocities, \\( v_{1f} \\) and \\( v_{2f} \\). Finding the relation between the initial and final velocities is the solution to the collision problem.

Since no external forces are present at any times, including the collision itself, the total momentum of the system is conserved and so,

$$
  m_1 v_{1i} + m_2 v_{2i} = m_1 v_{1f} + m_2 v_{2f}
$$

By assumption, this is an elastic collision and so the total kinetic energy is conserved:

$$
  \frac{1}{2} m_1 v^2_{1i} + \frac{1}{2} m_2 v^2_{2i} = \frac{1}{2} m_1 v^2_{1f} + \frac{1}{2} m_2 v^2_{2f}
$$

There are two solutions to these equations. The first is not very interesting:

$$
  v_{1i} = v_{2i}
$$

$$
  v_{2i} = v_{2f}
$$

This solution just means that no collision occurred. The second solution that is more interesting is given by:

$$
  v_{1f} = \left( \frac{m_1 - m_2}{m_1 + m_2} \right) v_{1i} + \left( \frac{2 m_2}{m_1 + m_2} \right) v_{2i}
$$

$$
  v_{2f} = \left( \frac{2 m_1}{m_1 + m_2} \right) v_{1i} + \left( \frac{m_1 - m_2}{m_1 + m_2} \right) v_{2i}
$$

There are several simple cases where this general solution is particularly simple. First, if the two objects have the same mass, \\( m_1 = m_2 \\), then after the collision they simply exchange their velocities:

$$
  v_{1f} = v_{2i}
$$

$$
  v_{2f} = v_{1i}
$$

Second, if one object is much heavier than the second one, then:

$$
  v_{1f} = v_{1i}
$$

$$
  v_{2f} = - v_{2i} + 2 v_{1i}
$$

The heavier object does not change its motion, while the lighter one is greatly affect by the collision. In particular, if \\( v_{1i} = 0 \\), then the lighter object just bounces off the heavier one, \\( v_{2f} = - v_{2i} \\).
