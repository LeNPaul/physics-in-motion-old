---
layout: post
title:  "Explosions"
date: 2016-12-06
categories: Momentum
---

There are many natural as well as human-made phenomena where a body at rest disintegrates into its components due to some internal release of energy. In the case of explosions, for example, the internal energy (be it chemical, nuclear, or otherwise) results in heat transfer to the component's kinetic energy, which causes them to fly apart, namely to explode. How fast do the pieces move outwards? How much energy was released in the explosion?

Let's begin with the simplest system involving a single body disintegrating into two components of mass \\( m_1 \\) and \\( m_2 \\). The disintegration process involves the release of heat \\( Q \\), which is transferred to the kinetic energy of the outgoing pieces, so conservation of energy dictates,

$$
  Q = \frac{1}{2} m_1 v^2_1 + \frac{1}{2} m_2 v^2_2
$$

Where \\( v_1 \\) and \\( v_2 \\) are the velocities of the two pieces. Since there are no external forces acting on the system, momentum is also conserved during the process,

$$
  0 = m_1 v_1 + m_2 v_2
$$

Where the left hand side is zero because the initial body is at rest so its momentum vanishes. Momentum conservation, and the positivity of the inertial mass make it immediately evident that the outgoing pieces must fly apart from each other in opposite directions:

$$
  m_1 v_1 = - m_2 v_2
$$

Using the conservation of energy, we can solve for the outgoing velocities,

$$
  v_1 = \pm \sqrt{\frac{m_2}{m_1}} \sqrt{\frac{2 Q}{m_1 + m_2}}
$$

$$
  v_2 = \mp \sqrt{\frac{m_1}{m_2}} \sqrt{\frac{2 Q}{m_1 + m_2}}
$$

The signs represent the physical point we made above, namely that if one of the pieces is flying out in the positive direction, then the other must be flying out in the negative direction and vice-versa. The problem as posed does not provide enough information to further determine which piece goes in what direction.

Let's consider a couple of simple cases. If the masses are equal, then the velocities are equal in magnitude and opposite in direction:

$$
  v_1 = - v_2
$$

$$
  |v_1| = |v_2| = \sqrt{Q/m}
$$

On the other hand, if the first piece is much heavier than the second one, then we have:

$$
  v_1 \rightarrow \pm \frac{m_2}{m_1} \sqrt{\frac{2 Q}{m_2}}
$$

$$
  v_2 \rightarrow \mp \sqrt{\frac{2 Q}{m_2}}
$$

Therefore, the heavier object moves out much slower than the lighter one by a factor of \\( m_2 / m_1 \\).
