---
layout: post
title:  "Superposition of Waves"
date: 2016-11-24
categories: Waves
---

An important property of the wave equation is known as the superposition principle. If \\( y_1 (x,t) \\) and \\( y_2 (x,t) \\) are two solution of the wave euqation, the so is their sum, \\( y_{sum} (x,t) = y_1 (x,t) + y_2 (x,t) \\). This simple observation leads to a variety of interesting phenomena.

### Beats

The phenomenon of beats arises when two waves of similar, but not equal, frequencies overlap at some region of space. Let's consider then two sources of sound, a piano and a tuning fork, that produce sound waves of different frequencies, say \\( f_1 \\) and \\( f_2 \\), respectively. When the sound waves reach our ear they combine together,

$$
  y (0,t) = y_{piano} (0,t) + y_{fork} (0,t)
$$

$$
  y (0,t) = \sin (2 \pi f_1 t) + \sin (2 \pi f_2 t)
$$

Where I have assumed our ear or listening device is position at \\( x = 0 \\). Also, I have chosen the phases and amplitudes for convenience and simplicity, but the effect we are about to discuss does not depend on these choices. Using a trigonometric identity we find that,

$$
  \sin (2 \pi f_1 t) + \sin (2 \pi f_2 t) = 2 \cos \left( 2 \pi \left( \frac{f_1 - f_2}{2} \right) t \right) \sin \left( 2 \pi \left( \frac{f_1 + f_2}{2} \right) t \right)
$$

The second factor represents a note with frequency,

$$
  f_{sum} = f_1 - f_2
$$

Typical notes are measured in hundred of \\( Hz \\), and the human ear cannot discern the rapid oscillations associated with the notes. However, \\( f_{beat} \\) can easily be only a few \\( Hz \\) or less as one tunes the piano to the fork and bring \\( f_1 \rightarrow f_2 \\). Such amplitude modulations are certainly detectable by our ears and one can perceive the note's intensity increasing and decreasing in a periodic fashion. The piano is tuned when \\( f_{beat} = f_1 - f_2 \rightarrow 0 \\). This can be detected by listening to the beat as its period grows larger and larger.
