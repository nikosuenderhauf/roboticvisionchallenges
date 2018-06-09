---
layout: default
---

## Guiding Principles

A robot is an inherently active agent that acts in, and interacts
with the physical real world. It perceives the world with
its different sensors, builds a coherent model of the world,
and updates this model over time, but ultimately a robot has
to make decisions, plan actions, and execute these actions
to fulfill a useful task.
This is where robotic vision differs from computer
vision. For robotic vision, perception is only one part of a
more complex, embodied, active, and goal-driven system.
Robotic vision therefore has to take into account that its
immediate outputs (object detection, segmentation, depth
estimates, 3D reconstruction, a description of the scene, and
so on), will ultimately result in actions in the real world. In a
simplified view, whereas computer vision takes images and
translates them into information, robotic vision translates
images into actions.
This fundamental difference between robotic vision and
computer vision motivates a number of research challenges
along three conceptually orthogonal axes: learning, embodiment,
and reasoning. We position individual challenges
along these axes according to their increasing complexity,
and their dependencies


### Temporal Embodiment

In contrast to typical recent
computer vision systems that treat every image as independent,
a robotic vision system perceives a stream of consecutive
and therefore strongly correlated images. Whereas
current work on action recognition, learning from demonstration,
and similar directions in computer vision work
on video data (e.g. by using recurrent neural networks or
by simply stacking consecutive frames in the input layers),
the potential of temporal embodiment to improve the
quality of the perception process for object detection or
semantic segmentation, is currently rarely utilized: a robotic
vision system that uses its temporal embodiment can, for
example, accumulate evidence over time (preferably using
Bayesian techniques, if uncertainty estimates are available) or exploit small viewpoint
variations that occur over time in dynamic scenes.


### Spatial Embodiment

In robotic vision, the camera
that observes the world is part of a larger robotic system
that acts and moves in the world: the camera is spatially
embodied. As the robot moves in its environment, the camera
will observe the scene from different viewpoints, which
poses both challenges and opportunities to a robotic vision
system: observing an object from different viewpoints can
help to disambiguate its semantic properties, improve depth
perception, or segregate an object from other objects or the
background in cluttered scenes. On the other hand, occlusions
and the resulting sudden appearance changes complicate
visual perception and require capabilities such as
object unity and object permanence that are
known to develop in the human visual system.
