---
layout: post
title:  "Simple Motion in One Dimension"
date: 2016-12-30
categories: Kinematics
---

When studying the motion of a particle, you will encounter two special cases: motion with constant velocity, and motion with constant acceleration. In the case of constant velocity, we have \\( v(t) = v_c \\), where \\( v_c \\) is a constant with units of velocity. Since the velocity is constant, there is no acceleration.

Consider the case where \\(v(t) = v_c\\) :

$$
  a(t) = \frac{d v(t)}{dt} = 0 .
$$

By integrating the velocity function, we can find the position function:

$$
  x(t) = \int v(t)dt = \int v_c dt = v_c t + x_0 ,
$$

where \\( x_0 \\) is the integration constant, which in this case physically indicates the starting position of the particle. In other words, \\( x(0) = x_0 \\) is the initial position of the body along the x-axis. It can also be seen that the position function above is a linear function of time, where the slope is the velocity, and the y-intercept is the initial position.

In the case of constant acceleration, we have \\( a(t) = a_c \\), where \\( v_c \\) is a constant with units of acceleration. The velocity of an object with constant acceleration can therefore be found by integrating the acceleration constant.

Consider the case where \\( a(t) = a_c \\) :

$$
  \frac{d a(t)}{dt} = 0 .
$$

By integrating the acceleration function, we can find the velocity function:

$$
  v(t) = \int a_c dt = a_c t + v_0 ,
$$

where \\( v_0 \\) is an integration constant that represents the initial velocity. By integrating the above velocity function again, we can then find the position function:

$$
  x(t) = \int v(t) dt = \frac{1}{2} a_c t^2 + v_0 t + x_0 ,
$$

where \\( x_0 \\) is the integration constant that represents the initial position, as before.

We can see here that by knowing the position of an object as a function of time, we know everything about the velocity and acceleration of that object at any time.

Of course, this requires knowing about the time in a system. In cases where this is not possible, but we know any two of the position, velocity, or acceleration of the object, we can still relate these functions to each other.

For example, in the case of uniform acceleration, and using the above relations, we can solve for time:

$$
  t = \frac{(v - v_0)}{a_c} .
$$

Plugging this into the position function above, we can solve for position as follows:

$$
  x = \frac{1}{2} \frac{v^2 - v^2_0}{a_c} + x_0 .
$$
