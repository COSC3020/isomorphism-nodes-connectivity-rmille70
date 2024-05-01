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

Consider the edge connecting nodes x & y in $A.$ By the properties of connected graphs, we know that for all pairs of nodes in a graph, there is a unique edge connecting them; thus there exists an edge connecting nodes x & y. This property also hold true for any two unique nodes in $B.$ Since $A$ and $B$ have the same number of nodes, we also know that we can create a one-to-one and onto function between their elements such that every individual node in $A$ can be mapped to some individual unique node in $B.$ So if $A$ and $B$ have the same number of nodes and are completely connected, then there exists some function such that every individual node in $A$ can be mapped to some individual unique node in $B,$ and there exists a unique edges between all pairs of nodes in each graphs. Thus by the definition of isomorphism, $A$ and $B$ are isomorphic graphs