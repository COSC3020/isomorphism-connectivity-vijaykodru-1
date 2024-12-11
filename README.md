# Isomorphism

Prove that if two graphs $A$ and $B$ are isomorphic they do *not* have to
be completely connected. I have started with the formal definition of
isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.


Let's consider two graphs G1 and G2

G1 has the vertices {a, b, c} and the edge {(a, b), (b, c)}

likewise G2 has the vertices {u, v, w} and the edge {(u, v), (v, w)}

Both these graphs are not completely connected because not every pair of vertices in the graphs has an edge between them. Meaning there is no edge between (a, c) in graph G1 and there is no edge between (u, w) in graph G2. 

Two graphs G1 and G2 are isomorphic if there exists a bijection function such that $f(v1) \rightarrow v2$. In the graphs above we can get this by f(a) = u, f(b)=v, f(c)=w, this mapping establishes a bijection between the vertex sets of G1 and G2, satisfying the condition for isomorphism. Along with this, we can also map the edges of G1 to G2 as (a, b) maps to (u, v) and (b, c) maps to (v, w) maintaining the same correspondence between edges. Therefore, the graphs G1​ and G2 are isomorphic even though they are not completely connected. 

References:

I did not needed any references as doing the isomorphism nodes and connectivity exercise earlier helped me do this easily. I did look at my previous repository for the structure of the implementation I did last time.

I certify that I have listed all sources used to complete this exercise, including the use of any Large Language Models. All of the work is my own, except where stated otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is suspected, charges may be filed against me without prior notice
