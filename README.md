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

```
Closure under 'o' : <img src="doc/equations/5a832965338752a5f9cc9a020790496a.svg?invert_in_darkmode" align=middle width=69.08887919999998pt height=22.465723500000017pt/>
Closure under \Epsilon : <img src="doc/equations/226bc5682ee5b42b42e29421faff531d.svg?invert_in_darkmode" align=middle width=67.67106555pt height=22.465723500000017pt/>
Inverse <img src="doc/equations/2dc5e84a2ed629815c7979087387fb1f.svg?invert_in_darkmode" align=middle width=31.735235399999993pt height=26.76175259999998pt/>: <img src="doc/equations/48093084f92b527052113020ed503cf7.svg?invert_in_darkmode" align=middle width=131.96342444999996pt height=26.76175259999998pt/>
Associativity: <img src="doc/equations/2ed71851fac5b53c3db5320759f997df.svg?invert_in_darkmode" align=middle width=160.3653315pt height=24.65753399999998pt/>
```

where <img src="doc/equations/7e1096128b080021db736ec4d7400387.svg?invert_in_darkmode" align=middle width=7.968051299999991pt height=14.15524440000002pt/> is the group action.
