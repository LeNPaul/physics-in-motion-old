---
layout: post
title:  "Simple Forces"
date: 2016-12-22
categories: Forces
---

### Near Earth Gravity

Near the surface of the earth, all objects are attracted to the earth with a constant force given by:

$$
  F = -mg
$$

Where \\( m \\) is the gravitational mass, and \\( g \\) is the acceleration due to the earth's gravity, which for most cases can be approximated by \\( g = 9.8 m/s^2 \\), where the negative sign exists as a result of choosing the upwards direction as being positive. The force an object feels due to the local gravitational force is known as the object's weight.

It is important to understand that there is a difference between the gravitational mass of an object, which is an intrinsic quantity of that object, and the weight of that same object, which depends on the local gravitational field, which is an extrinsic quantity. That is why a person would weigh less on the moon, for example, since the moon is much smaller than the earth. In both cases though, the person's mass remains the same.

When analyzing the force diagrams of an object near the surface of the earth, we can conclude that:

$$
  F = ma = - m g \rightarrow a = - g
$$

In other words, the acceleration of that object is therefore constant, and pointing downwards, which we would expect. For most applications, taking \\( g \\) to be a constant is a good approximations, although do realize that the value of \\( g \\) in fact varies on the earth's surface, and depending on how far from the surface you are. A more accurate description of the force of gravity can be described by Newton's law of universal gravitation, which we will cover later.

### Hooke's Law

When you pull on an elastic material, such as a spring, you will feel a force pulling back on you, in an attempt to restore the material back to its equilibrium position. You might also notice that the further away from the equilibrium position that you pull, the stronger the force is. One of the best ways to model this force dependence on position is known as Hooke's law:

$$
  F = - k x
$$

Where \\( x \\) is the position away from equilibrium, and \\( k \\) is a constant known as the spring constant, with units \\( N / m \\). The negative sign in front of the spring constant denotes the fact that the restoring force opposes the displacing force. If you pull a spring right, it will pull left, with the inverse being true.

### Normal Forces

When one object interacts with another object with a force, the other object will apply an equal but opposite force on the first. The direction of these interacting forces will be perpendicularly away from each object, as both objects are opposing each other with equal but opposite force.

As an example, consider a book laying on top of a table. The book is being pulled downwards towards the ground by the earth's gravity, while the table is exerting an equal and opposite force perpendicular to the table on the book, the normal force.

The total force on the book in the vertical direction is therefore:

$$
  F_{tot} = -m_{b} g + N = 0
$$

The book is not accelerating in the vertical direction, since the net force is zero.

### Tension

Consider a lamp of mass \\( m \\) hanging from the ceiling by a massless rope. Gravity is pulling the lamp downwards with a force equal to the lamp's weight:

$$
  W = - m g
$$

Since the lamp is stationary, we know that the net force on the lamp must be zero, and that the rope must be pulling the lamp upwards with a force opposing the weight of the lamp:

$$
  F_{rope} = -W
$$

Here, we are taking the upwards direction, or the direction towards the ceiling, to be the negative direction. By Newton's third law, the lamp should be applying an equal but opposite force on the rope, and so the rope is being pulled downwards by:

$$
  F_{lamp} = W
$$

This force is the tension in the rope, and since we assumed that the rope is stiff and massless, the tension must be the same throughout:

$$
  T = F_{lamp} = W
$$

Since the ceiling is also pulling the rope upwards, and the pull of the ceiling must exactly equal the tension in the rope, since the total net force is zero. Again, by Newton's third law, the rope must there be applying an equal but opposite force on the ceiling, pulling the ceiling downwards with a force equal to the tension \\( T \\). Since \\( T = W \\), then the ceiling is experiencing a pull downwards equal to the weight of the lamp.

More generally, ropes and strings provide a connection between two separate objects, and the tension on them is uniform through and applies to both objects on the two ends.
