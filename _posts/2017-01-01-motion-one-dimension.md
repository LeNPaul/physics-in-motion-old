---
layout: post
title:  "Motion in One Dimension"
date: 2017-01-01
categories: Kinematics
---

We can describe the motion of a particle in one dimension using a single function that we will call \\(x(t)\\). Here, \\(t\\) refers to time, and \\(x\\) refers to the position of the particle.

If we know what \\(x(t)\\) is, then we know everything we need to know about the motion of the particle.

For example, the velocity of the particle is defined as the derivative of the position function:

$$
  v(t) = \frac{d x(t)}{dt} .
$$

This describes how fast something moves, and in which direction the particle is moving at any point in time.

We can also define the acceleration of the particle as the derivative of the velocity function:

$$
  a(t) = \frac{d v(t)}{dt} = \frac{d^2 x(t)}{dt^2} .
$$

If we know what the acceleration or velocity functions are, we can work backwards and calculate the position function through integration:

$$
  x(t) = \int v(t) dt ,
$$

$$
  v(t) = \int a(t) dt .
$$

When studying the motion of a particle, you will encounter two special cases: motion with constant velocity, and motion with constant acceleration.

Consider the case where \\(v(t) = v_c\\) :

$$
  a(t) = \frac{d v(t)}{dt} = 0 .
$$

By integrating the velocity function, we can find the position function:

$$
  x(t) = \int v(t)dt = \int v_c dt = v_c t + x_0 ,
$$

where \\(x_0\\) is the integration constant, which in this case physically indicates the starting position of the particle.

Now consider the case where \\( a(t) = a_c \\) :

$$
  \frac{d a(t)}{dt} = 0 .
$$

By integrating the acceleration function, we can find the velocity function:

$$
  v(t) = \int a_c dt = a_c t + v_0 .
$$

By integrating the above velocity function, we can find the position function:

$$
  x(t) = \int v(t) dt = \frac{1}{2} a_c t^2 + v_0 t + x_0 .
$$

Using the above relations, we can calculate for time by using:

$$
  t = \frac{v = v_0}{a_c} .
$$

If we don't know time, we can solve for position as follows:

$$
  x = \frac{1}{2} \frac{v^2 v_0^2}{a_c} + x_0 .
$$
