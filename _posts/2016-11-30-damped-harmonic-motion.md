---
layout: post
title:  "Damped Harmonic Motion"
date: 2016-11-30
categories: Simple-Harmonic-Motion
---

In most cases, simple harmonic motion eventually decays and stops. Forces such as friction and drag work to dampen the motion of an object in simple harmonic motion.

Consider a pendulum, but this time include the effect of the surrounding air and its resistance as well as the mechanical friction of the string. We will model the combined effect of the resistive forces as linear drag,

$$
  F_{r} = - b v(t) = -b l \frac{d \theta}{dt}
$$

Where \\( b \\) is some constant of dimensions \\( Ns / m \\), and the fact that the velocity of the pendulum is \\( v = l d \theta / dt \\). The equation of motion is then the same as before, with the combined resistive force added to the sum of the forces:

$$
 \frac{d^2 \theta(t)}{d t^2} = - \frac{g}{l} \theta(t) - \frac{b}{m} \frac{d \theta}{d t}
$$

The solution to this equation is not very simple and depends on the exact relation of the different parameters involved. In the limit that the resistance is very weak, it is given by,

$$
  \theta (t) = \Theta \exp^{-bt /2m} \cos(\omega t + \phi)
$$

Where \\( \omega = \sqrt{l/g - b^2/(4m^2)} \\). Damped harmonic oscillation oscillates in a periodic fashion as expected from a pendulum, but the amplitude of the oscillations also diminishes over time.
