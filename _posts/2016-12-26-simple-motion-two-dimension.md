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


## Motion in a Circle

It is possible to describe the motion of a body in circular motion with constant speed, using the following equation:

$$
  \vec{r}(t) = ( R \cos(2 \pi t / T), R \sin (2 \pi t / T) ),
$$

where \\( R \\) is the radius of the circle, and \\( T \\) is the period of motion. By finding the derivative of this function, we obtain the velocity:

$$
  \vec{v}(t) = ( -V \sin(2 \pi t/ T), V \cos(2 \pi t / T) ),
$$

where \\( V = 2 \pi R / T \\), as can be determined by geometry. Note that the velocity vector is perpendicular to the position vector everywhere along the path. In addition, the magnitude, or speed, of this vector is constant:

$$
  |\vec{v}(t)| = \sqrt{V^2 \sin^2 (2 \pi t / T) + V^2 \cos^2(2 \pi t /T)} = V,
$$

The last step in the above equation used a trigonometric identity to simplify the equation.

By differentiating the velocity function, we can find the acceleration of the particle:

$$
  \vec{a}(t) = ( -a \cos(2 \pi t / T ), -a \sin(2 \pi t / T) ),
$$

where \\( a = 2 \pi V / T \\). The magnitude of the acceleration is also constant, and is equal to \\( a \\). The acceleration is always pointing towards the centre of the circle, perpendicular to the velocity vector, which is always tangential to the circle. By considering the definition of \\( V \\) and \\( a \\), we can deduce the following relationship:

$$
  a = \frac{V^2}{R}.
$$

This is known as centripetal acceleration. It is always pointing towards the center of the circle, and its magnitude is given by the above equation. It is present when a body follows a circular path, since this acceleration is responsible for changing the direction of the velocity along the path.
