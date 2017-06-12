---
layout: post
title:  "Conservative Forces"
date: 2016-12-18
categories: Energy
---

The idea of energy permeates much of physics and allows us to understand both qualitatively and quantitatively a diverge range of phenomena. Through the consideration of mechanical systems, we will explore the notion of energy, and what it is. The concept of energy shows up in many physical systems, and you will no doubt  develop of understand and appreciation of how useful energy is.

The dynamics of many systems is governed by forces that result in a constant of motion known as the energy. Such forces are called conservative forces, and they are defined through a function referred to as the potential energy.

### Energy in One-Dimension

Consider a force acting on a single body, where the force takes the following form:

$$
  F = - \frac{d U(x)}{d x}
$$

Where \\( U(x) \\) is the potential energy. From Newton's second law, we have:

$$
  F = m \frac{d v}{d t} = \frac{d U}{d x}
$$

By multiplying both sides by \\( v = dx/dt \\) we obtain:

$$
  m v \frac{dv}{dt} = - \frac{dx}{dt} \frac{dU}{dx}
$$

If \\( U(x) \\) is not an explicit function of time, and only depend son time through the coordinate \\( x(t) \\), then the chain rule of calculus allows us to simplify the right hand side:

$$
  m v \frac{dv}{dt} = - \frac{dU}{dt}
$$

Moving the potential energy to the left hand side and nothing that \\( vdv / \fra{1}{2} d v^2 \ dt \\), we find,

$$
  \frac{d}{dt} \left( \frac{1}{2} m v^2 + U(x) \right) = 0
$$

Therefore, the energy,

$$
  E = \frac{1}{2} m v^2 + U(x),
$$

is a constant of the motion. The part of the energy which is not he potential energy is known as the kinetic energy is typically labeled \\( K \\),

$$
  K = \frac{1}{2} m v^2
$$

Kinetic energy is the part of the energy that is assoicated with the motion of the object. Together, the kinetic and potential energies form the total energy. The total energy is the part that is conserved.

The standard unit of energy is known as the joule, and is defined as:

$$
  Joule = \frac{Kg \times m^2}{s^2}
$$

### Energy in Three-Dimensions

In two or three dimensions, the potential energy function \\( U(\vec{r}) \\) defines the force:

$$
  \vec{F} = \left( \frac{d U(\vec{r})}{dx} , \frac{d U(\vec{r})}{dy} , \frac{d U(\vec{r})}{dz} \right)
$$

Following the same steps as we did above, we find that the energy is given by:

$$
  E = \frac{1}{2} m ( v^2_x + v^2_y + v^2_z ) + U( \vec{r} )
$$

Which is also conserved. The part that involves the velocity is again the kinetic energy of the system:

$$
  K = \frac{1}{2} m ( v^2_x + v^2_y + v^2_z )
$$

### The Zero of the Potential Energy

The equations of motion, which determine the dynamics of the system, are insensitive to any constant shift of the potential energy since the force is the derivative of the potential. Therefore, the zero of the potential can be chosen at our convenience. However, once a choice is made, it must be respected throughout the analysis of the motion.
