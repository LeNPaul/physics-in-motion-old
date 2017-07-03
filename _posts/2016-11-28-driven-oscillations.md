---
layout: post
title:  "Driven Oscillations"
date: 2016-11-28
categories: Simple-Harmonic-Motion
---

Due to drag and friction, simple harmonic motion will generally not persist unless aided by an external force. If we denote such an external force by \\( F_{ext} \\), then the equations of motion for the spring take the form

$$
  F_{tot} = -k x(t) + F_{ext} = m \frac{d^2 x(t)}{d t^2}
$$

The solution to this equation depends on the precise form of F_{ext}, and we will now consider a couple of important examples.

### Constant External force

Consider a mass \\( m \\) hanging vertically from the ceiling by a spring with spring constant \\( k \\). Take the downwards direction to be positive. The equation of motion then takes the form

$$
  - k x(t) + m g = m \frac{d^2 x(t)}{d t^2}
$$

Recall the \\( x(t) \\) denotes the displacement form the length of the spring at rest, so a positive value actually implies an extension downwards. To solve the motion, note that we can redefine the displacement function as:

$$
  x'(t) = x(t) - x_0
$$

Where \\( x_0 = mg / k \\). Then the equation takes the from:

$$
  - k x'(t) = m \frac{d^2 x'(t)}{d t^2}
$$

The right had side is easy because the derivative of a constant banishes. But, we already encountered the solution to the equation, it is simply:

$$
  x'(t) = A \cos( \omega t + \phi )
$$

Where \\( \omega = \sqrt{k / m} \\). Therefore, using the relation between \\( x'(t) \\) and \\( x(t) \\), the solution for the original displacement function is:

$$
  x(t) = x_0 + A \cos( \omega t + \phi )
$$

This is the same behavior as usual as far as the oscillations are concerned, but the displacement suffers a constant elongation, \\( x_0 = m g / k )\\. This is as it should be, the gravitational pull downwards is causing the spring to adopt a new equilibrium length, which is longer by and amount \\( x_0 \\) as compared with the horizontal length of the spring as rest.

### Periodic External Forces - Resonance Phenomena

It should be intuitively clear to anyone who as pushed a swing before that one can most efficiently increase the amplitude of oscillations by pushing at the right moment. The periodic push must be done in coordination with the periodic motion of the swing. This lends us to the idea of a periodic external force:

$$
  F_{ext} = F_0 \cos ( \omega_{ext} t ),
$$

where \\( F_0 \\) is the amplitude of the external force, \\( \omega_{ext} \\) is the angular frequency, and \\( \phi_{ext} \\) is the phase. We can again write the equation of motion for the oscillator,

$$
  - k x(t) + F_0 \cos( \omega_{ext} )
$$
