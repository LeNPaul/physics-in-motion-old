---
layout: post
title:  "Newton's Laws"
date: 2016-12-24
categories: Forces
---

When we study kinematics, we assume that we already know everything about the position function, \\( x(t) \\), and from there, we can calculate the velocity and acceleration. In most cases, we do explicitly know the position function, and must determine \\( x(t) \\), based off of the forces that are interacting with an objects, which are often easier to measure.

### First Law of Motion

In the absence of any forces, the acceleration of an object is zero. This results in the velocity of an object remaining unchanged. If the velocity of the object was zero, or unmoving, then it will remain so. If the velocity of the object was nonzero, then it will remain traveling in a straight line.

In the case where \\( \vec{F} = 0 \\), the system is said to be in equilibrium, and there are two possibilities where this is the case: static and dynamic equilibrium. Static equilibrium refers to a body that is at rest, where the net force on the body is zero. Dynamic equilibrium refers to a body that is moving with a constant velocity, where the acceleration on that body is zero. This distinction will be important later on when dealing with environmental forces that depend on the velocity of the object, such as friction and drag.

### Second Law of Motion

The effect of forces on the motion of an object are described by Newton's second law of motion:

$$
  \vec{F}_{tot} = m \vec{a}
$$

Where \\( \vec{a} \\) is the acceleration of the object, \\( m \\) is the inertial mass, and \\( \vec{F}_{tot} \\) is the total force acting on the object (as there are often multiple forces acting on a system), given by the following:

$$
  \vec{F}_{tot} = \vec{F}_1 + \vec{F}_2 + ... = m \vec{a}
$$

The standard unit for measuring forces is called a Newton, where

$$
  1 N = kg \times m/s^2
$$

By knowing the total force, \\( \vec{F}_{tot} \\), as a general function, we know everything about the kinematics of the system, as well as the time. By itself, the second law does not provide us with that the general function of force is. This has to be determined based on the context of the system, primarily through experimentation. Over many centuries, this has resulted in comprehensive understanding of the forces present in different physical situations, some of which we will later explore.


### Third Law of Motion

Consider two separate bodies that exert forces on each other. The force exerted by the first body on the second is going to be equal in magnitude, but opposite in direction to the force exerted by the second body on the first. This can be written down as follows:

$$
  \vec{F}_{12} = - \vec{F}_{21}
$$

Where the subscripts \\( 12 \\) refers to the first body acting the second, and \\( 21 \\) refers to the second body acting on the first. It is important to understand that these forces are not acting on the same body, but rather it is the force exerted by one body on the other.

### Force Diagrams

When dealing with the dynamics, or forces, on a system, it is often useful to identify all of the different bodies involved, and to draw a separate diagram for each body, indicating the forces on that body alone. Such diagrams are known as force diagrams.

Things to consider when drawing such diagrams are Newton's third law of motion when dealing with interacting bodies. In addition, Newton's second law applies to each body separately, where the total force acting of a particular body is easily visualized through the force diagram. The dynamics of the system are then obtained by looking at Newton's second law for the total force:

$$
  \vec{F}_{tot} = \vec{F}_1 + \vec{F}_2 + ... = m \vec{a}
$$

This is known as the equation of motion, and by analyzing this equation, we can obtain the equations of motion associated with all the bodies in the system through the use of kinematics.
