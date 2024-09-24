--------------------------------
**Sep 11**

0) what is known in the literature?

1) is there a combinatorial characterization of near-Ramanujan graphs?  e.g. lossless expansion + some mild properties?

- Lossless Expansion alone would not work if we consider a disconnected graph.

2) if the answer to (1) is yes, then the zig-zag construction of lossless conductors potentially gives us a way to construct near-Ramanujan graphs?

3) check whether other existing combinatorial constructions (e.g. the ones by Golowich) can be used to construct near-Ramanujan graphs

4) cut-matching game for vertex expanders?

5) better cut-matching game using min-cost flow?

--------------------------------
**Sep 18**

0) Assumptions: (1) $d = n^{\epsilon}$, (2) lossless vertex expansion, (3) edge conductance close to $$1/2$$

1) Do these imply the graph has constant mixing time?

2) Exercise: near Ramanujan with $$d = n^{\epsilon}$$ implies $$O(1/\epsilon)$$ mixing time 

- This can be directly derived through the mixing time lemma proof.

3) problem: is the converse true as well?

- By reversing the mixing time lemma and bounding the spectral radius, we see that for $d=n^\epsilon$ (and actually more generally for some $d=\Omega (\ln^2 n)$ graph), constant mixing time $\mathcal{O} (1/\epsilon)$ is equivalent to being Ramanujan.

4) make sense of the converse of expander mixing lemma
