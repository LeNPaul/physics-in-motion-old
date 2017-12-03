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
