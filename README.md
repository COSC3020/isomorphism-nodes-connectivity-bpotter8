[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/ppBU16qM)
# Isomorphism

Prove that if two graphs $A$ and $B$ have the same number of nodes and are
completely connected, they must be isomorphic. I have started with the formal
definition of isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

Answer:

If graph $A$ and graph $B$ have the same amount of nodes, and they are all connected, the two graphs must be isomorphic.

Bijection: $f: V_A \rightarrow V_B$

This bijection always exists because the two graphs have the same amount of nodes.

For any edge in graph $A$ (x, y), there is a corresponding edge in graph $B$ (f(x), f(y)) which proves the graphs are completely connected.

If the two graphs have the same amount of nodes and there is a bijection between the nodes in graph $A$ and graph $B$, the two graphs must be isomorphic.
