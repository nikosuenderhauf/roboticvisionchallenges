---
layout: default
---
<script src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.0/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>



## The Robotic Vision Scene Understanding Challenge
> Where are my keys?  Where is the red toy car?
>
> Are there any wine bottles on the table in the living room?
>
> How many plates are on the table in the kitchen?


The Robotic Vision Scene Understanding Challenge evaluates how well a vision system can __understand__ the 


### Types of Questions
The questions asked for the scene understanding challenge can be formalised as a [context-free grammar](https://en.wikipedia.org/wiki/Context-free_grammar) $$G = \{V, T, P, \sigma\}$$ with variables $$V = \{Q, S, L\}$$ representing a question phrase ($$Q$$), a subject phrase ($$S$$), and a location phrase ($$L$$). We use $$\sigma$$ to denote the start symbol.

$$
\begin{align}
G & = & \{V, T, P, \sigma \} \\
V & = & \{Q, S, L\} \\
\sigma & \rightarrow & QS \;\; | \;\; QSL \\

Q & \rightarrow & \texttt{exists}\;\; | \;\; \texttt{how_many} \;\; | \;\; \texttt{where}

\end{align}
$$

**Existence**

**
