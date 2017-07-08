---
layout: post
title:  "Sinusoidal Waves"
date: 2016-11-24
categories: Waves
---

A very particular form for the general function describing a wave, \\( f(x - v_w t) \\), is known as a sinusoidal wave,

$$
  y(x,t) = A \sin (k x - \omega t + \phi)
$$

Where \\( \omega \\) is the angular frequency and \\( k \\) is known as the wave-number. This function is periodic in both time and space. Concentrating on a particular point along the x-axis, say \\( x = 0 \\), we see that the point in the string is executing a simple harmonic motion about the equilibrium position,

$$
  y(x_0,t) = A \sin(\omega t)
$$

You can prove that \\( y(0, t + 2 \pi / \omega) = y(0,t) \\), and so the period of this motion is

$$
  T = \frac{2 \pi}{\omega}
$$

This sinusoidal wave also exhibits spatial periodicity, repeating itself at a distance:

$$
  \lambda = \frac{2 \pi}{k}
$$

Where \\( \lambda \\) is kown as the wavelength. Indeed, you can show that at any given moment, say \\( t = t_0 \\), we have \\( y(x + \lambda, t_0) = y(x,t_0) \\). If it is a wave, then it must have some velocity, which can obtain by writing

$$
  y(x,t) = A \sin k (x -\frac{\omega}{k} t)
$$

Comparison with the defining equation of a general wave, we see that

$$
  v_w = \frac{\omega}{k} = \frac{\lambda}{T} = f \lambda
$$

The velocity of a sinusoidal wave is its frequency times its wavelength.

### Power and Intensity

The power of a wave, which is the rate that energy is transported by the wave, has units of \\( kg m^2 / s^2 \\). For a wave on a string, there are four independent quantities that carry units, the mass density \\( \mu \\) with units of \\( kg/m \\), the wave speed \\( v_w \\) with units of \\( m/s \\), the amplitude of the wave \\( A \\) with units of \\( m \\), and the angular frequency \\( \omega \\) with units of \\( s^{-1} \\). We expect the power to be delivered at the same rate as the wave is propagating, hence \\( P \propto v_w \\). Also, on dimensional grounds, the power must involved one power of the mass density \\( P \propto \mu \\) because of the units associated with mass. Therefore, against on dimensional grounds we can conclude that the power in a wave must be,

$$
  P_{string} \propto \mu A^2 \omega^2 v_w
$$

Where the constant of proportionality turns out to be \\( 1/2 \\). Very generally, the power in waves increases quadratically with the wave's amplitude and linearly with its speed,

$$
  P_{wave} \propto A^2 v_w
$$

This result holds in general for waves whether they are sinusoidal or not.

As a wave propagates away from the source it spreads out and diminishes in amplitude. Instruments that detect the waves are only sensitive to the area of the wave front covered by the detector. Therefore, it proves useful to define the intensity of the wave, which is its power divided by the area over which the power is distributed. For example, the intensity of a uniform spherical wave at a distance \\( r \\) from a source of power \\( P \\) is given by,

$$
  I = \frac{P}{4 \pi r^2}
$$

This relation between the intensity measured, the power emitted, and the distance to the source is of great importance in many fields of science and technology. For example, the intensity of star light or other astronomical objects is used by astronomers to infer the distance to other stars if their power output is known or vice versa.
