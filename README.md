# Catalyst Motion

Catalyst Motion brings time-based behaviour to Bloc.

Elements can move, fade, scale and change over time, with those changes driven by reusable behaviours rather than animation code embedded throughout an interface. Motion provides the progression between states, including duration, easing and interpolation, and keeps that progression synchronised with presentation in Bloc.

Multiple motions can act on the same element at the same time. Their contributions are coordinated before presentation, allowing independent behaviours to be composed without each needing to know who else is involved. A hover effect can fade an element while another motion moves it and another changes its scale; each contributes its part of the final presentation.

Motion also supports behaviours whose values come from somewhere other than interpolation. [https://github.com/BenjaVision-Catalyst/Physics](Catalyst Physics) uses this to present simulation results through the same machinery as ordinary motion. This means an element can combine animation, interaction and simulation while still arriving at Bloc through a single presentation path.

Motion is useful anywhere an interface changes over time rather than all at once—from a simple transition to behaviours that remain active for the lifetime of an element.
