---
layout: post
title:  "Simple Motion in Two Dimensions"
date: 2016-12-26
categories: Kinematics
---

## Projectile Motion

A type of motion that is often encountered in practical applications of kinematics is projectile motion. This is the path that an object thrown on earth follows as it moves through space. For simplicity, we will ignore air resistance.

In the case of projectile motion, if we were to choose our coordinate system such that the x-axis is parallel to the ground, and the y-axis is perpendicular to the ground, then we have the object being accelerated along the y-axis towards the ground, in the negative direction:

$$
  a_x (t) = 0,
$$

$$
  a_y (t) = -g,
$$

where there is no acceleration along the x-axis, and \\( g \\) is the acceleration of the object towards the ground, as a result of gravity. Since we usually denote up as being positive, and down as being negative, \\( g \\) is negative.

We can find the velocity functions by integrating the acceleration functions above:

$$
  v_x (t) = \int a_x (t) dt = v_{x0},
$$

$$
  v_y (t) = \int a_y (t) dt = v_{y0} - g t,
$$

where \\( v_{x0} \\) and \\( v_{y0} \\) are the initial velocities in the x and y-axes, respectively. As there is no acceleration along the x-axis, the velocity remains a constant, as expected. Since the y-axis does experience an acceleration due to the earth's gravity, the velocity does not remain constant, and in fact, increases in magnitude as time increases, as expected.

We can find the position function by integrating the above velocities:

$$
  x(t) = \int v_x (t) dt = x_0 + v_{x0} t,
$$

$$
  y(t) = \int v_y (t) dt = y_0 + v_{y0} t - \frac{1}{2} g t^2,
$$

where \\( x_0 \\) and \\( y_0 \\) are the initial positions of the object along the x and y axes respectively.
