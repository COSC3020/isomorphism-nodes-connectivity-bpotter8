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

Bijection: $f: V_A \rightarrow V_B$ (Each node in graph $A$ is paired with a node in graph $B$)

If we define the nodes in graph $A$ as,

$V_A:$ { $a_1, a_2, ..., a_n$ }

And the nodes in graph $B$ as,

$V_B:$ { $b_1, b_2, ..., b_n$ }

Where $n$ is the amount of nodes, then we can state that

$f(a_1) = b_1$

$f(a_2) = b_2$

...

$f(a_n) = b_n$

Because both graphs have the same amount of nodes, we can ensure that the bijection exists and that each node in graph $A$ is mapped to a corresponding node in graph $B$.

For any edge in graph $A$ $(a_1, a_2)$, there is a corresponding edge in graph $B$ $(f(a_1), f(a_2))$ which proves the graphs are completely connected.

If the two graphs have the same amount of nodes and there is a bijection between the nodes in graph $A$ and graph $B$, and the two graphs are completely connected, the two graphs must be isomorphic.
