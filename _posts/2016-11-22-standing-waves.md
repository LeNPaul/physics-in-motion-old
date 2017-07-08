---
layout: post
title:  "Standing Waves"
date: 2016-11-22
categories: Waves
---

As we saw above, general sinusoidal waves are characterized by their wavelength, \\( \lambda \\), and frequency, \\( f \\). The only restriction on these quantities is that their product must equal the velocity. Further restrictions arise when the medium is forbidden from vibrating at particular points. For concreteness, let us consider a long string of length \\( l \\) whose ends are clamped at two points \\( x = 0 \\) and \\( x = l \\). The displacement, \\( y(x,t) \\), must then satisfy the following conditions,

$$
  y(0,t) = 0
$$

$$
  y(l,t) = 0
$$

The string cannot be displaced at its ends at any time. Clearly, this cannot be satisfied by a traveling wave, because even if it vanishes at a point at a given moment, it will not vanish there a moment later. But, what if we consider two waves traveling in opposite directions? The general expression is,

$$
  y (x,t) = A \sin k (x - v_w t) + B \sin k (x + v_w t)
$$

This sort of wave, which is the superposition of a wave moving to the right and a wave moving to the left, can certainly satisfy the first condition,

$$
  y (0,t) = A \sin k (-v_w t) + B \sin k (+ v_w t) = 0
$$

$$
  A = B
$$

With a simple trigonometric identity we can now write the wave as follows,

$$
  y (x,t) = 2 A \cos (\omega t) \sin (k x)
$$

The string is also clamped at \\( x = l \\) and so we must impose the second condition, namely, \\( y (l,t) = 0 \\) at all times,

$$
  y (l,t) = 2 A \cos (\omega t) \sin (k l) = 0
$$

$$
  k l = n \pi, n = 1,2,3...
$$

Where \\( n \\) is a positive integer. This condition results because for the function to vanish at all times, the argument of the sine function must vanish at \\( x = l \\). This can be satisfied if it is an integer multiple of \\( \pi \\). We thus arrive at an important condition on the wavelengths supported by the string clamped at both ends,

$$
  \lambda_n = \frac{2 l}{n}
$$

$$
  n = 1,2,3...
$$

The longest wavelength supported is twice the string's length, \\( \lambda = 2 l \\), corresponding to \\( n = 1 \\). It is known as the fundamental. Shorter wavelength are also supported, corresponding to \\( n = 2,3... \\) and are known as harmonics. The waveform satisfying all the boundary conditions is simply.

$$
  y(x,t) = 2 A \cos (\omega t) \sin(2 \pi x / \lambda_n)
$$

Remarkably, even though it was formed from the combination of two traveling waves, the resulting wave is a standing wave. It has a spatial profile of \\( \sin (2 \pi x / \lambda_n) \\) with an amplitude that oscillates in time as \\( 2 A \cos(\omega t) \\).

If you are familiar with any musical string instrument, then you have undoubtedly encountered the phenomenon of standing waves. The different notes on the musical scale are produced by plicking on a string of a well defined length. On a violin, or a guitar, you can created a string of a particular length by clamping down on the string with your finger at a particular place. One typically excites the fundamental vibration, \\( \lambda = 2 l \\). The thickness and tension in the string determine the speed of waves in the string, and hence the vibration frequency,

$$
  \omega = v_w k = \frac{2 \pi v_w}{\lambda} = \frac{2 \pi v_w}{2 l} \rightarrow f = \frac{v_w}{2 l}
$$

This is the frequency of the note produced. Alongside the fundamental, the higher harmonics are also excited, \\( f = v_w / l, 3 v_w/2 l,... \\). The contribution of the higher harmonics is essential in creating a full-bodied sound. The same note, produced by two instruments, sounds differently because the contribution of the higher harmonics is different between the two instruments. There are also ways to clamp the string so as to produce one of the higher harmonics directly without exciting the fundamental. The notes produced in this way are known as flageolets and are much pure since there are fewer harmonics contributing.

Finally, I would like the briefly mention a phenomenon known as sympathetic resonance. We have previously discussed a harmonic oscillator with natural frequency \\( \omega = \sqrt{k/m} \\) driven by an external force with frequency \\( \omega_{ext} \\). We saw that the best way to drive the oscillator is to do so on resonance, that is by tuning the external force to the same frequency, \\( \omega_{ext} \rightarrow \omega \\). Now consider several close by strings, like the strings of a guitar, each of them vibrating at a certain frequency. If the fundamental (or harmonics) of one of the strings happens to coincide with the fundamental (or harmonics) of a second string then it is possible to excite the second by simply plucking the first. The sound waves produced by the first string act as an external force driving the second string on a resonance in its natural frequencies, the fundamental or harmonics. This has the very pleasant effect of creating a very rich sound and is called sympathetic resonance.
