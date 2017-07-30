---
layout: post
title:  "The Pendulum"
date: 2016-12-02
categories: Simple-Harmonic-Motion
---

So far, \\( x(t) \\) has been discussed as the linear displacement from equilibrium. But simple harmonic motion is not restricted to linear motion. Consider a long string of length \\( l \\) and negligible mass that is used to hang an object of mass \\( m \\) from the ceiling. This is known as a pendulum. Unperturbed, the object remains in equilibrium along the vertical with the pull of gravity downwards balanced against the tension of the string upwards.

Suppose the object is displaced so as to make an angle \\( \theta \\) with the vertical. The forces are still gravity and the string's tension, but a horizontal component is now present due to the string tension that acts to push the object back towards the vertical. When the angle is small, the displacement in the vertical is negligible and we can write Newton's second law for the component of the force acting in the vertical,

$$
  0 = - mg + T \cos(\theta (t)) \rightarrow T = mg / \cos(\theta(t))
$$

Where the angle \\( \theta \\) is written explicitly as a function of time, \\( \theta(t) \\). From geometry, we can see that the horizontal displacement is \\( x(t) = l \sin(\theta(t)) \\). Therfore, the horizontal component of Newton's second law reads,

$$
  T \sin (\theta(t)) = - m \frac{d^2 (l \sin(\theta(t)))}{d t^2}
$$

where the minus sign comes about because the positive angular displacements where chosen to correspond to negative horizontal displacements from the vertical. When the angular displacement is small, \\( \| \theta(t) \| \approx 0  \\), we can use the approximations \\( \sin(\theta(t)) \approx \theta(t) \\) and \\( \cos(\theta(t)) \approx 1 \\). Then, using the results for both the vertical and horizontal components, we obtain the important relation,

$$
  \frac{d^2 \theta(t)}{d t^2} = - \frac{g \theta(t)}{l}
$$

This equation describes the motion of the pendulum when the angle remains small. It is the same equation as the equation for simple harmonic motion, with the change of notation, \\( x(t) \rightarrow \theta(t) , k \rightarrow g , m \rightarrow g \\). Therefore, we can immediately write down the solution for the motion.

$$
  \theta(t) = \Theta \cos ( t \sqrt{g / l} + \phi )
$$

Where \\( \Theta \\) is the maximum angular displacement and \\( \phi \\) is the phase. The period associated with the pendulum's motion is,

$$
  T = f^{-1} = \frac{s \pi}{\omega} = 2 \pi \sqrt{\frac{l}{g}}
$$

On earth, a pendulum of length one meter will complete half a period (one swing) in almost exactly one second.
