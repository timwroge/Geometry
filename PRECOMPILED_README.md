# Geometry

The geometry library is here to leverage geometry for programming problems involving 
control, state estimation, perception, signal processing and physics. My contributions
here are really based on just random interest in these topological problems and how they apply
to some projects I am working on for fun.


## Lie Algebra and Manifolds

Lie algebra is an abstract algebra that's core is built around group theory. This description of
lie algebra is based on this paper: [A micro Lie theory for state estimation in robotics](https://arxiv.org/abs/1812.01537).

### Basic group theory
The core of group theory is based on this definition:

Every group satisfies these axioms:


### Axioms of a Group
Closure under 'o' : $X o Y \in G$

Closure under $E$ : $E o X = X o E$

Inverse $X^{-1}$: $X^{-1} o X = X o X^{-1}$

Associativity: $(X o Y) o Z  = X o (Y o Z)  $

where $o$ is the group action.
